---
layout: post
title: Sensitive Dependence for Unimodal Maps on the Interval
description: "Unimodal maps"
category: articles
tags: [Math, Analysis]
comments: true  
---

{% include default.html %}
A function $~f : [a,b] \to [0,1]$ is unimodal if $~f(a) = f(b) = 0$, and
there is a point $~c$ in $~(a,b)$ such that 
$~f$ is strictly increasing on $~[a,c]$ and strictly decreasing on
$~[c,b]$. If $~[a,b] = [0,1]$, then we can consider the composition 
of $~f$ with itself $~n$ times, and we will denote that by $~f^n$. We can
think of $~f$ as a dynamical system that gives a rule for 
how states change after time $~n$. (If the initial state is $~x$, then
after one unit of time, the new state is $~f(x)$, and after two 
units of time, it is $~f^2(x)=f(f(x))$, etc. ) One of the features 
of a chaotic dynamical system is that for a given initial condition 
$~x$, you can find another initial condition $~y$, arbitrarily close to
$~x$, such that after a long period of time $~n$, $~f^n(x)$ and $~f^n(y)$ 
are far apart. This is called sensitive dependence on initial conditions.
Intuitively, it means that the long-term future 
cannot be accurately predicted, because there will always be some errors 
in measuring the initial conditions. I will discuss an easily verifiable 
condition on the derivatives of $~f$ (in the case of a three times
differentiable unimodal map $~f$) that will guarantee sensitive dependence on initial conditions. 
Math M211 is the only prerequisite for this talk.
FOO FOO FOO FOO

