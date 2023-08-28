# HuggingSD

### 项目简介

受到[HuggingLLM](https://github.com/datawhalechina/hugging-llm)项目的启发，本项目想介绍以stable-diffusion为代表的视觉生成大模型的原理、使用和应用，降低使用门槛，让更多感兴趣的非专业人士能够无障碍使用SD创造价值。

### 立项理由

以stable-diffusion为代表的视觉生成大模型正在深刻改变视觉领域中的上下游任务（包括二维和三维）。甚至正在改变许多产业，比如绘画、3D建模、影视、游戏等等。我们想借这个项目将SD介绍给更多的人，尤其是对此感兴趣、想利用相关技术做一些新产品或应用的朋友。希望新的技术能够促进行业更快更好发展，提高人们工作效率和生活质量。AI for humans!

### 项目受众

项目适合以下人员：

- 学生。希望通过学习相关技术，或是开发新应用，或是入门视觉生成式大模型，或是结合其他行业做AI for science的研究等。
- 相关或非相关行业从业者。对stable-diffusion或视觉生成大模型感兴趣，希望在实际中运用该技术创造提供新的服务或解决已有问题。

项目不适合以下人员：

- 研究其底层算法细节，比如DDPM数学推导、讨论SDS / SJC VSD等。
- 对其他技术细节感兴趣。

### 项目亮点

聚焦于如何使用stable-diffusion API创造新的功能和应用（二维和三维）。
了解相关算法原理以更便捷高效使用。
提供示例代码和使用流程。

### 项目规划

**二维视觉**
- 1 stable-diffusion原理简介
    - 1.1 主流视觉生成大模型 （俞笛）
    - 1.2 ddpm算法 （孝杰）
- 2 stable-diffusion使用指南
    - 2.1 提示词 （宝华）
      - 2.1.x 提示词工具（柏特）
    - 2.2 文生图 （宝华）
    - 2.3 图生图（包括image2image、inpainting、）
    - 2.4 模型调优(沁瑜)
      - 2.4.1 模型基础知识
      - 2.4.2 Textual Inversion
      - 2.4.2 DreamBooth
      - 2.4.3 LoRA（俞笛）
      - 2.4.4 ControlNet（俞笛）
    - 2.5 插件 (柏特)
    - 2.6 sdxl1.0与应用(沁瑜)


**三维视觉**（孝杰）
- 3 三维生成原理
    - 3.1 介绍背景和应用（prolificdreamer magic3d等 ）
    - 3.2 NeRF神经辐射场
    - 3.3 Dreamfusion原理
    - 3.4 Zero123原理
    - 3.5 几何与纹理生成
- 4 三维视觉应用
    - 4.1 blender软件使用简介
    - 4.2 趣味应用举例（建模自己的手办并3d打印..）

**技术局限与未来发展**
- 5 目前局限
  - 5.1 二维生成：版权等
  - 5.2 三维生成：质量有待提升、生成时间长、渲染速度慢等
- 6 未来发展
  - 6.1 社区生态（柏特）
  - 6.2 行业应用
      - 二维场景：营销作图、游戏作画、美图工具等
      - 三维场景：游戏、电影、虚拟资产、vision pro内容等
