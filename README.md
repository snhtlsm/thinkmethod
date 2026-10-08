# ThinkMethod — 多维度后果推演与最优决策引擎

> **v2.1.0 · 更新于 2026-10-05** · 💰 Paid Skill（付费下载，本仓为落地页）

[中文](#中文说明) | [English](#english)

---

## 中文说明

### 这是什么

**ThinkMethod** 是一个注入 Agent 系统提示层的**底层思考协议**：在执行任何工具调用、代码修改或决策**之前**，强制进行多维度后果推演、成本效益分析与最优路径选择。

核心哲学：**没有无后果的行动 · 多维度优于单维度 · 最优解非最快解**。

### 功能特性（v2.1.0）

| 模块 | 说明 |
|------|------|
| 5D-CF 五维度推演 | 每个方案预演 最有利/有利/平凡/不利/最差 五种结局，含触发条件、成本与补救措施 |
| CEM 综合评估矩阵 | 效果30% · 成本25% · 风险20% · 体验15% · 可维护性10% 加权打分选最优 |
| 八步执行流程 | 收集信息 → 脑暴方案 → 5D推演 → CEM打分 → 选定 → 预置补救 → 执行 → 事后复盘 |
| 特殊场景规则 | 信息不足 / 时间敏感 / 涉及外部API付费服务 / 涉及文件数据修改 的专项处置 |
| 防陷阱清单 | 防分析瘫痪、防低估用户耐心、防因噎废食、防忽视情感需求 |
| Skill 协同表 | 与 plan / debugging / code-review / spike / TDD 等技能的开箱协同方式 |

### 适用场景

生产环境变更、不可逆操作、多方案取舍、风险评估、成本敏感任务——任何"先想清楚再动手"的时刻。

### 💰 价格与获取（Paid Access）

- **一次性买断：¥9.9 / US$2.9**（含后续全部更新）
- 支付方式：
  - **GitHub Sponsors**：https://github.com/sponsors/snhtlsm （一次性赞助 ≥$2.9 即获得访问权）
  - **微信 / 支付宝**：收款码见下方图片
- **流程**：付款 → 备注你的 GitHub 用户名 → 作者邀请你加入私有仓库 `thinkmethod-pro` → 按仓内 README 安装

![微信支付](pay-wechat.png) ![支付宝](pay-alipay.png)

### 使用要求

任何支持 SKILL.md 的 Agent 环境（Hermes Agent 最佳；Claude Code / Kimi CLI 等亦可）。无外部 API 依赖，零密钥。

### License

- 本公开仓内容：**View & Review Only**
- 付费用户：个人使用授权。**禁止**二次分发、转售、公开 skill 内容
- Copyright © 2026 snhtlsm. All rights reserved.

---

## English

**ThinkMethod** is a foundational reasoning-protocol skill injected into your agent's system layer: **before** any tool call, code change, or decision, it forces multi-scenario consequence prediction, cost-benefit analysis, and optimal-path selection.

### Highlights (v2.1.0, 2026-10-05)

- **5D-CF**: every candidate plan is pre-played across Best / Good / Neutral / Bad / Worst outcomes, with preconditions, costs, and remediation for each
- **CEM scoring matrix**: weighted scoring (effectiveness 30% · cost 25% · risk 20% · experience 15% · maintainability 10%) picks the optimal path
- 8-step execution flow, special-scenario rules (insufficient info / time-critical / paid-API / data-modifying), anti-trap checklist, skill synergy table
- Zero external API dependencies, no keys required

### 💰 Paid Access

- **One-time: US$2.9 / ¥9.9** (all future updates included)
- Payment: **GitHub Sponsors** https://github.com/sponsors/snhtlsm · WeChat / Alipay (QR codes above)
- Flow: pay → note your GitHub username → invitation to private repo `thinkmethod-pro` → install per its README

### License

Public repo: **View & Review Only**. Buyers: personal-use license; redistribution and resale prohibited. Copyright © 2026 snhtlsm. All rights reserved.

---

*Author: snhtlsm | Built by BlackCatWoman*
