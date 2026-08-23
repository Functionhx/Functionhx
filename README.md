<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=210&section=header&text=Hi%20I'm%20Yuchen%20Fan&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Robotics%20%26amp%3B%20AI%20Systems%20%C2%B7%20Embodied%20AI%20%C2%B7%203D%20Scene%20Intelligence&descSize=18&descAlignY=58&animation=twinkling)

[English](https://github.com/Functionhx) · 简体中文

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=760&lines=%E8%AE%A9%E6%9C%BA%E5%99%A8%E4%BA%BA%E7%9C%8B%E8%A7%81%E3%80%81%E5%AE%9A%E4%BD%8D%E3%80%81%E7%90%86%E8%A7%A3%E5%B9%B6%E8%A1%8C%E5%8A%A8;Building+systems+that+perceive%2C+reason%2C+and+move;3DGS+%C2%B7+Embodied+AI+%C2%B7+Autonomous+Systems+%C2%B7+Open+Source)](https://git.io/typing-svg)

[![Followers](https://img.shields.io/github/followers/Functionhx?style=flat-square&logo=github&label=Followers&color=blue)](https://github.com/Functionhx?tab=followers)
[![Stars](https://img.shields.io/github/stars/Functionhx?affiliations=OWNER&style=flat-square&logo=github&label=Stars&color=yellow)](https://github.com/Functionhx?tab=repositories)
![Profile Views](https://komarev.com/ghpvc/?username=Functionhx&style=flat-square&label=Profile%20Views&color=blueviolet)

[![Website](https://img.shields.io/badge/Website-functionhx.github.io-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://functionhx.github.io/)
[![Email](https://img.shields.io/badge/Email-functionhx%40gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:functionhx@gmail.com)

</div>

---

## 关于我

我是北京理工大学机器人工程本科生，关注机器人、自动驾驶、具身智能、三维场景表示与 AI 系统工程。

我喜欢把研究原型推进到真实系统：从感知、状态估计与导航，到推理部署、通信架构、测试验证和故障恢复。相比“只让 Demo 跑起来”，我更关心它能否稳定运行、能否被复现，以及遇到异常时如何恢复。

- **正在做** — 3DGS 视觉定位、实例导航与可编辑道路场景生成
- **正在玩** — ROS 2、Nav2、Habitat、VLA/VLN、世界模型与 AI Agent
- **正在沉淀** — 机器人实机系统、AI 推理部署、自动驾驶工程与开源贡献
- **想聊聊** — 具身智能、三维场景智能、机器人中间件、AI Infra 与科研自动化
- **一些结果** — 34 个上游已合入 PR；Kaggle Bronze Medal（Solo，Top 9.6%）

---

## 代表项目

<table>
<tr>
<td width="50%" valign="top">

### ⭐ [Batch-LIO](https://github.com/Functionhx/Batch-LIO)

[![Stars](https://img.shields.io/github/stars/Functionhx/Batch-LIO?style=social)](https://github.com/Functionhx/Batch-LIO)

Point-LIO 的 batch-wise 扩展，引入窗口内运动去畸变、批量 EKF 更新与并行计算，面向高带宽 LiDAR-Inertial Odometry。

`C++` `LiDAR-Inertial Odometry` `EKF` `ROS`

</td>
<td width="50%" valign="top">

### ⭐ [BITFSD-Annotator](https://github.com/Functionhx/BITFSD-Annotator)

[![Stars](https://img.shields.io/github/stars/Functionhx/BITFSD-Annotator?style=social)](https://github.com/Functionhx/BITFSD-Annotator)

面向无人方程式点云数据的三维标注与 AI 预标注平台，支持质量门控、OpenPCDet 格式及 TensorRT 推理后端。

`3D Vision` `TensorRT` `Vue` `FastAPI`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [CatchLab](https://github.com/Functionhx/catchlab)

[![Stars](https://img.shields.io/github/stars/Functionhx/catchlab?style=social)](https://github.com/Functionhx/catchlab)

面向可重复使用运载火箭末端回收的开源仿真与验证框架 —— 覆盖返回飞行、制导导航与控制、塔架与柔性阻拦索捕获动力学，以及 SIL → HIL → 缩比实物的可解释、可复现 sim-to-real 研究平台。

`Rocket Recovery` `GNC` `Sim-to-Real` `C++20`

</td>
<td width="50%" valign="top">

### [ActuateX](https://github.com/Functionhx/actuatex)

[![Stars](https://img.shields.io/github/stars/Functionhx/actuatex?style=social)](https://github.com/Functionhx/actuatex)

三后端（Isaac Gym / Isaac Lab / MuJoCo）强化学习控制课堂：在一个仿真器里训练策略，再让它在陌生动力学、持续扰动、台阶与另一套物理引擎下自证鲁棒性。

`Reinforcement Learning` `Sim2Sim` `Robot Control` `Isaac Lab`

</td>
</tr>
</table>

---

## 开源贡献

累计贡献 **34 个上游已合入 Pull Request**，下方按领域分组 —— 聚焦机器人中间件、具身智能 / 强化学习、AI 系统、Agent 工具与三维感知，以及更广的工程贡献。

| Project | Pull Request | Focus |
|---|---|---|
| Comfy-Org / comfy-angle | [#6](https://github.com/Comfy-Org/comfy-angle/pull/6) | 无窗口系统依赖的 Linux ANGLE wheel |
| NVIDIA OSMO | [#1211](https://github.com/NVIDIA/OSMO/pull/1211) | 默认 / IRSA S3 端点处理 |
| LangChain | [#38765](https://github.com/langchain-ai/langchain/pull/38765) | Anthropic 思维流回放修复 |
| vLLM | [#48153](https://github.com/vllm-project/vllm/pull/48153) | MistralLarge3 → AutoWeightsLoader |
| DeepSpeed | [#8154](https://github.com/deepspeedai/DeepSpeed/pull/8154) | 流水线梯度缩放修复 |
| ARIS | [#360](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/pull/360) | 带来源校验的跨模型审查 |
| ros2_control | [#3454](https://github.com/ros-controls/ros2_control/pull/3454) | `update_rate` 模零 UB 防护 |
| CycloneDDS | [#2425](https://github.com/eclipse-cyclonedds/cyclonedds/pull/2425) | `pthread_create` 失败时恢复信号掩码 |
| OpenRLHF | [#1261](https://github.com/OpenRLHF/OpenRLHF/pull/1261) | Qwen3.5 ZeRO-3 冻结权重检测 |
| Hugging Face TRL | [#6439](https://github.com/huggingface/trl/pull/6439) | GRPO 损失归一化 |
| OpenCV | [#29487](https://github.com/opencv/opencv/pull/29487) | 标定与投影矩阵修复 |
| Gymnasium | [#1618](https://github.com/Farama-Foundation/Gymnasium/pull/1618) | `default_camera_config` 渲染修复 |

<details>
<summary><b>查看全部 34 个上游已合入 PR（按领域）</b></summary>

<br>

**🤖 机器人与自主系统中间件**

- [ros-controls/ros2_control #3454](https://github.com/ros-controls/ros2_control/pull/3454) — 为 `update_rate` 增加模零 UB 防护
- [eclipse-cyclonedds/cyclonedds #2425](https://github.com/eclipse-cyclonedds/cyclonedds/pull/2425) — `pthread_create` 失败时恢复信号掩码
- [eclipse-iceoryx/iceoryx2 #1818](https://github.com/eclipse-iceoryx/iceoryx2/pull/1818) — 为 C++ `NodeState` 增加 `node_id()` getter
- [ros2/ros2cli #1257](https://github.com/ros2/ros2cli/pull/1257) — `interface show --no-comments` 不再泄露注释
- [ros2/rmw_cyclonedds #591](https://github.com/ros2/rmw_cyclonedds/pull/591) — 将嘈杂的 type-hash 解析日志降级到 DEBUG
- [ros2/rmw_cyclonedds #590](https://github.com/ros2/rmw_cyclonedds/pull/590) — 当 `net.core.rmem_max` 低于 CycloneDDS 最低要求时发出警告

**🧠 具身智能与强化学习**

- [huggingface/trl #6439](https://github.com/huggingface/trl/pull/6439) — GRPO 截断补全的损失归一化
- [OpenRLHF/OpenRLHF #1261](https://github.com/OpenRLHF/OpenRLHF/pull/1261) — Qwen3.5 ZeRO-3 冻结权重检测
- [Farama-Foundation/Gymnasium #1618](https://github.com/Farama-Foundation/Gymnasium/pull/1618) — `default_camera_config` 渲染修复
- [huggingface/trl #6348](https://github.com/huggingface/trl/pull/6348) — DPO/KTO ref-log-prob `FileNotFoundError`

**⚡ AI 系统与推理基础设施**

- [Comfy-Org/comfy-angle #6](https://github.com/Comfy-Org/comfy-angle/pull/6) — 构建无 X11、Wayland 或 GBM 依赖的无头 Linux ANGLE wheels
- [NVIDIA/OSMO #1211](https://github.com/NVIDIA/OSMO/pull/1211) — 使用默认或 IRSA S3 端点验证环境凭据
- [vllm-project/vllm #48153](https://github.com/vllm-project/vllm/pull/48153) — 将 Mistral Large 3 迁移到 AutoWeightsLoader
- [deepspeedai/DeepSpeed #8154](https://github.com/deepspeedai/DeepSpeed/pull/8154) — 流水线各阶段重复梯度缩放
- [deepspeedai/DeepSpeed #8144](https://github.com/deepspeedai/DeepSpeed/pull/8144) — 属性代理模块的 ZeRO-3 hooks
- [NVIDIA/cccl #9785](https://github.com/NVIDIA/cccl/pull/9785) — 用 `__builtin_bswapg` 实现 `cuda::std::byteswap`

**🧪 AI Agent 与科研自动化**

- [langchain-ai/langchain #38765](https://github.com/langchain-ai/langchain/pull/38765) — 在流式签名回放中保留 Anthropic 的空 `thinking` 字段
- [wanshuiyin/Auto-claude-code-research-in-sleep #360](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/pull/360) — 默认启用带模型来源校验、fail-closed 的原生跨模型审查

**👁️ 三维与计算机视觉感知**

- [opencv/opencv #29487](https://github.com/opencv/opencv/pull/29487) — 标定文档、`decomposeProjectionMatrix`、`convertMaps` 表述

**🛠️ 其他工程贡献**

- [nautechsystems/nautilus_trader #4443](https://github.com/nautechsystems/nautilus_trader/pull/4443) — 单文件周期窗口的合并数据丢失
- [rust-lang/cargo #17203](https://github.com/rust-lang/cargo/pull/17203) — `cargo_compile_with_invalid_code_in_deps` 竞态
- [duckdb/duckdb #23773](https://github.com/duckdb/duckdb/pull/23773) — VARCHAR→DECIMAL 科学计数法舍入
- [biomejs/biome #10915](https://github.com/biomejs/biome/pull/10915) — `noNegationInEqualityCheck` lint 规则
- [BishopFox/sliver #2286](https://github.com/BishopFox/sliver/pull/2286) — 防止代理 CONNECT 时的 UA 泄露
- [Pennyw0rth/NetExec #1311](https://github.com/Pennyw0rth/NetExec/pull/1311) — 为 `export keys` 增加 `get_keys` 回退,避免崩溃
- [Velocidex/velociraptor #4921](https://github.com/Velocidex/velociraptor/pull/4921) — 有状态 shell ack 行缺失列
- [vyperlang/vyper #5185](https://github.com/vyperlang/vyper/pull/5185) — 拒绝裸 `await` 关键字
- [conda/conda #16391](https://github.com/conda/conda/pull/16391) — 类型注解与文档字符串
- [ccxt/ccxt #29192](https://github.com/ccxt/ccxt/pull/29192) — Backpack 行情百分比归一化
- [rsheftel/pandas_market_calendars #469](https://github.com/rsheftel/pandas_market_calendars/pull/469) — 2026 CME 能源/金属提前收盘
- [fullpage-lab/PatchWing #3](https://github.com/fullpage-lab/PatchWing/pull/3) — 可移植重构与双语文档
- [fullpage-lab/PatchWing #1](https://github.com/fullpage-lab/PatchWing/pull/1) — P0 审计修复(DB 路径、NameError 崩溃)
- [Unclecheng-li/poc-lab #21](https://github.com/Unclecheng-li/poc-lab/pull/21) — Januscape PoC 内核模块 BUILD.md
- [Unclecheng-li/poc-lab #20](https://github.com/Unclecheng-li/poc-lab/pull/20) — 标准 `.gitignore` 模式

</details>

---

## 技术与工具

<div align="center">

![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CMake](https://img.shields.io/badge/-CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

![ROS 2](https://img.shields.io/badge/-ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Nav2](https://img.shields.io/badge/-Nav2-1F6FEB?style=for-the-badge&logo=ros&logoColor=white)
![CycloneDDS](https://img.shields.io/badge/-CycloneDDS-0F766E?style=for-the-badge&logo=eclipseide&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![ONNX](https://img.shields.io/badge/-ONNX-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![TensorRT](https://img.shields.io/badge/-TensorRT-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![OpenCV](https://img.shields.io/badge/-OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

![Open3D](https://img.shields.io/badge/-Open3D-2563EB?style=for-the-badge&logo=threedotjs&logoColor=white)
![3DGS](https://img.shields.io/badge/-3D%20Gaussian%20Splatting-8B5CF6?style=for-the-badge&logo=blender&logoColor=white)
![Habitat](https://img.shields.io/badge/-Habitat-111827?style=for-the-badge&logo=meta&logoColor=white)
![MuJoCo](https://img.shields.io/badge/-MuJoCo-334155?style=for-the-badge&logo=googledeepmind&logoColor=white)

</div>

---

## GitHub 数据

<div align="center">

<table width="100%">
<tr>
<td width="50%">
<img width="100%" src="https://raw.githubusercontent.com/Functionhx/Functionhx/main/profile/stats.svg" />
</td>
<td width="50%">
<img width="100%" src="https://streak-stats.demolab.com?user=Functionhx&theme=transparent&hide_border=true&ring=58A6FF&fire=8B5CF6&currStreakLabel=0F766E&sideLabels=334155&dates=64748B&currStreakNum=8B5CF6&sideNums=58A6FF" />
</td>
</tr>
</table>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Functionhx&theme=github-compact&hide_border=true&area=true" />

</div>

<div align="center">

![Snake animation](https://raw.githubusercontent.com/Functionhx/Functionhx/output/github-contribution-grid-snake.svg)

</div>

---

<div align="center">

### 如果你也在探索机器人、具身智能、三维场景表示与可靠 AI 系统，欢迎交流

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Functionhx)
[![Website](https://img.shields.io/badge/-Website-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://functionhx.github.io/)
[![Email](https://img.shields.io/badge/-Email-334155?style=for-the-badge&logo=gmail&logoColor=white)](mailto:functionhx@gmail.com)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=90&section=footer)

</div>
