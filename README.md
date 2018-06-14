---
description: 介绍文档功能
---

# readme-test

## Linux防火墙

Linux防火墙主要netfilter/iptables实现，iptables命令格式如下：

```
$ iptables -P INPUT DROP
```

{% hint style="info" %}
 iptables命令可以以脚本的方式运行。
{% endhint %}

当iptables熟练之后，就可以使用iptables进行Linux防火墙的配置：

```
# /bin/bash
iptables -A INPUT -m state --state ESTABLISHED,RELATED -j ACCEPT
```



