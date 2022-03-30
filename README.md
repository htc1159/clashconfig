# ClashXProConfig4js

clashXPro 自用规则

文件介绍:
maying_clash_default_direct.ini
黑名单模式，意为「只有命中规则的网络流量，才使用代理」，适用于服务器线路网络质量不稳定或不够快，或服务器流量紧缺的用户。通常也是软路由用户、家庭网关用户的常用模式。


maying_clash_default_proxy.ini
白名单模式，意为「没有命中规则的网络流量，统统使用代理」，适用于服务器线路网络质量稳定、快速，不缺服务器流量的用户。

custom_rules
存放自定义连接,可以自定义配置强制直连/强制走代理(高优先级)
设置方法参见其内部example

自定义方法:
1.修改custom_rules文件,并提交github
2.在clash客户端中点击配置->托管配置->更新


使用方法:
1.复制SSR单端口多用户订阅地址：
2.打开https://api.nameless13.com,转换订阅地址
其中:
[订阅链接]填写1中的订阅地址
[远程配置]填写github中的 maying_clash_default_direct.ini 的地址.
参见:https://docs.nameless13.com/shr#8

规则参见:
https://github.com/Loyalsoldier/clash-rules
规则命令含义参见:
https://blog.666old666.cn/archives/1292


