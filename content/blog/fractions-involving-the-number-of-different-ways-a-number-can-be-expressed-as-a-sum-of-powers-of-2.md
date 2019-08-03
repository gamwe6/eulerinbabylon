---
date: "2007-12-28T13:00:00"
title: "Fractions involving the number of different ways a number can be expressed as a sum of powers of 2"
description: ""
---

Define f(0)=1 and f(<var>n</var>) to be the number of ways to write <var>n</var> as a sum of powers of 2 where no power occurs more than twice. 

For example, f(10)=5 since there are five different ways to express 10:10 = 8+2 = 8+1+1 = 4+4+2 = 4+2+2+1+1 = 4+4+1+1

It can be shown that for every fraction <var>p/q</var> (<var>p</var>>0, <var>q</var>>0) there exists at least one integer <var>n</var> such that f(<var>n</var>)/f(<var>n</var>-1)=<var>p/q</var>.
For instance, the smallest <var>n</var> for which f(<var>n</var>)/f(<var>n</var>-1)=13/17 is 241.
The binary expansion of 241 is 11110001.
Reading this binary number from the most significant bit to the least significant bit there are 4 one's, 3 zeroes and 1 one. We shall call the string 4,3,1 the <span style="font-style:italic;">Shortened Binary Expansion</span> of 241.
Find the Shortened Binary Expansion of the smallest <var>n</var> for which f(<var>n</var>)/f(<var>n</var>-1)=123456789/987654321.
Give your answer as comma separated integers, without any whitespaces.

