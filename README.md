# mydataharbor-redis
# 作者

MyDataHarbor([1053618636@qq.com](mailto:1053618636@qq.com))

# 项目介绍

该项目是为MyDataHarbor实现redis的Sink，让使用者可以将数据写入redis。

# 实现版本

| 中间件/协议 | 数据源（DataSource） | 写入源（Sink） |
| ----------- | -------------------- | -------------- |
| redis       | 暂不考虑             | ✅全部版本      |

# 配置

## Sink配置

```json
{
    "host": "",
    "port": {},
    "enableAuth": false,
    "auth":"",
    "timeout":""
  }
```

