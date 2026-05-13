# 夏苏安

> 计算机视觉 / 3D/4D Gaussian Splatting / VR 直播与沉浸式渲染 / 非视域成像

![夏苏安](assets/self-150kb.jpg)

## 联系方式

- 手机 / 微信：18018591626
- Email：956974516@qq.com
- GitHub：<https://github.com/Akua1919>
- 期望职位：CV 工程师
- 期望城市：江浙沪、深圳
- 期望薪资：面谈

## 个人信息

- 男 / 1999
- 上海科技大学，计算机科学与技术，本科 + 硕士研究生
- 工作年限：1 年
- 研究方向：计算机视觉、AI、计算摄影学、非视域成像

## 教育经历

### 上海科技大学 | 计算机科学与技术

2017.09 - 2025.07

- 学历：本科 + 硕士研究生
- 导师组：虞晶怡
- 研究方向：计算机视觉、AI、计算摄影学、非视域成像
- 关注主题：3D/4D 重建、2D/3D AIGC、瞬态成像、神经渲染

## 学术相关项目

### HOLI-1-to-3：结合 AIGC 的非视域成像与整体 3D 生成

- 论文链接：[IEEE TPAMI](https://ieeexplore.ieee.org/document/10684158/)
- 面向单视点整体 3D 形状恢复问题，结合 line-of-sight（LOS）RGB/深度信息与 non-line-of-sight（NLOS）瞬态测量，缓解单图像 3D 生成中不可见背面几何歧义。
- 方法上引入 Neural RGB-T Fields，将 LOS RGB 图像对应的 radiance field 与 NLOS transients 对应的 transient field 统一到同一神经全光表示中。
- 使用两阶段优化流程：粗阶段结合 Stable Diffusion、Zero-1-to-3 等生成先验与瞬态约束获得初始几何，细阶段通过 DMTet 提升最终 mesh 质量。
- 在仿真与真实采集数据上验证方法效果；实验显示，即使稀疏瞬态信息也能帮助消除不可见区域歧义，并提升整体生成质量。
- 个人收获：系统理解了 AIGC 先验、ToF/SPAD 瞬态测量、可微渲染和 3D 表示在计算摄影任务中的结合方式。

## 工作经历

### 宁波万有引力电子科技有限公司 | CV / 3D 重建 / VR 方向

2025.07 - 至今

#### 4DGS 重建项目

- 从零搭建动态 3D/4D 重建系统，重点评估多相机同步问题，最终采用 Genlock + 闪光灯记录 实现帧级多机同步。
- 基于 SpacetimeGS、FreeTimeGS 等方法开发算法，实现 4K 级别动态场景重建。
- 引入前馈式高斯初始化方案，加快训练收敛过程，提升重建迭代效率。
- 引入动静分离方法，实现背景与运动主题的分别重建与结合，提升重建质量。
- 实现多卡训练版本算法，支持8张RTX 5090显卡训练长时间与高分辨率数据。
- 在 Unity 中实现并优化高斯渲染代码，结合 OpenXR 支持在头显中观看 4DGS 模型。
- 未来：调研 GS 与世界模型的联系，助力 VR 内容的制作与输出。

#### VR 直播项目

- 从零搭建 VR 直播链路，覆盖相机、服务器、路由器、终端等设备的选型与网络布线，实现约 500 ms 低延时、7680 x 3840 高分辨率、多机位切换的直播。
- 部署流媒体服务器框架mediamtx，并通过多轮测试比较不同传输协议，最终采用 WebRTC 作为低延时直播协议。
- 使用 Flutter 开发 2D 播放器app，测试 WebRTC 协议在实际播放端的低延时与画质表现。
- 使用 Unity 开发沉浸式 3D 播放器app，实现头显内实时观看VR180格式的 7680 x 3840 分辨、可多机位切换的VR直播内容。
- 未来：计划于下个月将这套系统部署到浙超足球的比赛现场，验证这套系统在局域网下的最终表现效果。

## 论文与成果

1. **Siyuan Shen, Suan Xia, Xingyue Peng, Ziyu Wang, Yingsheng Zhu, Shiying Li, Jingyi Yu.** HOLI-1-to-3: Transient-Enhanced Holistic Image-to-3D Generation. *IEEE Transactions on Pattern Analysis and Machine Intelligence*, 2025. [IEEE](https://ieeexplore.ieee.org/document/10684158/)
2. **Ruiqian Li, Siyuan Shen, Suan Xia, Ziheng Wang, Xingyue Peng, Chengxuan Song, Yingsheng Zhu, Tao Wu, Shiying Li, Jingyi Yu.** TransiT: Transient Transformer for Non-line-of-sight Videography. *ICCV*, 2025. [arXiv](https://arxiv.org/abs/2503.11328)
3. **Yuehan Wang, Siyuan Shen, Suan Xia, Ruiqian Li, Xingyue Peng, Yanhua Yu, Shiying Li, Jingyi Yu.** Neural Reconstruction through Scattering Media with Forward and Backward Losses. *ICCP*, 2023. [IEEE](https://ieeexplore.ieee.org/document/10233796)
4. **Siyuan Shen, Ziheng Wang, Xingyue Peng, Suan Xia, Ruiqian Li, Shiying Li, Jingyi Yu.** MARMOT: Masked Autoencoder for Modeling Transient Imaging. *arXiv*, 2025. [arXiv](https://arxiv.org/abs/2506.08470)
5. **Yanhua Yu, Siyuan Shen, Zi Wang, Binbin Huang, Yuehan Wang, Xingyue Peng, Suan Xia, Ping Liu, Ruiqian Li, Shiying Li.** Enhancing Non-line-of-sight Imaging via Learnable Inverse Kernel and Attention Mechanisms. *ICCV*, 2023. [IEEE](https://ieeexplore.ieee.org/document/10378421)

## 技能清单

- 编程与实验：Python、PyTorch、MATLAB、C++
- 视觉与重建：Computer Vision、3D/4D Gaussian Splatting、AIGC、Non-line-of-sight Imaging、Transient Imaging、Neural Rendering
- 图形与 XR：Unity、OpenXR、Blender、实时渲染、头显端内容展示
- 直播与工程：WebRTC、Flutter、流媒体服务器、多机同步、Genlock、多卡训练
- 开发工具：Codex、Claude Code、Git；能熟练使用 AI 辅助开发工具提升代码实现、调试、重构与文档整理效率
- 其他：爱好摄影，了解摄影原理与基础拍摄技巧；喜欢骑行，学过入门程度的网球和击剑
