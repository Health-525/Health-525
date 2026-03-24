# JiangShu

> Building AI workflows, learning systems, and useful tools.

I like turning messy inputs into structured systems —
videos into notes, schedules into workflows, and daily learning into reusable knowledge.

---

## What I work on

- **AI-powered workflows** for extraction, note generation, and content automation
- **Learning systems** that make studying easier to organize, review, and accumulate
- **Knowledge pipelines** that turn daily inputs into long-term assets
- **Lightweight tools** focused on usefulness, clarity, and speed

---

## Featured Projects

<table>
<tr>
<td width="50%">

### 🎓 Learning OS
**[全自动学习工作流](https://mp.weixin.qq.com/s/ZKxoxGp7p0mkfp-9q5FgfA)** · `2026.03`

GitHub + OpenClaw + Obsidian 三端联动，打通课表/调课/笔记/作业/信息流的自动化学习系统。

`GitHub Actions` `Obsidian` `iOS Shortcuts`

</td>
<td width="50%">

### 🎯 FrameDetective
**["人贩终结者"](https://github.com/Health-525/FrameDetective)** · `Hackathon 2025.12`

大模型驱动的视频目标追踪系统，支持样本图+提示词检索海量监控。

🏆 **模法黑客松 S1 最佳人气奖**

`Qwen-2.5-VL` `SAM-3` `视频帧级检索`

</td>
</tr>
<tr>
<td width="50%">

### 📹 VideoNote AI
**[字幕提取与 AI 总结](https://github.com/Health-525/videonote-ai)** · `2025.10`

YouTube/Bilibili 一键字幕提取 + 智能总结，yt-dlp 实时获取替代复杂 ASR 链路。

`n8n` `yt-dlp` `LLM Summarization`

</td>
<td width="50%">

### 🏫 Campus Hub
**校园学习与生活管理** · `2025.11–12`

飞书多维表格驱动的课表查询、笔记管理、练功打卡一体化系统。

`飞书多维表格` `自动化公式` `数据可视化`

</td>
</tr>
<tr>
<td width="50%">

### ⚡ 网课榨汁机
**究极体自动化系统** · `2025.11`

n8n + Coze + 飞书多场景自动化，本地→内网穿透→云部署完整链路。

`n8n` `Coze` `Cloudflare Tunnel` `火山引擎 ECS`

</td>
<td width="50%">

### 📅 Timetable
**[自动化中枢](https://github.com/Health-525/timetable)**

GitHub Actions 驱动的课表生成、作业追踪、调课同步、YouTube 笔记流水线。

`GitHub Actions` `Next.js` `PWA`

</td>
</tr>
</table>

<details>
<summary><b>📁 更多项目</b></summary>

- **[jiangshu-study](https://github.com/Health-525/jiangshu-study)** — Obsidian-native 个人知识库，支持作业自动追踪与归档
- **[vibechat](https://github.com/Health-525/vibechat)** — 轻量级聊天交互实验

</details>

---

## Project Details

### 🎓 学习操作系统 | 2026.03
> 公众号文章：[阅读原文](https://mp.weixin.qq.com/s/ZKxoxGp7p0mkfp-9q5FgfA)

以 **GitHub 为中枢**，结合 OpenClaw 自动化与 Obsidian 笔记体系：
- 课表/调课/笔记/作业/信息流全打通
- 跨设备实时同步
- 每日自动化流水线

---

### 🎯 智能监控目标追踪系统（"人贩终结者"）| Hackathon 2025.12
> 仓库：[FrameDetective](https://github.com/Health-525/FrameDetective)

| | |
|:---|:---|
| **核心能力** | 上传目标样本图 + 自然语言提示词 → 海量监控视频帧级检索定位 |
| **技术栈** | Qwen-2.5-VL-32B-Instruct · SAM-3 · 视频帧级特征比对 · 动态掩码标注 · 推理报告自动生成 |
| **应用场景** | ToG 公共安全 / ToC 家庭安全，支持私有化部署 |
| **我的职责** | 核心架构设计 · 模型选型与集成 · 高并发视频处理 · 前端开发 |
| **项目成果** | 🏆 **模法黑客松 S1 最佳人气奖** · 获相关部门领导认可，推进落地合作 |

---

### 📹 视频字幕自动提取与 AI 总结系统 | 2025.10
> 仓库：[videonote-ai](https://github.com/Health-525/videonote-ai)

**技术演进路径：**
```
音频提取 → 云存储 → ASR API 调用    [旧流程：复杂、慢、贵]
        ↓ 优化为
yt-dlp 实时获取字幕 → LLM 总结       [新流程：简洁、快、省]
```

**输出格式：**
- 原始字幕（SRT/VTT）
- AI 精炼总结（Markdown）

**价值：** 3 分钟判断 2 小时视频是否值得看

---

### ⚡ 网课榨汁机（究极体）| 2025.11

**工程落地历程：**
```
本地调试 → Cloudflare Tunnel 内网穿透 → 火山引擎 ECS 云部署
```

**独立解决的工程问题：**
- 网络环境兼容性
- 依赖版本冲突
- 端口配置与安全组

**架构：** n8n + Coze + 飞书，打通多工具割裂，形成可扩展的自动化底座

---

### 🏫 校园学习与生活管理系统（校园搭子）| 2025.11–12

**核心模块：**
| 模块 | 功能 |
|:---|:---|
| 课表查询 | 结构化课程数据 + 自动周次计算 |
| 笔记管理 | 分类归档 + 快速检索 |
| 练功打卡 | 习惯追踪 + 连续天数统计 |
| 成果展示 | 自动统计 + 可视化看板 |

**技术亮点：** 飞书多维表格公式设计，实现零代码数据逻辑

**职责：** 需求分析 → 功能设计 → 数据逻辑 → 上线运维 全流程独立负责

---

## Current Focus

- Study automation with GitHub Actions + Obsidian + iOS Shortcuts
- AI-assisted note-taking from YouTube and other sources
- Personal knowledge management
- Turning repeated manual tasks into zero-friction workflows

---

## Tech Stack

**Languages & Frameworks**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white)

**Automation & Tools**

![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Obsidian](https://img.shields.io/badge/Obsidian-7C3AED?logo=obsidian&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-FF6D5A?logo=n8n&logoColor=white)

**AI & Cloud**

![Qwen](https://img.shields.io/badge/Qwen-2.5--VL-8B5CF6)
![SAM](https://img.shields.io/badge/SAM-3-10B981)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?logo=cloudflare&logoColor=white)

---

## Philosophy

> I prefer tools that stay useful after the hype is gone.

Good systems should:
- **Reduce friction** — 减少使用阻力
- **Save time** — 节省时间成本
- **Improve clarity** — 提升信息清晰度
- **Make knowledge reusable** — 让知识可复用

---

## Links

- 🌐 Website: [jiangshu.fun](https://jiangshu.fun)
- 💻 GitHub: [@Health-525](https://github.com/Health-525)
- 📧 Contact: [通过 GitHub 联系](https://github.com/Health-525)

---

<p align="center">
  <i>Building systems that compound.</i>
</p>
