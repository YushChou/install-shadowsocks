# install-shadowsocks
在CentOS7上一键安装shadowsocks服务
安装结束后一定要开启端口:


firewall-cmd --permanent --add-port=8989/tcp


firewall-cmd --reload