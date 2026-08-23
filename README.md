<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=210&section=header&text=Hi%20I'm%20Yuchen%20Fan&fontSize=58&fontColor=ffffff&fontAlignY=38&desc=Robotics%20%26amp%3B%20AI%20Systems%20%C2%B7%20Embodied%20AI%20%C2%B7%203D%20Scene%20Intelligence&descSize=18&descAlignY=58&animation=twinkling)

English · [简体中文](https://github.com/Functionhx/Functionhx/blob/zh-CN/README.md)

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=21&duration=2800&pause=900&color=58A6FF&center=true&vCenter=true&width=760&lines=Building+robots+that+see%2C+localize%2C+understand%2C+and+act;Building+systems+that+perceive%2C+reason%2C+and+move;3DGS+%C2%B7+Embodied+AI+%C2%B7+Autonomous+Systems+%C2%B7+Open+Source)](https://git.io/typing-svg)

[![Followers](https://img.shields.io/github/followers/Functionhx?style=flat-square&logo=github&label=Followers&color=blue)](https://github.com/Functionhx?tab=followers)
[![Stars](https://img.shields.io/github/stars/Functionhx?affiliations=OWNER&style=flat-square&logo=github&label=Stars&color=yellow)](https://github.com/Functionhx?tab=repositories)
![Profile Views](https://komarev.com/ghpvc/?username=Functionhx&style=flat-square&label=Profile%20Views&color=blueviolet)

[![Website](https://img.shields.io/badge/Website-functionhx.github.io-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://functionhx.github.io/)
[![Email](https://img.shields.io/badge/Email-functionhx%40gmail.com-334155?style=flat-square&logo=gmail&logoColor=white)](mailto:functionhx@gmail.com)

</div>

---

## About Me

I am an undergraduate Robotics Engineering student at Beijing Institute of Technology, working at the intersection of robotics, autonomous driving, embodied AI, 3D scene representation, and AI systems engineering.

I enjoy turning research prototypes into real systems—from perception, state estimation, and navigation to inference deployment, communication architecture, testing, and fault recovery. Beyond getting a demo to run, I care about reliability, reproducibility, and graceful recovery when things go wrong.

- **Currently building** — 3DGS visual localization, instance navigation, and editable road-scene generation
- **Exploring** — ROS 2, Nav2, Habitat, VLA/VLN, world models, and AI agents
- **Engineering** — reliable real-robot systems, AI inference deployment, autonomous-driving infrastructure, and open-source software
- **Let's talk about** — embodied AI, 3D scene intelligence, robotics middleware, AI infrastructure, and research automation
- **Highlights** — 34 merged upstream PRs; Kaggle Bronze Medal (solo, top 9.6%)

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### ⭐ [Batch-LIO](https://github.com/Functionhx/Batch-LIO)

[![Stars](https://img.shields.io/github/stars/Functionhx/Batch-LIO?style=social)](https://github.com/Functionhx/Batch-LIO)

A batch-wise extension of Point-LIO featuring within-window motion undistortion, batched EKF updates, and parallel computation for high-bandwidth LiDAR-inertial odometry.

`C++` `LiDAR-Inertial Odometry` `EKF` `ROS`

</td>
<td width="50%" valign="top">

### ⭐ [BITFSD-Annotator](https://github.com/Functionhx/BITFSD-Annotator)

[![Stars](https://img.shields.io/github/stars/Functionhx/BITFSD-Annotator?style=social)](https://github.com/Functionhx/BITFSD-Annotator)

A 3D annotation and AI-assisted pre-labeling platform for Formula Student Driverless point clouds, with quality gates, OpenPCDet export, and a TensorRT inference backend.

`3D Vision` `TensorRT` `Vue` `FastAPI`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [CatchLab](https://github.com/Functionhx/catchlab)

[![Stars](https://img.shields.io/github/stars/Functionhx/catchlab?style=social)](https://github.com/Functionhx/catchlab)

An open simulation and verification framework for reusable-launch-vehicle terminal recovery — return flight, GNC, tower and arrestor-cable catch dynamics, and a SIL → HIL → scaled-experiment path built for explainable, reproducible sim-to-real.

`Rocket Recovery` `GNC` `Sim-to-Real` `C++20`

</td>
<td width="50%" valign="top">

### [ActuateX](https://github.com/Functionhx/actuatex)

[![Stars](https://img.shields.io/github/stars/Functionhx/actuatex?style=social)](https://github.com/Functionhx/actuatex)

A three-backend (Isaac Gym / Isaac Lab / MuJoCo) reinforcement-learning classroom for robust locomotion — train a policy in one simulator, then make it prove itself under unfamiliar dynamics, sustained pushes, stairs, and a different physics engine.

`Reinforcement Learning` `Sim2Sim` `Robot Control` `Isaac Lab`

</td>
</tr>
</table>

---

## Open-Source Contributions

Contributed **34 merged upstream pull requests**, grouped below by domain — focused on robotics middleware, embodied AI & RL, AI systems, agent tooling, and 3D perception, plus broader engineering work.

| Project | Pull Request | Focus |
|---|---|---|
| vLLM | [#48153](https://github.com/vllm-project/vllm/pull/48153) | Mistral Large 3 → AutoWeightsLoader |
| DeepSpeed | [#8154](https://github.com/deepspeedai/DeepSpeed/pull/8154) | Pipeline gradient-scaling fix |
| LangChain | [#38765](https://github.com/langchain-ai/langchain/pull/38765) | Anthropic thinking-stream replay fix |
| ARIS | [#360](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/pull/360) | Provenance-checked cross-model review |
| ros2_control | [#3454](https://github.com/ros-controls/ros2_control/pull/3454) | `update_rate` modulo-by-zero UB guard |
| CycloneDDS | [#2425](https://github.com/eclipse-cyclonedds/cyclonedds/pull/2425) | Signal-mask restore on `pthread_create` |
| OpenRLHF | [#1261](https://github.com/OpenRLHF/OpenRLHF/pull/1261) | Qwen3.5 ZeRO-3 frozen-weight detection |
| Hugging Face TRL | [#6439](https://github.com/huggingface/trl/pull/6439) | GRPO loss normalization |
| Comfy-Org / comfy-angle | [#6](https://github.com/Comfy-Org/comfy-angle/pull/6) | Headless Linux ANGLE wheels |
| NVIDIA OSMO | [#1211](https://github.com/NVIDIA/OSMO/pull/1211) | Default / IRSA S3 endpoint handling |
| OpenCV | [#29487](https://github.com/opencv/opencv/pull/29487) | Calibration & projection-matrix fixes |
| Gymnasium | [#1618](https://github.com/Farama-Foundation/Gymnasium/pull/1618) | `default_camera_config` render fix |

<details>
<summary><b>View all 34 merged upstream PRs (by domain)</b></summary>

<br>

**🤖 Robotics & autonomous-systems middleware**

- [ros-controls/ros2_control #3454](https://github.com/ros-controls/ros2_control/pull/3454) — guard `update_rate` against modulo-by-zero UB
- [eclipse-cyclonedds/cyclonedds #2425](https://github.com/eclipse-cyclonedds/cyclonedds/pull/2425) — restore signal mask when `pthread_create` fails
- [eclipse-iceoryx/iceoryx2 #1818](https://github.com/eclipse-iceoryx/iceoryx2/pull/1818) — add `node_id()` getter to C++ `NodeState`
- [ros2/ros2cli #1257](https://github.com/ros2/ros2cli/pull/1257) — `interface show --no-comments` stops leaking comments
- [ros2/rmw_cyclonedds #591](https://github.com/ros2/rmw_cyclonedds/pull/591) — downgrade noisy type-hash parse log to DEBUG
- [ros2/rmw_cyclonedds #590](https://github.com/ros2/rmw_cyclonedds/pull/590) — warn when `net.core.rmem_max` is below CycloneDDS minimum

**🧠 Embodied AI & reinforcement learning**

- [huggingface/trl #6439](https://github.com/huggingface/trl/pull/6439) — GRPO truncated-completion loss normalization
- [OpenRLHF/OpenRLHF #1261](https://github.com/OpenRLHF/OpenRLHF/pull/1261) — Qwen3.5 ZeRO-3 frozen-weight detection
- [Farama-Foundation/Gymnasium #1618](https://github.com/Farama-Foundation/Gymnasium/pull/1618) — `default_camera_config` render fix
- [huggingface/trl #6348](https://github.com/huggingface/trl/pull/6348) — DPO/KTO ref-log-prob `FileNotFoundError`

**⚡ AI systems & inference infrastructure**

- [vllm-project/vllm #48153](https://github.com/vllm-project/vllm/pull/48153) — migrate Mistral Large 3 to AutoWeightsLoader
- [deepspeedai/DeepSpeed #8154](https://github.com/deepspeedai/DeepSpeed/pull/8154) — repeated gradient scaling across pipeline stages
- [deepspeedai/DeepSpeed #8144](https://github.com/deepspeedai/DeepSpeed/pull/8144) — ZeRO-3 hooks for attribute-delegating modules
- [NVIDIA/cccl #9785](https://github.com/NVIDIA/cccl/pull/9785) — `cuda::std::byteswap` via `__builtin_bswapg`
- [Comfy-Org/comfy-angle #6](https://github.com/Comfy-Org/comfy-angle/pull/6) — build headless Linux ANGLE wheels without X11, Wayland, or GBM dependencies
- [NVIDIA/OSMO #1211](https://github.com/NVIDIA/OSMO/pull/1211) — use default or IRSA S3 endpoints when validating ambient credentials

**🧪 AI agents & research automation**

- [langchain-ai/langchain #38765](https://github.com/langchain-ai/langchain/pull/38765) — preserve empty Anthropic thinking blocks during streamed signature replay
- [wanshuiyin/Auto-claude-code-research-in-sleep #360](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep/pull/360) — default to provenance-checked native cross-model review

**👁️ 3D & computer-vision perception**

- [opencv/opencv #29487](https://github.com/opencv/opencv/pull/29487) — calibration docs, `decomposeProjectionMatrix`, `convertMaps` claims

**🛠️ Other engineering contributions**

- [nautechsystems/nautilus_trader #4443](https://github.com/nautechsystems/nautilus_trader/pull/4443) — consolidation data loss with single-file windows
- [rust-lang/cargo #17203](https://github.com/rust-lang/cargo/pull/17203) — race in `cargo_compile_with_invalid_code_in_deps`
- [duckdb/duckdb #23773](https://github.com/duckdb/duckdb/pull/23773) — VARCHAR→DECIMAL scientific-notation rounding
- [biomejs/biome #10915](https://github.com/biomejs/biome/pull/10915) — `noNegationInEqualityCheck` lint rule
- [BishopFox/sliver #2286](https://github.com/BishopFox/sliver/pull/2286) — prevent UA leak on proxy CONNECT
- [Pennyw0rth/NetExec #1311](https://github.com/Pennyw0rth/NetExec/pull/1311) — add `get_keys` fallback to prevent `export keys` crash
- [Velocidex/velociraptor #4921](https://github.com/Velocidex/velociraptor/pull/4921) — missing columns in stateful shell ack rows
- [vyperlang/vyper #5185](https://github.com/vyperlang/vyper/pull/5185) — reject bare `await` keyword
- [conda/conda #16391](https://github.com/conda/conda/pull/16391) — type hints and docstrings
- [ccxt/ccxt #29192](https://github.com/ccxt/ccxt/pull/29192) — Backpack ticker percentage normalization
- [rsheftel/pandas_market_calendars #469](https://github.com/rsheftel/pandas_market_calendars/pull/469) — CME Energy/Metals early closes 2026
- [fullpage-lab/PatchWing #3](https://github.com/fullpage-lab/PatchWing/pull/3) — portable refactor with bilingual docs
- [fullpage-lab/PatchWing #1](https://github.com/fullpage-lab/PatchWing/pull/1) — P0 audit fixes (DB paths, NameError crash)
- [Unclecheng-li/poc-lab #21](https://github.com/Unclecheng-li/poc-lab/pull/21) — BUILD.md for Januscape PoC kernel module
- [Unclecheng-li/poc-lab #20](https://github.com/Unclecheng-li/poc-lab/pull/20) — standard `.gitignore` patterns

</details>

---

## Technologies & Tools

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

## GitHub Stats

<div align="center">

<table width="100%">
<tr>
<td width="50%">
<img width="100%" src="./profile/stats.svg" />
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

### If you are exploring robotics, embodied AI, 3D scene representation, or reliable AI systems, let's connect

[![GitHub](https://img.shields.io/badge/-GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Functionhx)
[![Website](https://img.shields.io/badge/-Website-0A66C2?style=for-the-badge&logo=googlechrome&logoColor=white)](https://functionhx.github.io/)
[![Email](https://img.shields.io/badge/-Email-334155?style=for-the-badge&logo=gmail&logoColor=white)](mailto:functionhx@gmail.com)

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=90&section=footer)

</div>
