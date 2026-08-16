<h1 align="center">你好，我是楠 👋</h1>

<p align="center">
  <a href="mailto:nanbloom001@gmail.com">nanbloom001@gmail.com</a>
  · 河海大学 · 智能科学与技术
</p>

<div align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Noto+Sans+SC&pause=1400&color=2F81F7&center=true&vCenter=true&width=600&lines=%E8%AE%A9%E7%AE%97%E6%B3%95%E4%BB%8E%E4%BB%BF%E7%9C%9F%E8%B5%B0%E5%90%91%E7%9C%9F%E5%AE%9E%E6%9C%BA%E5%99%A8%E4%BA%BA;%E5%85%B3%E6%B3%A8%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%AD%A6%E4%B9%A0%E3%80%81%E9%AA%8C%E8%AF%81%E4%B8%8E%E9%83%A8%E7%BD%B2%E7%9A%84%E5%AE%8C%E6%95%B4%E9%97%AD%E7%8E%AF;Learning%20%C2%B7%20Simulation%20%C2%B7%20Deployment"
    alt="机器人学习、仿真与部署"
  />
  <br />
  <img src="https://img.shields.io/badge/Robot_Learning-00599C?style=flat-square" alt="Robot Learning" />
  <img src="https://img.shields.io/badge/Reinforcement_Learning-2E7D32?style=flat-square" alt="Reinforcement Learning" />
  <img src="https://img.shields.io/badge/Sim2Real-B35C00?style=flat-square" alt="Sim2Real" />
  <img src="https://img.shields.io/badge/Legged_Robotics-6F42C1?style=flat-square" alt="Legged Robotics" />
  <br />
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/ROS_1-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 1" />
  <img src="https://img.shields.io/badge/Isaac_Lab-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Isaac Lab" />
  <img src="https://img.shields.io/badge/MuJoCo-1F6FEB?style=flat-square" alt="MuJoCo" />
  <img src="https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Jetson" />
</div>

---

我专注于机器人学习、强化学习与 Sim2Real，持续探索学习型方法在真实机器人系统中的落地。在我看来，<strong>算法若只停留在仿真中，便缺少了与物理世界对话的关键一环</strong>；同样，再出色的硬件，也需要算法赋予它<strong>感知、决策与行动</strong>的灵魂。我始终保持着极客式的探索精神，在算法与硬件之间不断迭代与验证，追求两者的真正融合，直至想法在<strong>真实机器人</strong>上跑起来。

## 代表项目

