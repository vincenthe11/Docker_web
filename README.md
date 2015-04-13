Docker_web
==========

安装docker

$ sudo apt-get update
$ sudo apt-get install docker.io
$ sudo ln -sf /usr/bin/docker.io /usr/local/bin/docker
$ sudo sed -i '$acomplete -F _docker docker' /etc/bash_completion.d/docker.io

安装docker python api
$ pip install docker-py

修改docker_web 下setting.py
设置自己mysql数据库
然后执行python manage.py syncdb同步数据库
