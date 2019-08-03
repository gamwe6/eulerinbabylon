---
date: "2012-03-10T22:00:00"
title: "Minimum of subsequences"
description: ""
---

<p>Let <var>S</var><sub><var>n</var></sub> be an integer sequence produced with the following pseudo-random number generator:</p>
<center><table class="p375"><tr><td style="text-align:right;"><var>S</var><sub>0</sub></td>
<td>=<sub> </sub></td>
<td>290797<sub> </sub></td>
</tr><tr><td><var>S</var><sub><var>n</var>+1</sub></td>
<td>=<sub> </sub></td>
<td><var>S</var><sub><var>n</var></sub><sup>2</sup> mod 50515093</td>
</tr></table></center>
<p>
Let A(<var>i</var>, <var>j</var>) be the minimum of the numbers <var>S</var><sub><var>i</var></sub>, <var>S</var><sub><var>i</var>+1</sub>, ... , <var>S</var><sub><var>j</var></sub> for <var>i</var> ≤ <var>j</var>.
Let M(<var>N</var>) = ΣA(<var>i</var>, <var>j</var>) for 1 ≤ <var>i</var> ≤ <var>j</var> ≤ <var>N</var>.
We can verify that M(10) = 432256955 and M(10 000) = 3264567774119.</p>
<p>
Find M(2 000 000 000).
</p>

