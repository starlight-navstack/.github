<p align="center">
  <img src="https://raw.githubusercontent.com/<YOUR_ORG>/.github/main/profile/banner.png" alt="starlight-navstack" width="100%" />
</p>

<h1 align="center">Starlight Navstack</h1>
<p align="center">
  <a href="https://github.com/<YOUR_ORG>"><img alt="Org" src="https://img.shields.io/badge/org-starlight--navstack-black"></a>
  <a href="https://github.com/<YOUR_ORG>?q=type%3Aall"><img alt="Repos" src="https://img.shields.io/badge/repos-_-informational"></a>
  <a href="https://github.com/<YOUR_ORG>"><img alt="License" src="https://img.shields.io/badge/license-Apache--2.0-lightgrey"></a>
  <a href="https://github.com/<YOUR_ORG>"><img alt="Chat" src="https://img.shields.io/badge/contact-issues%2Fdiscussions-blue"></a>
</p>

> 🚀 我们在做：**室外移动机器人/割草机器人**的导航栈与工具链（地图/分区、覆盖式路径规划、任务调度、可视化等）。

---

## 🧭 核心仓库（入口）
> 👉 组织右侧的 *Pinned* 会展示关键仓库；如未看到请切到 **View as: Member** 或查看下列入口。

- **coverage_global_planner** —— 覆盖式路径规划插件（BCD 分块 + 弓形轨迹等）
- **ros_navigation** —— 全局/局部规划、MoveBase 集成与适配
- **nav_area_layers** —— 区域/禁区/通道图层与编辑工具
- **robo_nav / mower_env** —— 机器人仿真与环境

> 维护者：@<core-maintainer> · 路线图：见各仓库 `Projects` / `Milestones`。

---

## 🗺️ 架构总览
- **MCU 层（STM32 / HAL / FreeRTOS）**：电机/传感器/灯效等底层驱动  
- **ROS1 导航层**：地图管理、分区、全局覆盖规划、局部避障  
- **任务与调度**：App/Bridge、JSON 计划、状态上报  
- **工具链**：地图格式（.rmap / .bound_map）、可视化、仿真环境

