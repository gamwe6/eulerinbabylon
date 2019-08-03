---
date: "2007-01-12T18:00:00"
title: "Fibonacci golden nuggets"
description: "Problem 137"
---

<p>Consider the infinite polynomial series A<sub>F</sub>(<i>x</i>) = <i>x</i>F<sub>1</sub> + <i>x</i><sup>2</sup>F<sub>2</sub> + <i>x</i><sup>3</sup>F<sub>3</sub> + ..., where F<sub><i>k</i></sub> is the <i>k</i>th term in the Fibonacci sequence: 1, 1, 2, 3, 5, 8, ... ; that is, F<sub><i>k</i></sub> = F<sub><i>k</i>−1</sub> + F<sub><i>k</i>−2</sub>, F<sub>1</sub> = 1 and F<sub>2</sub> = 1.</p>
<p>For this problem we shall be interested in values of <i>x</i> for which A<sub>F</sub>(<i>x</i>) is a positive integer.</p>
<table border="0" cellpadding="0" cellspacing="0"><tr><td>Surprisingly A<sub>F</sub>(1/2)</td>
<td> = </td>
<td>(1/2).1 + (1/2)<sup>2</sup>.1 + (1/2)<sup>3</sup>.2 + (1/2)<sup>4</sup>.3 + (1/2)<sup>5</sup>.5 + ...</td>
</tr><tr><td> </td>
<td> = </td>
<td>1/2 + 1/4 + 2/8 + 3/16 + 5/32 + ...</td>
</tr><tr><td> </td>
<td> = </td>
<td>2</td>
</tr></table><p>The corresponding values of <i>x</i> for the first five natural numbers are shown below.</p>
<table class="grid" style="margin:0 auto;"><tr><th><b><i>x</i></b></th><th width="50"><b>A<sub>F</sub>(<i>x</i>)</b></th>
</tr><tr><td>√2−1</td><td>1</td>
</tr><tr><td>1/2</td><td>2</td>
</tr><tr><td>(√13−2)/3</td><td>3</td>
</tr><tr><td>(√89−5)/8</td><td>4</td>
</tr><tr><td>(√34−3)/5</td><td>5</td>
</tr></table><p>We shall call A<sub>F</sub>(<i>x</i>) a golden nugget if <i>x</i> is rational, because they become increasingly rarer; for example, the 10th golden nugget is 74049690.</p>
<p>Find the 15th golden nugget.</p>

