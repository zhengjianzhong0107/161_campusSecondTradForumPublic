## 本项目完整源码是收费的  接毕业设计和论文

### 作者微信：grapro666 QQ：3642795578 (支持部署调试、支持代做毕设)

### 接javaweb、python、小程序、H5、APP、各种管理系统、单片机、嵌入式等开发

### 选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/141259301](https://blog.csdn.net/2303_76227485/article/details/141259301)**

**视频演示：
[https://www.bilibili.com/video/BV1cGeMeqE9Y/](https://www.bilibili.com/video/BV1cGeMeqE9Y/)**

**毕业设计所有选题地址：
[https://github.com/zhengjianzhong0107/allProject](https://github.com/zhengjianzhong0107/allProject)**

## 基于Java+Springboot+vue+微信小程序的校园论坛二手闲置系统(源代码+数据库+万字论文)161

## 一、系统介绍
本项目前后端分离带小程序，分为用户、管理员两种角色，可自行分配角色菜单
### 1、用户：
- 注册、登录、推文、帖子(评论、收藏、点赞)、二手闲置、个人信息

### 2、管理员：
- 用户管理、菜单管理、权限管理、日志管理、评论管理、帖子管理、分类管理、轮播图管理、二手闲置管理、推文管理

## 二、所用技术

后端技术栈：

- Springboot
- MybatisPlus
- Mysql
- Maven
- Redis
- Rabbit

前端技术栈：
 
- Vue
- Vue-router
- axios
- elementUi
- vuex
- uniapp
- 小程序

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, node14, navicat, redis5.0, rabbit

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
论文目录：
![contents](./picture/picture0.png)
![contents](./picture/picture00.png)
### 1、用户：
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
### 2、管理员：
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)

## 五、浏览地址

后台地址：http://localhost:8080

管理员账户密码：admin/admin123

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件

2. 使用IDEA/Eclipse导入admin项目，若为maven项目请选择maven，等待依赖下载完成

3. 修改xlf-interface/src/main/resources/application.yml里面的redis,rabbit,本地文件上传配置,小程序登录配置、数据库配置,

4. 先确认电脑已经启动mysql、redis和rabbit,然后src/main/java/com/xlf/XlfInterfaceApplication.java启动后端项目

5. vscode或idea打开admin-vue项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示后台访问地址

7. hbuilder打开wechatapp项目, 修改manifest.json里面的微信小程序配置AppId(从注册的微信小程序账号里面复制)

8. hbuilder点击运行-运行到小程序模拟器-微信开发者工具，然后会打开微信开发者工具，小程序页面就展示出来了

## 七、创新点
1、使用rabbit实现订阅发布的消息模式，评论会先发送到rabbit然后再消费入数据库
2、使用redis缓存频繁使用的数据

