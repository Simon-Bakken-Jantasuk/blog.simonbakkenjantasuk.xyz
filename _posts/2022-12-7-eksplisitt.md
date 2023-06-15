---
layout: post
title: Hvorledes finner vi en rekursiv formel for en rekke?
date: 2022-12-07
author: Simon 
category: matematikk 
---
La oss se på noen rekker.

Aritmetiske rekken på eksplisitt form er, 

$$a_n = a_1 + (n - 1)d$$

\(a_n = a_1 + (n - 1)d\)

Setter inn for $ n + 1 $,

$a_{n + 1} = a_1 + (n + 1 - 1)d$ 

$a_1 + nd$

$ a_n = a_1 + nd - d $

$= a_n = a_{n + 1} + d$ 

Hvor vi løser for $a_{n + 1}$

Vi får $a_{n + 1} = a_n + d$

Som var det vi skulle bevise!

Hvis du vil finne en $ a_{n - 1}$ så setter du bare inn for $n - 1$

Det samme fungerer for en geometrisk rekke.

$a_n = a_1k^{n-1}$ 

$= a_1k^nk^{-1}$

$ a_{n + 1} = a_1k^{n} $

$ a_n = \frac{a_{n+1}}{k}$

$ a_{n+1} = a_nk$

Og en harmonisk rekke!

$\sum_{n = 1}^{\infty} \frac{1}{n} $

$a_n = \frac{1}{n}$

$ a_{n + 1} = \frac{1}{n + 1}$

$a_nn = 1$

$ a_{n + 1} = \frac{a_nn}{n + 1}$
