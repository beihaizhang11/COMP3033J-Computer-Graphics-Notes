**写在前面**
机考，注重了解即可，使用中文笔记加快浏览速度，多看几遍，不必深究

# Line
## Dot Product
- 向量的长度     ($|A| = \sqrt{A \cdot A}$)
- 向量的夹角    ($A \cdot B = |A||B|\cos(\theta)$)
- 法向量（判断垂直） ($a \cdot b = 0$)
- 投影
- 计算点到直线的距离
- 两条直线的交点

## Equations of Lines
- Explicit Form   ($y = mx + c$)
- Implicit Form   ($Ax+By+C=0$)
- Normal Form   (没懂，见PPt)
- Parametric Form
 $$
\begin{cases}
x = x_0 + t \cdot v_x \\
y = y_0 + t \cdot v_y
\end{cases} 
$$

## Points & Lines
- 点在线上
$$
\begin{aligned}
p_x & =m p_y+c & & \text { (explicit) } \\
A p_x+B p_y & =c & & \text { (implicit) } \\
\vec{n} \cdot p & =c & & \text { (normal) } \\
p & =\left[\begin{array}{l}
x(t) \\
y(t)
\end{array}\right] \text { for some } t & & \text { (parametric) }
\end{aligned}
$$

- 点到直线的距离
$$
d=\|\vec{v}\| \cos \theta
$$

- 点在直线的哪一侧
$$
\begin{aligned}
\frac{\vec{n} \cdot p-c}{\|\vec{n}\|} & =\vec{n} \cdot \vec{v} \\
& =\|\vec{n}\|\|\vec{v}\| \cos \theta
\end{aligned}
$$

- 直线上最近的一点  (找投影)
- 两直线的交点
- - 显式方程  ($y=m_1 x+c_1=m_2 x+c_2$)
- - 隐式方程  ($\left(m_1-m_2\right) x=c_1-c_2$)
- - 参数方程 
- - 相似三角形  (关键是求d&D)
  
任取直线上两点连接(l)，与原直线构造三角形。

![alt text](image.png)