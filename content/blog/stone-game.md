---
date: "2009-10-16T13:00:00"
title: "Stone Game"
description: ""
---

<p>A game is played with three piles of stones and two players.
At her turn, a player removes one or more stones from the piles. However, if she takes stones from more than one pile, she must remove the same number of stones from each of the selected piles.</p>
<p>In other words, the player chooses some N&gt;0 and removes:
</p><ul><li>N stones from any single pile; or</li>
<li>N stones from each of any two piles (2N total); or</li>
<li>N stones from each of the three piles (3N total).</li></ul>
The player taking the last stone(s) wins the game.

<p>A <i>winning configuration</i> is one where the first player can force a win.
For example, (0,0,13), (0,11,11) and (5,5,5) are winning configurations because the first player can immediately remove all stones.</p>
<p>A <i>losing configuration</i> is one where the second player can force a win, no matter what the first player does. 
For example, (0,1,2) and (1,3,3) are losing configurations: any legal move leaves a winning configuration for the second player.</p>
<p>Consider all  losing configurations (x<sub>i</sub>,y<sub>i</sub>,z<sub>i</sub>) where x<sub>i</sub> ≤ y<sub>i</sub> ≤ z<sub>i</sub> ≤ 100.
We can verify that Σ(x<sub>i</sub>+y<sub>i</sub>+z<sub>i</sub>) = 173895 for these.</p>
<p>Find Σ(x<sub>i</sub>+y<sub>i</sub>+z<sub>i</sub>) where (x<sub>i</sub>,y<sub>i</sub>,z<sub>i</sub>) ranges over the losing configurations
with x<sub>i</sub> ≤ y<sub>i</sub> ≤ z<sub>i</sub> ≤ 1000.</p>

