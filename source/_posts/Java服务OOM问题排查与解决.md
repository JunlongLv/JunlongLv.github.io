---
title: Java服务OOM问题排查与解决
---

## 问题定位

### 查日志

``` bash
kubectl -n [namespace] logs [pod] --previous --tail=50
```
第三次编辑
