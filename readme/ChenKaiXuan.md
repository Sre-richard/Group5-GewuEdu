## 陈凯旋进展记录

### 时间范围

截至 2026.3.27（week 4 周五）

### 已完成

- 搭建了该项目的 GitHub 仓库。
- 尝试将 Unity 画面推送到 Web 端，当前采用的方案是 WebGL 原生导出。

### 遇到的困难

- WebGL 的计算资源放在浏览器端，部署形态类似 GitHub Pages 这类静态页面。
- 单线程算力不足以支撑 Unity-RL-Playground 在 Web 端的正常部署。见 [WebGL_Power_Consumption](../assets/ChenKaiXuan/imgs/WebGL_Power_Consumption.png)。
- 相关讨论见 [ppt/Group5_GewuEdu_2026_3_27.pptx](../ppt/Group5_GewuEdu_2026_3_27.pptx)。

### 下一步

- 继续探索适合在 Web 端演示 Unity-RL-Playground 的替代方案，要求可行性、性能和实现成本，优先选择可快速演示的方案。

===========================================================================

### 时间范围

截至 2026.4.3（week 5 周五）

### 已完成

- 采用新方案在 Web 端演示 Unity-RL-Playground，方案为Unity Render Streaming。
- 初步搭建完成，web端可以选择Playground和HeTu两个场景，并支持web端进行操控，如选择模型，退回目录，键盘控制机器人移动等

点击查看演示视频：[week5.mp4](../assets/ChenKaiXuan/videos/week5.mp4)



### 下一步

- 美化界面
- 适配新场景
- 测试推流速度

===========================================================================
### 时间范围

截至 2026.4.10（week 5 周五）

### 已完成

- 租用阿里云服务器(提供唯一固定的公网IP),并在服务器上搭Coturn(确保在严格网络地址转换环境下仍然能建立P2P数据传输链路),跨省测试和本地测试响应效果差不多。
- 添加了TinkerCoin场景,开始时有斜向上辅助拉力F，50w steps后每10wsteps降低0.2F,100w steps后无外力，耗时约为4min+4min.

点击查看演示视频：[week6.mp4](../assets/ChenKaiXuan/videos/week6_0.mp4)，[training_4min_later.mp4](../assets/ChenKaiXuan/videos/week6_1.mp4)

### 下一步

- 美化界面
- 建立类 Urdf Studio 场景
===========================================================================