# 网络测试

一些对于临时测试网络有用的 API

## Plain Text

### IP

```
GET https://net.lolicon.app
```

### User Agent

```
GET https://net.lolicon.app/ua
```

## JSON

#### Details

```
GET https://net.lolicon.app/detail
```

| 字段名         | 数据类型 | 说明                                         |
| -------------- | :------: | -------------------------------------------- |
| `ip`           | `string` | IP                                           |
| `headers`      | `object` | HTTP 请求头                                  |
| `httpProtocol` | `string` | HTTP 协议版本                                |
| `tlsVersion`   | `string` | TLS 版本                                     |
| `tlsCipher`    | `string` | TLS 加密算法                                 |
| `asn`          |  `int`   | ASN                                          |
| `country`      | `string` | 两个字母表示的国家/地区代码                  |
| `colo`         | `string` | 三个字母表示的请求命中的 CloudFlare 数据中心 |
