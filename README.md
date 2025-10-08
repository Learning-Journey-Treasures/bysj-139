## 1.项目介绍
- 系统角色：管理员、学生、教师
- 功能模块：管理员（学院管理、专业管理、班级管理、学生管理、教师管理、课程管理、选课修改）、教师（授课查询、教师课表、成绩录入）、学生（选修课程、学生课程、课表查询、成绩查询、信息维护）等
- 技术选型：SpringBoot，Vue等
- 测试环境：idea2024，jdk1.8，mysql5.7，maven3，node12.16.1、redis5
## 2.项目部署
### 2.1 后端部署
- 创建数据库，导入sql文件
- idea打开目录server，根据本地数据库环境修改src/main/resources/application.yaml  6-9行
- 启动项目src/main/java/com/rainng/coursesystem/Application.java
### 2.2 管理web
- idea（安装vue.js插件）或者webstorm、vscode等ide工具打开项目client(命令行操作也可以）
- 进入终端，输入 npminstall安装依赖（下载失败自行配置阿里的镜像加速）
- 启动项目 npm run dev
- 打开终端的地址，输入账号密码：管理员（admin、123456）其他自行查表
## 3.项目部分截图
![输入图片说明](1.png)
![输入图片说明](2.png)
![输入图片说明](3.png)
![输入图片说明](4.png)
![输入图片说明](5.png)
![输入图片说明](6.png)
![输入图片说明](7.png)
![输入图片说明](8.png)
![输入图片说明](9.png)
# 4.获取方式
[戳我查看](https://gitee.com/aven999/mall)
