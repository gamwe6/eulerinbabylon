---
date: "2013-09-14T19:00:00"
title: "Unfair wager"
description: ""
---

<p>Julie proposes the following wager to her sister Louise.
She suggests they play a game of chance to determine who will wash the dishes.
For this game, they shall use a generator of independent random numbers uniformly distributed between 0 and 1.
The game starts with <var>S</var> = 0.
The first player, Louise, adds to <var>S</var> different random numbers from the generator until <var>S</var> &gt; 1 and records her last random number '<var>x</var>'.
The second player, Julie, continues adding to <var>S</var> different random numbers from the generator until <var>S</var> &gt; 2 and records her last random number '<var>y</var>'.
The player with the highest number wins and the loser washes the dishes, i.e. if <var>y</var> &gt; <var>x</var> the second player wins.</p>
<p>For e<var>x</var>ample, if the first player draws 0.62 and 0.44, the first player turn ends since 0.62+0.44 &gt; 1 and <var>x</var> = 0.44.
If the second players draws 0.1, 0.27 and 0.91, the second player turn ends since 0.62+0.44+0.1+0.27+0.91 &gt; 2 and <var>y</var> = 0.91.
Since <var>y</var> &gt; <var>x</var>, the second player wins.</p>
<p>Louise thinks about it for a second, and objects: "That's not fair".
What is the probability that the second player wins?
Give your answer rounded to 10 places behind the decimal point in the form 0.abcdefghij</p>

