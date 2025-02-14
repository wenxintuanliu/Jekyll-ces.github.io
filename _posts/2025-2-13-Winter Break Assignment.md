---
layout: post
title: Winter Break Assignment
date: 2025-02-13 13:25:57 +0800
last_modified_at: 2025-02-13 13:25:59 +0800
tags: [Assignment, Conclusion]
toc:  true
---
Welcome to **我的必做与选做**! 下面我将对以下内容展开回忆.
{: .message }

>- 个人信息
>- 学习情况
>- 职业规划
>**上述信息在word文档中体现**
>- **生活愿景**
  
---------
- 新技能
- 农村招标项目披露

## 生活愿景
  1.希望工作地点在家乡（其实感觉在哪里都可以，但是退休后应该是在家乡），如果有国外工作的可能，希望时间不宜过长，最多十年。  
  2.我希望工作稳定，属于稀缺性人才那种哈哈哈😄,对未来生活我没过多考虑，也没过多奢求，只是希望不要太简单，也不要困难得我难以喘气；人应当在考验与抉择中度过此生。  
  3.至于我想要成为什么样的人，我认为这是水到渠成的结果，我也难以用几个标签贴在我身上，我自认为我难以保持，我不愿意背着几个空壳在世上行走；总之，当我在往后几年、几十年回忆一些事的时候，发现我绝大多数在对的时空下做了对的事，那我就十分满足了。  
  4.我没有**最**崇拜的人，以我的评判标准得出值得我崇拜的人中，许多都是平行的。人的思维就是很奇妙，很难将这种非数指标量化为严谨的数值排列，所以我的脑子告诉我：我没法排出**最**崇拜的人。没法排出绝对的第一，但某些人当我想到他的神态作风的时候，他却能无限接近于这一位置。理查德。费曼教授就是这样一个例子。  
  在我的微信朋友圈主页上一直放着这张照片：
  ![alt text]({{ site.baseurl }}/pictures/f7aa1908fe233a44ad90dc48bf2b316.jpg)
  至于为什么，如果我说我只从几个短视频或长视频、他的照片或他的访谈中就能将他排为伪1，你可能不信。**但确实是这样的**。最核心的是我认为他含有**真**这个属性。他的思考方式和一些想法是十分令人羡慕的，我估计很难达到他这种状态。[视频](https://www.bilibili.com/video/BV1wo4y197nX/?spm_id_from=333.337.search-card.all.click&vd_source=31b093f01b01f65c886b2a4b2ea15e38)

你知道，存在人类几百万年，有记录的、没有记录的；被推崇的、被贬低的；声名显赫的、默默无闻的；在世上活着的和死了的人太多了！改变世界的，一个是科学、一个是政治、一个是天地，而思考是这些的全部。

------
## 新技能——搭建网页
如你所见，现在你正在浏览一个网页。  
编写完成的网页花费了我3天，老师您要求`写一篇不少于3000字的学习记录及心得体会`,我估计写不了这么多，我真写这么多估计许多都是废话	😂；  
### 学习记录
1.产生搭建网页的想法  
于是乎按下面图上的步骤进行：
<![alt text]({{ site.baseurl }}/pictures/1.png)
了解到要服务器要**买**！！！好，遂放弃  
2.在进行上述步骤的时候无意了解到github中的GitHub Pages功能  
>GitHub Pages 是 GitHub 提供的一个免费的静态网站托管服务，它允许 GitHub 用户创建和托管自己的静态网站，这些网站可以通过特定的 GitHub 仓库进行管理和托管。 
好，开始：
- github注册
为了能较流畅访问github.com（大好青年应防止沉迷**科学上网**😋）,修改hosts文件，添加相关IP地址
>修改的内容：<https://gitee.com/jyotish/githubhosts/>
之后能打开github.com，便注册成功了  
3.添加仓库
 ![alt text]({{ site.baseurl }}/pictures/2.png)
添加成功后还不能得到自己的网址，需要至少在根目录下添加一个**index.html**,因为其默认读取index.html。等2分钟左右在**setting>Pages**发现已经有自己的网址了。
 ![alt text]({{ site.baseurl }}/pictures/3.png)  
 >还需要设置Build and deployment等  
 这个时候打开网页就能看到index.html内容了  
 
 上述过程我基本没有遇到困难，我想主要由于我之前找到了一份指南：<https://zhuanlan.zhihu.com/p/91652100>

 但是仍然面临两个问题：  
 1.我该如何构建网页内容？  
 虽然在index.html编写能够实现基本要求，但是维护太麻烦，并且只能有一个页面，显然这是不够的。我需要能分层管理和实现多个网页跳转。  
 2.如何将网页文件在本地编写后发到仓库  
 因为虽然在github上能直接修改并上传，但是操作过你就会发现相当繁琐。我希望在本地IDE编写调试后再上传，效率能大大提高。  

 **解决**
 1.对问题1，一是可以将多个网页`html`文件或样式文件`css`等上传到根目录，在html文件指定好跳转网页的文件位置，如下面**成果展示**1就是这样实现的；二是学习更复杂的网页构建知识，学会分层管理，由于这个学习成本颇高（可能针对专业学生），我自然不愿花费太多时间学习专业知识。后来我想自己既然从头开始很难，为什么不使用别人的开源模板呢？  
 其实在之前构建github网页时，我在浏览网页的时候就了解到Github-Pages就默认使用**Jekll**模版，然后我在网址<https://jekyllthemes.io/free>找到本网页使用的模板并下载。此模板包含的文件如果你替换到你仓库的index.html，你就能得到此模版得到的网页！！！  
 好了，别人的永远是别人的，感谢其开源为我带来了便利，但是网页我肯定需要改为我的内容或者改为我想要的形式。那么，就需要知道这些文件的作用的是什么。某些文件名字可以删改，这就意味着两个不同的**Jekll**模板可能文件夹名字不完全相同，这就没有统一的学习标准，即当我看到某个文件夹我不知道他里面的内容是用来干什么的：是用来定义首页样式还是总体布局、还是子页面样式。这当然比较麻烦，必须要了解了每个文件的作用。
 >到此步我还只能适应模板的不同  
 2.对问题2
 Git！！！！！OK  
 [Git的安装](https://blog.csdn.net/mukes/article/details/115693833)  
 [Git的使用](https://blog.csdn.net/ZYZMZM_/article/details/86142418)  
 在此不做赘述，因为上述两个网站将的很清楚了。

---------
>写在最后:这样一个简单的网页搭建给我的感悟是：  
1.在实行操作前请先做必要准备，比如浏览较多相关知识网页后再选择较好的网页进行操作，因为每个人在实际实施时会遇到不同的问题，博客和AI真的提供了很好的解决办法；  
2.许多博客提到的内容或方法或许没有采用，但很可能在几个月后你从事完全不同的工作时会使用这些方法。

下面我来总结下搭建我这样简单的网页的流程吧：  
1.创建`.github.io仓库`并进行相关设置；  
这就能拥有一个关联到属于自己的仓库的网址而不必购买云服务器  
2.本地安装`Jekll`主题(如果想保持在github提供的网页上打开就不必，主要为了方便本地服务器打开)；  
3.fork或clone喜欢的主题仓库到本地做删改再上传就变成自己希望的内容了。`本网页的搭建就基于某个主题，因为我不具备写大型网页的能力`  
>说明：2、3步骤可以直接不用进行，在仓库根目录下创建个index.html网页即可实现最简单地网页

### 成果展示
1.[纯html的不良导体导热系数计算网页](https://wenxintuanliu.github.io/Calculation-of-the-thermal-conductivity-of-poor-conductors.github.io/):
 ![alt text]({{ site.baseurl }}/pictures/image.png)  
 2.[带少量css和js的简陋主页面](https://wenxintuanliu.github.io/stru-web.github.io/):
 ![alt text]({{ site.baseurl }}/pictures/image-1.png)  
3.你所见的

----
## 项目披露

<!-- - **To bold text**, use `<strong>`.
- *To italicize text*, use `<em>`.
- <mark>To highlight</mark>, use `<mark>`.
- Abbreviations, like <abbr title="HyperText Markup Langage">HTML</abbr> should use `<abbr>`, with an optional `title` attribute for the full phrase.
- Citations, like <cite>&mdash; Mark Otto</cite>, should use `<cite>`.
- <del>Deleted</del> text should use `<del>` and <ins>inserted</ins> text should use `<ins>`.
- Superscript <sup>text</sup> uses `<sup>` and subscript <sub>text</sub> uses `<sub>`. -->

## Footnotes

Footnotes are supported as part of the Markdown syntax. Here's one in action. Clicking this number[^fn-sample_footnote] will lead you to a footnote. The syntax looks like:

{% highlight text %}
Clicking this number[^fn-sample_footnote]
{% endhighlight %}

Each footnote needs the `^fn-` prefix and a unique ID to be referenced for the footnoted content. The syntax for that list looks something like this:

{% highlight text %}
[^fn-sample_footnote]: Handy! Now click the return link to go back.
{% endhighlight %}

You can place the footnoted content wherever you like. Markdown parsers should properly place it at the bottom of the post.

## Heading

Vivamus sagittis lacus vel augue rutrum faucibus dolor auctor. Duis mollis, est non commodo luctus, nisi erat porttitor ligula, eget lacinia odio sem nec elit. Morbi leo risus, porta ac consectetur ac, vestibulum at eros.

### Code

Inline code is available with the `<code>` element. Snippets of multiple lines of code are supported through Rouge. Longer lines will automatically scroll horizontally when needed. You may also use code fencing (triple backticks) for rendering code.

{% highlight js %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

You may also optionally show code snippets with line numbers. Add `linenos` to the Rouge tags.

{% highlight js linenos %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa.

### Lists

Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Aenean lacinia bibendum nulla sed consectetur. Etiam porta sem malesuada magna mollis euismod. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.

- Praesent commodo cursus magna, vel scelerisque nisl consectetur et.
- Donec id elit non mi porta gravida at eget metus.
- Nulla vitae elit libero, a pharetra augue.

Donec ullamcorper nulla non metus auctor fringilla. Nulla vitae elit libero, a pharetra augue.

1. Vestibulum id ligula porta felis euismod semper.
2. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.
3. Maecenas sed diam eget risus varius blandit sit amet non magna.

Cras mattis consectetur purus sit amet fermentum. Sed posuere consectetur est at lobortis.

<dl>
  <dt>HyperText Markup Language (HTML)</dt>
  <dd>The language used to describe and define the content of a Web page</dd>

  <dt>Cascading Style Sheets (CSS)</dt>
  <dd>Used to describe the appearance of Web content</dd>

  <dt>JavaScript (JS)</dt>
  <dd>The programming language used to build advanced Web sites and applications</dd>
</dl>

Integer posuere erat a ante venenatis dapibus posuere velit aliquet. Morbi leo risus, porta ac consectetur ac, vestibulum at eros. Nullam quis risus eget urna mollis ornare vel eu leo.

### Images

Quisque consequat sapien eget quam rhoncus, sit amet laoreet diam tempus. Aliquam aliquam metus erat, a pulvinar turpis suscipit at.

![placeholder](http://placehold.it/800x400 "Large example image")
![placeholder](http://placehold.it/400x200 "Medium example image")
![placeholder](http://placehold.it/200x200 "Small example image")

Align to the center by adding `class="align-center"`:

![placeholder](http://placehold.it/400x200 "Medium example image"){: .align-center}

### Tables

Aenean lacinia bibendum nulla sed consectetur. Lorem ipsum dolor sit amet, consectetur adipiscing elit.

<table>
  <thead>
    <tr>
      <th>Name</th>
      <th>Upvotes</th>
      <th>Downvotes</th>
    </tr>
  </thead>
  <tfoot>
    <tr>
      <td>Totals</td>
      <td>21</td>
      <td>23</td>
    </tr>
  </tfoot>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>10</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>4</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Charlie</td>
      <td>7</td>
      <td>9</td>
    </tr>
  </tbody>
</table>

Nullam id dolor id nibh ultricies vehicula ut id elit. Sed posuere consectetur est at lobortis. Nullam quis risus eget urna mollis ornare vel eu leo.

-----

Want to see something else added? <a href="https://github.com/vszhub/not-pure-poole/issues/new">Open an issue.</a>

[^fn-sample_footnote]: Handy! Now click the return link to go back.
