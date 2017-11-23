## API目录
* [登录认证](docs/api/Authenticate.md)
* [媒体管理](docs/api/MediaManage.md)
* [任务管理](docs/api/Job.md)
* [通道管理](docs/api/Pipeline.md)
* [模板管理](docs/api/Preset.md)
* [媒体库管理](docs/api/Storage.md)

## 公共错误码
| Code | Message | 语义 |
| :---: | :----: | :--- |
| 0    | Success       | 成功    |
| 1    | Params Error | 参数错误    |
| 2    | Method Error | HTTP方法错误    |
| 3    | Not Found       | 没有查询到数据 |
| 5    | Permission Denied | 权限不够  |
| 99    | Failed| 操作失败  |
| 302    | Location | 重定向，通常由于登录超时  |
