---
title: Wireshark工具使用
date: 2022-06-18 13:59:11
tags:
- Wireshark
- 网络
- 抓包
---

## wireshark常用筛选规则
```
# 筛选源IP
ip.addr==<source-ip>

# 筛选目标IP
ip.dst==<target-ip>

# 筛选server端口
tcp.port==<target-port>

# 协议名称过滤
比如:http

```

## 关于localhost调试

> wireshark选择网卡的时候需要选择 <npcap loopback adapter网卡（环回网卡）>

## FAQ

1.使用本地工程调试，无法显示http协议
解答：在http协议的配置中，配置tcp端口，比如本地工程开放8009端口调试，则在此处添加8009端口。

