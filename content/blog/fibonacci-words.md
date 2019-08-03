---
date: "2009-01-31T13:00:00"
title: "Fibonacci Words"
description: ""
---

<p>For any two strings of digits, A and B, we define F<sub>A,B</sub> to be the sequence (A,B,AB,BAB,ABBAB,...) in which each term is the concatenation of the previous two.</p>
<p>Further, we define D<sub>A,B</sub>(<var>n</var>) to be the <var>n</var><sup>th</sup> digit in the first term of F<sub>A,B</sub> that contains at least <var>n</var> digits.</p>
<p>Example:</p>
<p>Let A=1415926535, B=8979323846. We wish to find D<sub>A,B</sub>(35), say.</p>
<p>The first few terms of F<sub>A,B</sub> are:
1415926535
8979323846
14159265358979323846
897932384614159265358979323846
1415926535897932384689793238461415<span style="color:#FF0000;"><b>9</b></span>265358979323846</p>
<p>Then D<sub>A,B</sub>(35) is the 35<sup>th</sup> digit in the fifth term, which is 9.</p>
<p>Now we use for A the first 100 digits of π behind the decimal point:</p>
<p>14159265358979323846264338327950288419716939937510 
58209749445923078164062862089986280348253421170679 </p>
<p>and for B the next hundred digits:</p>
<p>82148086513282306647093844609550582231725359408128 
48111745028410270193852110555964462294895493038196 .</p>
<p>Find ∑<sub><var>n</var> = 0,1,...,17</sub>   10<sup><var>n</var></sup>× D<sub>A,B</sub>((127+19<var>n</var>)×7<sup><var>n</var></sup>) .</p>

