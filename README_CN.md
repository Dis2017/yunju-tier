# yunju-tier

[![GitHub](https://img.shields.io/github/license/Dis2017/yunju-tier)](LICENSE)

> 基于 [EasyTier](https://github.com/EasyTier/EasyTier) 的定制发行版，在保留原项目完整的 P2P 组网能力基础上，针对特定场景进行增强和二次开发。

---

## 说明

本仓库 Fork 自 [EasyTier v2.6.4](https://github.com/EasyTier/EasyTier)（LGPL-3.0 协议），
在此鸣谢 EasyTier 原项目及其贡献者。

### 与原版的差异

在此基础上的增量能力：

- (待开发)

其余所有 P2P 组网、NAT 穿透、隧道协议、路由、管理等功能与原版保持一致。

### 原版能力摘要

yunju-tier 继承了 EasyTier 的完整能力：

- **去中心化组网**：节点平等且独立，无需中心化服务
- **多协议隧道**：TCP / UDP / WireGuard / WebSocket / WSS / QUIC / FakeTCP
- **NAT 穿透**：UDP 打洞、TCP 打洞、UPnP、端口预测
- **智能路由**：OSPF 风格链路状态路由，延迟优先路径选择
- **子网代理**：节点可共享本地子网
- **加密**：AES-GCM / ChaCha20-Poly1305 / WireGuard 加密
- **跨平台**：Linux / Windows / macOS / FreeBSD / Android
- **Web 控制台**：可选部署，浏览器管理

详见 [EasyTier 官方文档](https://easytier.cn)。

---

## License

本项目基于 LGPL-3.0 协议开源。详见 [LICENSE](LICENSE)。
