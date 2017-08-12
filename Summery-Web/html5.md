# html5笔记

## html5标签和属性

## 标签

hgroup

figure

<video src="" controls="controls"></video>

audio同上

mark

time

<canvas id="myCanvas" width="200" hight="200"></canvas>

output

source

<menu>

​      <li><input type="checkbox"</li>

</menu>

## 全局属性

<ul contentEditable="true">可以进行编辑</ul>

designMode     on和off

hidden    true和false

spellcheck    true和false

tabindex     按tab键访问元素

## 其他功能

querySelector()

querySelectorAll()

## 基本格局笔记

1，article 和 section区分

- article注重内容完整独立性；section注重关联性

2.draggable="true" 可拖拽

3.nav 设计导航信息

4.aside 设计辅助信息；两种： article的辅助或者全局的辅助信息

5.设计微格式：简化web开发的数据提取（根据标签抓取信息）

- 文章发表时间、作者、修改时间等

6.添加发布日期

- <p>发布日期<time datetime="2012-5-22" pubdate>2012年5月22日</time></p>
- time也可以表示通知、约会等其他时间，上例中加pubdate表示是发布日期

7.hgroup给标题编组

<header><hgroup><h1></h1><h2></h2></hgroup>

<p><time datetime="">发布时间</time></p></header>

8.添加脚注块

- 作者、版权信息、相关阅读等

9.添加联系信息   address

<address>

<a title="作者" html="">W3C</a>

</address>

## 设计















