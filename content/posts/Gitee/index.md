---
title : 'Gitee'
date : 2024-10-13T00:09:48+08:00
draft : true
tags: ["LLM"]
author: "Collin Liu"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: false
description: "The Intelligence Age by Sam Altman"
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false 
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
# cover:
   # image: "https://ia.samaltman.com/_next/image?url=%2Fimages%2Fcover.png&w=3840&q=75" # image path/url
   # alt: "<alt text>" # alt text
   # caption: "The Intelligence Age" # display caption under cover
   # relative: false # when using page bundles set this to true
    # hidden: false # only hide on current single page
# editPost:
#     URL: "https://github.com/<path_to_repo>/content"
#     Text: "Suggest Changes" # edit text
#     appendFilePath: true # to append file path to Edit link
---
# Git

---

![image.png](pics/image.png)

```bash
cd projectFile
git confit --global user.name "Collin Liu"
git confit --global user.email juunbailiu@gmail.com

```

```bash
git init  -- 初始化本地项目
git status  -- 查看文件状态
git add     -- 添加到缓存区
git commit  -- 提交到本地仓库

touch .gitignore -- 添加不需要追踪的文件
git branch bad-boy
git branch 
git checkout bad-boy -- 切换分支

trick：
	git commit -a -m “XXXX”

git branch -D bad-boy --删除分支
git checkout -b tmp   --创建并切换新分支
git merge temp -- 把temp版本的文件合并到当前分支

```