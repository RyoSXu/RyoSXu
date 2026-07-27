## 徐尚 · Ryo Xu

上海大学计算机科学与技术硕士（2027 届）｜AI 应用 · 工业软件全栈 · PLC 工程 · 材料机器学习

ABB/B&R 工业自动化 · AI 应用开发实习生（2026.04 — 至今）

[个人主页](https://ryosxu.github.io) · [Email](mailto:xushang@shu.edu.cn)

---

### Featured Work

#### MDoctor · 工业振动分析平台

- 将原 PyQt 工具重构为 FastAPI + Vue 3 / TypeScript 前后端分离平台，独立完成需求分析、架构设计、核心开发及 Windows 部署交付。
- 打通 PLC、FTP、CSV、SQLite、特征提取与诊断展示链路，覆盖在线监测、离线导入、异常重试、配置管理及报告归档。
- 基于 NumPy / SciPy 实现时域特征、FFT、包络解调、速度谱与异常检测，并通过 ECharts 构建波形、频谱、瀑布图及健康趋势分析。
- 建立 pytest + Vitest 自动化测试与历史样本回归体系，覆盖 **1,200+ 项后端测试、69 项前端测试**，并基于 **720 份历史采样**验证重构一致性。

#### MCode · 工业智能编程工具

- 围绕代码修改、上下文管理和编译诊断独立设计 **3 类场景、80+ 条测试用例**，提交 **20+ 个有效缺陷**并完成多轮版本回归。
- 参与迭代 AGENTS.md、Agent Skill 与 MCP 配置，将代码规范、工程约束、知识检索和 Build 反馈接入 Agent 工作流。

---

### Research

#### Phonon Transformer · Atomic Relative Position Encoding Attention Transformer

基于 PyTorch 独立实现从晶体结构预测声子态密度的 Phonon Transformer，在注意力机制中引入原子相对位置与距离编码以捕获晶体几何关系。

- 构建并验证 **24,000+ 条数据、覆盖 86 种元素**的声子态密度数据集。
- 相较原 SOTA 模型 Mat2Spec，**MAE 降低 27.6%**；将传统 DFT 小时级计算压缩至毫秒级推理。
- 相关成果发表于 *npj Computational Materials*（**第一作者，中科院一区 TOP，JCR Q1，IF 13.1**）。

[Paper](https://doi.org/10.1038/s41524-026-02199-3) · [Code](https://github.com/RyoSXu/ARPAT)

---

### Selected Projects

- **[ARPAT](https://github.com/RyoSXu/ARPAT)** — Atomic Relative Position Encoding Attention Transformer，端到端预测声子态密度。
- **[RyoMonitor](https://github.com/RyoSXu/RyoMonitor)** / **[RyoAuthGate](https://github.com/RyoSXu/RyoAuthGate)** — 基于 Go 的 VPS 监控与 Caddy forward-auth 统一认证。
- **[d2-ai-context](https://github.com/RyoSXu/d2-ai-context)** — 将 Destiny 2 装备数据转换为 AI 可读的本地上下文。

---

### Open Source Contributions

- **[mm7894215/TokenTracker](https://github.com/mm7894215/TokenTracker)**
  - [![PR #311 status](https://img.shields.io/github/pulls/detail/state/mm7894215/TokenTracker/311?style=flat-square&label=PR%20%23311)](https://github.com/mm7894215/TokenTracker/pull/311) — 为 AnythingLLM Desktop 增加跨平台、隐私友好的增量 Token 用量采集，已随 v0.79.3 发布。
- **[transmute-app/transmute](https://github.com/transmute-app/transmute)**
  - [![PR #222 status](https://img.shields.io/github/pulls/detail/state/transmute-app/transmute/222?style=flat-square&label=PR%20%23222)](https://github.com/transmute-app/transmute/pull/222) — 支持跟随系统并分别配置浅色、深色主题。
  - [![PR #220 status](https://img.shields.io/github/pulls/detail/state/transmute-app/transmute/220?style=flat-square&label=PR%20%23220)](https://github.com/transmute-app/transmute/pull/220) — 为文件与任务历史增加 API 驱动的服务端分页。
  - [![PR #214 status](https://img.shields.io/github/pulls/detail/state/transmute-app/transmute/214?style=flat-square&label=PR%20%23214)](https://github.com/transmute-app/transmute/pull/214) — 为 PDF 转换增加 Docker 友好的自定义 CSS 支持。
- **[hmjz100/LinkSwift](https://github.com/hmjz100/LinkSwift)**
  - [![PR #431 status](https://img.shields.io/github/pulls/detail/state/hmjz100/LinkSwift/431?style=flat-square&label=PR%20%23431)](https://github.com/hmjz100/LinkSwift/pull/431) — 修复 `alipan.com` 域名兼容场景下的 Token 空值问题。
- **[C4illin/ConvertX](https://github.com/C4illin/ConvertX)**
  - [![PR #571 status](https://img.shields.io/github/pulls/detail/state/C4illin/ConvertX/571?style=flat-square&label=PR%20%23571)](https://github.com/C4illin/ConvertX/pull/571) — 增加面向 PDF 转换的区域感知 CJK 字体支持。
- **[glanceapp/glance](https://github.com/glanceapp/glance)**
  - [![PR #1033 status](https://img.shields.io/github/pulls/detail/state/glanceapp/glance/1033?style=flat-square&label=PR%20%231033)](https://github.com/glanceapp/glance/pull/1033) — 修复 `X-Forwarded-For` 解析导致的速率限制绕过。
- **[imsyy/DailyHotApi](https://github.com/imsyy/DailyHotApi)**
  - [![PR #141 status](https://img.shields.io/github/pulls/detail/state/imsyy/DailyHotApi/141?style=flat-square&label=PR%20%23141)](https://github.com/imsyy/DailyHotApi/pull/141) — 将快手热榜路由由 HTML 抓取切换至 GraphQL API。
- **[iib0011/omni-tools](https://github.com/iib0011/omni-tools)**
  - [![PR #398 status](https://img.shields.io/github/pulls/detail/state/iib0011/omni-tools/398?style=flat-square&label=PR%20%23398)](https://github.com/iib0011/omni-tools/pull/398) — 提议使用密码学安全随机数生成密码；并行实现 [#401](https://github.com/iib0011/omni-tools/pull/401) 合并时获维护者公开致谢。

---

### Tech Stack

- **编程语言：** Python · TypeScript · C/C++ · Go · Structured Text
- **机器学习：** PyTorch · Transformer · GNN
- **全栈开发：** Vue 3 · FastAPI · ECharts · SQLite · REST API
- **工业与部署：** PLC · OPC UA · FTP · Git · Windows/Linux · Docker
- **AI 工程：** RAG · Agent Skill · MCP · Coding Agent
