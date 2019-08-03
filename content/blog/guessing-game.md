---
date: "2012-12-16T07:00:00"
title: "Guessing Game"
description: ""
---

<p>We are trying to find a hidden number selected from the set of integers {1, 2, ..., <var>n</var>} by asking questions. 
Each number (question) we ask, we get one of three possible answers:</p><ul><li> "Your guess is lower than the hidden number" (and you incur a cost of <var>a</var>), or</li>
<li> "Your guess is higher than the hidden number" (and you incur a cost of <var>b</var>), or</li>
<li> "Yes, that's it!" (and the game ends).</li>
</ul><p>Given the value of <var>n</var>, <var>a</var>, and <var>b</var>, an <i>optimal strategy</i> minimizes the total cost <u>for the worst possible case</u>.</p>
<p>For example, if <var>n</var> = 5, <var>a</var> = 2, and <var>b</var> = 3, then we may begin by asking "<b>2</b>" as our first question.</p>
<p>If we are told that 2 is higher than the hidden number (for a cost of <var>b</var>=3), then we are sure that "<b>1</b>" is the hidden number (for a total cost of <span style="color:#3333ff;"><b>3</b></span>).
If we are told that 2 is lower than the hidden number (for a cost of <var>a</var>=2), then our next question will be "<b>4</b>".
If we are told that 4 is higher than the hidden number (for a cost of <var>b</var>=3), then we are sure that "<b>3</b>" is the hidden number (for a total cost of 2+3=<span style="color:#3333ff;"><b>5</b></span>).
If we are told that 4 is lower than the hidden number (for a cost of <var>a</var>=2), then we are sure that "<b>5</b>" is the hidden number (for a total cost of 2+2=<span style="color:#3333ff;"><b>4</b></span>).
Thus, the worst-case cost achieved by this strategy is <span style="color:#FF0000;"><b>5</b></span>. It can also be shown that this is the lowest worst-case cost that can be achieved. 
So, in fact, we have just described an optimal strategy for the given values of <var>n</var>, <var>a</var>, and <var>b</var>.</p>
<p>Let C(<var>n</var>, <var>a</var>, <var>b</var>) be the worst-case cost achieved by an optimal strategy for the given values of <var>n</var>, <var>a</var>, and <var>b</var>.</p>
<p>Here are a few examples:
C(5, 2, 3) = 5
C(500, √2, √3) = 13.22073197...
C(20000, 5, 7) = 82
C(2000000, √5, √7) = 49.63755955...</p>
<p>Let F<sub><var>k</var></sub> be the Fibonacci numbers: F<sub><var>k</var></sub> = F<sub><var>k</var>-1</sub> + F<sub><var>k</var>-2</sub> with base cases F<sub>1</sub> = F<sub>2</sub> = 1.Find $\sum \limits_{k = 1}^{30} {C \left (10^{12}, \sqrt{k}, \sqrt{F_k} \right )}$, and give your answer rounded to 8 decimal places behind the decimal point.</p>
