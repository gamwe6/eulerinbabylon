---
date: "2010-10-17T07:00:00"
title: "Paper-strip Game"
description: "Problem 306"
---

<p>The following game is a classic example of Combinatorial Game Theory:</p>
<p>Two players start with a strip of <var>n</var> white squares and they take alternate turns.
On each turn, a player picks two contiguous white squares and paints them black.
The first player who cannot make a move loses.</p>
<p></p><ul><li>If <var>n</var> = 1, there are no valid moves, so the first player loses automatically.</li>
<li>If <var>n</var> = 2, there is only one valid move, after which the second player loses.</li>
<li>If <var>n</var> = 3, there are two valid moves, but both leave a situation where the second player loses.</li>
<li>If <var>n</var> = 4, there are three valid moves for the first player; she can win the game by painting the two middle squares.</li>
<li>If <var>n</var> = 5, there are four valid moves for the first player (shown below in red); but no matter what she does, the second player (blue) wins.</li>
</ul><div align="center"><img alt="p306_pstrip.gif" class="dark_img" src="/images/p306_pstrip.gif"/></div>
<p>So, for 1 ≤ <var>n</var> ≤ 5, there are 3 values of <var>n</var> for which the first player can force a win.
Similarly, for 1 ≤ <var>n</var> ≤ 50, there are 40 values of <var>n</var> for which the first player can force a win.</p>
<p>For 1 ≤ <var>n</var> ≤ 1 000 000, how many values of <var>n</var> are there for which the first player can force a win?</p>

