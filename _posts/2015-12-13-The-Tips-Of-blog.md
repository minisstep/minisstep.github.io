---
layout: post
title: 怎么创建自己的第一个博客
categories: [blog ]
tags: [Tech,blog ]
description: 在Github上搭建Jekyll博客
---
#方案的优势#

github基于github-pages的博客方案完全免费，且有稳定性保障

所有博文可以通过github做版本管理

使用markdown语法写博客,可以专注于内容无需过度关心页面样式

##first step  申请一个github-pages blog##
1.在GITHUB 创建一个库（举例子：库的名字是：myblog）[github](https://github.com/)

2.在新库"myblog"页面选择“setting”

3，在setting页面，only 选择 Launch automatic page generator(翻译，生成主页)

4，生成的主页会有标题，副标题等，暂时可以考虑不用修改，继续next

5.由于只是为了建立博客模板样式，就暂时用官方的，不用修改，任一选择一个模板，发布，OK，现在就可以看到自己的Blog(这是由于没有修改，因此没有内容，下一步就是修改blog模板)

6，tip:一个帐号只能建立一个blog，注意咯。

##create blog##
1.单纯的是为了写博客，写博客，那就很简单，使用别人的博客模板。
 参考博客模板：

[jekyllthemes.org](http://jekyllthemes.org/)

[jekythemes.net](www.jekyllthemes.net)

[blog](https://github.com/minisstep/azeril.github.io)

模板安装
2.直接在github 主页选择下载保存到本地

3.下载自己创建BLOG，保存本地。

4.复制模板：在自己本地BLOG文件夹，除了“git”文件夹，删除其他所有内容，复制别人的模板到自己的本地BLOG 下面。

5.下载[git](https://git-for-windows.github.io/),目的是上传本地BLOG（已经克隆好别人的模板）文件到GITHUB仓库中。

6.上传
 
  *选择本地BLOG文件夹，右键选择git bash here 
  *进入类是与cmd命令框:输入如下命令：
    git 命令

    $ git add .

    $ git commit -m "first post" #("first post" 此处修改标记，可以任意填写)

    $ git remote add origin https://github.com/minisstep/minisstep.github.io.git # （ https://github.com/minisstep/minisstep.github.io.git这个是自己创建BLOG仓库中的HTTP，自己选择copy，复制，粘贴到这里）

    $ git push origin master
7.现在模板任务已经完成。可以预览



## 参考资料

[傻瓜都可以利用github pages建博客](http://cyzus.github.io/2015/06/21/github-build-blog/)