ThinkPHP

----

1.框架目录

```
www WEB部署目录（或者子目录） 
├─index.php 入口文件
├─README.md README文件
├─.htaccess 主要体现在伪静态的使用
├─composer.json
├─Application 应用目录 
├─Public 资源文件目录 
└─ThinkPHP 框架目录
```

##### .htaccess的基本作用

- URL重写、自定义错误页面
- MIME类型配置
- 访问权限控制等
- 主要体现在伪静态的应用
- 图片防盗链
- 自定义404错误页面
- 阻止/允许特定IP/IP段
- 目录浏览与主页
- 禁止访问指定文件类型
- 文件密码保护

其中框架目录ThinkPHP的结构如下： 

```
├─ThinkPHP 框架系统目录（可以部署在非web目录下面） 
│ ├─Common 核心公共函数目录 
│ ├─Conf 核心配置目录 
│ ├─Lang 核心语言包目录 
│ ├─Library 框架类库目录 
│ │ ├─Think 核心Think类库包目录 
│ │ ├─Behavior 行为类库目录 
│ │ ├─Org Org类库包目录 
│ │ ├─Vendor 第三方类库目录 
│ │ ├─ ... 更多类库目录
│ ├─Mode 框架应用模式目录 
│ ├─Tpl 系统模板目录 
│ ├─LICENSE.txt 框架授权协议文件 
│ ├─logo.png 框架LOGO文件 
│ ├─README.txt 框架README文件 
│ └─ThinkPHP.php 框架入口文件
```

2.MVC

M(Model)模型；也叫业务模型，主要在应用程序中

V（View）视图：展示数据，

C（Controller）控制器

C->M->V

![](C:\phpDevelopment\myweb\ThinkPHPNote\分享thinkPHP\MVC.jpg)

3.Model

4.Controller

5.View