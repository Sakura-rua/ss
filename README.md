一键脚本安装shadowsocks/shadowsocksR/V2Ray + 开启bbr
---

一键脚本搭建shadowsocks/shadowsocksR/V2Ray + 设置开启自启动 + 升级内核&开启bbr加速。


## 支持系统

CentOS 6+

Debian 7+

Ubuntu 12+

## 使用教程

#### 一键搭建ss/ssr

```markdown

Centos  
yum -y install git
  
Debian  
apt-get update && apt-get -y install git  
  
git clone https://github.com/Sakura-rua/ss.git  
  
一键搭建ss脚本  
ss/ss.sh -i password port  
  
卸载ss  
ss/ss.sh -uninstall

相关ss操作  
启动：/etc/init.d/ss start  
停止：/etc/init.d/ss stop  
重启：/etc/init.d/ss restart  
状态：/etc/init.d/ss status  
查看ss链接：ss/ss.sh -sslink  
修改配置文件：vim /etc/shadowsocks.json

```

