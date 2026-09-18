<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=210&section=header&text=Hi%20I'm%20Yuchen%20Fan&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Robotics%20%26amp%3B%20AI%20Systems%20%C2%B7%20Embodied%20AI%20%C2%B7%203D%20Scene%20Intelligence&descSize=18&descAlignY=58&animation=twinkling)

[English](https://github.com/Functionhx) · 简体中文

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=760&lines=%E4%BB%8E%E6%84%9F%E7%9F%A5%E3%80%81%E8%A7%84%E5%88%92%E5%88%B0%E5%AE%9E%E6%97%B6%E6%8E%A7%E5%88%B6;%E7%AE%97%E6%B3%95%E3%80%81%E8%BD%AF%E4%BB%B6%E4%B8%8E%E7%A1%AC%E4%BB%B6%E7%9A%84%E5%8D%8F%E5%90%8C%E8%AE%BE%E8%AE%A1;SLAM+%C2%B7+3DGS+%C2%B7+Embodied+AI+%C2%B7+Robotics+Infrastructure)](https://git.io/typing-svg)

<h2><a href="https://functionhx.github.io/">个人网站 ↗</a></h2>

[![Followers](https://img.shields.io/github/followers/Functionhx?style=flat-square&logo=github&label=Followers&color=blue)](https://github.com/Functionhx?tab=followers)
[![Stars](https://img.shields.io/github/stars/Functionhx?affiliations=OWNER&style=flat-square&logo=github&label=Stars&color=yellow)](https://github.com/Functionhx?tab=repositories)
![Profile Views](https://komarev.com/ghpvc/?username=Functionhx&style=flat-square&label=Profile%20Views&color=blueviolet)

[![Email](https://img.shields.io/badge/Email-functionhx%40gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:functionhx@gmail.com)

</div>

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

### ⭐ [RoboAccel](https://github.com/Functionhx/RoboAccel)

[![Stars](https://img.shields.io/github/stars/Functionhx/RoboAccel?style=social)](https://github.com/Functionhx/RoboAccel)

面向 FPGA 与 MCU 的端到端强化学习控制部署栈，在五种实现间验证定点计算逐位一致，实测 FPGA 纯推理速度达到 Cortex-M7 的 14.4 倍。

`Reinforcement Learning` `FPGA` `STM32` `Quantization`

</td>
</tr>
</table>

---

## 关于我

**北京理工大学**机器人工程本科生。

通过算法、软件与硬件的协同设计，把机器人研究原型做成可靠的实机系统，重视部署落地与结果可复现。

---

## 开源贡献

累计 **34 个已合并 PR**；下方精选 **15 个项目 · 18 个 PR**。

### AI 与系统工具

| 项目 · 已合并 PR | 贡献内容 |
|---|---|
| **vLLM** · [#48153](https://github.com/vllm-project/vllm/pull/48153) | Mistral Large 3 权重加载迁移 |
| **DeepSpeed** · [#8154](https://github.com/deepspeedai/DeepSpeed/pull/8154) · [#8144](https://github.com/deepspeedai/DeepSpeed/pull/8144) | 流水线梯度缩放与 ZeRO-3 hooks 修复 |
| **LangChain** · [#38765](https://github.com/langchain-ai/langchain/pull/38765) | Anthropic 思维流回放修复 |
| **Hugging Face TRL** · [#6439](https://github.com/huggingface/trl/pull/6439) · [#6348](https://github.com/huggingface/trl/pull/6348) | GRPO 损失归一化与 DPO/KTO 参考概率缓存修复 |
| **OpenRLHF** · [#1261](https://github.com/OpenRLHF/OpenRLHF/pull/1261) | Qwen3.5 的 ZeRO-3 权重冻结修复 |
| **NVIDIA CCCL** · [#9785](https://github.com/NVIDIA/cccl/pull/9785) | CUDA 字节交换的编译器内建支持 |
| **NVIDIA OSMO** · [#1211](https://github.com/NVIDIA/OSMO/pull/1211) | S3 验证端点处理修复 |
| **Rust Cargo** · [#17203](https://github.com/rust-lang/cargo/pull/17203) | 编译测试竞态修复 |

### 机器人与感知

| 项目 · 已合并 PR | 贡献内容 |
|---|---|
| **ros2_control** · [#3454](https://github.com/ros-controls/ros2_control/pull/3454) | 控制器更新频率的模零防护 |
| **CycloneDDS** · [#2425](https://github.com/eclipse-cyclonedds/cyclonedds/pull/2425) | 线程创建失败后的信号掩码恢复 |
| **iceoryx2** · [#1818](https://github.com/eclipse-iceoryx/iceoryx2/pull/1818) | C++ 节点 ID 访问接口 |
| **ROS 2 · ros2cli** · [#1257](https://github.com/ros2/ros2cli/pull/1257) | 接口定义的注释过滤 |
| **ROS 2 · rmw_cyclonedds** · [#591](https://github.com/ros2/rmw_cyclonedds/pull/591) · [#590](https://github.com/ros2/rmw_cyclonedds/pull/590) | 日志级别调整与接收缓冲区诊断 |
| **OpenCV** · [#29487](https://github.com/opencv/opencv/pull/29487) | 标定与投影相关文档修正 |
| **Gymnasium** · [#1618](https://github.com/Farama-Foundation/Gymnasium/pull/1618) | 渲染相机配置修复 |

<details>
<summary><b>查看全部 34 个已合并 PR · 29 个仓库</b></summary>

| 项目 | 已合并 PR 与贡献内容 |
|---|---|
| **[Biome](https://github.com/biomejs/biome)** | [#10915](https://github.com/biomejs/biome/pull/10915) — `noNegationInEqualityCheck` lint 规则 |
| **[Sliver](https://github.com/BishopFox/sliver)** | [#2286](https://github.com/BishopFox/sliver/pull/2286) — 防止代理 CONNECT 时的 UA 泄露 |
| **[CCXT](https://github.com/ccxt/ccxt)** | [#29192](https://github.com/ccxt/ccxt/pull/29192) — Backpack 行情百分比归一化 |
| **[Comfy-Org / comfy-angle](https://github.com/Comfy-Org/comfy-angle)** | [#6](https://github.com/Comfy-Org/comfy-angle/pull/6) — 构建无 X11、Wayland 或 GBM 依赖的无头 Linux ANGLE wheels |
| **[Conda](https://github.com/conda/conda)** | [#16391](https://github.com/conda/conda/pull/16391) — 类型注解与文档字符串 |
| **[DeepSpeed](https://github.com/deepspeedai/DeepSpeed)** | [#8154](https://github.com/deepspeedai/DeepSpeed/pull/8154) — 流水线各阶段重复梯度缩放<br>[#8144](https://github.com/deepspeedai/DeepSpeed/pull/8144) — 属性代理模块的 ZeRO-3 hooks |
| **[DuckDB](https://github.com/duckdb/duckdb)** | [#23773](https://github.com/duckdb/duckdb/pull/23773) — VARCHAR→DECIMAL 科学计数法舍入 |
| **[CycloneDDS](https://github.com/eclipse-cyclonedds/cyclonedds)** | [#2425](https://github.com/eclipse-cyclonedds/cyclonedds/pull/2425) — `pthread_create` 失败时恢复信号掩码 |
| **[iceoryx2](https://github.com/eclipse-iceoryx/iceoryx2)** | [#1818](https://github.com/eclipse-iceoryx/iceoryx2/pull/1818) — 为 C++ `NodeState` 增加 `node_id()` getter |
| **[Gymnasium](https://github.com/Farama-Foundation/Gymnasium)** | [#1618](https://github.com/Farama-Foundation/Gymnasium/pull/1618) — `default_camera_config` 渲染修复 |
| **[PatchWing](https://github.com/fullpage-lab/PatchWing)** | [#3](https://github.com/fullpage-lab/PatchWing/pull/3) — 可移植重构与双语文档<br>[#1](https://github.com/fullpage-lab/PatchWing/pull/1) — P0 审计修复(DB 路径、NameError 崩溃) |
| **[Hugging Face TRL](https://github.com/huggingface/trl)** | [#6439](https://github.com/huggingface/trl/pull/6439) — GRPO 截断补全的损失归一化<br>[#6348](https://github.com/huggingface/trl/pull/6348) — DPO/KTO ref-log-prob `FileNotFoundError` |
| **[LangChain](https://github.com/langchain-ai/langchain)** | [#38765](https://github.com/langchain-ai/langchain/pull/38765) — 在流式签名回放中保留 Anthropic 的空 `thinking` 字段 |
| **[NautilusTrader](https://github.com/nautechsystems/nautilus_trader)** | [#4443](https://github.com/nautechsystems/nautilus_trader/pull/4443) — 单文件周期窗口的合并数据丢失 |
| **[NVIDIA CCCL](https://github.com/NVIDIA/cccl)** | [#9785](https://github.com/NVIDIA/cccl/pull/9785) — 用 `__builtin_bswapg` 实现 `cuda::std::byteswap` |
| **[NVIDIA OSMO](https://github.com/NVIDIA/OSMO)** | [#1211](https://github.com/NVIDIA/OSMO/pull/1211) — 使用默认或 IRSA S3 端点验证环境凭据 |
| **[OpenCV](https://github.com/opencv/opencv)** | [#29487](https://github.com/opencv/opencv/pull/29487) — 标定文档、`decomposeProjectionMatrix`、`convertMaps` 表述 |
| **[OpenRLHF](https://github.com/OpenRLHF/OpenRLHF)** | [#1261](https://github.com/OpenRLHF/OpenRLHF/pull/1261) — Qwen3.5 ZeRO-3 冻结权重检测 |
| **[NetExec](https://github.com/Pennyw0rth/NetExec)** | [#1311](https://github.com/Pennyw0rth/NetExec/pull/1311) — 为 `export keys` 增加 `get_keys` 回退,避免崩溃 |
| **[ros2_control](https://github.com/ros-controls/ros2_control)** | [#3454](https://github.com/ros-controls/ros2_control/pull/3454) — 为 `update_rate` 增加模零 UB 防护 |
| **[ROS 2 / rmw_cyclonedds](https://github.com/ros2/rmw_cyclonedds)** | [#591](https://github.com/ros2/rmw_cyclonedds/pull/591) — 将嘈杂的 type-hash 解析日志降级到 DEBUG<br>[#590](https://github.com/ros2/rmw_cyclonedds/pull/590) — 当 `net.core.rmem_max` 低于 CycloneDDS 最低要求时发出警告 |
| **[ROS 2 / ros2cli](https://github.com/ros2/ros2cli)** | [#1257](https://github.com/ros2/ros2cli/pull/1257) — `interface show --no-comments` 不再泄露注释 |
| **[pandas_market_calendars](https://github.com/rsheftel/pandas_market_calendars)** | [#469](https://github.com/rsheftel/pandas_market_calendars/pull/469) — 2026 CME 能源/金属提前收盘 |
| **[Rust Cargo](https://github.com/rust-lang/cargo)** | [#17203](https://github.com/rust-lang/cargo/pull/17203) — `cargo_compile_with_invalid_code_in_deps` 竞态 |
| **[poc-lab](https://github.com/Unclecheng-li/poc-lab)** | [#21](https://github.com/Unclecheng-li/poc-lab/pull/21) — Januscape PoC 内核模块 BUILD.md<br>[#20](https://github.com/Unclecheng-li/poc-lab/pull/20) — 标准 `.gitignore` 模式 |
| **[Velociraptor](https://github.com/Velocidex/velociraptor)** | [#4921](https://github.com/Velocidex/velociraptor/pull/4921) — 有状态 shell ack 行缺失列 |
| **[vLLM](https://github.com/vllm-project/vllm)** | [#48153](https://github.com/vllm-project/vllm/pull/48153) — 将 Mistral Large 3 迁移到 AutoWeightsLoader |
| **[Vyper](https://github.com/vyperlang/vyper)** | [#5185](https://github.com/vyperlang/vyper/pull/5185) — 拒绝裸 `await` 关键字 |
| **[ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep)** | [#360](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/pull/360) — 默认启用带模型来源校验、fail-closed 的原生跨模型审查 |

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
