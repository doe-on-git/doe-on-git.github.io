---
layout: post
title: Github新手向科普（It's not just for geeks!）
description: "
Github能怎好？除了用来管理代码，GitHub还能怎么玩？各种代码名词看起来很复杂？（也许它只是只傲娇的猫星人啦～"
modified: 2019-06-22
lang: zh
tags: [sample post]
image:
  path: /images/abstract-3.jpg
  feature: abstract-3.jpg
  credit: dargadgetz
  creditlink: http://www.dargadgetz.com/ios-7-abstract-wallpaper-pack-for-iphone-5-and-ipod-touch-retina/
---

## Github是什么？（能？）

GitHub最初是为开发者所创建的社区。在这里，程序员们可以进行代码的版本控制与协同工作。但如今，许多的非程序员们也将GitHub作为其创作平台，享受它管理项目与合作的便利。正如GitHub官方所说，GitHub是一个为所有“知识工作者”（knowledge worker）所提供的工具。

与其他的网络平台相比，GitHub更像是一个工具箱。它没有所谓的“正确”玩法，如何利用它来做自己想做的事，一切都靠想象力。推荐一些很有趣的非程序开发向GitHub repo：（repository 即仓库：用来管理项目。后文会有简单介绍）

Public Self ：作者的内心世界，他的三观（belief），他的生活准则（rule），他喜欢的思想等等。
Travel Plan：作者所去过的地方以及想要去的地方。可以看到很多人在这里提出了旅行建议。
The League of Moveable Type：一个开源的字体设计组织，目前有18个仓库。任何人都能够下载字体，并提出设计意见。
A novel：一本完全利用GitHub写成的小说，已在amazon上架。任何人都能够提出修改建议，甚至基于此来写自己的小说。
DC Law：Columbia州的法律，很多人在这里找typo。（不少国家和地区都把法律公开在了GitHub上。甚至于有人传了这个(you-know-what done by you-know-who)
Organizing personal life：一个私人项目（private repo，仅自己可见）利用GitHub来管理自己的生活，如各种文件，照片，to-do list 等等。


## 如何使用GitHub？（怎？）

当然首先你需要一个账号。（大部分功能免费。对于在校学生来说还有student pack，有兴趣可以自行研究。）接下来要怎么做？满屏幕的不明词语令人头秃？不用担心啦，只要大概理解GitHub的工作流程，这只傲娇的Octocat也只是一只傲娇的喵星人而已。

下图是一张简要的github工作流程：
人类1和人类2打算合作写一本小说。在写到第十章时，两人的思路发生了分歧，于是人类2创建了分支(branch)。但随后两人的故事实在无法融合，于是经过协商，他们决定从第十章重新开始写，于是将仓库滚回版本1.2。两人分别完成自己的部分后，将仓库融合(merge)。

A test about in-line math: $$ 5 + 5 $$ \$$ 5 + 5 $$

A test about formular:
$$
\begin{align*}
  & \phi(x,y) = \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right)
  = \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j) = \\
  & (x_1, \ldots, x_n) \left( \begin{array}{ccc}
      \phi(e_1, e_1) & \cdots & \phi(e_1, e_n) \\
      \vdots & \ddots & \vdots \\
      \phi(e_n, e_1) & \cdots & \phi(e_n, e_n)
    \end{array} \right)
  \left( \begin{array}{c}
      y_1 \\
      \vdots \\
      y_n
    \end{array} \right)
\end{align*}
$$


Below is just about everything you'll need to style in the theme. Check the source code to see the many embedded elements within paragraphs.

# Heading 1

## Heading 2

### Heading 3

#### Heading 4

##### Heading 5

###### Heading 6

### Body text

Lorem ipsum dolor sit amet, test link adipiscing elit. **This is strong**. Nullam dignissim convallis est. Quisque aliquam.

![Smithsonian Image]({{ site.url }}/images/3953273590_704e3899d5_m.jpg)
{: .image-right}

*This is emphasized*. Donec faucibus. Nunc iaculis suscipit dui. 53 = 125. Water is H<sub>2</sub>O. Nam sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. The New York Times <cite>(That’s a citation)</cite>. <u>Underline</u>. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.

HTML and <abbr title="cascading stylesheets">CSS<abbr> are our tools. Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus.

### Blockquotes

> Lorem ipsum dolor sit amet, test link adipiscing elit. Nullam dignissim convallis est. Quisque aliquam.

## List Types

### Ordered Lists

1. Item one
   1. sub item one
   2. sub item two
   3. sub item three
2. Item two

### Unordered Lists

* Item one
* Item two
* Item three

## Tables

| Header1 | Header2 | Header3 |
|:--------|:-------:|--------:|
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|----
| cell1   | cell2   | cell3   |
| cell4   | cell5   | cell6   |
|=====
| Foot1   | Foot2   | Foot3
{: rules="groups"}

## Code Snippets

Syntax highlighting via Rouge

```css
#container {
  float: left;
  margin: 0 -240px 0 0;
  width: 100%;
}
```

Non Pygments code example

    <div id="awesome">
        <p>This is great isn't it?</p>
    </div>

## Buttons

Make any link standout more when applying the `.btn` class.

```html
<a href="#" class="btn btn-success">Success Button</a>
```

<div markdown="0"><a href="#" class="btn">Primary Button</a></div>
<div markdown="0"><a href="#" class="btn btn-success">Success Button</a></div>
<div markdown="0"><a href="#" class="btn btn-warning">Warning Button</a></div>
<div markdown="0"><a href="#" class="btn btn-danger">Danger Button</a></div>
<div markdown="0"><a href="#" class="btn btn-info">Info Button</a></div>
