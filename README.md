# python-Django

This repo is a collection of study demo of Django

## dj01: how to build environment

## dj01: creat a simple project of Django

	1. django-admin startproject myproject

	2. 目录组成
	   * manage.py 用于运行管理项目 的 管理命令 。比如运行开发服务器，运行测试，创建迁移等 
	   * __init.py 告诉python 这个文件夹是一个python
	   * settings.py 比较重要 包含所有的项目配置。
	   * urls.py     映射项目中的路由与路径 
	   * wsgi.py     部署简单的网管接口  

	3. python manage.py runserver   

	4. 打开 http://127.0.0.1:8000

	5. django-admin startapp boards

	6.目录组成 
	  *  migrations/ 次文件夹， Django 会存储一些文件来跟踪你在models.py 文件中创建的 变更。用来保持数据库和models.py 的同步
	  *  admin.py  此文件是一个django内置的应用程序Django Admin 的配置文件
	  *  app.py    应用程序本身的配置文件
	  *  models.py 此文件用来定义 Web应用程序实例的地方。models会有Django自动转化为数据库表
	  *  tests.py  此文件用来写当前程序的单元测试
	  *  views.py  此文件是用来处理Web应用程序 request 与 response 周期文件
	7. settings.py 中添加 boards



