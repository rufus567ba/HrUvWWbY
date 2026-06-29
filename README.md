# 前言

欢迎来到我们的家政服务管理系统项目，该项目是基于SSM框架开发的一款线上家政服务管理系统。本项目旨在为用户提供便捷、高效的家政服务管理，满足家政公司的业务需求。

# 内容介绍

家政服务管理系统主要包含以下功能模块：用户管理、家政人员管理、订单管理、服务项目管理、财务管理等。通过这些模块，家政公司可以轻松地实现对各项业务的高效管理，提高工作效率，降低运营成本。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，mybatis，微信小程序

## 前端技术：JS、Vue、css3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven: apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下为一段关于用户管理的核心代码：

```java
// 用户管理控制器
@RestController
@RequestMapping("/user")
public class UserController {

    @Autowired
    private UserService userService;

    // 获取用户列表
    @GetMapping("/list")
    public ResponseEntity<List<User>> userList() {
        List<User> users = userService.list();
        return ResponseEntity.ok(users);
    }

    // 添加用户
    @PostMapping("/add")
    public ResponseEntity<User> addUser(@RequestBody User user) {
        User savedUser = userService.save(user);
        return ResponseEntity.ok(savedUser);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/326178/29/19629/114640/68c4dfdeF3894ed2e/8cc45ec45dba6b4c.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/332725/30/12422/57636/68c4dfb6F57cd6ca1/25f1794492e68fad.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/348065/10/2792/55723/68c4dfb6F825b971d/acdae2194dd8a2c4.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324643/27/19380/9432/68c4dfb6Fc79878a0/2c776a90f474a2ba.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/322620/33/17258/8554/68c4dfb6F83870232/b9c180db3d3e06b7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/349414/25/2726/36165/68c4dfb6Fc43be2f9/72b08e73d175fb43.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/344948/8/2831/38260/68c4dfb7F7d277f09/23b128a06cc632ac.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325484/40/19215/42135/68c4dfb7F64f36a1c/3427fa1f54c825d1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/350738/39/2801/37472/68c4dfb7Fbaccb256/f9ffd0599b15708a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/345938/34/2797/37241/68c4dfb7Fafc7f4d6/666c720d2e43128f.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
