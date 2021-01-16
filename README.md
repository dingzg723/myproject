# 介绍
这是一个简单的Django项目，主要功能是从百度获取covid-19疫情数据，使用pyecharts将数据可视化。
python版本不应低于3.6.5，Django版本不应低于3.1.3
# 效果如下
![累计确诊](../main/累计确诊.png)

------

![现有确诊](../main/现有确诊.png)
# 使用方法
拉取项目：git clone https://github.com/ljc545w/myproject.git
创建虚拟环境：
Windows：py -3 -m venv myproject_env
Linux：Virtualenv -p /usr/bin/python3 myproject_env
启动虚拟环境：
Windows：\myproject_env\Scripts\activate
Linux：source myproject_env/bin/activate
安装依赖：
pip3 install -Ur requirements.txt
启动项目：
python manage.py runserver
访问项目：
127.0.0.1:8000
