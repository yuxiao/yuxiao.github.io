---
layout: post
category : blog
tagline: "Supporting tagline"
tags : [intro, markdown]
---
{% include JB/setup %}

测试中文页面!
===================


一直在想着开始写博客，却总是在折腾一些基础建设，没有实际内容输出，深感惭愧~
定力不行，专注度不行，基本功也比较欠缺。
还有，大部分时间花在看剧上面，得改改了。

----------


技能进展
-------------

近期本人研究的领域，做个总结。

#### BLE

只是拿一个cypress的开发板跑了下demo程序，结合手机app演示了蓝牙控制三色灯。
然后找了下ble的中文资料，想了解ble通讯需要的基础知识，并没有太大收获，后期还需要认真研究代码和尝试修改

> **目标**
> - 实现透传串口功能
> - 研究ibeacon

#### Python

学了下基本语法，主要用于处理一些工作上的自动化任务，例如批量生成蓝牙MAC地址列表，之前用智能卡大师脚本比较慢，现在换成Python之后速度有了质的飞跃:)

> **目标**
> - 实践web开发，重新开发公司网站
> - 研究如何调dll或c库，进一步优化速度，比如DES算法

#### JavaScript

大多浅尝辄止，还处于比较入门的阶段，主要是没有编码产出，没有实质进步

#### Git

通过折腾本博客的过程，熟悉了基本用法

> **目标**
> - 继续blog建设，记录技术点滴

----------


娱乐项目
-------------------

又进入深宅的阶段了 -_-!

#### 影视剧

业余时间大多花在了这方面

**目前进展**
- The Big Bang Thorey 
    轻松搞笑幽默 
    从第4季开始看到现在的第9季，追更中
- 冰与火之歌-权利的游戏 
    血腥暴力暴露
    从第一季开始，已到第二季末尾了，这个真的很耗时间

#### 音乐

无


### 运动

跑步，频率大概2周一次，最近天冷，估计要变成一月一次了。
俯卧撑，现在一次只能坚持到50，现在天冷，要变成重点项目，因为懒

### 社交

无


**Markdown Extra** has a special syntax for tables:

Item     | Value
-------- | ---
Computer | $1600
Phone    | $12
Pipe     | $1

You can specify column alignment with one or two colons:

| Item     | Value | Qty   |
| :------- | ----: | :---: |
| Computer | $1600 |  5    |
| Phone    | $12   |  12   |
| Pipe     | $1    |  234  |


### Definition Lists

**Markdown Extra** has a special syntax for definition lists too:

Term 1
Term 2
:   Definition A
:   Definition B

Term 3

:   Definition C

:   Definition D

	> part of definition D


### Fenced code blocks

GitHub's fenced code blocks are also supported with **Highlight.js** syntax highlighting:

```
// Foo
var bar = 0;
```

> **Tip:** To use **Prettify** instead of **Highlight.js**, just configure the **Markdown Extra** extension in the <i class="icon-cog"></i> **Settings** dialog.

> **Note:** You can find more information:

> - about **Prettify** syntax highlighting [here][5],
> - about **Highlight.js** syntax highlighting [here][6].


### Footnotes

You can create footnotes like this[^footnote].

  [^footnote]: Here is the *text* of the **footnote**.


### SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                  | ASCII                        | HTML              |
 ----------------- | ---------------------------- | ------------------
| Single backticks | `'Isn't this fun?'`            | 'Isn't this fun?' |
| Quotes           | `"Isn't this fun?"`            | "Isn't this fun?" |
| Dashes           | `-- is en-dash, --- is em-dash` | -- is en-dash, --- is em-dash |


### Table of contents

You can insert a table of contents using the marker `[TOC]`:

[TOC]


### MathJax

You can render *LaTeX* mathematical expressions using **MathJax**, as on [math.stackexchange.com][1]:

The *Gamma function* satisfying $\Gamma(n) = (n-1)!\quad\forall n\in\mathbb N$ is via the Euler integral

$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

> **Tip:** To make sure mathematical expressions are rendered properly on your website, include **MathJax** into your template:

```
<script type="text/javascript" src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS_HTML"></script>
```

> **Note:** You can find more information about **LaTeX** mathematical expressions [here][4].


### UML diagrams

You can also render sequence diagrams like this:

```sequence
Alice->Bob: Hello Bob, how are you?
Note right of Bob: Bob thinks
Bob-->Alice: I am good thanks!
```

And flow charts like this:

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
```

> **Note:** You can find more information:

> - about **Sequence diagrams** syntax [here][7],
> - about **Flow charts** syntax [here][8].

### Support StackEdit

[![](https://cdn.monetizejs.com/resources/button-32.png)](https://monetizejs.com/authorize?client_id=ESTHdCYOi18iLhhO&summary=true)

  [^stackedit]: [StackEdit](https://stackedit.io/) is a full-featured, open-source Markdown editor based on PageDown, the Markdown library used by Stack Overflow and the other Stack Exchange sites.


  [1]: http://math.stackexchange.com/
  [2]: http://daringfireball.net/projects/markdown/syntax "Markdown"
  [3]: https://github.com/jmcmanus/pagedown-extra "Pagedown Extra"
  [4]: http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference
  [5]: https://code.google.com/p/google-code-prettify/
  [6]: http://highlightjs.org/
  [7]: http://bramp.github.io/js-sequence-diagrams/
  [8]: http://adrai.github.io/flowchart.js/