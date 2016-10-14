## Quick Start

### HEXO安装

``` bash
$ npm install -g hexo
```

### 运行服务

``` bash
$ hexo server
```

##### 切换到hexo-demo目录，运行 npm install 安装依赖，并启动Hexo服务器

### 创建文章
#### 方法一 hexo新建帖子

``` bash
$ hexo new "My New Post"
```
新建的帖子在 source/_posts 文件夹内

#### 方法二 复制markdown文件
写好的markdown放进source/_posts文件夹内
##### PS.默认布局为POST，文章开头需添加以下内容
```
---
title: {{ title }}
date: {{ date }}
tags:
---
```

### 部署静态文件

``` bash
$ hexo generate
```
##### 部署后生成的public文件夹内的文件上传


### 目录和文件

文件夹/文件名 | 作用 | 
----|------|
scaffolds | 布局模板  |
source | 存放文章  |
themes | 主题模板  |
_config.yml | 配置文件  |




