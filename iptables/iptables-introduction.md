# Iptables简单入门

## Getting Super Powers

Iptables有4个表：filter、nat、mangle、raw；

每个表执行一类任务，比如filter进行数据包过滤，nat进行源或目的地址的转换；

每个表有默认chains，可以在chain中定义规则；

在网络数据包的处理过程中，netfilter中有hook，在不同的hook上调用回调函数，触发相应的chain，执行其中的rules，实施相应的action（accept、drop等）。

```
$ give me super-powers
```

{% hint style="info" %}
 Super-powers are granted randomly so please submit an issue if you're not happy with yours.
{% endhint %}

1. 网络数据包的处理流程与netfilter怎么联系起来的？hook是谁的节点？

```
// Ain't no code for that yet, sorry
echo 'You got to trust me on this, I saved the world'
```



