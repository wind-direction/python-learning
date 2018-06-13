# [flask官网教程实现](http://docs.jinkan.org/docs/flask/tutorial/index.html)

## 本地运行
```bash
# 进入项目目录
$ cd project/path
$ virtualenv venv
$ . venv/bin/acticate
(venv)$ pip install
# 初始化sqlite
(venv)$ python
>>> from flaskr import init_db
>>> init_db()
>>> exit()
# 增加系统变量: 执行本项目里的setting.cfg文件
(venv)$ export FLASKR_SETTINGS=/project/path/setting.cfg
# 启动服务
(venv)$ python flask.py
```


