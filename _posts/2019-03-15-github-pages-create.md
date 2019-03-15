---
title: 网站搭建 | 半小时内搭建GitHub Pages个人主页！
date: 2019-03-15 00:00:00
categories:
- 网站搭建
tags:
- 个人主页
- GitHub pages
typora-root-url: ../../iseex.github.io
---

想拥有一个免费的个人主页吗？在这里，你可以发布自己的博客、自由定制网站的主题，你可以拥有极好的创作体验，它可以成为你对外的一张“名片”，体现你的品味和兴趣，还有更重要的，它是免费的、可控的、无需维护的。

那么，我推荐你用GitHub Pages搭建你的个性化主页。

今天这篇推文就以最简单的方式介绍GitHub Pages的使用入门，跟着我做，不到半个小时你就能拥有自己的网站。

## 傻瓜式教程

1. 注册GitHub账号。到[https://github.com](https://github.com)注册一个GitHub账号。如下。
   ![](/assets/images/posts/GitHub-Pages/create-github-account.png)

2. 创建仓库。创建一个以`username.github.io`命名的仓库（repository），注意这里的`username`就是第一步注册的GitHub账号的用户名。举个例子，如果你的用户名是`sophshep`，那么你的仓库名则为`sophshep.github.io，`如下图所示。

   ![](/assets/images/posts/GitHub-Pages/create-repository.png)

3. 下载GitHub Desktop客户端。到[https://desktop.github.com](https://desktop.github.com)下载GitHub Desktop客户端（Windows或MacOS）,作为git工具（方便不懂git的用户使用）。安装完成后，登陆自己的GitHub账号，并克隆（clone）前面创建的仓库到电脑上（可设置路径）。
   ![](/assets/images/posts/GitHub-Pages/github-desktop.png)

4. 创建Hello world网页（先以创建一个最简单的Hello world为例，介绍如何在网站上发布第一个网页）。在上一步克隆在电脑上的仓库文件夹中新建文件`index.html`，内容如下。
   ![](/assets/images/posts/GitHub-Pages/index-file.png)

5. Commit & publish。创建完index.html文件后，GitHub Desktop会提醒有内容更新，此时进行Commit & publish即可。如下图所示。
   ![](/assets/images/posts/GitHub-Pages/push.gif)

6. 大功告成。到这里，一个最简单的个人主页就搭建完成了，访问`https://username.github.io`即可看到网站的样子。

## 网站主题

可能有人要问了，刚刚创建的只有Hello world网页的个人主页也太简单了吧！？别急，下面教你如何5分钟内把网站装扮的更漂亮，有好看的主题，有强大的功能。

此时，我们需要用到Jekyll静态网页生成工具（也可以用Hexo，以后介绍），这也是GitHub官方推荐的静态网页生成工具。

1. Jekyll提供了丰富的免费主题，可到网站[http://jekyllthemes.org](http://jekyllthemes.org)查看，如下图所示。
   ![](/assets/images/posts/GitHub-Pages/Jekyll-themes.png)
2. 选择你喜欢的的主题（个人觉得Jekyll Next主题不错）并下载，先将电脑上的`username.github.io`仓库文件夹中的内容清空，再将下载的主题中的所有文件拷贝到里面。以我的仓库为例，如下图所示。![](/assets/images/posts/GitHub-Pages/my-site-filefolder.png)
3. 然后在GitHub Desktop客户端Commit & publish。再次访问`https://username.github.io`，你会看到焕然一新的个人主页！

到这里，一个简洁漂亮的个人主页就搭建成功了。当然你还可以继续修改仓库中的代码（主要是_config.yml文件），来调整和定制网站的风格，这个以后会介绍，今天就提供一些官方的参考资料，通过阅读它们，你能够对GitHub Page和Jekyll有个深入的了解。

## 参考资料

📖 GitHub Pages的Jekyll使用教程：[https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages](https://help.github.com/en/articles/using-jekyll-as-a-static-site-generator-with-github-pages)

📖 Jekyll官网：[https://jekyllrb.com/docs/](https://jekyllrb.com/docs/)