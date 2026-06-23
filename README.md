# sb-rule-set

本项目通过 GitHub Actions 每天定时拉取 [Loyalsoldier/v2ray-rules-dat](https://github.com/Loyalsoldier/v2ray-rules-dat) 最新发布的路由数据，并使用 `v2dat` 将其精准拆分，最终编译为 [sing-box](https://github.com/SagerNet/sing-box) 原生支持的 `.srs` (Rule Set) 二进制格式。

**✨ 特性：**
* 🕒 **每日更新**：跟随上游规则库每天自动同步编译。
* 📦 **按需获取**：所有 tag 均被拆分为独立的 `.srs` 文件，拒绝臃肿。
* ⚡ **直链友好**：完全支持在 sing-box 配置中通过 GitHub Raw 或 jsDelivr 等 CDN 远程调用。
