---
date: "2015-10-25T04:00:00"
title: "Chinese leftovers"
description: ""
---

<p>
Let g(<var>a,n,b,m</var>) be the smallest non-negative solution <var>x</var> to the system:<var>x = a</var> mod <var>n</var><var>x = b</var> mod <var>m</var>
if such a solution exists, otherwise 0.
</p>
<p>
E.g. g(2,4,4,6)=10, but g(3,4,4,6)=0.
</p>
<p>
Let φ(<var>n</var>) be Euler's totient function.
</p>
<p>
Let f(n,m)=g(φ(n),n,φ(m),m)
</p>
<p>
Find ∑f(n,m) for 1000000 ≤ n &lt; m &lt; 1005000
</p>

