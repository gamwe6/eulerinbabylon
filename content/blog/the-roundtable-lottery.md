---
date: "2013-11-09T19:00:00"
title: "The Roundtable Lottery"
description: ""
---

<p>A group of <var>p</var> people decide to sit down at a round table and play a lottery-ticket trading game. Each person starts off with a randomly-assigned, unscratched lottery ticket. Each ticket, when scratched, reveals a whole-pound prize ranging anywhere from £1 to £<var>p</var>, with no two tickets alike. The goal of the game is for each person to maximize his ticket winnings upon leaving the game.</p>
<p>An arbitrary person is chosen to be the first player. Going around the table, each player has only one of two options:</p>
<p>1. The player can scratch his ticket and reveal its worth to everyone at the table.
2. The player can trade his unscratched ticket for a previous player's scratched ticket, and then leave the game with that ticket. The previous player then scratches his newly-acquired ticket and reveals its worth to everyone at the table.</p>
<p>The game ends once all tickets have been scratched. All players still remaining at the table must leave with their currently-held tickets.</p>
<p>Assume that each player uses the optimal strategy for maximizing the expected value of his ticket winnings. </p>
<p>Let E(<var>p</var>) represent the expected number of players left at the table when the game ends in a game consisting of <var>p</var> players (e.g. E(111) = 5.2912 when rounded to 5 significant digits).</p>
<p>Let $S_1(N) = \sum \limits_{p = 1}^{N} {E(p)}$.
Let $S_k(N) = \sum \limits_{p = 1}^{N} {S_{k-1}(p)}$ for $k \gt 1$.</p>
<p>Find S<sub>20</sub>(10<sup>14</sup>) and write the answer in scientific notation rounded to 10 significant digits. Use a lowercase e to separate mantissa and exponent (e.g. S<sub>3</sub>(100) = 5.983679014e5).</p>

