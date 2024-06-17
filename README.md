# SecReport



ChatGPT加持的，多人协同信息安全渗透测试报告`编写`/`导出`平台

[官方网站](https://sec-report.com/)

- 标准化渗透测试流程
- 多人协同编辑
- 自定义导出模版
- ChatGPT生成漏洞简介及修复方案
- 复测报告生成
- 多人协同的临时信息同步窗口
- APP安全合规测试报告
- APP安全合规测试报告自定义模板

> 报告模版在template文件夹



## 来源

- https://github.com/sec-report/SecReport

**因应监管部需求，国内访问Docker源pull镜像开始变得复杂且困难起来了，大佬github给的在线/离线安装脚本跑了很久也无法拉取到镜像，所以将以前的镜像打包后重新改了改，形成本地化离线部署。**





## 环境

需具备基本docker环境以及docker-compose

#全量安装文件中打包了docker基本环境



## 下载

SecReport https://www.alipan.com/s/qTJ7gg3U124 提取码: os89 点击链接保存，或者复制本段内容，打开「阿里云盘」APP即可下载 

![1718663155203](https://github.com/chengling-ing/SecReport/blob/master/image/1718663155203.png)





## 安装

安装docker

```
cd docker
bash install.sh
```

安装docker-compose

```
cd docker-compose
bash install.sh
```

安装镜像文件

```
bash install_image.sh
```

运行程序

```
bash run.sh
```

![1718663421056](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\1718663421056.png)



## 初始化

web访问 :   http://ip

![1718663536585](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\1718663536585.png)

初始化管理员

![1718663584336](https://github.com/chengling-ing/SecReport/blob/master/image/1718663584336.png)

默认开启了动态口令二次验证，需使用二次验证软件验证即可，时间差不能太大

![1718663950787](https://github.com/chengling-ing/SecReport/blob/master/image/1718663950787.png)





## 免责声明

仅做经验分享用途！利用本文章所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责。
