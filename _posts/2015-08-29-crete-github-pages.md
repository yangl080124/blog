---
layout: post
title: 利用github创建自己的博客。
category: share
comments: true
---


## 关于github的pages

github pages 是用于用户的个人主页或者项目的主页。
我们可以利用他来搭建自己的博客。

原因：

- 搭建简单且免费。
- 可以绑定域名。
- 不用管理且没有广告。
- 可以自由发挥的平台。

不过最近网络上发起了关于使用pages搭建博客是否道德的问题？

我觉得搭建博客就是用于个人主页的展示，且把一些自己认为值得分享的东西分享给大家。我觉得这样做是符合github pages的目标和要求的。

## 创建博客

为了大家能更好的建立自己的博客，我做的是不需要在git上敲指令。我在这里主要是把创建博客的步骤浅说一下，希望对新手来说有一定的帮助。

- 简单创建博客
首先进入主页


	填写仓库名字
	Description可以不写
	直接点击create repository
	创建的时候有一些标记介绍,后面我会对这块单独分享出来



	创建仓库


<figure>
   <img src="https://raw.githubusercontent.com/wfiskz/blog/gh-pages/res/create_repositories.png"></a>
   <figcaption></figcaption>
</figure>



	填写仓库信息



<figure>
   <img src="https://raw.githubusercontent.com/wfiskz/blog/gh-pages/res/edit_info.png"></a>
   <figcaption></figcaption>
</figure>



	点击设置


<figure>
   <img src="https://raw.githubusercontent.com/wfiskz/blog/gh-pages/res/sel_settings.png"></a>
   <figcaption></figcaption>
</figure>



	注意
	- Default branch这个是master
	- 而创建的pages是只能在gh-pages下才可以创建博客的
	- 进入后点击Contlnue to layouts
	此处只是提醒，直接点击 Launch automatlc page generator


<figure>
   <img src="https://raw.githubusercontent.com/wfiskz/blog/gh-pages/res/cteate_pages.png"></a>
   <figcaption></figcaption>
</figure>


	Publlsh page



<figure>
   <img src="https://raw.githubusercontent.com/wfiskz/blog/gh-pages/res/success.png"></a>
   <figcaption></figcaption>
</figure>


在做下面借助第三方库做博客之前，我先介绍几点我们需要修改的东西，一般你fork别人的项目的时候就会看到作者提示要修改的哪些方面。

1.CNAME 记录域名信息。（如何绑定域名这个请自行百度）
2.README.MD 这个直接就是你fork之后，你看到项目下的那些项目描述或者帮助描述。
3._config.yml 这个是我们fork最关心的东西，我们大部分修改的就是这个文件。



- 利用别人提供的主题来创建博客  

推荐一篇介绍github + Jekyll的文章，里面详细介绍了Jekyll的工作流程<a href="http://blog.csdn.net/on_1y/article/details/19259435">http://blog.csdn.net/on_1y/article/details/19259435</a>

这些是一些<a href="https://github.com/jekyll/jekyll/wiki/Sites">总结的开源库</a>，选择一个自己喜欢的，fork一下。


现在我们做一些前期工作，前面也说到了就是分支，你的分支一定要在*gh-page*(不是下划线)下，如果不是自己创建的话一般都是有这个分支的。如果没有的话，就自己创建这个分支。一般还要修改_config.xml下的这个用户名等信息，这个可以根据fork后的项目提示去修改。




- 自己实现


	

