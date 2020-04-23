---
title: "免费 js.org 域名申请教程"
date: 2020-01-1T15:43:48+08:00
lastmod: 2020-01-31T15:43:48+08:00
draft: false
tags: ["js.org免费域名", "js.org", "免费域名"]
categories: ["域名"]
author: "Your"
autoCollapseToc: true

---

js.org 这个免费域名有点特别，与其它免费域名与众不同的是，它不是完全对外开放，也不提供 DNS 解析，js.org 只限于本身使用 Github pages 服务的用户，如果你正在使用 Github page 那么申请是非常简单的。<!--more-->

### 简介   

官网：[https://js.org](https://js.org)    
项目：[https://github.com/js-org/js.org](https://github.com/js-org/js.org)     

js.org 是一个特别的免费域名提供者，不提供 DNS 解析功能，只可以解析运行于 Github page 上的内容。你可以看作是 Github pages 免费提供的 username.github.io 的另一个版本。  
我们知道当你注册使用 Github pages 服务时，Github 免费提供一个 username.github.io 二级域名。不过，如果你的开源项目内容与当前流行的前端技术有关，那么 js.org 就比 github.io 更为贴切实用了。再者 js.org 也比 github.io 更短更酷。    

### 注册和使用   

域名是人工审核，所以申请之前，确保你已经有实在内容、且运行在 Github page 的仓库，可以是介绍文档可以是项目，没关系也可以是博客内容。   

1、搜索未使用的 xxx.js.org 域名    

js.org 域名不提供可用性搜查，所以先想好你需要的二级域名，比如你想使用 one.js.org ，那就自行在浏览器打开 one.js.org ，要是打不开内容，恭喜，这二级域名还没人使用，那你可以使用它。    

2、在你的仓库绑定你 xxx.js.org     

在你仓库设置中 Settings 找到 Custom domain 项，填上你要绑的 xxx.js.org 域名    

### 申请 xxx.js.org 

1、fork 仓库    

打开 js.org 的主仓库：[https://github.com/js-org/js.org](https://github.com/js-org/js.org)，点击右上角的 **Fork** 按钮。稍等一下刷新页面。这样，这个仓库就被 fork 到你自己的名下。   

![](/images/jsorg_fork.png)   

2、修改 cnames_active.js 文件   

见上图，fork 之后看一眼仓库 ，其实很简单，整个仓库就6个文件，3个.md 不用说也知道相关的说明文档，然后剩下3个 js 文档，点开 cnames_active.js 文件，你只要看一下文件，也知道是怎么回事了吧，全都是别人已申请使用中的二级域名，点右上角的“笔”符号，直接在里面编辑添加你要申请的 xxx.js.org 域名，以及要 CNAME 指向的 Github page 网址。要注意的是，大家的约定都是按字母顺序排序的。添加好以后点最下面绿色的 **Commit changes** 保存修改。    

![](/images/jsorg_edit.png)    

3、Pull Request   

回到你 fork 的仓库页面，左上角找到 **New pull request** 的按钮，点击它来提交你的修改。这样就完成了域名申请和绑定了。是不是很简单。剩下的就是等待审批，因为中美之间的时差关系，你最好在晚上零点之前完成上面这些操作。等美国那边的项目维护者上线之后，就会对你的 pull request 进行检查，如果没有问题，就会 approve，一切顺利，就会 merge，之后很快你就可以用拿到的域名访问。    
