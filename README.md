# 分布式系统与云计算大作业
## 作业要求
使用Django开发一个云盘系统
## 作业完成过程
## 主要问题和解决方法
### 问题1 如何使本地仓库与远程仓库同步？
解决办法：生成本地的公私钥对，并将公钥内容复制到git服务器的ssh密钥中。
步骤如下：
在本地git bash（windows）、命令行中运行命令生成公私钥对：ssh-keygen
将 ~/.ssh/id_rsa.pub文件的内容复制到git服务器的ssh 秘钥中。
### 问题2 
## 作业结果展示