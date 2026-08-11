<h1 align="center">你好，我是楠 👋</h1>

<p align="center">
  <strong>@nanbloom001</strong><br />
  <a href="mailto:nanbloom001@gmail.com">nanbloom001@gmail.com</a>
</p>

<p align="center">
  河海大学 · 智能科学与技术
</p>

<p align="center">
  <img
    src="https://readme-typing-svg.demolab.com?font=Noto+Sans+SC&pause=1400&color=2F81F7&center=true&vCenter=true&width=600&lines=%E8%AE%A9%E7%AE%97%E6%B3%95%E4%BB%8E%E4%BB%BF%E7%9C%9F%E8%B5%B0%E5%90%91%E7%9C%9F%E5%AE%9E%E6%9C%BA%E5%99%A8%E4%BA%BA;%E5%85%B3%E6%B3%A8%E6%9C%BA%E5%99%A8%E4%BA%BA%E5%AD%A6%E4%B9%A0%E3%80%81%E9%AA%8C%E8%AF%81%E4%B8%8E%E9%83%A8%E7%BD%B2%E7%9A%84%E5%AE%8C%E6%95%B4%E9%97%AD%E7%8E%AF;Learning%20%C2%B7%20Simulation%20%C2%B7%20Deployment"
    alt="机器人学习、仿真与部署"
  />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Robot_Learning-00599C?style=flat-square" alt="Robot Learning" />
  <img src="https://img.shields.io/badge/Reinforcement_Learning-2E7D32?style=flat-square" alt="Reinforcement Learning" />
  <img src="https://img.shields.io/badge/Sim2Real-B35C00?style=flat-square" alt="Sim2Real" />
  <img src="https://img.shields.io/badge/Legged_Robotics-6F42C1?style=flat-square" alt="Legged Robotics" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 2" />
  <img src="https://img.shields.io/badge/ROS_1-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS 1" />
  <img src="https://img.shields.io/badge/Isaac_Lab-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Isaac Lab" />
  <img src="https://img.shields.io/badge/MuJoCo-1F6FEB?style=flat-square" alt="MuJoCo" />
  <img src="https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Jetson" />
</p>

---

我专注于机器人学习、强化学习与 Sim2Real，持续探索学习型方法在真实机器人系统中的落地。在我看来，算法若只停留在仿真中，便缺少了与物理世界对话的关键一环；同样，再出色的硬件，也需要算法赋予它感知、决策与行动的灵魂。我始终保持着极客式的探索精神，在算法与硬件之间不断迭代与验证，追求两者的真正融合，直至想法在真实机器人上跑起来。

## 代表项目

<table width="100%">
  <tr>
    <td valign="top" width="68%">
      <strong>01 · <a href="https://github.com/nanbloom001/wheeled_leg_RL">12-DOF 四足机器人强化学习与 Sim2Real</a> 🔗</strong>
      <p>基于自组装 12 自由度四足机器人，完成从仿真训练、Sim2Sim 验证到真机部署的完整 Sim2Real 闭环。</p>
      <p><strong>主要工作：</strong></p>
      <ul>
        <li>完成机器人本体设计与组装，并构建数字资产接入 Isaac Lab 强化学习框架</li>
        <li>开展运动策略训练与 MuJoCo Sim2Sim 验证</li>
        <li>在 Jetson 边缘端完成策略部署，并与 STM32 下位机联调</li>
      </ul>
      <p><code>Isaac Lab</code> <code>MuJoCo</code> <code>Sim2Real</code> <code>Jetson</code></p>
    </td>
    <td valign="top" width="32%" align="center">
      <img src="https://raw.githubusercontent.com/nanbloom001/nanbloom001/main/assets/quadruped-sim2real.jpg" width="100%" alt="自组装 12 自由度四足机器人真机与控制系统联调" />
      <br />
      <sub>12-DOF 实机</sub>
    </td>
  </tr>
  <tr>
    <td valign="top" colspan="2">
      <strong>02 · <a href="https://github.com/nanbloom001/kaiwuFinal">强化学习导航</a> 🔗</strong>
      <p><strong>项目定位：</strong>使用强化学习完成四足机器人的目标跟随、复杂地形导航与unitreeGO2实机部署验证。</p>
      <p><strong>核心贡献：</strong>完成训练环境搭建、奖励机制设计和训练流程优化，并针对导航稳定性、目标跟随效果与部署表现进行测试验证。</p>
      <p><code>强化学习</code> <code>自主导航</code> <code>Sim2Real</code></p>
    </td>
  </tr>
  <tr>
    <td valign="top" colspan="2">
      <strong>03 · <a href="https://github.com/nanbloom001/2025AiCOMP_ZHSQ">社区智能巡检</a> 🔗</strong>
      <p><strong>项目定位：</strong>协同机器人导航、视觉检测与巡检决策，完成社区场景中的多模态任务。</p>
      <p><strong>核心贡献：</strong>搭建事件驱动状态机，级联 YOLO 与 OCR 检测，通过ROS1将视觉模块与运动模块结合。</p>
      <p><code>ROS 1</code> <code>YOLO</code> <code>OCR</code> <code>边缘 AI</code></p>
    </td>
  </tr>
  <tr>
    <td valign="top" colspan="2">
      <strong>04 · <a href="https://github.com/nanbloom001/unitree_cnsoft_demo">四足机器人巡航系统</a> 🔗</strong>
      <p><strong>项目定位：</strong>基于宇树 GO2 EDU 的自主巡航系统开发，攻克长流程巡航下的定位漂移难题。</p>
      <p><strong>核心贡献：</strong>基于 ROS 2 设计分层状态机编排多阶段任务，融合 SLAM 与高频里程计双源定位，以关键路径点校准抑制累计漂移。</p>
      <p><code>ROS 2</code> <code>SLAM</code> <code>状态机</code> <code>宇树 GO2</code></p>
    </td>
  </tr>
</table>

> **项目成果**
>
> - **全国一等奖**｜中国软件杯 · 四足机器人巡检系统
> - **全国一等奖**｜全球校园人工智能算法精英大赛 · 社区智能巡检机器人
> - **区域赛一等奖**｜服务外包腾讯开悟赛道 · 四足机器狗强化学习

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
