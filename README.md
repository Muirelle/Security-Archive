# hut-sec 
## 18-12-16
算算上次11-28到现在才20天不到.现在二进制有人搞,web学的还挺快...比我去年好多了...现在我布置下这阶段的任务:
  
Web方向
  
- PHP:学习MVC框架,这里推荐我当初学的:https://www.awaimai.com/128.html
- http协议,tcp/ip协议等知识:可以购买书籍(<<图解http>>等,多看看没事), 届时我会带几本过来.
- Linux系统的学习:书籍<<鸟哥的Linux私房菜>>
  
Bin
  
- 继续看汇编语言?
- 等你们的pwn学长,re学姐布置吧

Web方向,关于书本的学习,不要求记住,但是要有印象. 这样以后遇到相关问题不至于抓耳挠腮.遇到搞不懂的,不需要你死究,有个印象就好.以后遇到实际问题,你就能够理解了.  
至于Bin,我就不懂了.
  
## 18-11-28
今天晚上大概看了下你们有学python的,有看php的,还有看css样式的.  
我还是推荐你们web的先去学php,python对于你们目前来说用处不是特别大,css也没必要过多的去了解,这些你们现在根本用不上.对入门基本没帮助.  
  
然后希望你们能够看了解下二进制方面哇....web狗真的不好活..pwn爷爷才是正道.虽然二进制主要是英文资料.但是希望你们能够多去看看.但是web到后面也是有很多英文资料的,尽早接触英文还是蛮不错的.  

所以你们目前这样学:  
web方向
  
- 主要先学习好php,尽早掌握php的语法.  
- 之后学者会给你们布置接下来的任务
     
二进制方向
  
- 首先学习汇编语言(图书馆可以借,学长会带1,2本到实验室)
- 也可以看视频 b站搜索:小甲鱼的汇编
- 感兴趣的多和田仲立学长,和杨思诺学姐交流,了解如何下手学习二进制,不要害羞哈...不懂就问就好.web狗不知道这个怎么入门...

学习的过程中,无论是看视频还是看书,必须亲自动手实践.  
你们目前主要任务是确定自己的学习方向
2个方向都需要了解
## 前言
目前比较主流的两个网络安全大方向，也是我们组主要的两个方向

 - Web安全
 - 二进制安全

简单的说 Web安全主要研究对象是运行的Web服务，偏向应用层。  
二进制安全会更底层，对基础要求比较高。  

可以自己通过搜索引擎了解一下这两个方向的相关知识。（信息搜集能力也是一个黑客的必要前提

考虑到大部分人之前可能没有了解过，会给一段考虑选择的时间。前期可以两个都学，然后选一个适合自己的方向深入学习。

**最迟**需要在**寒假结束前**给出明确的学习方向。

以下是目前两个方向的学习计划。

## Web
Web安全的基础是开发，需要知道网站是如何运作的，才能知道网站是如何被攻击的（know it then hack it

- **了解** 静态网页基础 html 、css 、 javascript
- **熟悉** 一门动态Web开发语言 —— PHP 
- **了解** 数据库——MySQL的基本使用:建立数据库,建立表,插入数据,数据查询等。

注意**了解**和**熟悉**的区别。
> **了解**只需要能够看懂它是干什么的  
> **熟悉**需要自己能够独立的进行开发
  
关于PHP,首先了解基本的PHP语法,然后再学习PHP和数据库以及html的交互  
  
PHP初步入门(语法):  
  
- 菜鸟教程,w3school.com  
- 书籍:《PHP从入门到精通》(滑稽.jpg,学长当初是看这个的hhh)  
- 博客:csdn  
  
PHP开发进阶(PHP和mysql及html的交互): 
   
- 书籍《php and MySQL Web Development》  
- 博客:csdn,个人博客等..  

最终的目的需要自己实现一个小型留言板的网站
> 不需要华丽的前端设计,需要的是你理解前端和后端的交互过程,并且自己能够独立完成这个过程。 
  
PHP及MySQL的环境安装,网上都是有教程的(可能很耗时间,所以需要耐心,如果成功了,可以记录下自己的过程).  

有问题可以问李盛旗学长,李星辰学长,以及黄耀康学长.问t神,k神也可以(偷看.jpg)  

eg:网安的学习需要你们多实践,多思考.问问题前百度(谷歌)先行.鼓励多思考,多问思考过的问题.
## Bin
**前置技能**：

  - 掌握汇编基础：王爽《汇编语言》、虚拟机安装Ubuntu（建议版本16.4）、Linux基本操作、GDB调试、IDA调试（静态调试）（前期懂简单操作就行，后面根据视频以及使用手册再增加）Python
  - 工具说明书：[GDB使用手册](https://blog.csdn.net/weiyuefei/article/details/72522973),IDA暂时还没找到，找到比较好的可以交流一波

### Pwn
  - 基础的调试、入门首选 [LiveOverFlow](http://liveoverflow.com/binary_hacking/) （翻墙官网能自动翻译）
### Reverse
  - 在前置技能完成后推荐找一个讲解ctf逆向题目的入门视频，一是了解ida基本的静态调试，二是增加兴趣
  - 增加工具：虚拟机安装win7、吾爱破解Ollydug（动态调试）
  - 学习程序调试技能：逆向工程核心原理
 
 后期学习计划我放在我的博客里面[snow146](https://snow146.github.io/),有什么问题可以看我和田仲立学长的博客[Muirelle](https://muirelle.com/)，也欢迎来提问

### 参考资料
  - 论坛：看雪、吾爱、tuts4you**（逛论坛很重要，大佬，学习资料，工具，题解，不懂的问题都能找到）**
# Reference
- [Web-Security-Learning](https://github.com/CHYbeta/Web-Security-Learning) （较好的web安全相关学习资源）
- [CTF-All-In-One](https://github.com/firmianay/CTF-All-In-One) （一本 CTF 领域的大杂烩指南）
- [Awesome-Hacking](https://github.com/Hack-with-Github/Awesome-Hacking) （非常全面的黑客技术清单）
- [CTF-Wiki](https://ctf-wiki.github.io/ctf-wiki/) （CTF的入门简介）
