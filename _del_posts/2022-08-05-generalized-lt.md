---
layout: post
comments: true
title: "Why do we need the generalized long-tailed classification"
date: 2022-08-05 02:00:00
tags: data_imbalance
---


> This article mainly discusses the limitations of the existing class-wise long-tailed classification tasks. It also introduces our ECCV 2022 paper Invariant Feature Learning for Generalized Long-Tailed Classification. 

<!--more-->

{: class="table-of-content"}
* TOC
{:toc}

## Reflections and prospects on long-tail classification problems

Let’s start with our conclusion: if the training set and the test set are independent and identically distributed (IID) and the long tail is only reflected in the distribution of classes, Google’s [Logit Adjustment research](https://arxiv.org/abs/2007.07314) has theoretically provided a very elegant solution . In other words, the traditional long-tailed classification setting in computer vision has already been "perfectly" solved. So this brings up two questions: (1) What exactly has the recent "progress" in the field of long-tail classification improved? (2) Do we still need to work on the long-tailed distribution problem in the future? 

### An elegant formulation of IID inter-class long-tail classification

First of all, we need to explain why the IID inter-class long-tail classification problem has been perfectly solved.



Hello World, balabalabala

## Emphasis

*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_



## Lists

Unordered
- Item 1
- Item 2
  - Item 2a
  - Item 2b


Ordered
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b


## Images


![My Logo]({{ '/assets/logos/logo_home.png' | relative_url }})
{: style="width: 50%;" class="center"}
*Fig. 1: This Logo is created by Troll (https://dribbble.com/shots/4668586-Red-Panda). All rights reserved by Him/Her.*
{:.image-caption}


## Links
[GitHub](http://github.com)


## Blockquotes
As Kanye West said:

> We're living the future so
> the present is our past.


## Inline code
To print some text with python, you should use the `print()` function.
```
print("Hello world!")
```


## Example of Mathematic Fomulars

$$
\mathcal{L}_u^\Pi = \sum_{\mathbf{x} \in \mathcal{D}} \text{MSE}(f_\theta(\mathbf{x}), f'_\theta(\mathbf{x}))
$$

$$n$$ feed-forward networks as experts $$\{E_i\}^n_{i=1}$$

$$p(x)$$, $$p(y \mid x)$$, $$\frac{p(x)}{p(y)}$$, $$p(y \mid x)=\frac{p(x \mid y)p(y)}{p(x)}$$

## References

[1] Lilian Weng. [“Lil'Log”](https://lilianweng.github.io/lil-log/).
