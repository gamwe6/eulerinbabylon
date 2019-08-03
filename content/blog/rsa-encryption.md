---
date: "2008-02-15T13:00:00"
title: "RSA encryption"
description: ""
---

<p>The RSA encryption is based on the following procedure:</p>
<p>Generate two distinct primes <var>p</var> and <var>q</var>.Compute <var>n=pq</var> and φ=(<var>p</var>-1)(<var>q</var>-1).
Find an integer <var>e</var>, 1&lt;<var>e</var>&lt;φ, such that gcd(<var>e</var>,φ)=1.</p>
<p>A message in this system is a number in the interval [0,<var>n</var>-1].
A text to be encrypted is then somehow converted to messages (numbers in the interval [0,<var>n</var>-1]).
To encrypt the text,  for each message, <var>m</var>, <var>c</var>=<var>m</var><sup><var>e</var></sup> mod <var>n</var> is calculated.</p>
<p>To decrypt the text, the following procedure is needed: calculate <var>d</var> such that <var>ed</var>=1 mod φ, then for each encrypted message, <var>c</var>, calculate <var>m=c<sup>d</sup></var> mod <var>n</var>.</p>
<p>There exist values of <var>e</var> and <var>m</var>  such that <var>m<sup>e</sup></var> mod <var>n=m</var>.We call messages <var>m</var> for which <var>m<sup>e</sup></var> mod <var>n=m</var> unconcealed messages.</p>
<p>An issue when choosing <var>e</var> is that there should not be too many unconcealed messages.  For instance, let <var>p</var>=19 and <var>q</var>=37.
Then <var>n</var>=19*37=703 and φ=18*36=648.
If we choose <var>e</var>=181, then, although gcd(181,648)=1 it turns out that all possible messages<var>m</var> (0≤<var>m</var>≤<var>n</var>-1) are unconcealed when calculating <var>m<sup>e</sup></var> mod <var>n</var>.
For any valid choice of <var>e</var> there exist some unconcealed messages.
It's important that the number of unconcealed messages is at a minimum.</p>
<p>Choose <var>p</var>=1009 and <var>q</var>=3643.
Find the sum of all values of <var>e</var>, 1&lt;<var>e</var>&lt;φ(1009,3643) and gcd(<var>e</var>,φ)=1, so that the number of unconcealed messages for this value of <var>e</var> is at a minimum.</p>

