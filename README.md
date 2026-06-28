# 前言

欢迎来到我们的基于微信小程序的短文写作竞赛管理系统项目。本项目采用Spring Boot技术，旨在为用户提供一个便捷、高效的短文写作竞赛平台。以下是本项目的详细介绍。

## 内容介绍

本项目是一个基于微信小程序的短文写作竞赛管理系统，主要功能包括用户注册、登录、短文投稿、评审、排行榜等。通过本系统，用户可以轻松参与短文写作竞赛，实时查看自己的排名和竞赛结果。同时，管理员可以对参赛作品进行评审和打分，确保竞赛的公平公正。

## 技术介绍

### 语言：Java
### 使用框架：Spring Boot、Spring MVC、MyBatis、微信小程序
### 前端技术：JS、Vue、CSS3、Uniapp
### 开发工具：IDEA/Eclipse，Uniapp
### 数据库：MySQL 5.7/8.0
### 数据库管理工具：phpstudy/Navicat
### JDK版本：jdk1.8
### Maven：apache-maven 3.8.1-bin
### 前端环境：Node.Js 12\14\16

## 核心代码

以下是项目中的一段核心代码，展示了如何实现短文投稿功能：

```java
// ShortEssayController.java
@PostMapping("/submit")
public ResponseEntity<?> submitShortEssay(@RequestBody ShortEssay shortEssay, HttpSession session) {
    User user = (User) session.getAttribute("user");
    if (user == null) {
        return new ResponseEntity<>(HttpStatus.UNAUTHORIZED);
    }
    shortEssayService.submitShortEssay(user.getUserId(), shortEssay);
    return new ResponseEntity<>(HttpStatus.OK);
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/341854/16/2749/89930/68c64b18F2c23a69f/892b08aec12109ed.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/345981/6/3326/29099/68c64af0F3109efd9/55d116f978fe1832.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/339447/34/10671/42348/68c64af0Fac305426/fc663b8f4f80566d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/347263/35/3159/27217/68c64af0F06c78486/388fbe5591102df1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/346842/17/3243/32943/68c64af0F9c7e41a1/aa8aec27400e18f7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337239/22/10459/36359/68c64af1F74add79a/32b48c380706e174.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/346171/8/3273/30756/68c64af1F48d7c14d/c56f227f1fa04714.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/330464/17/13092/16285/68c64af1Fa91773e7/4c2fec129a567026.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/348111/30/3244/30713/68c64af1F0a58b4a9/2605e1a9f0401d82.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/329602/21/13225/31177/68c64af1Fecd379ec/e5727d34714c933b.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
