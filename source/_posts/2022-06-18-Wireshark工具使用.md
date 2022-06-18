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

