---
date: "2008-10-25T14:00:00"
title: "Totient Chains"
description: ""
---

<p>Let φ be Euler's totient function, i.e. for a natural number <var>n</var>,
φ(<var>n</var>) is the number of <var>k</var>, 1 ≤ <var>k</var> ≤ <var>n</var>, for which gcd(<var>k</var>,<var>n</var>) = 1.</p>
<p>By iterating φ, each positive integer generates a decreasing chain of numbers ending in 1.
E.g. if we start with 5 the sequence 5,4,2,1 is generated.
Here is a listing of all chains with length 4:</p>
<div style="text-align:right;margin-right:350px;">
5,4,2,1
7,6,2,1
8,4,2,1
9,6,2,1
10,4,2,1
12,4,2,1
14,6,2,1
18,6,2,1</div>
<p>Only two of these chains start with a prime, their sum is 12.</p>
<p>What is the sum of all primes less than 40000000 which generate a chain of length 25?</p>
