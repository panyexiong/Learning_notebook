# 基础搭建

```powershell
#重启网络服务
service network start

#修改网络配置
vim /etc/sysconfig/network-scripts/ifcfg-ens33

TYPE=Ethernet
PROXY_METHOD=none
BROWSER_ONLY=no
BOOTPROTO=static
DEFROUTE=yes
IPV4_FAILURE_FATAL=no
IPV6INIT=yes
IPV6_AUTOCONF=yes
IPV6_DEFROUTE=yes
IPV6_FAILURE_FATAL=no
IPV6_ADDR_GEN_MODE=stable-privacy
NAME=ens33
UUID=824ec4bd-a9ae-4410-8346-17ce7f3dd111
DEVICE=ens33
ONBOOT=yes
IPADDR=192.168.31.21
NETMASK=255.255.255.0
GATEWAY=192.168.31.1
DNS1=119.29.29.29
```

