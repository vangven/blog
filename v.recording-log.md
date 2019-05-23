
# V.Recording-Log

这个页面记录了这个站点的建立和修改过程.  
本文档`./v.recording-log.md`
  
  
## 目录
{:.no_toc}
0. this unordered seed list will be replaced by toc as unordered list
{:toc}


## 域名
* 域名为`wangwen0914.com`在`godaddy`
* 由`DNSPOD`解析到`github`
* 在github的blog仓库建立CNMAE文件指向  

## 站点来源
* 站点存储在`github\blog`仓库
* 站点采用`Jelyll`
* 站点采用[`Hydejack V8.4.0`](http://jekyllthemes.org/themes/hydejack/)主题

## 记录
### 先导部分
* 从Hydejack页面`fork`到`blog`仓库使用
* 在本地`git clone`到`/资料库/科技相关/github/blog/`进行修改部署
* 修改完成后`git add .` `git commit -m "modify"` `git pull` `git push`进行部署

### 对`/_fonfig.yml`的修改： 
~~~yml
# file: _config.yml

url:  http://wangwen0914.com
baseurl:  ''
title:  V.Recording
description:           >"Page For Personal".
tagline:               >"Page For Personal".
author:
  name:                vangven
  email:               1781134136@qq.com
menu:
  - title:             常用链接
    url:               /links/				# 保存在./links.md
  - title:             文章集
    url:               /blog/
  - title:             软件收藏
    url:               /software/
  - title:             不公开的页面
    url:               /private-page/		# 保存在./private-page.md
  - title:             声明
    url:               /about/				# 保存在./about.md
  - title:             Hydejack-backup
    url:               /hydejack-backup/	# 保存在./hydejack-backup.md
~~~


### 对`./_data/authors.yml`的修改： 
~~~yml
# file: _config.yml
author1:
  name:              vangven
  email:             1781134136@qq.com
about:             |
    这是一个个人使用的站点，使用Hydejack在github上建立。
    主要用来留存一些记录信息、链接一些常用的文档，不用作经营性使用。
    如果您发现该站点存在一些侵犯您权利的信息，请联系1781134136@qq.com删除。
picture:
    path:            https://wangwen0914.com/img/about-128.png
    srcset:
      1x:            https://wangwen0914.com/img/about-128.png
      2x:            https://wangwen0914.com/img/about-256.png
social:
     github:          vangven
     email:           1781134136@qq.com
     sina-weibo:           http://weibo.com/209993055
	 download:         v.recording-log/		# 链接到./v.recording-log.md
~~~

### 对于`./_data/strings.yml`的修改：  
~~~yml
# file:./_data/strings.yml
related_posts:         其他文章			# 在每个文章页下显示其他文章
older:                 较早的文章		# 在文章列表最后显示
newer:                 更新的文章		# 在文章列表最后显示

~~~

### 文件目录修改

#### 对站点目录的修改
~~~
├──_featured_categories
│  ├──blog.md			# 显示文章集中的文档目录和内容页
│  ├──software.md		# 显示软件收藏中的文档目录和内容页
├──blog/_post/			# 建立文章集的文章页
├──links.md				# 编写常用链接
├──software/_post/		# 建立编写软件收藏文章页
├──assets
│  ├── icons
│      ├── favicon.ico	# 自定义修改
│      ├── icon.png		# 自定义修改
├──img					# 保存文章页面需要的图片
│  ├── about-128.png	# 每个内容页页尾的about展示
└  └── about-256.png	# 每个内容页页尾的about展示

~~~


#### 对资料库相关联的修改
~~~
├── 资料库
└	└── 私人记录.md		# 链接到./private-page.md


~~~
  
  
### 一些常用的
#### 本地git
~~~bash
$ git clone
$ git add .
$ git commit -m "修改描述"
$ git pull
$ git push
~~~


#### 页面编辑
* 生成页面内目录链接

~~~yml
# 内容页.md
{:.no_toc}
0. this unordered seed list will be replaced by toc as unordered list
{:toc}
~~~


* 页面内页头标注

~~~yml
# 内容页.md
---
title: 这是显示的文件名和页面标题
image: /img/***.png
description: >
   这是一些描述。
---
~~~

* 中文缩进  

~~~yml
# 内容页.md
&#160; &#160; &#160; &#160;
~~~
