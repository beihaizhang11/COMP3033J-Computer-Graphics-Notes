# Resterization
## 画直线
### Explicit Form
$y = mx + c$

通过遍历(x0,x1)之间的每一个x值，并计算相应的y值，可以逐个像素绘制直线：
```
for (int x = x0; x < x1; x++) {
    y = m * x + c;
    setPixel(x, y);
}
```

**挑战**
1. slope > 1时失效
2. 无法从右向左绘制， 当 $x_0 > x_1$（即直线从右向左绘制）时

**Bresenham算法**

### Implicit Form

$Ax + By + C = 0$

绘制直线时，需要遍历直线覆盖的每个像素，并检查每个像素是否在直线的范围内。判断像素到直线的距离
```
for (int x = xMin; x < xMax; x++) {
    for (int y = yMin; y < yMax; y++) {
        if (abs(distance((x, y), (x0, y0), (x1, y1))) < 0.5) {
            setPixel(x, y);
        }
    }
}
```

### Parametric Form
简单code
```
for (float t = 0.0; t <= 1.0; t += 0.001) {
    // 计算参数 t 对应的点
    float r_x = p_x + (q_x - p_x) * t;
    float r_y = p_y + (q_y - p_y) * t;
    
    // 将计算的点四舍五入到最近的像素位置
    setPixel(round(r_x), round(r_y));
}
```


## 颜色插值
用于颜色之间的平缓过度

### Linear Interpolation
假设我们有两个颜色 $C_0$ 和 $C_1$，以及一个参数 $t$，其中 $t$ 在 0 到 1 之间变化。线性插值的公式如下：

$f(t)=f(A)+\left(\frac{t-A}{B-A}\right)(f(B)-f(A))$

## 三角形

### Explicit Form  (linewise scan)
$\begin{array}{lll}y_{A C} \leq y \leq y_{A B} & \text { if } & x_A \leq x \leq x_B \\ y_{A C} \leq y \leq y_{B C} & \text { if } & x_B \leq x \leq x_C\end{array}$

通常是水平循环



### Winding Order

顺时针（多边形位于右边）

逆时针（多边形位于左边）

### Half-Plane Test

每条边将平面分为两部分，点 
𝑃是否在“正确的半平面”中决定了它是否在三角形内部。

### Implicit / Normal Form
基于半平面测试，判断像素是否在三角形内

### Barycentric Coordinates
对于三角形的三个顶点 
𝐴、𝐵、𝐶，任意点 𝑃可以用重心坐标 𝛼、𝛽、𝛾来表示：
𝛼是点 𝑃到顶点 𝐴的“权重”。
𝛽是点 𝑃到顶点 𝐵的“权重”。
𝛾是点 𝑃到顶点 𝐶的“权重”。

$$
\begin{gathered}
\alpha+\beta+\gamma=1 \\
\alpha, \beta, \gamma \geq 0
\end{gathered}
$$

用于计算颜色插值