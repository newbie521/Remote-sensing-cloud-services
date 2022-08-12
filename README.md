调用flex、bison做出的计算器编译器，支持自定义函数，前端html，js，css， 后端flask

调用

1. 进入服务器中
1. 进入 /home/falsk 路径下
1. 启动虚拟环境，source env/bin/activate
1. 进入 ./calculator 文件夹中
1. 启动 flask项目 pthon calculator.py
1. 该项目运行在1024端口，即[http://124.223.190.139:1024/](http://124.223.190.139:1024/)

![image.png](https://cdn.nlark.com/yuque/0/2022/png/26707870/1648211076112-4a6faec4-b338-4ed5-be3a-4b225eee2da5.png#clientId=uabc72c50-1480-4&crop=0&crop=0&crop=1&crop=1&from=paste&height=850&id=ucbba3896&margin=%5Bobject%20Object%5D&name=image.png&originHeight=850&originWidth=1503&originalType=binary&ratio=1&rotation=0&showTitle=false&size=567306&status=done&style=none&taskId=uadcda91c-8766-45d9-8f40-cd98b8eab81&title=&width=1503)



```c
# ubuntu20 已移除python2且自带python3
apt update && apt upgrade 
python3 -V 
apt-cache search venv 
apt -y install python3-venv 

# 创建venv环境
python3 -m venv /opt/my_first_venv 
cd /opt/my_first_venv 
# 激活venv环境
source my_first_venv/bin/activate

# 激活后shell提示会变化为如下所示
(my_first_venv) # 

# 停用venv环境
(my_first_venv)  deactivate



```