<table width="100%">
  <tr>
    <td valign="top" width="68%">
      <strong>01 · <a href="https://github.com/nanbloom001/weixue-dog-RL">12-DOF 四足机器人强化学习与 Sim2Real</a> 🔗</strong>
      <p><strong>项目简介：</strong>基于自组装 12 自由度四足机器人，完成从仿真训练、Sim2Sim 验证到真机部署的完整 Sim2Real 闭环。</p>
      <p><strong>主要工作：</strong></p>
      <ul>
        <li>完成机器人本体设计与组装，并构建数字资产接入 Isaac Lab 强化学习框架</li>
        <li>开展运动策略训练与 MuJoCo Sim2Sim 验证</li>
        <li>在 Jetson 边缘端完成策略部署，并与 STM32 下位机联调</li>
      </ul>
      <p><code>Reinforcement Learning</code> <code>Sim2Sim</code> <code>Sim2Real</code> <code>Hardware Integration</code></p>
    </td>
    <td valign="top" width="32%" align="center">
      <img src="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/quadruped-sim2real.jpg" width="100%" alt="自组装 12 自由度四足机器人真机与控制系统联调" />
      <br />
      <sub>12-DOF 实机</sub>
    </td>
  </tr>
  <tr>
    <td valign="top" width="68%">
      <strong>02 · <a href="https://github.com/nanbloom001/kaiwu-final-sim2real">四足机器人自主导航与运控</a> 🔗</strong>
      <p><strong>项目简介：</strong>面向 Unitree Go2，完成复杂地形自主导航与 Sim2Real 真机部署验证。</p>
      <p><strong>主要工作：</strong></p>
      <ul>
        <li>教师—学生分阶段蒸馏 + DAgger，实现特权高程向深度视觉策略迁移</li>
        <li>解耦高层导航与低层步态控制，降低迭代耦合并加速训练</li>
        <li>通过时序记忆与域随机化提升真机感知与执行鲁棒性</li>
      </ul>
      <p><code>Policy Distillation</code> <code>Hierarchical Navigation</code> <code>Sim2Real</code></p>
    </td>
    <td valign="top" width="32%" align="center">
      <img src="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/go2-field-test.jpg" width="100%" alt="Unitree Go2 复杂地形自主导航场地实测" />
      <br />
      <sub>Go2 复杂地形场地实测</sub>
    </td>
  </tr>
  <tr>
    <td valign="top" width="68%">
      <strong>03 · <a href="https://github.com/nanbloom001/unitree_cnsoft_demo">四足机器人自主巡航系统</a> 🔗</strong>
      <p><strong>项目简介：</strong>基于 Unitree Go2 EDU，完成面向复杂路线的自主巡航系统开发与真机运行验证。</p>
      <p><strong>主要工作：</strong></p>
      <ul>
        <li>基于 ROS 2 构建分层状态机，编排导航、避障、登坡与识别任务</li>
        <li>融合 SLAM 位姿与高频里程计，通过关键路径点校准抑制累计漂移</li>
        <li>设计非阻塞任务调度与独立通信线程，保障导航与外部识别任务连续协同</li>
      </ul>
      <p><code>ROS 2</code> <code>Autonomous Navigation</code> <code>SLAM</code></p>
    </td>
    <td valign="top" width="32%" align="center">
      <img src="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/go2-autonomous-cruise.jpg" width="100%" alt="Unitree Go2 EDU 复杂路线自主巡航真机验证" />
      <br />
      <sub>Go2 自主巡航真机验证</sub>
    </td>
  </tr>
  <tr>
    <td valign="top" width="68%">
      <strong>04 · <a href="https://github.com/nanbloom001/2025AiCOMP_ZHSQ">社区智能巡检机器人</a> 🔗</strong>
      <p><strong>项目简介：</strong>面向社区巡检场景，完成自主导航、视觉识别与语音播报的一体化机器人系统开发。</p>
      <p><strong>主要工作：</strong></p>
      <ul>
        <li>设计事件驱动分层调度，实现导航与视觉任务异步协同</li>
        <li>采用 YOLO/OCR 级联推理，降低边缘侧视觉计算开销</li>
        <li>结合时序校验与规则后处理，提升识别与巡检流程稳定性</li>
      </ul>
      <p><code>ROS 1</code> <code>Computer Vision</code> <code>Edge AI</code></p>
    </td>
    <td valign="top" width="32%" align="center">
      <img src="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/community-inspection-robot.jpg" width="100%" alt="社区智能巡检机器人场景验证" />
      <br />
      <sub>社区智能巡检场景验证</sub>
    </td>
  </tr>
</table>

> **项目成果**
>
> - **全国一等奖**｜第 14 届中国软件杯 · 四足机器人自主巡航系统
> - **全国一等奖**｜第 7 届全球校园人工智能算法精英大赛 · 社区智能巡检机器人
> - **全国二等奖**｜第 6 届全球校园人工智能算法精英大赛 · 社区智能巡检机器人
> - **全国二等奖**｜第 17 届服务外包·人工智能专项赛道 · 四足机器人自主导航与运控
> - **赛区二等奖**｜第 8 届全国大学生嵌入式芯片与系统设计竞赛·芯片应用赛道

<details>
  <summary><strong>技术栈与工具</strong></summary>
  <br />

| 方向 | 技术与工具 |
| --- | --- |
| 编程语言 | C、C++、Python |
| 机器人系统 | ROS 1、ROS 2、SLAM、AMCL、导航控制 |
| 强化学习与仿真 | Isaac Lab、MuJoCo、Sim2Sim、Sim2Real |
| 视觉与部署 | YOLO、OCR、ONNX、Jetson Nano、Docker |

</details>

## 人生档案

<p align="center">
  <a href="https://nanbloom001.github.io/journey-archive/" title="打开交互式人生档案">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/life-archive-dark.png" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/life-archive-light.png" />
      <img width="100%" src="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/life-archive-light.png" alt="楠的 Life Archive 人生档案预览" />
    </picture>
  </a>
</p>

<p align="center"><sub>17 个时间节点 · 点击预览进入交互版本</sub></p>

项目代码和阶段性实验会持续整理在 GitHub。技术交流请联系我的邮箱：nanbloom001@gmail.com 。
