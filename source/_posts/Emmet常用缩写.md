---
title: Emmet常用缩写
tags:
  - Emmet
  - 前端
  - 前端技术
  - 学习
translate_title: emmet-common-abbreviation
date: 2016-08-30 15:01:04
---

## 后代：&gt;

**缩写**：nav&gt;ul&gt;li
> <pre class="xml"><span class="tag">&lt;<span class="title">nav</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">nav</span>&gt;</span>> 
> </pre>

#### 兄弟：+

**缩写**：div+p+bq
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span>&gt;</span><span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">p</span>&gt;</span><span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">blockquote</span>&gt;</span><span class="tag">&lt;/<span class="title">blockquote</span>&gt;</span>> 
> </pre>

#### 上级：^

**缩写**：div+div&gt;p&gt;span+em^bq
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span>&gt;</span><span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">div</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">p</span>&gt;</span><span class="tag">&lt;<span class="title">span</span>&gt;</span><span class="tag">&lt;/<span class="title">span</span>&gt;</span><span class="tag">&lt;<span class="title">em</span>&gt;</span><span class="tag">&lt;/<span class="title">em</span>&gt;</span><span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">blockquote</span>&gt;</span><span class="tag">&lt;/<span class="title">blockquote</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> </pre>
**缩写**：div+div&gt;p&gt;span+em^^bq
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span>&gt;</span><span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">div</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">p</span>&gt;</span><span class="tag">&lt;<span class="title">span</span>&gt;</span><span class="tag">&lt;/<span class="title">span</span>&gt;</span><span class="tag">&lt;<span class="title">em</span>&gt;</span><span class="tag">&lt;/<span class="title">em</span>&gt;</span><span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">blockquote</span>&gt;</span><span class="tag">&lt;/<span class="title">blockquote</span>&gt;</span>> 
> </pre>

#### 分组：()

**缩写**：div&gt;(header&gt;ul&gt;li*2&gt;a)+footer&gt;p
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">header</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>             <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;<span class="title">a</span> <span class="attribute">href</span>=<span class="value">""</span>&gt;</span><span class="tag">&lt;/<span class="title">a</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>             <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;<span class="title">a</span> <span class="attribute">href</span>=<span class="value">""</span>&gt;</span><span class="tag">&lt;/<span class="title">a</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>         <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
>     <span class="tag">&lt;/<span class="title">header</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">footer</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">p</span>&gt;</span><span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
>     <span class="tag">&lt;/<span class="title">footer</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> </pre>
**缩写**：(div&gt;dl&gt;(dt+dd)*3)+footer&gt;p
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">dl</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">dt</span>&gt;</span><span class="tag">&lt;/<span class="title">dt</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">dd</span>&gt;</span><span class="tag">&lt;/<span class="title">dd</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">dt</span>&gt;</span><span class="tag">&lt;/<span class="title">dt</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">dd</span>&gt;</span><span class="tag">&lt;/<span class="title">dd</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">dt</span>&gt;</span><span class="tag">&lt;/<span class="title">dt</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">dd</span>&gt;</span><span class="tag">&lt;/<span class="title">dd</span>&gt;</span>> 
>     <span class="tag">&lt;/<span class="title">dl</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">footer</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">p</span>&gt;</span><span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">footer</span>&gt;</span>> 
> </pre>

#### 乘法：*

**缩写**：ul&gt;li*5
> <pre class="xml"><span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
> </pre>

#### 自增符号：$

**缩写**：ul&gt;li.item$*5
> <pre class="xml"><span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item1"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item2"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item3"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item4"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item5"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
> </pre>
**缩写**：h$[title=item$]{Header $}*3
> <pre class="xml"><span class="tag">&lt;<span class="title">h1</span> <span class="attribute">title</span>=<span class="value">"item1"</span>&gt;</span>Header 1<span class="tag">&lt;/<span class="title">h1</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">h2</span> <span class="attribute">title</span>=<span class="value">"item2"</span>&gt;</span>Header 2<span class="tag">&lt;/<span class="title">h2</span>&gt;</span>> 
> <span class="tag">&lt;<span class="title">h3</span> <span class="attribute">title</span>=<span class="value">"item3"</span>&gt;</span>Header 3<span class="tag">&lt;/<span class="title">h3</span>&gt;</span>> 
> </pre>
**缩写**：ul&gt;li.item$$$*5
> <pre class="xml"><span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item001"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item002"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item003"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item004"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item005"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
> </pre>
**缩写**：ul&gt;li.item$@-*5
> <pre class="xml"><span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item5"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item4"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item3"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item2"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item1"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
> </pre>
**缩写**：ul&gt;li.item$@3*5
> <pre class="xml"><span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item3"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item4"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item5"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item6"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"item7"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
> </pre>> 
> 
> #### ID和类属性
**缩写**：#header
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span> <span class="attribute">id</span>=<span class="value">"header"</span>&gt;</span><span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> </pre>
**缩写**：.title
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span> <span class="attribute">class</span>=<span class="value">"title"</span>&gt;</span><span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> </pre>
**缩写**：form#search.wide
> <pre class="xml"><span class="tag">&lt;<span class="title">form</span> <span class="attribute">id</span>=<span class="value">"search"</span> <span class="attribute">class</span>=<span class="value">"wide"</span>&gt;</span><span class="tag">&lt;/<span class="title">form</span>&gt;</span>> 
> </pre>
**缩写**：p.class1.class2.class3
> <pre class="xml"><span class="tag">&lt;<span class="title">p</span> <span class="attribute">class</span>=<span class="value">"class1 class2 class3"</span>&gt;</span><span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
> </pre>

