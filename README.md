在Centos OS中不会自动开启端口 centos 7.0 以后可以用一下命令查看、开启对应端口

查看指定区域所有开启的端口号
firewall-cmd --zone=public --list-ports
在指定区域开启端口(如80端口号，命令方式)
firewall-cmd --zone=public --add-port=80/tcp --permanent
重新启动防火墙
firewall-cmd --reload

# v2ray
最好用的 V2Ray 一键安装脚本 &amp; 管理脚本

## 脚本说明
[V2Ray 一键安装脚本](https://github.com/233boy/v2ray/wiki/V2Ray%E4%B8%80%E9%94%AE%E5%AE%89%E8%A3%85%E8%84%9A%E6%9C%AC)

## 搭建教程
[V2Ray搭建详细图文教程](https://github.com/233boy/v2ray/wiki/V2Ray%E6%90%AD%E5%BB%BA%E8%AF%A6%E7%BB%86%E5%9B%BE%E6%96%87%E6%95%99%E7%A8%8B)

## 资助 V2Ray
请考虑 [资助 V2Ray 发展](https://www.v2ray.com/chapter_00/02_donate.html)

## 更多 V2Ray 教程文章
https://github.com/233boy/v2ray/wiki


