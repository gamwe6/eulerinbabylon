---
date: "2010-02-13T05:00:00"
title: "Linear Combinations of Semiprimes"
description: "Problem 278"
---

<p>
Given the values of integers 1 &lt; <var>a</var><sub>1</sub> &lt; <var>a</var><sub>2</sub> &lt;... &lt; <var>a</var><sub><var>n</var></sub>, consider the linear combination<var>q</var><sub>1</sub><var>a</var><sub>1</sub> + <var>q</var><sub>2</sub><var>a</var><sub>2</sub> + ... + <var>q</var><sub><var>n</var></sub><var>a</var><sub><var>n</var></sub> = <var>b</var>, using only integer values <var>q</var><sub><var>k</var></sub> ≥ 0. 
</p>
<p>
Note that for a given set of <var>a</var><sub><var>k</var></sub>, it may be that not all values of <var>b</var> are possible.
For instance, if <var>a</var><sub>1</sub> = 5 and <var>a</var><sub>2</sub> = 7, there are no <var>q</var><sub>1</sub> ≥ 0 and <var>q</var><sub>2</sub> ≥ 0 such that <var>b</var> could be 
1, 2, 3, 4, 6, 8, 9, 11, 13, 16, 18 or 23.

In fact, 23 is the largest impossible value of <var>b</var> for <var>a</var><sub>1</sub> = 5 and <var>a</var><sub>2</sub> = 7. We therefore call <var>f</var>(5, 7) = 23. Similarly, it can be shown that <var>f</var>(6, 10, 15)=29 and <var>f</var>(14, 22, 77) = 195.
</p>
<p>
Find ∑ <var>f</var>(<var>p*q,p*r,q*r</var>), where <var>p</var>, <var>q</var> and <var>r</var> are prime numbers and <var>p</var> &lt; <var>q</var> &lt; <var>r</var> &lt; 5000.
</p>

