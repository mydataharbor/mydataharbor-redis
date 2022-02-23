# mydataharbor-redis
# 作者

MyDataHarbor([1053618636@qq.com](mailto:1053618636@qq.com))

# 项目介绍

该项目是为MyDataHarbor实现redis的Sink，让使用者可以将数据写入redis。支持连接单机，主从，哨兵，cluster模式的各种redis服务端，目前支持string数据格式的操作，有需要可以联系作者扩展：list、set、zset、hash

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

