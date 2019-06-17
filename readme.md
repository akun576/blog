# 基于Node.js+Express+Mongodb+Mongoose的zk-blog项目

-响应式界面开发

-进入根目录
- npm install 安装包依赖
- node app.js 运行项目
- 在浏览器输入 http://localshot:3000访问
## MVC模块化思想

- Model 模型（数据操作）
- View 模板视图（页面展示）
- Controller 控制器（路由控制）

app.js

-项目结构
-zk-blog
my_item
│  package-lock.json
│  package.json  项目配置文件
│  readme.md  项目说明
├─node_modules 第三方模块文件
├─controller  路由控制
├─libs  后台工具包
├─models 模型 操作数据
├─static 前台静态资源
├─assets 前台静态资源
└─views 视图模板
- 使用第三方静态模板
!(极简wap菜单个人主页博客模板)[http://www.cssmoban.com/cssthemes/8138.shtml]
## 第三方包
1.express
2. mongoose
3 ejs 模板引擎

4 formidable 上传文件
5 uuid 生成一个唯一的字符串

##前台模板说明
整理好前台模板以后，把它放入views文件夹

###前台页面
index 文件夹
-首页 index.html
-列表页 blog.html
-内容页 detail.html

抽象出首页模块的公共头和公共底部
### 用户页面
user 文件夹
-用户首页 index.html
-用户登录 login.html
-用户注册 reg.html
-用户发表文章 publish.html
## 设计路由
路由决定了用户想要什么，用户想要和服务器交互只能t通过路由
路由去之后按对应的末班和数据
###首页路由模块

### 用户路由模块

##上传文件

## 设计数据库
