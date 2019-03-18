---
title: hexo的使用
categories: 博客工具
description: hexo的一些基本使用方法以及配置文件的含义
---
 hexo的一些基本使用方法以及配置文件的含义
<!--more-->


### hexo的常用方法

``` bash
$ hexo n "我的博客" == hexo new "我的博客" #新建文章
$ hexo p == hexo publish
$ hexo g == hexo generate#生成
$ hexo s == hexo server #启动服务预览
$ hexo d == hexo deploy#部署
```
### hexo的_config.yml文件

####网站参数
```bash
    title :      网站标题
    subtitle :   网站副标题
    description: 网站描述
    author:      您的名字
    language:    网站使用的语言
    timezone:    网站时区
```

####网址参数
```bash
    url :              你的第三方域名
    root :             网站根目录
    permalink:         文章的 永久链接 格式
    permalink_default: 永久链接中各部分的默认值
```

####目录
```bash
source_dir 	资源文件夹，这个文件夹用来存放内容。	source
public_dir	公共文件夹，这个文件夹用于存放生成的站点文件。	public
tag_dir	标签文件夹	tags
archive_dir	归档文件夹	archives
category_dir	分类文件夹	categories
code_dir	Include code 文件夹	`downloads/code
i18n_dir	国际化（i18n）文件夹	:lang
skip_render	跳过指定文件的渲染，您可使用 glob 表达式来匹配路径。
```
