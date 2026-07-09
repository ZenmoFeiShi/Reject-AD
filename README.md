# Reject-AD

Quantumult X / 通用重写广告拦截规则合集。

[![Stars](https://img.shields.io/github/stars/ZenmoFeiShi/Reject-AD?style=flat-square)](https://github.com/ZenmoFeiShi/Reject-AD/stargazers)

## 文件

| 文件 | 说明 |
|---|---|
| `rewrite.conf` | 广告拦截 / reject-dict 规则 |

## 使用方式

在 Quantumult X 中添加远程重写资源：

```text
https://raw.githubusercontent.com/ZenmoFeiShi/Reject-AD/main/rewrite.conf, tag=Reject-AD, update-interval=172800, opt-parser=true, enabled=true
```

或手动复制规则到本地 `[rewrite_local]` 段。

## 覆盖范围（节选）

- 同花顺广告
- 中信银行广告图
- 汽水音乐 / 抖音相关广告接口
- 百度网盘信息流
- 顺丰视频流
- 其它常见 App 开屏 / 弹窗接口

## 说明

- 规则会随 App 接口变化而失效，欢迎自行补充
- 仅供学习交流，自行承担使用风险

## Author

[@ZenmoFeiShi](https://github.com/ZenmoFeiShi) · 协作参考 fmz200
