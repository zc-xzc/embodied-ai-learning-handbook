# 致谢 | Acknowledgments

本手册在编写过程中参考、引用了大量优秀的开源项目、学术论文和社区资源。以下为完整的致谢与引用列表。

---

## 一、核心参考项目

以下项目是本手册的主要参考来源，手册的框架结构和大量内容基于这些项目构建：

### 1. Embodied-AI-Guide（具身智能技术指南）

- **作者**：陈天行（Tianxing Chen）
- **GitHub**：https://github.com/TianxingChen/Embodied-AI-Guide
- **邮箱**：chentianxing2002@gmail.com
- **许可协议**：非商业使用许可协议（Non-Commercial Use License）
- **贡献说明**：
  - 提供了本手册的核心框架结构（基础学习→经典算法→前沿技术→仿真环境→数据飞轮→项目实战）
  - 原始资料包括：具身智能基础技术路线（董云龙）、机器人学简介、RoboTwin 2.0 实践教程
  - 10 个 Awesome 论文资源仓库（Awesome-LLM-Robotics、Awesome-Embodied-Robotics-and-Agent 等）
  - 全球机器人实验室研究组索引（100+ 实验室）
  - State of Robot Learning 2025 年度报告
- **使用方式**：本手册在原项目框架基础上进行了扩展和深度分析，整合了 1800+ 篇本地文件的深度分析结果

### 2. Xbotics-Embodied-Guide（Xbotics 社区具身智能学习指南）

- **作者**：Xbotics 具身智能社区（创始人：Xbotics-木木）
- **GitHub**：https://github.com/Xbotics-Embodied-AI-club/Xbotics-Embodied-Guide
- **社区网站**：https://xbotics-embodied.site/
- **许可协议**：CC BY-NC-SA 4.0（Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International）
  > **注意**：该仓库 README 中标注为 CC BY 4.0，贡献文档中标注为"MIT（代码）+ CC BY 4.0（文档）双许可"，但实际 LICENSE 文件为 CC BY-NC-SA 4.0。本手册以 LICENSE 文件为准，遵循 CC BY-NC-SA 4.0 的全部条款，包括署名、非商业、相同方式共享。
- **贡献说明**：
  - 提供了「具身综述→学习路线→仿真学习→开源实物→人物图谱→公司图谱」的路线化组织思路
  - 学习路线（RL / IL / 3D 视觉 / VLA / Sim2Real 等 10 条 4-8 周路线）的规划方法
  - 仿真学习章节（Isaac Lab、MuJoCo、PyBullet、Genesis、Gazebo）的组织结构
  - 人物与公司图谱的分类方式
- **使用方式**：本手册参考其路线化组织方法，在 01-09 章节的编排中借鉴了其"路线 + 清单 + 实作任务"的理念

### 3. Xbotics-Embodied-AI-Job（Xbotics 具身智能社区内推清单）

