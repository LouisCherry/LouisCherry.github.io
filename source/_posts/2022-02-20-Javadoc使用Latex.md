---
title: Javadoc使用Latex
date: 2022-02-20 12:27:49
tags: 
- Javadoc
- Latex
---

## 配置方法:javadoc arguments
```
-encoding UTF-8 -charset UTF-8 --allow-script-in-comments -header "<script type='text/javascript' src='http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML'></script>"
```

## Latex写法注意: \(Latex表达式\)
```
例如：\(\sum_i a_i\)

```

缺点：依赖于在线资源
优点：比较方便