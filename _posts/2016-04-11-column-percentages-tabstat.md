---
layout: post
title:  "Adding column percentages to tabstat"
date:   2015-04-11
categories: stata
permalink: /posts/column-percentages-tabstat
---

Here's some Stata code:

<pre class="sh_stata">
. sysuse bpwide, clear
. local controls sex agegrp
. reg bp_after bp_before `controls'
</pre>