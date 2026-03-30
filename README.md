# BiliTaskLite

轻量版 B 站每日任务脚本。

当前保留的调整：

- 投币成功判断以 `code === 0` 为准
- 投币结束后再次查询经验，确认今日投币进度

已确认的投币成功返回示例：

```json
{
  "code": 0,
  "message": "OK",
  "ttl": 1,
  "data": {
    "like": true
  }
}
```

订阅地址：

- `https://raw.githubusercontent.com/WenJiazhi/BiliTaskLite/main/BiliTaskLite.plugin`