#### 自定义属性

**缩写**：p[title="Hello world"]
> <pre class="xml"><span class="tag">&lt;<span class="title">p</span> <span class="attribute">title</span>=<span class="value">"Hello world"</span>&gt;</span><span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
> </pre>
**缩写**：td[rowspan=2 colspan=3 title]
> <pre class="xml"><span class="tag">&lt;<span class="title">td</span> <span class="attribute">rowspan</span>=<span class="value">"2"</span> <span class="attribute">colspan</span>=<span class="value">"3"</span> <span class="attribute">title</span>=<span class="value">""</span>&gt;</span><span class="tag">&lt;/<span class="title">td</span>&gt;</span>> 
> </pre>
**缩写**：[a='value1' b="value2"]
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span> <span class="attribute">a</span>=<span class="value">"value1"</span> <span class="attribute">b</span>=<span class="value">"value2"</span>&gt;</span><span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> </pre>

#### 文本：{}

**缩写**：a{Click me}
> <pre class="xml"><span class="tag">&lt;<span class="title">a</span> <span class="attribute">href</span>=<span class="value">""</span>&gt;</span>Click me<span class="tag">&lt;/<span class="title">a</span>&gt;</span>> 
> </pre>
**缩写**：p&gt;{Click }+a{here}+{ to continue}
> <pre class="xml"><span class="tag">&lt;<span class="title">p</span>&gt;</span>Click <span class="tag">&lt;<span class="title">a</span> <span class="attribute">href</span>=<span class="value">""</span>&gt;</span>here<span class="tag">&lt;/<span class="title">a</span>&gt;</span> to continue<span class="tag">&lt;/<span class="title">p</span>&gt;</span>> 
> </pre>

#### 隐式标签

**缩写**：.class
> <pre class="xml"><span class="tag">&lt;<span class="title">div</span> <span class="attribute">class</span>=<span class="value">"class"</span>&gt;</span><span class="tag">&lt;/<span class="title">div</span>&gt;</span>> 
> </pre>
**缩写**：em&gt;.class
> <pre class="xml"><span class="tag">&lt;<span class="title">em</span>&gt;</span><span class="tag">&lt;<span class="title">span</span> <span class="attribute">class</span>=<span class="value">"class"</span>&gt;</span><span class="tag">&lt;/<span class="title">span</span>&gt;</span><span class="tag">&lt;/<span class="title">em</span>&gt;</span>> 
> </pre>
**缩写**：ul&gt;.class
> <pre class="xml"><span class="tag">&lt;<span class="title">ul</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">li</span> <span class="attribute">class</span>=<span class="value">"class"</span>&gt;</span><span class="tag">&lt;/<span class="title">li</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">ul</span>&gt;</span>> 
> </pre>
**缩写**：table&gt;.row&gt;.col
> <pre class="xml"><span class="tag">&lt;<span class="title">table</span>&gt;</span>> 
>     <span class="tag">&lt;<span class="title">tr</span> <span class="attribute">class</span>=<span class="value">"row"</span>&gt;</span>> 
>         <span class="tag">&lt;<span class="title">td</span> <span class="attribute">class</span>=<span class="value">"col"</span>&gt;</span><span class="tag">&lt;/<span class="title">td</span>&gt;</span>> 
>     <span class="tag">&lt;/<span class="title">tr</span>&gt;</span>> 
> <span class="tag">&lt;/<span class="title">table</span>&gt;</span>> 
> </pre>

### 

&nbsp;

[Emmet官方cheat-sheet](http://docs.emmet.io/cheat-sheet/)