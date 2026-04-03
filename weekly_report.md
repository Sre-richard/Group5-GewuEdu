## 小组进展记录(周报)


### 时间范围

截至 2026.3.27（week 4 Friday）

### 已完成

- 搭建了该项目的 GitHub 仓库。
- 尝试将 Unity 画面推送到 Web 端，当前采用的方案是 WebGL 原生导出。

### 遇到的困难

- WebGL 的计算资源放在浏览器端，部署形态类似 GitHub Pages 这类静态页面。
- 单线程算力不足以支撑 Unity-RL-Playground 在 Web 端的正常部署。
- 相关讨论见 [ppt/Group5_GewuEdu_2026_3_27.pptx](../ppt/Group5_GewuEdu_2026_3_27.pptx)。
- 二年级学生不熟悉Unity-RL-Playground，难以开发新教育项目。

### 下一步

- 继续探索适合在 Web 端演示 Unity-RL-Playground 的替代方案，要求可行性、性能和实现成本，优先选择可快速演示的方案。二年级学生熟悉Unity-RL-Playground。


===========================================================================

### 时间范围

截至 2026.4.3（week 5 Friday）

### 已完成

- 采用新方案在 Web 端演示 Unity-RL-Playground，方案为Unity Render Streaming。
- 初步搭建完成，web端可以选择Playground和HeTu两个场景，并支持web端进行操控，如选择模型，退回目录，键盘控制机器人移动等

点击查看演示视频：[week5.mp4](../assets/KaixuanChen/videos/week5.mp4)

### 遇到的困难

- 二年级学生不熟悉Unity-RL-Playground，难以开发新教育项目。


### 下一步

- 美化界面
- 适配新场景
- 测试推流速度
- 二年级学生熟悉Unity-RL-Playground，探索开发教育项目。

===========================================================================