---
date: "2013-12-15T07:00:00"
title: "Hypocycloid and Lattice points"
description: "Problem 450"
---

<p>
A hypocycloid is the curve drawn by a point on a small circle rolling inside a larger circle. The parametric equations of a hypocycloid centered at the origin, and starting at the right most point is given by:</p><p style="text-align:center;">
$x(t) = (R - r) \cos(t) + r \cos(\frac {R - r} r t)$
$y(t) = (R - r) \sin(t) - r \sin(\frac {R - r} r t)$</p><p>
Where <var>R</var> is the radius of the large circle and <var>r</var> the radius of the small circle.
</p>
<p>
Let $C(R, r)$ be the set of distinct points with integer coordinates on the hypocycloid with radius <var>R</var> and <var>r</var> and for which there is a corresponding value of <var>t</var> such that $\sin(t)$ and $\cos(t)$ are rational numbers.</p>
<p>
Let $S(R, r) = \sum_{(x,y) \in C(R, r)} |x| + |y|$ be the sum of the absolute values of the <var>x</var> and <var>y</var> coordinates of the points in $C(R, r)$.</p>
<p>

Let $T(N) = \sum_{R = 3}^N \sum_{r=1}^{\lfloor \frac {R - 1} 2 \rfloor} S(R, r)$ be the sum of $S(R, r)$ for <var>R</var> and <var>r</var> positive integers, $R\leq N$  and $2r &lt; R$.
</p>
<div>You are given:<table style="border:none;"><tr><td><div style="text-align:right;"><var>C</var>(3, 1) =</div></td>
<td>{(3, 0), (-1, 2), (-1,0), (-1,-2)}</td>
</tr><tr><td style="vertical-align:top;"><div style="text-align:right;"><var>C</var>(2500, 1000) =</div></td>
<td style="vertical-align:top;">{(2500, 0), (772, 2376), (772, -2376), (516, 1792),
 (516, -1792), (500, 0), (68, 504), (68, -504),(-1356, 1088), (-1356, -1088), (-1500, 1000), (-1500, -1000)}</td>
</tr></table></div>
<p><i>Note: (-625, 0) is not an element of C(2500, 1000) because $\sin(t)$ is not a rational number for the corresponding values of <var>t</var>.</i></p>
<p>
<var>S</var>(3, 1) = (|3| + |0|) + (|-1| + |2|) + (|-1| + |0|) + (|-1| + |-2|) = 10</p>
<p>
<var>T</var>(3) = 10; <var>T</var>(10) = 524 ;<var>T</var>(100) = 580442; <var>T</var>(10<sup>3</sup>) = 583108600.
</p>
<p>
Find <var>T</var>(10<sup>6</sup>).
</p>

