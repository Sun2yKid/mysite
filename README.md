Django official tutorial

[https://docs.djangoproject.com/zh-hans/3.0](https://docs.djangoproject.com/zh-hans/3.0)


```
$ django-admin startproject mysite

$ python manage.py startapp polls

$ python manage.py migrate
应用数据库迁移, migrate 命令检查 INSTALLED_APPS 设置, 为其中的每个应用创建需要的数据表 

$ python manage.py makemigrations polls
通过运行 makemigrations 命令，Django 会检测你对模型文件的修改，并且把修改的部分储存为一次迁移

$ python manage.py sqlmigrate polls 0001
sqlmigrate 命令接收一个迁移的名称，然后返回对应的 SQL

$ python manage.py check
检查项目中的问题，在检查过程中不会对数据库进行任何操作

$ python manage.py migrate
应用数据库迁移

$ python manage.py shell
打开 Python 交互式命令行

$ python manage.py createsuperuser
创建一个能登陆管理页面对用户

```

Django 源码所在位置

> $ python -c "import django; print(django.__path__)"
