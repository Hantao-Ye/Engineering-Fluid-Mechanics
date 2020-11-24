# Chapter 4

[TOC]

## 4-1 Eulerian Description

- Pressure Field: $P=P(x,y,z,t)$
- Velocity Field: $\vec{V}=\vec{V}(x,y,z,t)$
- Acceleration Field: $\vec{a}=\vec{a}(x,y,z,t)$

where the rate of change of the particle's x-position with respect to time is $u$ and similar to y($v$) and z($w$)

$$
\vec{a}(x,y,z,t) = \frac{\partial{\vec{V}}}{\partial{t}}+u\frac{\partial{\vec{V}}}{\partial{x}}+v\frac{\partial{\vec{V}}}{\partial{y}}+w\frac{\partial{\vec{V}}}{\partial{z}}
$$

and in Cartesian coordinates, we could get that

$$
\begin{cases}
    a_x = \frac{\partial{u}}{\partial{t}}+u\frac{\partial{u}}{\partial{x}}+v\frac{\partial{u}}{\partial{y}}+w\frac{\partial{u}}{\partial{z}}\\[2ex]
    a_y = \frac{\partial{v}}{\partial{t}}+u\frac{\partial{v}}{\partial{x}}+v\frac{\partial{v}}{\partial{y}}+w\frac{\partial{v}}{\partial{z}}\\[2ex]
    a_x = \frac{\partial{w}}{\partial{t}}+u\frac{\partial{w}}{\partial{x}}+v\frac{\partial{w}}{\partial{y}}+w\frac{\partial{w}}{\partial{z}}
\end{cases}
$$