- **作者**：Xbotics 具身智能社区（创始人：Xbotics-木木，微信：mmls20240701）
- **GitHub**：https://github.com/Xbotics-Embodied-AI-club/Xbotics-Embodied-AI-Job
- **内推邮箱**：xbot_hc@163.com
- **许可协议**：该仓库未包含 LICENSE 文件，未明确声明许可协议。本手册仅引用其公开的岗位信息进行行业分析，未直接复制其原始内容。
- **关联项目**：Embodied-AI-Guide 中引用了 [StarCycle/Awesome-Embodied-AI-Job](https://github.com/StarCycle/Awesome-Embodied-AI-Job)（Lumina Robotics Talent Call），两者均为具身智能岗位信息合集，本手册使用的本地文件版本来自 Xbotics 社区。
- **贡献说明**：
  - 提供了 100+ 份具身智能岗位 JD（Job Description）的行业参考
  - 本手册 09-行业与职业 目录基于此项目数据进行行业趋势分析和整理

### 4. BotRunner64（遥操作项目体系）

- **GitHub**：https://github.com/BotRunner64
- **子项目**：
  | 子项目 | GitHub 链接 | 说明 |
  |--------|------------|------|
  | teleopit | https://github.com/BotRunner64/teleopit | VR/动捕遥操作核心模块 |
  | somehand | https://github.com/BotRunner64/somehand | 灵巧手设计与控制 |
  | pico-bridge | https://github.com/BotRunner64/pico-bridge | Pico VR 设备通信桥接 |
  | OpenNeck | https://github.com/BotRunner64/openneck | 机器人颈部控制 |
- **贡献说明**：本手册 06.4-BotRunner64 遥操作项目实战 和 04.4-Sim2Real技术 中的实践内容基于该项目

---

## 二、Awesome 论文资源仓库

以下开源论文索引仓库为本手册的论文分析和分类提供了重要参考：

| 仓库名称 | GitHub 链接 | 内容覆盖 |
|---------|------------|---------|
| Awesome-LLM-Robotics | https://github.com/GT-RIPL/Awesome-LLM-Robotics | LLM + 机器人论文（Reasoning/Planning/Manipulation/Navigation） |
| Awesome-Embodied-Robotics-and-Agent | （Embodied-AI-Guide 内嵌） | 具身机器人与 Agent 论文 |
| Awesome-RL-VLA | （Embodied-AI-Guide 内嵌） | 强化学习 + VLA 论文 |
| Awesome-Affordance-Learning | （Embodied-AI-Guide 内嵌） | 可供性学习论文 |
| Awesome-Video-Robotic-Papers | （Embodied-AI-Guide 内嵌） | 视频机器人论文 |
| Embodied-AI-Paper-TopConf | （Embodied-AI-Guide 内嵌） | 顶会具身 AI 论文 |
| Paper-List | （Embodied-AI-Guide 内嵌） | 21 主题分类论文列表 |
| RoboScholar | （Embodied-AI-Guide 内嵌） | 14 主题机器人学者论文集 |
| awesome-embodied-vla-va-vln | （Embodied-AI-Guide 内嵌） | VLA/VA/VLN 论文 |
| awesome-humanoid-robot-learning | （Embodied-AI-Guide 内嵌） | 人形机器人学习论文 |

---

## 二点五、Embodied-AI-Guide 捆绑补充资源

以下资源作为 Embodied-AI-Guide 项目的补充材料随仓库分发，本手册第 15 章对其进行了索引分析。各资源版权归原作者所有，遵循各自原始许可协议：

| 资源名称 | 说明 | 本手册引用章节 |
|---------|------|---------------|
| Book-Mathematical-Foundation-of-Reinforcement-Learning | 强化学习数学基础教材（Shiyu Zhao） | 15.4-Embodied-AI-Guide 补充资源分析 |
| dive-into-llms | LLM 实践教程（11 章，含 Notebook） | 15.4-Embodied-AI-Guide 补充资源分析 |
| train_custom_LLM | LLM 微调教程（Baichuan LoRA） | 15.4-Embodied-AI-Guide 补充资源分析 |
| LangChain for LLM Application Development | LangChain 应用开发课程 | 15.4-Embodied-AI-Guide 补充资源分析 |
| TOP28 多模态大模型代码合集 | PandaGPT、LLaVA、MiniGPT-4、BLIP-2 等 28 个模型源码 | 15.4-Embodied-AI-Guide 补充资源分析 |
| CVPR 2024 论文代码合集 | PaSCo、Marigold、mip-splatting 等 | 15.4-Embodied-AI-Guide 补充资源分析 |

> **说明**：以上资源均为 Embodied-AI-Guide 项目推荐的补充学习材料，本手册仅对其进行了目录级索引和简要分析，未直接复制其原始内容。

---

## 三、开源仿真平台与工具

| 项目 | GitHub 链接 | 在本手册中的引用章节 |
|------|------------|---------------------|
| Genesis | https://github.com/Genesis-Embodied-AI/Genesis | 05.4-Genesis |
| RoboTwin 2.0 | https://github.com/TianxingChen/RoboTwin | 08-项目实战 |
| LeRobot | https://github.com/huggingface/lerobot | 07.1-LeRobot 框架详解 |
| MuJoCo | https://github.com/google-deepmind/mujoco | 05.2-MuJoCo |
| Isaac Lab | https://github.com/isaac-sim/IsaacLab | 05.1-Isaac-Sim 与 Isaac-Lab |
| PyBullet | https://github.com/bulletphysics/bullet3 | 05.3-PyBullet |

---

## 四、学术论文引用

本手册中分析和引用的论文版权归原作者所有。以下为主要论文分类（完整清单见 `10-论文与资源/10.1-必读论文清单.md`）：

### 4.1 VLA 核心论文

| 论文 | 来源 | 本手册引用章节 |
|------|------|---------------|
| BayesVLA: Seeing to Act Prompting to Specify a Bayesian Factorization | arXiv 2512.11218 | 13.1-VLA 四篇核心论文精读 |
| WoVR: World Models as Reliable Simulators for Post-training | arXiv | 13.1-VLA 四篇核心论文精读 |
| Sim-Real: Beyond Imitation - Reinforcement Learning B... | arXiv | 13.1-VLA 四篇核心论文精读 |
| OpenVLA | CoRL 2024 | 04.1-VLA 模型详解 |
| RT-1 / RT-2 | Google DeepMind | 04.1-VLA 模型详解 |

### 4.2 顶会论文（CVPR / AAAI / ICLR / NeurIPS 2023-2025）

本手册分析了 486+ 篇顶会论文，精选 103 篇与具身智能直接相关的论文，详见：
- `16.1-CVPR-AAAI-ICLR-NeurIPS 论文精选与具身智能关联分析.md`
- `16.2-LLM-Agent 与 RLHF 论文精析.md`

### 4.3 LLM Agent 与 RLHF 论文

| 论文 | 来源 | 本手册引用章节 |
|------|------|---------------|
| Voyager: An Open-Ended Embodied Agent with LLMs | NeurIPS 2023 Workshop | 16.2-LLM-Agent 与 RLHF 论文精析 |
| LEO: An Embodied Generalist Agent in 3D World | arXiv 2311.12871 | 16.2 |
| InstructGPT: Training Language Models to Follow Instructions | OpenAI | 16.2 |
| Constitutional AI: Harmlessness from AI Feedback | Anthropic | 16.2 |

---

## 五、行业报告引用

本手册 14-行业研究与产业报告 目录引用了以下行业研究报告：

| 报告名称 | 发布机构 | 发布时间 |
|---------|---------|---------|
| 人形机器人行业专题报告 6：人形本体&灵巧手的电机进化"势" | 国海证券 | 2026.01 |
| 2025 年中国人形机器人六维力传感器市场调研报告 | MIR 睿工业 | 2025.07 |
| 2025 年人形机器人行业白皮书 | 幸福招商 | 2025 |
| 2024 具身智能科技前沿热点 | 中关村智友研究院 | 2025.01 |
| 人形机器人系列专题：感知系统 | 平安证券 | 2025.03 |

---

## 六、个人贡献说明

### 原创内容

以下内容为本手册的原创分析和整理（非直接引用）：

- `11-本地项目与技术讨论` 目录下的全部会议记录分析和技术讨论精华
- `12-主动视觉专项` 目录下的论文综述和学习计划
- `15-ML-DL 基础与大模型资源` 目录下的学习路线和资源汇总
- `16-顶会论文分类精选` 目录下的论文分类和关联分析
- 所有目录中标注为"分析"、"总结"、"精华提取"的内容

### 衍生内容

以下内容基于原始项目进行了深度扩展和重新组织：

- 手册整体目录结构：基于 Embodied-AI-Guide 框架，新增了 11-16 共 6 个目录
- 基础知识章节（01-10）：参考原项目结构，内容进行了大幅扩展和本地化
- 论文分析：基于原项目提供的论文索引，进行了逐篇深度阅读和关联分析

---

## 七、版权与使用声明

1. **非商业使用**：本手册遵循 Embodied-AI-Guide 的非商业使用许可协议，并继承 Xbotics-Embodied-Guide 的 CC BY-NC-SA 4.0 许可条款，仅供非商业学习交流使用
2. **相同方式共享（ShareAlike）**：基于 CC BY-NC-SA 4.0 条款，对本手册的修改和再分发必须采用相同的许可协议
3. **论文版权**：手册中引用的所有论文版权归原作者所有，引用仅用于学术讨论和学习
4. **代码版权**：引用的开源项目代码遵循各自的开源协议
5. **岗位信息**：Xbotics-Embodied-AI-Job 仓库未包含 LICENSE 文件，本手册仅引用其公开信息进行行业趋势分析，未直接复制原始内容
6. **商业授权**：如需商业使用，需同时联系以下原作者获取授权：
   - Embodied-AI-Guide：chentianxing2002@gmail.com
   - Xbotics 社区：xbot_hc@163.com

---

> 最后更新：2026-07-31
