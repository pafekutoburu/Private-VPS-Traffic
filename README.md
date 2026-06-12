# Surge VPS Traffic Panels

Surge iOS information panels for VPS traffic usage.

## 搬瓦工

通过 KiwiVM API 显示 VPS 状态、月流量、剩余流量和重置时间。

安装地址：

```text
https://raw.githubusercontent.com/succichang/surge-bandwagon-traffic/main/Bandwagon-Traffic.sgmodule
```

安装后在模组参数中填写自己的 `VEID` 和 `API_KEY`。

## NovixLink

通过 AnyTLS 节点读取 VPS 本机的持久化流量统计，不需要 NovixLink 账户或
商家 API，也不开放额外公网端口。

安装地址：

```text
https://raw.githubusercontent.com/succichang/surge-bandwagon-traffic/main/NovixLink-Traffic.sgmodule
```

使用前需要在 VPS 安装本地统计服务，详见
[NovixLink-Traffic-使用说明.md](./NovixLink-Traffic-%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E.md)。

## 安全

仓库不包含任何用户密钥、VPS IP 或节点密码。
