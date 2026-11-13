### 你好，我是金仁杰

**自动化专业（2023 级，GPA 4.01/5.0，专业排名 8/107）** ｜ 中国石油大学（北京）克拉玛依校区 → **天津大学 纳电子科学与芯片工程学院（仪器科学与技术，学硕）**

本科期间主要围绕**控制算法、数学建模、嵌入式硬件与软件开发**开展学习与实践。以下仓库整理了不同阶段完成的课程、竞赛及科研相关代码，均已附可复现实验或测试说明。

🌐 **个人主页（支持按方向筛选项目及浏览公开简历）**：[https://ffgxfvy.github.io/personal-site/](https://ffgxfvy.github.io/personal-site/)

---

#### 按方向索引

| 方向 | 相关仓库 | 主要工作与量化结果 |
|---|---|---|
| **具身智能 / 机器人** | [`lerobot-act-wiping-arm`](https://github.com/ffgxfvy/lerobot-act-wiping-arm) | 工业仪表擦拭机械臂 ACT 模仿学习 · 8 类工况 201 episodes · 多阶段微调后综合成功率 **76.8% → 91.2%**（中国机器人及人工智能大赛新疆三等奖） |
| **强化学习 / 时序建模** | [`offline-rl-industrial-control`](https://github.com/ffgxfvy/offline-rl-industrial-control) | 工业控制离线强化学习（CQL → GRU → TCN） · 100 随机种子平均得分 **6.224 → 10.862 → 30.442** · 66 项 pytest |
| **控制仿真与论文代码** | [`quadrotor-fosm-ipso`](https://github.com/ffgxfvy/quadrotor-fosm-ipso) · [`fuzzy-pid-ipso-temperature-control`](https://github.com/ffgxfvy/fuzzy-pid-ipso-temperature-control) | 两篇第一作者 EI 会议论文的 MATLAB/Simulink 仿真代码（四旋翼分数阶滑模控制、Levy-PSO 模糊 PID 温控） |
| **嵌入式系统与视觉** | [`eec-auto-aiming-car`](https://github.com/ffgxfvy/eec-auto-aiming-car) · [`k230-edge-vision-demo`](https://github.com/ffgxfvy/k230-edge-vision-demo) · [`embedded-lab-collection`](https://github.com/ffgxfvy/embedded-lab-collection) | 2025 电赛 E 题省二（TI MSPM0G3507 + K230，巡迹 `1.2 mm` / 瞄准 `0.8 cm` / 响应 `183 ms`）· 蓝桥杯单片机国三（省一）· 46 项 K230 模块单元测试 |
| **数学建模与数据分析** | [`math-modeling-portfolio`](https://github.com/ffgxfvy/math-modeling-portfolio) | 统计建模省一 ×2、国赛数模省二 ×2（NIPT 数据 Spearman/XGBoost/聚类、ARIMAX 波动模型、BP/LSTM 对比与抽样优化） |
| **软件工程与网络编程** | [`equipment-inspection-system`](https://github.com/ffgxfvy/equipment-inspection-system) · [`p2p-file-sync`](https://github.com/ffgxfvy/p2p-file-sync) | SpringBoot 3 + MyBatis-Plus + Vue 3 + Docker 设备巡检系统（46 项 JUnit + 19 项 API 实测）· 局域网 P2P 文件同步重构（SHA-256 + 断点续传 + 90 项 pytest） |

---

#### 主要研究与工程实践

- **EI 会议论文（第一作者，2 篇）**：
  1. *Fractional-Order Sliding Mode Trajectory Tracking Control of Quadrotor UAVs Based on Improved PSO*（四旋翼动力学建模、分数阶滑模控制与扰动仿真，代码见 [`quadrotor-fosm-ipso`](https://github.com/ffgxfvy/quadrotor-fosm-ipso)）
  2. *Research on Optimized Fuzzy PID Temperature Control Strategy Based on Improved PSO*（大滞后温控对象改进 PSO 优化与多指标仿真对比，代码见 [`fuzzy-pid-ipso-temperature-control`](https://github.com/ffgxfvy/fuzzy-pid-ipso-temperature-control)）
- **机械臂模仿学习实验**：围绕工业现场仪表清洁场景，基于双相机 SO-ARM 与 LeRobot ACT 收集 8 类工况共 201 组示教数据，通过统一相机视角、动作分块参数调整与失败样本补充微调，将多工况综合成功率提升至 **91.2%**。
- **全栈软件项目实践**：结合仪表巡检记录流程，独立完成 [`equipment-inspection-system`](https://github.com/ffgxfvy/equipment-inspection-system) 前后端开发，包含任务状态流转约束、`@Transactional` 多表事务处理、批量查询防 N+1、`SXSSFWorkbook` 分批导出与自动化测试。

---

#### 荣誉奖项与综合经历

- **学业成绩**：GPA **4.01/5.0（8/107，前 7.48%）** · 2023–2024 学年国家奖学金 · 连续两年「三好学生标兵」「科技创新先进个人」· CET-6 **501** / CET-4 **563**
- **国家级竞赛**：
  - 第 18 届全国先进机器人及仿真技术大赛 国家二等奖 1 项、国家三等奖 3 项
  - 2025 中国大学生计算机设计大赛 国家二等奖
  - 第 7 届全国高校计算机能力挑战赛 Word 科目 国家二等奖
  - 第十七届蓝桥杯单片机设计与开发赛道（2026） 国家三等奖（新疆赛区一等奖）
- **省区级竞赛**：
  - 全国大学生电子设计竞赛（2025 E 题）新疆赛区二等奖
  - 全国大学生统计建模大赛 新疆赛区一等奖 ×2（2024、2025）
  - 全国大学生数学建模竞赛 新疆赛区二等奖 ×2（2024、2025）
  - 先进成图大赛 机械类个人二等奖（第 3 名）、团体一等奖 · 中国机器人及人工智能大赛 新疆赛区三等奖
- **交流、实践与体育**：2025 春季学期北京校本部交流学习 · 2025.6–7 哈萨克斯坦阿特劳石油天然气大学暑期实践 · 累计志愿服务 **183.5 h** · 校运会男子 5000 米冠军 · 连续三年完赛克拉玛依马拉松

---

#### 其他入口

- 个人网页：[ffgxfvy.github.io/personal-site](https://ffgxfvy.github.io/personal-site/)（含方向筛选与脱敏简历下载）
- 仓库列表：[github.com/ffgxfvy?tab=repositories](https://github.com/ffgxfvy?tab=repositories)
- 邮箱：`ffgxfvy5562@163.com`
