---
title: 'Some Exercise Answers to A Computational Introduction to Number Theory and Algebra by Victor Shoup (2nd Ed)'
date: 2024-11-02
permalink: /posts/2012/08/exe_NTA/
tags:
  - Number Theory
---
I’m currently learning the basics of number theory and algebra through "A Computational Introduction to Number Theory and Algebra by Victor Shoup", recommended by my supervisor, Ron Steinfeld. To support others learning independently like myself, I’ll be sharing some of my solutions to the exercises from this book. I hope this will spark discussions and mutual learning. If you spot any inaccuracies or have suggestions, please feel free to reach out at Xinyu.Zhang1@monash.edu. (I’ll continue updating this blog whenever I find some free time, so check back for new insights!)

Chapter 1 Basic Properties of the Integers
===
Exercise 1.1. Let $a, b, d \in \mathbb{Z}$ with $d \neq 0$. Show that $a | b$ iff $da | db$.

Proof: We first prove $a|b \implies da|db$: $a|b \implies b = az$ for some $z \in \mathbb{Z}$. Multiplying both sides with $d$ we get $bd = azd = (ad)z \implies ad | bd$. 

Now we prove $da | db \implies a | b$: Since $da | db \implies da = dbz$ for some $z \in \mathbb{Z}$. Since $d \neq 0$, we can divide both sides by $d$ to get $a = bz \implies a | b$. $\square$


