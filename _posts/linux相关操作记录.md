---
title: 'linux相关操作记录'
date: 23-09-01
permalink: /posts/2023/09/blog-post/
tags:
  - Linux
  - 自学
---

### 这篇用来持续更新linux学习过程中的相关信息和指令技巧


## 查看显存情况
- nvidia-smi
- watch -n 1 nvidia-smi 或 nvitop

## 启动或查看screen
- screen -ls
- screen -R wmz
- Ctrl +A+D
- Ctrl+A [ 查看翻页
- screen -r wmz

## 开启或关闭局域网代理
- export http_proxy=http://代理IP:端口号
- export https_proxy=http://代理IP:端口号

## 启动或关闭虚拟环境
- conda activate llava
- conda deactivate

## 安装python包
- pip install -i https://pypi.tuna.tsinghua.edu.cn/simple +包

## 查看网关
- ifconfig

## wandb同步
- wandb sync 