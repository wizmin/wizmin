<div align="center">

# wizmin

**Windows 平台工具链 · 本地化工程 · 桌面自动化**

`Go` · `PowerShell` · `Win32 API` · 中文优先 / Windows-first

</div>

---

## 我在做什么

日常在 Windows 上写两类东西：**把重复劳动变成脚本**，和**把 LLM 接进具体工作流**。
偏工程落地，少做框架。

- **本地化工具链** —— RPG Maker MV 游戏文本翻译：全量 / 重新 / 补充三种模式，带翻译记忆库与多 LLM 后端。功夫都花在边界上：escape code 还原、遗漏条目对账、多后端输出一致性。
- **桌面自动化** —— 基于 MaaFramework 的 GUI 流程编排：改 pipeline JSON、调 OCR ROI、处理多分辨率与不同客户端之间的差异。
- **加密归档** —— 7-Zip AES-256 + `-mhe=on` 头加密 + KeePassXC 自动登记/读取密码，一条链跑完，全程只输一次主密码。
- **本地推理集成** —— LM Studio 跑 qwen 系列做离线推理，接到翻译、浏览器翻译插件等具体场景里，而不是当聊天玩具。

## 技术栈

| 领域 | 用到的 |
|---|---|
| 语言 | Go · PowerShell · Bash · JSON / 正则重度使用 |
| Windows | Win32 API · 进程与窗口枚举 · 文件/注册表 · 进程令牌与完整性级别 |
| 自动化 | MaaFramework · 图像识别 · OCR ROI 调优 · 定时任务 |
| 工程 | Git / GitHub Actions · 7-Zip CLI · keepassxc-cli · VSCode |
| LLM | LM Studio（qwen2.5-7b / qwen3-14b）· 多家 API 接入 · 提示词与输出校验 |

## 关于这些仓库

主页上的公开仓库**全部是 fork**，是我实际在用的上游工具 —— 游戏签到脚本、逆向样本、资料存档、
早期代理客户端这类，不代表我的开发工作。我自己写的东西多数是自用工具，
因为涉及第三方客户端与素材，按约定不公开分发。

> 涉及第三方软件与素材的改动**仅作个人学习与测试，不分发修改版**。
> 仓库中 fork 项目的版权归各原作者所有，使用请遵守其许可证。

## 环境

Windows · PowerShell 7 · Go · VSCode · LM Studio

---

<sub>Most of my work is Windows-side tooling and LLM-assisted automation. Public repos here are all forks of upstream tools I use day to day; original projects stay private for licensing reasons.</sub>
