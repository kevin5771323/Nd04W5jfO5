## 前言

您好！欢迎来到本项目的Gitee页面。这是一个名为“客家菜餐馆点菜系统+ssm”的实战项目，基于Java语言和Spring、Springmvc、Mybatis等主流框架，旨在为客家菜餐馆提供一个便捷、高效的点菜系统。以下将为您详细介绍本项目的相关内容。

## 内容介绍

本项目是一款针对客家菜餐馆的点菜系统，主要包括以下功能模块：用户模块、菜品模块、订单模块、支付模块等。用户可以通过微信小程序轻松实现点菜、下单、支付等一系列操作，为餐馆提供便捷的点餐服务。此外，系统还提供了后台管理功能，方便餐馆管理员进行菜品管理、订单管理、营业统计等操作。

## 技术介绍

- 语言：Java
- 使用框架：Spring、Springmvc、Mybatis，微信小程序
- 前端技术：JS、Vue、css3，Uniapp
- 开发工具：IDEA/Eclipse，Uniapp
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven: apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下是一段关于查询菜品的Mybatis核心代码：

```java
//.mapper.xml
<select id="queryDishes" resultType="com.example.entity.Dishes">
    SELECT * FROM dishes WHERE category_id = #{categoryId}
</select>

//Service层
public List<Dishes> queryDishesByCategoryId(Integer categoryId) {
    return dishesMapper.queryDishes(categoryId);
}

//Controller层
@RequestMapping("/queryDishes")
@ResponseBody
public List<Dishes> queryDishes(Integer categoryId) {
    return dishesService.queryDishesByCategoryId(categoryId);
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
![封面图片](https://img11.360buyimg.com/ddimg/jfs/t1/330528/21/12783/140436/68c573bdFc645e5ec/ef92ef46d25e7bd0.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/326621/34/19697/11600/68c57394F680d4c7b/6654386857f36462.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/348651/29/3025/29969/68c57395F3324401e/6432b0fa9064ef3d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/334953/1/12908/33679/68c57395F5eb50607/3d5e8be936831934.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/340148/8/10480/35398/68c57395F703559fc/df8ac5e46e4df8ac.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325305/37/19827/31106/68c57395F3884a56b/637689b90592be24.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332072/14/12858/27724/68c57396F38a3bfa9/a0caff461c2818b4.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/325410/1/19674/12339/68c57396F9c244c8a/8c7afedbcfac4234.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348665/32/2870/23403/68c57396F620e4d68/3917b0cabf3e5c0d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337824/5/10288/20630/68c57396F2a92afdc/0b21c47b46804b90.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
