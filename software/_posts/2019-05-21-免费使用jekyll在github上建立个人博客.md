---
title: 免费使用jekyll在github上建立个人博客
image: /img/buildblog.jpg
description: >
    本文以本站点为例，说明如何使用hydejack@jekyll主题在github上建立个人博客。
---

**Notes：**
本文以本站点为例，说明如何使用hydejack@jekyll主题在github上建立个人博客。

## 懒人目录
{:.no_toc}
0. this unordered seed list will be replaced by toc as unordered list
{:toc}

## DEMO
demo就是本站了。  
本站链接：[https://wangwen0914.com](https://wangwen0914.com)
## 为什么选择github
&#160; &#160; &#160; &#160;作为小白，选择github的原因很简单。总结就是没钱、没技术、易上手、资源多、易学习、能装X。
## 为什么选择jekyll的hydejack主题
&#160; &#160; &#160; &#160;对于个人来说，需求很简单，希望有一个站点，操作简单、方便分享，能够快速导航到常用的一些链接，然后偶尔再码一些简单的文字。仅此而已。
- 虽然hexo功能强大，但是每次都要生成静态重新部署，不能随时在网页上进行修改，个人也不是专业程序员，总觉得不方便，麻烦。
- 选择jekyll的主要原因是既可以本地构建再部署，也可以随时在网页上进行修改，自动生成页面。（虽然随着信息量的增大，访问速度会变慢，但基于个人少量单一需求，觉得不是问题。）
- 选择hydejack主题是因为漂亮、大方、官方文档明了、配置简单，首页导航页非常符合我的个人需求本站采用的就是hydejack主题免费版。
## 开始安装配置
### 需要用到的资源
- github账号  
- hydejack主题  
hydejack的链接：[hydejack的github仓库][hydejack]  
hydejack的官方教程文档（虽然是英文，但浅显易懂）：[教程文档][readme]  

### 第一步-注册github账号
注册很简单，如果不会可以自行百度。[github官网][github]
### 第二步-安装hydejack并配置
&#160; &#160; &#160; &#160;对于安装方式，官方建议了很多种方式，包括`via the Starter Kit` `Ruby gem` `Via zip` `Via git`等。  

&#160; &#160; &#160; &#160;我用的是懒人方法，直接fork配置。
- fork hydejack的仓库  
&#160; &#160; &#160; &#160;登陆github后，打开hydejack的仓库[链接][hydejack]，点击右上角的`Fork`按钮。  
![fork](https://wangwen0914.com/img/buildblog/fork.jpg)  
&#160; &#160; &#160; &#160;等待fork完成。  
![forking](http://wangwen0914.com/img/buildblog/forking.jpg)  
- 修改仓库设置  
&#160; &#160; &#160; &#160;Fork完成后，hydejack就已经在你自己的github仓库里了。  
&#160; &#160; &#160; &#160;点击edit按钮修改仓库描述，可改可不改。  
&#160; &#160; &#160; &#160;点击`Settings`  
![settings](http://wangwen0914.com/img/buildblog/setting.jpg)  
&#160; &#160; &#160; &#160;在`Repository name`中填写你需要的名称重命名仓库，点击`Rename`确认，我填写的是`blog`。  
![rename](http://wangwen0914.com/img/buildblog/rename.jpg)   
&#160; &#160; &#160; &#160;继续在Settings页面往下拉，找到GitHub Pages，在Source中下拉选择master branch    
![page](http://wangwen0914.com/img/buildblog/page.jpg)   
&#160; &#160; &#160; &#160;之后页面会自动刷新，生成博客的二级域名，生成的域名仍然在Source上方绿色方条位置显示。  
显示为“ Your site is published at https://你的github用户名.github.com/你的仓库名/”。  
这就是目前你的博客域名了，点击即可访问，我的显示是本站域名wangwen0914.com，随后会说到如何配置自定义域名。  
- 配置hydejack  
&#160; &#160; &#160; &#160;









Writing....


[github]: https://github.com/
[hydejack]: https://github.com/qwtel/hydejack-starter-kit
[readme]: https://hydejack.com/docs/
