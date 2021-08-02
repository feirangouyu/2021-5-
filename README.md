# 2021-5-english-by-us
项目主题：一遍过英语学习平台

主要技术：html,css,js,jQuey,nodejs,mysql

页面功能：用户登录注册以及支持自定义,提供在线答题、支持判卷等且附有记录答题情况等功能，使用sorket长连接实现了简易版的双人玩家在线单词pk

使用说明：

1.在mysql中新建数据库，数据库名:english, 运行SQL文件：<代码区/english.sql>

2.在<代码区/sqlList.js >文件修改配置参数，

connection = mysql.createConnection({
 
        host:"localhost", //主机名
				
        user:"root", //mysql用户名
				
        password:"123456", //mysql用户密码
				
        port:"3306",   //mysql运行端口号
				
        database:"english"   //数据库名
    });
    
3.在根目录的终端下运行nodejs服务器

nodemon server.js

nodemon pkServer.js

4.在项目环境下打开主页面

<代码区/src/index.html>

## 项目页面展示图：
主页：
![image](https://user-images.githubusercontent.com/54969710/123645616-128f4400-d859-11eb-8e41-9501bc4fa76a.png)
答题页面：
![image](https://user-images.githubusercontent.com/54969710/123646475-d4465480-d859-11eb-8bdc-b0c107c2d04a.png)
提交答题后页面：
![image](https://user-images.githubusercontent.com/54969710/123646612-f4761380-d859-11eb-937a-c6594b8223ab.png)
题型分类页面：
![image](https://user-images.githubusercontent.com/54969710/123646650-fd66e500-d859-11eb-91fa-813bd953d438.png)
个人资料页面：
![image](https://user-images.githubusercontent.com/54969710/123646762-14a5d280-d85a-11eb-9d17-c2a58de57de7.png)
学习记录页面：
![image](https://user-images.githubusercontent.com/54969710/123646951-4159ea00-d85a-11eb-93fd-8afe0e14fb8b.png)
错题记录页面：
![image](https://user-images.githubusercontent.com/54969710/123646894-356e2800-d85a-11eb-96a6-dc09dbceae48.png)
pk主页面：
![image](https://user-images.githubusercontent.com/54969710/123647080-5d5d8b80-d85a-11eb-9020-eb6a12ceb82d.png)




