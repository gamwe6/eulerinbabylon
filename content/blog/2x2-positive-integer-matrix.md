---
date: "2013-03-24T01:00:00"
title: "2x2 positive integer matrix"
description: ""
---

<p>A <i>positive integer matrix</i> is a matrix whose elements are all positive integers.
Some positive integer matrices can be expressed as a square of a positive integer matrix in two different ways. Here is an example:</p>

$$\begin{pmatrix}
40 & 12\\
48 & 40
\end{pmatrix} =
\begin{pmatrix}
2 & 3\\
12 & 2
\end{pmatrix}^2 =
\begin{pmatrix}
6 & 1\\
4 & 6
\end{pmatrix}^2
$$

<p>
We define F(<var>N</var>) as the number of the 2x2 positive integer matrices which have a <dfn title="the sum of the elements on the main diagonal">trace</dfn> less than <var>N</var> and which can be expressed as a square of a positive integer matrix in two different ways.
We can verify that F(50) = 7 and F(1000) = 1019.
</p>
<p>
Find F(10<sup>7</sup>).
</p>

