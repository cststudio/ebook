# ebook

# 前言
介绍编写本书初衷，包括什么内容，本书不具备什么内容，适用读者，勘误表地址、联系方式。

# (第一部分 基础概念篇)

# 第1章 嵌入式Linux基础概念
介绍嵌入式Linux是什么，由哪些部分构成，该怎么学  
## 1.1 嵌入式Linux是什么
## 1.2 嵌入式Linux由哪些部分组成
## 1.3 如何学习嵌入式Linux
## 1.4 本书代码示例说明
（使用ubuntu+qemu，另在实际板子上运行s3c2440）
## 1.5 本书实验平台说明
## 1.6 本章小结

# (第二部分 系统系统篇)

# Linux系统的安装——基于Ubuntu16.04
## 使用虚拟机VMware Workstation安装Ubuntu
（图解安装过程，添加说明）
## 安装Ubuntu后要做的配置
（分类说明要安装的软件及作用）

# Linux系统使用
## Linux系统目录
### Linux目录结构介绍
### /proc目录、/sys目录
## Linux命令
### 命令分类
### 编辑器类
### 命令行使用技巧
### 简单shell用法
### 系统配置
（环境变量、/etc/文件配置）
### 深入掌握Linux结构
（LFS、debootstrap）
## 本章小结

# 嵌入式Linux开发环境搭建
## 嵌入式Linux开发概述
工欲善其事，必先利其器  
（描述编写代码、编译代码、运行代码过程） 
## Windows系统所需工具
（source insight、notepad++、secureCRT）
## Linux系统所需服务
（前面已经安装好Linux系统）
### SSH
（scp）  
### FTP
### Samba
### NFS
## 本章小结

# （第三部分 Linux应用开发篇）

# 版本管理工具git
（说明为什么要使用git）
## 版本管理工具概述
重要性、必要性  
## git应用场景
## 入门使用
（建立仓库、克隆仓库、提交仓库）  
## 分支和标签
## 远程仓库
## 高级用法
### 子仓库
### 同一本地仓库配置多个远程仓库
## 国内外常用git托管网站
### github
### gitlab
### bitbucket
### gitee
## 本章小结

# Linux系统自动编译和Makefile
## Linux下工具、库编译方法
## autotool工具集
（http://www.linuxprobe.com/system-gnu-autotool.html ）  
## Makefile
### 基本内容
（介绍makefile基础内容、执行shell）
### Makefile模板实例
## 小结

# 二进制工具
## 概述
## gcc工具链
### ar
### nm
### strings
### strip
### objcopy
### readelf
## ELF格式

# 应用程序开发
## 概述
## Linux应用层模块分类
## 编码规范
## helloworld全面追踪

# 调试手段
## printf打印
## 从代码源码把控
## coredump调试

# (第四部分 嵌入式Linux移植篇)

# 移植总览
## 必备技能
## 阅读芯片手册

# bootloader移植
## u-boot
### u-boot概述
### u-boot在qemu环境的启动(使用qemu启动u-boot)
### 在u-boot中新加命令
### u-boot进程空间
## coreboot
### coreboot概述
### coreboot在qemu环境的启动

# Linux内核移植
## 内核配置编译
## 新加内核驱动
## 代码配合芯片手册
WDT、RTC

# rootfs移植
## rootfs概述
## busybox
### busybox编译
### 在qemu挂载busybox
## debootstrap

# Linux驱动开发
## 驱动分类概述
## platform设备驱动模板实例
## platform设备驱动流程跟踪
## 字符设备驱动流程跟踪
## GPIO驱动
## 打通用户空间与内核空间
sys、proc文件系统驱动示例  
