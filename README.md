![](https://github.com/Mocha-L/findtheone/blob/master/pic/findtheone.jpg)  

# [FindTheOne](http://honglingjin.online:520/)

> FindTheOne 知乎红娘小站 是针对知乎大家公布的择偶标准，做的筛选网站（知乎不提供筛选功能好气啊）。在这里可以筛选自己的地域、性别、排序标准等。点击[http://honglingjin.online:520/](http://honglingjin.online:520/)去实例站点查看功能和使用。

## 使用教程

[点击查看教程](https://www.zhihu.com/question/275359100/answer/540772904)

欢迎各位开发者丰富和优化该项目，提交PR。

## 微信

有问题可联系我。

<img src="https://github.com/Mocha-L/findtheone/blob/master/pic/myqr.jpg" width="250px" />

## 开发

本项目后端主要使用 `Python` + `Flask` ，前端使用 `zhihu`（就是照抄知乎的前端代码进行修改的），数据库是 `Mysql`

### 代码目录说明

```
public    公共文件目录
spider    爬虫目录 主要在里面的scrapy目录 其他的是demo文件
static    网站静态文件
templates 网站模板
web       flask相关代码
```

### 环境
![](https://img.shields.io/badge/Python-3.6%2B-brightgreen.svg) ![](https://img.shields.io/badge/Flask-1.0.2%2B-brightgreen.svg) ![](https://img.shields.io/badge/Mysql-5.7%2B-brightgreen.svg) ![](https://img.shields.io/badge/scrapy-1.6.0%2B-brightgreen.svg)

	Python 3.6.*    Mysql 5.7    Flask 1.0.2    scrapy 1.6.0

### 部署和运行

```
git clone https://github.com/Mocha-L/findtheone.git

pip install -r requirement.txt

python src/web/model.py  # 执行初始化数据库

# scrapy项目爬虫 需要自行部署 我用的是scrapyd部署和spiderkeeper定时任务

python src/web/view.py  # 开启网站，默认监听520端口（多浪漫~）
```
### 打赏

觉得有用，请我一杯咖啡。

<img src="https://github.com/Mocha-L/findtheone/blob/master/pic/ali.png" width="230px" /><img src="https://github.com/Mocha-L/findtheone/blob/master/pic/wechat.png" width="230px" />
