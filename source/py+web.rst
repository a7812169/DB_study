python web开发路线
====================
小白级

常用库
-------------
- `Flask <http://www.pythondoc.com/flask-mega-tutorial/index.html>`_  一个使用 Python 编写的轻量级 Web 应用框架
- Bootstrap 目前很受欢迎的前端框架 基于HTML，CSS,JavaScript
- Django Web应用框架，由Python写成。采用了MTV的框架模式，即模型M，模板T和视图V

技术
------------
- 了解并能使用前端基本内容，HTML,CSS,JavaScript
- 简单了解WSGI & uwsgi
- 能够灵活使用模板
- 了解ORM，MVC模式
- 可独立写微信小程序

书籍
-----------
- Flask Web开发:基于Python的Web应用开发实战
- Flask 扩展文档汇总

::

	柳真学长补充：

 （1）学习Flask框架，可以去尝试使用一下swagger工具。swagger可以根据接口文档自动生成编写接口代码，可以很快实现接口需求。缺点是稳定性可能不好，有可能出现bug, 不过对于一些小项目来说是绰绰有余。

 (2)打算学习python web方向，学会如何对后端项目配置nginx

 （3）除了Flask、Django框架外，还有高并发处理Tornado框架和底层自定义协议网络Twisted框架，有额外时间可以研究下

 （4）除了基本框架学习外，还要对数据存储方面的技术有所了解和研究。深入学习使用Redis数据库，最好能够阅读源码；学会使用rabbitmq,并能够在框架中结合使用；学会使用Celery，最好结合Redis进行使用，并整合到框架中进行使用，Celery最实用的一点就是定时任务相关功能实现。

 （5）作为数据库组成员，除了Redis键值对数据库外，还有学会设计关系型数据库，使用的话建议先上手mysql，然后再稍微研究一下Oracle。非关系型数据库，就研究一下MongoDB和Redis即可。

 （6）学习python，基础是要用好linux系统。初学者建议刚开始就从linux入门，不要图方便使用windows，有额外时间可以多研究一下linux系统相关命令，以及如何快捷高效部署后端代码。

 （7）python基础可以关注一下pythonic的写法，平常写代码要先思考，如何写的精简，代码也要学会怎样写较规范。

学习成果检验
-----------------
独立做出一个微信小程序并实现后台功能

or

独立开发一个自己的博客
