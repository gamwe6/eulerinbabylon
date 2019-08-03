---
date: "2014-04-19T13:00:00"
title: "Smooth divisors of binomial coefficients"
description: ""
---

<p>An integer is called <strong><var>B</var>-smooth</strong> if none of its prime factors is greater than <var>B</var>.</p>
<p>Let S<sub><var>B</var></sub>(<var>n</var>) be the largest <var>B</var>-smooth divisor of <var>n</var>.
Examples:
S<sub>1</sub>(10) = 1
S<sub>4</sub>(2100) = 12
S<sub>17</sub>(2496144) = 5712</p>
<p>Define F(<var>n</var>) = ∑<sub>1≤<var>B</var>≤<var>n</var></sub> ∑<sub>0≤<var>r</var>≤<var>n</var></sub> S<sub><var>B</var></sub>(C(<var>n</var>,<var>r</var>)). Here, C(<var>n</var>,<var>r</var>) denotes the binomial coefficient.
Examples:
F(11) = 3132
F(1 111) mod 1 000 000 993 = 706036312
F(111 111) mod 1 000 000 993 = 22156169</p>
<p>Find F(11 111 111) mod 1 000 000 993.</p>

