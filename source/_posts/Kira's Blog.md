---
title: Kira的博客搭建记录
date: 2023-02-18
tags: 0
categories: Dev
cover: 
---

兜兜转转终于还是搭建了自己的博客。

本博客采用分代回收算法
第0代为老生代，即该博客最终确定的效果。“很少修改”
第1代为中生代，为该博客中间阶段的里程表效果。中间有添加可能会往前或往后push。一般可以留证，没必要删。
-1代或2代为新生代，胡言乱语，读厚读繁，只要能写，自由发挥，虽不可言，但字最多（可能没发表出来就被删了）。定位类似“艺术家的费稿”

例：博客初建 想法颇多，建至中段 踩坑无数，终建完成 不知所言……每个阶段都有每个阶段的快乐。

鄙人秉性，还望海涵。

<!--more-->

---

Hexo + GitHub

### GitHub仓库

https://github.com/sols11/sols11.github.io

### 安装Hexo、Node.js等

https://zhuanlan.zhihu.com/p/35668237

### 注册域名

https://wanwang.aliyun.com/domain/

### 安装插件和icarus主题

https://github.com/uynad/uynad.github.io

maybe need to modify theme/archive.styl... etc

### 配置yml

https://blog.peiyingchi.com/2020/02/25/hexo-icarus-settings

### 支持评论

https://blog.csdn.net/sinat_37529938/article/details/111484179

### 谷歌、百度搜索收录

https://zhuanlan.zhihu.com/p/100922816

### 写、预览然后推送

格式：

```
---
title: 
date: 2023
categories: 
tags: 
cover: 
---

<!--more-->
---
```

hexo clean, hexo g, hexo d

hexo s 预览

### 寻找图床

### 提交GitHub备份

git branch -b blog

move .git

git push

### 关联坚果云

source/_post

### Fix Bug

[PowerShell无法运行hexo命令](https://cloud.tencent.com/developer/article/1866958)



