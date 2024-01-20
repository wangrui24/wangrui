---
layout: post
title: Nonexistent mean value theorem
date: 2023-05-12 15:53:00-0400
description: 
categories: math
giscus_comments: true
related_posts: true
---
## Nonexistent mean value theorem

Mean value theorem is a well known and widely-used theorem in statistical literature. The most common mean-value theorem in standard calculus textbook is stated as follows:

## Mean value theorem

Suppose that $O\subset mathbb{R}$ is an open set, $f:O\rightarrow \mathbb{R}$ is a differentiable function. Then for any interval $[a,b]\subset O$, there exists $c\in [a,b]$ such that

$$ f(b)-f(a) = f'(c)(b-a) $$


This mean value theorem can be extended to the case where $O$ is a subset of $\mathbb{R}^p$, we denote it as general mean value theorem
## General mean value theore
Suppose that $O\subset mathbb{R}^p$ is an open set, $f:O\rightarrow \mathbb{R}$ is a differentiable function. Then for any two points $a,b \in O$, suppose the line segment is a subset of $O$, there exists $c$ belonging to the line segment such that

$$ f(b)-f(a) = [f'(c)]^T(b-a) $$

The proof of the general mean value theorem can be found [here]([https://link-url-here.org](http://www.math.toronto.edu/courses/mat237y1/20199/notes/Chapter2/S2.4.html)http://www.math.toronto.edu/courses/mat237y1/20199/notes/Chapter2/S2.4.html). 

However, for vector valued function, there is direct extension of mean-value theorem. Following the paper listed in the end of this post, we called this Nonexistent mean value theorem (which is wrong!)


## Nonexistent mean value theorem 
Suppose that $O\subset mathbb{R}^p$ is an open set, $f:O\rightarrow \mathbb{R}^q$ is a differentiable function. Then for any two points $a,b \in O$, suppose the line segment is a subset of $O$, there exists $c$ belonging to the line segment such that

$$ f(b)-f(a) = [f'(c)]^T(b-a) $$


The reference paper also gives some examples that misuse this nonexistent theorem, including the famous semiparametric theory and missing data book. However, even though the nonexistent mean value theorem is wrong in general, there are two similar theorem can be used.

## First-order Taylor’s expansion
Suppose that $O\subset mathbb{R}^p$ is an open set, $f:O\rightarrow \mathbb{R}^q$ is a differentiable function. Then for any two points $a,b \in O$, we have

$$ f(b)-f(a) = [f'(a)]^T(b-a) + o(\Vert b-a \Vert) $$

This formula follows from the definition of differentiability. Another theorem, which can be found in the famous 'A course in large sample theory' book,

## Multivariate mean value theorem
Suppose that  $f:\mathbb{R}^p\rightarrow \mathbb{R}^q$ is a differentiable function and the derivative $Df$ is continuous in a neighborhood ${x: \Vert x-x_0 \Vert<r} $ of $x_0$, then for all $t$ with $\Vert t \Vert\leq r$

$$ f(x_0+t)-f(x_0) = \int_{0}^1 Df(x_0+ut)du \cdot t$$



Reference:
Feng, C., Wang, H., Han, Y., Xia, Y., & Tu, X. M. (2013). The mean value theorem and Taylor’s expansion in statistics. The American Statistician, 67(4), 245-248.
------
