# 下面的都是废话，其实只需要以下几条语句
- yum -y install git
- git clone https://github.com/flyzy2005/ss-fly
- git checkout master
- ss-fly/ss-fly.sh -ssr
- python /usr/local/shadowsocks/server.py -c /etc/shadowsocks.json -d start
#
{
    "server":"0.0.0.0",
    "server_ipv6":"[::]",
    "local_address":"127.0.0.1",
    "local_port":1080,
    "port_password": {
    "8080": "zkd",
    "8081": "sunyin01",
    "8082": "sunyin02",
    "8083": "sunyin03",
    "8084": "sunyin04",
    "8085": "sunyin05",
    "8086": "sunyin06",
    "8087": "sunyin07",
    "8088": "sunyin08",
    "9000": "sunyin"
    },
    "timeout":600,
    "method":"rc4-md5",
    "protocol":"origin",
    "protocol_param":"",
    "obfs":"plain",
    "obfs_param":"",
    "redirect":"",
    "dns_ipv6":false,
    "fast_open":false,
    "workers":1
}


一键脚本安装shadowsocks/shadowsocksR/V2Ray + 开启bbr
---

一键脚本搭建shadowsocks/shadowsocksR/V2Ray + 设置开启自启动 + 升级内核&开启bbr加速。

## 教程如何访问
因为这个脚本，[flyzy小站](https://www.flyzy2005.com)已经被GFW拉入黑名单了，直接DNS污染了，国内无法访问。

如果有翻墙方法，自然可以直接访问（目前flyzy2005.com已加入GFWList）。如果还在墙内，可以参考[flyzy小站最新访问方式与镜像网站地址](https://flyzyblog.com/way-to-flyzy2005/)访问教程，科学上网吧！

## 支持系统
CentOS 6+

Debian 7+

Ubuntu 12+

## 使用教程
一键搭建ss/ssr：[一键脚本搭建shadowsocks+开启bbr](https://www.flyzy2005.com/fan-qiang/shadowsocks/install-shadowsocks-in-one-command/)

一键搭建V2Ray：[一键脚本搭建V2Ray+配置与优化](https://www.flyzy2005.com/v2ray/how-to-build-v2ray/)

或者参考：[Wiki](https://github.com/flyzy2005/ss-fly/wiki)

## 交流群
flyzy小站交流群：http://t.me/flyzyxiaozhan

搬瓦工用户交流群：https://t.me/banwagongusers

## 推荐的VPS
### 国外VPS
[Vultr优惠网](https://www.vultryhw.cn/)

[搬瓦工优惠网](https://www.bwgyhw.cn/)

### 国内VPS
[阿里云优惠网](https://www.aliyunyhw.com)

[腾讯云优惠网](https://www.tengxunyunyhw.com)

### VPS信息汇总
[VPS GO](https://www.vpsgo.com)
