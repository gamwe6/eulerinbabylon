---
date: "2010-04-23T13:00:00"
title: "Eulerian Cycles"
description: "Problem 289"
---

<p>Let C(<var>x</var>,<var>y</var>) be a circle passing through the points (<var>x</var>, <var>y</var>), (<var>x</var>, <var>y</var>+1), (<var>x</var>+1, <var>y</var>) and (<var>x</var>+1, <var>y</var>+1).</p>
<p>For positive integers m and n, let E(<var>m</var>,<var>n</var>) be a configuration which consists of the <var>m</var>·<var>n</var> circles:
{ C(<var>x</var>,<var>y</var>): 0 ≤ <var>x</var> &lt; <var>m</var>, 0 ≤ <var>y</var> &lt; <var>n</var>, <var>x</var> and <var>y</var> are integers }</p>
<p>An Eulerian cycle on E(<var>m</var>,<var>n</var>) is a closed path that passes through each arc exactly once.
Many such paths are possible on E(<var>m</var>,<var>n</var>), but we are only interested in those which are not self-crossing: 
A non-crossing path just touches itself at lattice points, but it never crosses itself.</p>
<p>The image below shows E(3,3) and an example of an Eulerian non-crossing path.</p><div align="center"><img alt="p289_euler.gif" src="/images/p289_euler.gif"/></div>
<p>Let L(<var>m</var>,<var>n</var>) be the number of Eulerian non-crossing paths on E(<var>m</var>,<var>n</var>).
For example, L(1,2) = 2, L(2,2) = 37 and L(3,3) = 104290.</p>
<p>Find L(6,10) mod 10<sup>10</sup>.</p>

