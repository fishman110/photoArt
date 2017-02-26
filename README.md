## PhotoArt
> 6666666666666666

## 安装

访问网址：http://网址/install

> 系统必须开启伪静态

## 目录结构
~~~
├─addons                扩展插件目录
├─application           项目目录文件
│ ├─admin               网站后台模型
│ │ ├─controller
│ │ ├─static
│ │ ├─view
│ │ ├─config.php
│ ├─api                 API接口模型
│ │ ├─controller
│ │ ├─static
│ │ ├─view
│ │ ├─config.php
│ ├─common             COMMON公共模型，不可访问
│ │ ├─controller      公共基类目录
│ │ ├─model           模型目录
│ │ ├─validate        验证配置
│ │ ├─view            公共模板目录
│ │ ├─widget          扩展组件目录
│ ├─index             前台模型
│ │ ├─controller
│ │ ├─config.php
│ ├─user              用户中心模型
│ │ ├─controller
│ │ ├─config.php
│ ├─common.php        公共函数库文件
│ ├─config.php        基础配置文件
│ ├─database.php      数据库配置文件
│ ├─route.php         路由配置文件
│ ├─tags.php          行为扩展配置文件
│ ├─ueditor.json      编辑配置文件
├─core                thinkphp框架目录
├─data                缓存以及备份目录
├─public         公共资源库
├─uploads        上传文件目录
├─template       网站主题模板目录
├─.htaccess      Apache下伪静态文件
├─favicon.ico    ico图标
├─index.php      入口文件
├─README.md      系统介绍文件
~~~