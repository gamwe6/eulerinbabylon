---
date: "2011-03-27T05:00:00"
title: "Euler's Number"
description: "Problem 330"
---

An infinite sequence of real numbers <var>a</var>(<var>n</var>) is defined for all integers <var>n</var> as follows:
$$a(n) = \begin{cases}
1 & n \lt 0\\
\sum \limits_{i = 1}^{\infty}{\dfrac{a(n - i)}{i!}} & n \ge 0
\end{cases}$$

<p>For example,</p><table class="formula"><tr><td><var>a</var>(0) = </td>
<td><table class="frac"><tr><td>1</td></tr><tr><td class="overline">1!</td></tr></table></td>
<td>+</td>
<td><table class="frac"><tr><td>1</td></tr><tr><td class="overline">2!</td></tr></table></td>
<td>+</td>
<td><table class="frac"><tr><td>1</td></tr><tr><td class="overline">3!</td></tr></table></td>
<td>+ ... = e − 1 </td>
</tr></table><table class="formula"><tr><td><var>a</var>(1) = </td>
<td><table class="frac"><tr><td>e − 1</td></tr><tr><td class="overline">1!</td></tr></table></td>
<td>+</td>
<td><table class="frac"><tr><td>1</td></tr><tr><td class="overline">2!</td></tr></table></td>
<td>+</td>
<td><table class="frac"><tr><td>1</td></tr><tr><td class="overline">3!</td></tr></table></td>
<td>+ ... = 2e − 3 </td>
</tr></table><table class="formula"><tr><td><var>a</var>(2) = </td>
<td><table class="frac"><tr><td>2e − 3</td></tr><tr><td class="overline">1!</td></tr></table></td>
<td>+</td>
<td><table class="frac"><tr><td>e − 1</td></tr><tr><td class="overline">2!</td></tr></table></td>
<td>+</td>
<td><table class="frac"><tr><td>1</td></tr><tr><td class="overline">3!</td></tr></table></td>
<td>+ ... =</td>
<td><table class="frac"><tr><td>7</td></tr><tr><td class="overline">2</td></tr></table></td>
<td>e − 6 </td>
</tr></table>
with e = 2.7182818... being Euler's constant.

<p>
</p><table class="formula"><tr><td>It can be shown that <var>a</var>(<var>n</var>) is of the form 
    </td>
<td><table class="frac"><tr><td>A(<var>n</var>) e + B(<var>n</var>)</td></tr><tr><td class="overline"><var>n</var>!</td></tr></table></td>
<td>for integers A(<var>n</var>) and B(<var>n</var>). 
    </td>
</tr></table><table class="formula"><tr><td>For example <var>a</var>(10) = 
    </td>
<td><table class="frac"><tr><td>328161643 e − 652694486</td></tr><tr><td class="overline">10!</td></tr></table></td>
<td>.</td>
</tr></table><p>
Find A(10<sup>9</sup>) + B(10<sup>9</sup>) and give your answer mod 77 777 777.
</p>

