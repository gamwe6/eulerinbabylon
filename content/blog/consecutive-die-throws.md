---
date: "2013-04-14T10:00:00"
title: "Consecutive die throws"
description: "Problem 423"
---

<p>Let <var>n</var> be a positive integer.
A 6-sided die is thrown <var>n</var> times. Let <var>c</var> be the number of pairs of consecutive throws that give the same value.</p>
<p>For example, if <var>n</var> = 7 and the values of the die throws are (1,1,5,6,6,6,3), then the following pairs of consecutive throws give the same value:
(<u>1,1</u>,5,6,6,6,3)
(1,1,5,<u>6,6</u>,6,3)
(1,1,5,6,<u>6,6</u>,3)
Therefore, <var>c</var> = 3 for (1,1,5,6,6,6,3).</p>
<p>Define C(<var>n</var>) as the number of outcomes of throwing a 6-sided die <var>n</var> times such that <var>c</var> does not exceed π(<var>n</var>).<sup>1</sup>
For example, C(3) = 216, C(4) = 1290, C(11) = 361912500 and C(24) = 4727547363281250000.</p>
<p>Define S(<var>L</var>) as ∑ C(<var>n</var>) for 1 ≤ <var>n</var> ≤ <var>L</var>.
For example, S(50) mod 1 000 000 007 = 832833871.</p>
<p>Find S(50 000 000) mod 1 000 000 007.</p>
<p><sup>1</sup> π denotes the <b>prime-counting function</b>, i.e. π(<var>n</var>) is the number of primes ≤ <var>n</var>.</p>

