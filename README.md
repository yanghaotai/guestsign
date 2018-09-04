#### guest

基于Django的简易发布会签到系统。

### 介绍：

本项目为实现的一个较为完整的发布会签到系统。

__它包含功能:__
  * 完整的发布会签到系统（登录、发布会管理、嘉宾管理、签到功能）
  * 单元测试代码
  * 项目Web接口
  * 接口测试用例
  * Robot Framework测试脚本


### Python版本与依赖库：

  * python3.5+ :https://www.python.org/
  * Django 1.11.x :https://www.djangoproject.com/ (目前只在1.11.x 版本下运行通过)
  * Requests : http://www.python-requests.org/en/master/ (运行/function_tests目录下的接口用例需要)
  * django-bootstrap3 : https://github.com/dyve/django-bootstrap3


### 问题
  1、 在书中 “接口安全机制”一章，曾经介绍了Python的AES加密，由于PyCrypto库在Windows下面安装会有一些问题（而且也早已经年久失修），所以推荐在Linux下安装，我这里发出了一个替代的库：
  pycryptodome：https://github.com/Legrandin/pycryptodome
  它即可以在windows下完全安装，而且保持和PyCrypto API相同的使用。