# 网络测试

一些对于临时测试网络有用的 API

## Plain Text

### IP

```http
GET https://net.lolicon.app
```

or

```http
GET https://net.lolicon.app/ip
```

### User Agent

```http
GET https://net.lolicon.app/ua
```

## JSON

#### Details

```http
GET https://net.lolicon.app/detail
```

| 字段名    | 数据类型 | 说明                                                                                                                      |
| --------- | :------: | ------------------------------------------------------------------------------------------------------------------------- |
| `ip`      | `string` | IP                                                                                                                        |
| `headers` | `object` | HTTP 请求头                                                                                                               |
| `cf`      | `object` | 见 [Cloudflare Workers 文档](https://developers.cloudflare.com/workers/runtime-apis/request/#incomingrequestcfproperties) |
