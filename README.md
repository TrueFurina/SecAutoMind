# SecAutoMind · 官网单页

> 本仓只存放 SecAutoMind 的产品官网（`index.html` + `robots.txt`），**不含源码**。

| | |
|---|---|
| 源码 | [TrueFurina/SecAutoMind-src](https://github.com/TrueFurina/SecAutoMind-src) |
| 下载 | [SecAutoMind-src Releases](https://github.com/TrueFurina/SecAutoMind-src/releases) |
| 定位 | 面向**授权场景**的自主多智能体安全验证平台（赛事题号 XH-202609）：确定性工具优先，LLM 只在静态分析未命中时介入，敏感动作需人工审批 |

## 为什么单独一个仓

官网要独立部署到 GitHub Pages，与 88MB 的源码仓解耦——改一行首页文案不应该触发一次全量拉取。

## 维护约定

产品能力的任何更新只改 `SecAutoMind-src`；本仓仅同步首页文案、下载链接与 robots 策略。
