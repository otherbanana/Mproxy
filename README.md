# Mproxy
OP/SSX
# 使用教程：
把mproxy放到服务器/root里面

一键搭建mproxy命令：

wget https://raw.githubusercontent.com/otherbanana/Mproxy/master/mproxy;chmod 777 mproxy

运行mproxy

./mproxy -l 80 -r ss服务器ip:ss服务器端口 -d

关闭mproxy 

ps -ef | grep mproxy | grep -v grep | cut -c 9-15 | xargs kill -s 9
