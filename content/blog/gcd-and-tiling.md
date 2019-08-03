---
date: "2013-10-13T07:00:00"
title: "GCD and Tiling"
description: ""
---

<p>We want to tile a board of length <var>n</var> and height 1 completely, with either 1 × 2 blocks or 1 × 1 blocks with a single decimal digit on top:</p>
<div style="text-align:center;">
<img alt="p440_tiles.png" src="/images/p440_tiles.png"/></div>
<p>For example, here are some of the ways to tile a board of length <var>n</var> = 8:</p>
<div style="text-align:center;">
<img alt="p440_some8.png" src="/images/p440_some8.png"/></div>
<p>Let T(<var>n</var>) be the number of ways to tile a board of length <var>n</var> as described above.</p>
<p>For example, T(1) = 10 and T(2) = 101.</p>
<p>Let S(<var>L</var>) be the triple sum ∑<sub><var>a</var>,<var>b</var>,<var>c</var></sub> gcd(T(<var>c</var><sup><var>a</var></sup>), T(<var>c</var><sup><var>b</var></sup>)) for 1 ≤ <var>a</var>, <var>b</var>, <var>c</var> ≤ <var>L</var>.
For example:
S(2) = 10444
S(3) = 1292115238446807016106539989
S(4) mod 987 898 789 = 670616280.</p>
<p>Find S(2000) mod 987 898 789.</p>

