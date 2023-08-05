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

```{theorem, label, name="Mean value theorem"}
Suppose that $O\subset mathbb{R}$ is an open set, $f:O\rightarrow \mathbb{R}$ is a differentiable function. Then for any interval $[a,b]\subset O$, there exists $c\in [a,b]$ such that
$$ f(b)-f(a) = f'(c)(b-a) $$
```

This mean value theorem can be extended to the case where $O$ is a subset of $\mathbb{R}^p$, we denote it as general mean value theorem
```{theorem, label, name="General mean value theorem"}
Suppose that $O\subset mathbb{R}^p$ is an open set, $f:O\rightarrow \mathbb{R}$ is a differentiable function. Then for any two points $a,b \in O$, suppose the line segment is a subset of $O$, there exists $c$ belonging to the line segment such that
$$ f(b)-f(a) = [f'(c)]^T(b-a) $$
```
The proof of the general mean value theorem can be found [here]([https://link-url-here.org](http://www.math.toronto.edu/courses/mat237y1/20199/notes/Chapter2/S2.4.html)http://www.math.toronto.edu/courses/mat237y1/20199/notes/Chapter2/S2.4.html). 

However, for vector valued function, there is direct extension of mean-value theorem. 




------
