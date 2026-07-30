# 具身智能学习手册 | Embodied AI Learning Handbook

> 一份系统性的具身智能（Embodied AI）学习指南，覆盖从基础理论到前沿技术、从仿真实验到真机部署的完整知识体系。整合了 1800+ 篇论文、技术文档和项目资源的深度分析。

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)
[![Made with Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://www.markdownguide.org/)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./CONTRIBUTING.md)

---

## 项目简介

本手册是一份面向具身智能学习者的系统性知识指南，旨在帮助读者快速建立从感知-决策-执行的闭环认知框架，并提供可落地的实践路径。手册共包含 **17 个目录、69 篇 Markdown 文档**，内容涵盖：

- 具身智能基础理论（机器人学、深度学习、多模态融合）
- 核心算法（模仿学习、强化学习、视觉感知、轨迹规划）
- 前沿技术（VLA 模型、Diffusion Policy、Sim2Real、世界模型）
- 仿真环境实战（MuJoCo、Isaac Lab、PyBullet、Genesis）
- 数据飞轮与遥操作（ALOHA、UMI、数据采集与增强）
- 顶会论文精选（CVPR / AAAI / ICLR / NeurIPS 2023-2025）
- 行业研究与产业报告（人形机器人、灵巧手、传感器）
- 本地项目技术讨论精华（VLA 闭环落地、方向选择、会议记录）

## 目录结构

| 编号 | 目录 | 说明 |
|------|------|------|
| 00 | 总览与学习路径 | 手册导航、学习路线规划、资源地图、分析报告 |
| 01 | 具身智能概述 | 术语速览、操作/世界模型/运动控制/导航综述 |
| 02 | 基础学习 | 机器人学基础、Transformer、Diffusion、训练技巧、环境搭建 |
| 03 | 经典算法 | 模仿学习、强化学习、视觉感知、轨迹规划与控制 |
| 04 | 前沿技术 | VLA 模型、Diffusion Policy、VLA+RL、Sim2Real、大模型 SFT |
| 05 | 仿真环境 | MuJoCo、Isaac Lab、PyBullet、Genesis、Gazebo |
| 06 | 数据飞轮与遥操作 | 遥操作系统、数据采集、数据清洗与增强 |
| 07 | 开源实物与平台 | LeRobot、GR00T、人形机器人平台、灵巧手控制 |
| 08 | 项目实战 | 环境搭建、Sim2Sim、Sim2Real、VLA 训练、遥操作链路 |
| 09 | 行业与职业 | 公司图谱、学术界人物、岗位需求、求职指南 |
| 10 | 论文与资源 | 必读论文清单、开源项目索引、全球实验室图谱、Awesome 资源 |
| 11 | 本地项目与技术讨论 | VLA 闭环落地、模型架构、遥操作、智元开发者日、会议精华 |
| 12 | 主动视觉专项 | 主动视觉技术全景、论文综述、1 年转型计划 |
| 13 | VLA 前沿论文精读 | BayesVLA、WoVR、RL-Co、smart-video-nav |
| 14 | 行业研究与产业报告 | 人形机器人产业、灵巧手技术、电机演进、六维力传感器 |
| 15 | ML-DL 基础与大模型资源 | ML/DL 学习路线、大模型 Agent、RLHF、多模态资源 |
| 16 | 顶会论文分类精选 | CVPR/AAAI/ICLR/NeurIPS 论文精选、LLM-Agent 与 RLHF 精析 |

## 快速开始

### 推荐学习路径

```
初学者：00.1 总览 → 01.1 术语速览 → 02 基础学习 → 03 经典算法 → 04 前沿技术 → 08 项目实战
CV/NLP 转向：02.2 Transformer → 02.3 Diffusion → 04.1 VLA 模型 → 06 数据飞轮 → 08 项目实战
工业界速成：02.5 环境搭建 → 06 遥操作 → 04.1 VLA → 08.4 VLA 训练微调
研究方向探索：11.5 方向选择 → 12 主动视觉 → 13 VLA 论文精读 → 16 顶会论文精选
```

### 前置知识要求

- Python 编程（熟练）
- PyTorch 框架（中级）
- 线性代数、概率统计基础
- Linux 命令行基础

详细自测清单见 [00.1-README-总览.md](./00-总览与学习路径/00.1-README-总览.md)。

## 致谢与引用

本手册在编写过程中参考了大量优秀的开源项目和社区资源，特别是：

- **[Embodied-AI-Guide](https://github.com/TianxingChen/Embodied-AI-Guide)** by [@TianxingChen](https://github.com/TianxingChen) — 本手册的核心参考项目，提供了具身智能技术指南的框架和大量原始资料（非商业使用许可协议）
- **[Xbotics-Embodied-Guide](https://github.com/Xbotics-Embodied-AI-club/Xbotics-Embodied-Guide)** by [Xbotics 具身智能社区](https://xbotics-embodied.site/) — 提供了路线化学习指南的组织思路和方法论（CC BY-NC-SA 4.0）
- **[Xbotics-Embodied-AI-Job](https://github.com/Xbotics-Embodied-AI-club/Xbotics-Embodied-AI-Job)** by [Xbotics 具身智能社区](https://xbotics-embodied.site/) — 具身智能岗位信息合集，用于行业趋势分析
- **[BotRunner64](https://github.com/BotRunner64)** — 遥操作项目实战参考（teleopit、somehand、pico-bridge、OpenNeck）
- **[Awesome-LLM-Robotics](https://github.com/GT-RIPL/Awesome-LLM-Robotics)** by GT-RIPL — LLM + 机器人论文索引
- **[Genesis](https://github.com/Genesis-Embodied-AI/Genesis)** — 通用机器人仿真平台
- **[RoboTwin](https://github.com/TianxingChen/RoboTwin)** — 双臂操作仿真基准平台

完整致谢列表请见 [ACKNOWLEDGMENTS.md](./ACKNOWLEDGMENTS.md)。

> **重要声明**：本手册中引用的论文、代码、数据集等资源版权归原作者所有。Embodied-AI-Guide 项目采用非商业使用许可协议，Xbotics-Embodied-Guide 采用 CC BY-NC-SA 4.0 许可协议，本手册遵循两者中最严格的条款（非商业 + 署名 + 相同方式共享），仅供非商业学习交流使用。

## 许可证

本项目采用 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)（Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International）许可协议，继承自：

- Embodied-AI-Guide（非商业使用许可协议）
- Xbotics-Embodied-Guide（CC BY-NC-SA 4.0）

- 允许：免费使用、复制、修改、再分发（非商业）
- 禁止：任何形式的商业使用
- 要求：署名 + 相同方式共享（ShareAlike）+ 保留版权声明和许可条款

如需商业授权，请联系：
- Embodied-AI-Guide：chentianxing2002@gmail.com
- Xbotics 社区：xbot_hc@163.com

## 贡献

欢迎通过以下方式参与贡献：

1. 提交 Issue 报告错误或建议
2. 提交 Pull Request 补充内容
3. 分享学习笔记和实践经验

详见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 联系方式

- 提交 Issue：[GitHub Issues](../../issues)
- 邮件联系：（请在 Issue 中留下联系方式）

---

> 如果这个项目对你有帮助，欢迎 Star 支持一下！
