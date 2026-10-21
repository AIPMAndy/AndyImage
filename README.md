# 🎨 AndyImage

> 全面实用的AI图像生成提示词库 | Comprehensive AI Image Generation Prompt Library

[![GitHub stars](https://img.shields.io/github/stars/AIPMAndy/AndyImage?style=social)](https://github.com/AIPMAndy/AndyImage)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## 📖 简介

AndyImage 是一个精心策划的AI图像生成提示词集合，涵盖主流图像生成模型的高质量提示词，帮助创作者快速生成理想的图像。

### 🌟 特色

- ✅ **多模型支持** - GPT Image 2、Midjourney、Stable Diffusion、DALL-E 3、Flux、Ideogram
- ✅ **分类详细** - 按场景、风格、主题科学分类
- ✅ **实战验证** - 所有提示词都经过实际测试
- ✅ **持续更新** - 定期添加新的高质量提示词
- ✅ **中英双语** - 完整的中英文说明
- ✅ **社区驱动** - 欢迎贡献和反馈

## 📂 目录结构

```
AndyImage/
├── prompts/              # 提示词库
│   ├── gpt-image-2/     # GPT Image 2 专用
│   ├── midjourney/      # Midjourney 专用
│   ├── stable-diffusion/ # Stable Diffusion 专用
│   ├── dall-e/          # DALL-E 3 专用
│   ├── flux/            # Flux 专用
│   ├── ideogram/        # Ideogram 专用
│   ├── categories/      # 按类别分类
│   │   ├── portrait/    # 人物肖像
│   │   ├── landscape/   # 风景景观
│   │   ├── abstract/    # 抽象艺术
│   │   ├── illustration/# 插画设计
│   │   ├── photography/ # 摄影风格
│   │   └── 3d-render/   # 3D渲染
│   └── styles/          # 按风格分类
│       ├── anime/       # 动漫风格
│       ├── realistic/   # 写实风格
│       ├── oil-painting/# 油画风格
│       ├── watercolor/  # 水彩风格
│       ├── pixel-art/   # 像素艺术
│       └── minimalist/  # 极简风格
├── docs/                # 文档
├── examples/            # 示例图像
└── README.md
```

## 🚀 快速开始

### 浏览提示词

1. **按模型浏览** - 进入 `prompts/[模型名称]/` 查看特定模型的提示词
2. **按类别浏览** - 进入 `prompts/categories/` 按场景查找
3. **按风格浏览** - 进入 `prompts/styles/` 按艺术风格查找

### 使用提示词

每个提示词文件包含：
- **提示词内容** - 可直接复制使用
- **参数建议** - 推荐的模型参数
- **效果描述** - 预期生成效果
- **示例图片** - 实际生成的样例（部分提示词）

### 示例

```markdown
# 提示词：赛博朋克城市夜景

**模型**: GPT Image 2, Midjourney, Stable Diffusion

**提示词**:
Cyberpunk cityscape at night, neon lights reflecting on wet streets, 
towering skyscrapers with holographic advertisements, flying cars in the distance,
rain-soaked atmosphere, cinematic lighting, ultra detailed, 8k resolution

**关键词解析**:
- Cyberpunk cityscape - 赛博朋克城市景观
- neon lights - 霓虹灯
- wet streets - 湿润街道
- holographic advertisements - 全息广告
- flying cars - 飞行汽车
- cinematic lighting - 电影般灯光

**推荐参数**:
- GPT Image 2: Standard quality, 1024x1024
- Midjourney: --ar 16:9 --style raw --v 6
- Stable Diffusion: Steps: 30, CFG Scale: 7, Sampler: DPM++ 2M Karras
```

## 📚 提示词分类

### 按模型

| 模型 | 数量 | 特点 |
|------|------|------|
| GPT Image 2 | 200+ | 文字渲染强、理解力好 |
| Midjourney | 300+ | 艺术性强、风格丰富 |
| Stable Diffusion | 400+ | 可控性强、社区庞大 |
| DALL-E 3 | 150+ | 安全性高、概念理解 |
| Flux | 100+ | 速度快、质量高 |
| Ideogram | 100+ | 文字生成、Logo设计 |

### 按场景

- 🎭 **人物肖像** - 头像、全身像、群像
- 🏞️ **风景景观** - 自然风光、城市景观
- 🎨 **抽象艺术** - 几何、色彩、概念
- ✏️ **插画设计** - 扁平、矢量、手绘
- 📷 **摄影风格** - 人像、静物、街拍
- 🎮 **3D渲染** - 建筑、产品、角色

### 按风格

- 🌸 **动漫** - 日系、美系、韩系
- 📸 **写实** - 照片级、超写实
- 🖼️ **油画** - 古典、印象派、现代
- 💧 **水彩** - 清新、梦幻、流动
- 🎮 **像素艺术** - 8bit、16bit、现代像素
- ⬜ **极简** - 简约、几何、现代

## 🎯 使用技巧

### 提示词构建原则

1. **主体明确** - 清楚描述要生成的主要内容
2. **细节丰富** - 添加具体的视觉细节
3. **风格定义** - 指定艺术风格或参考
4. **质量控制** - 使用质量关键词（detailed, high quality, 8k等）
5. **氛围营造** - 描述光线、色调、情绪

### 常用质量关键词

**通用**:
- `masterpiece, best quality, ultra detailed`
- `8k resolution, high resolution`
- `professional, award-winning`

**光线**:
- `cinematic lighting, dramatic lighting`
- `soft light, natural light, golden hour`
- `volumetric lighting, rim lighting`

**风格**:
- `photorealistic, hyperrealistic`
- `concept art, digital art`
- `studio photography, portrait photography`

### 负面提示词（Negative Prompts）

用于Stable Diffusion等模型，避免不想要的元素：

```
ugly, blurry, low quality, distorted, deformed, 
bad anatomy, bad hands, watermark, text, 
signature, username, grainy, oversaturated
```

## 🤝 贡献指南

我们欢迎所有形式的贡献！

### 如何贡献

1. **Fork** 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingPrompt`)
3. 提交更改 (`git commit -m 'Add some amazing prompts'`)
4. 推送到分支 (`git push origin feature/AmazingPrompt`)
5. 创建 **Pull Request**

### 贡献内容

- ✨ **新提示词** - 分享你的高质量提示词
- 📝 **改进文档** - 完善说明和教程
- 🖼️ **示例图片** - 提供生成效果展示
- 🐛 **问题反馈** - 报告错误或提出建议
- 🌐 **翻译** - 帮助翻译成更多语言

### 提示词提交规范

提交新提示词时，请包含：

```markdown
# 提示词标题

**模型**: [适用的模型]
**类别**: [场景/风格分类]
**难度**: [简单/中等/复杂]

**提示词**:
[完整的提示词内容]

**描述**:
[预期效果描述]

**推荐参数**:
[模型特定的参数建议]

**示例图片**: （可选）
![示例](examples/xxx.png)
```

## 📊 统计信息

- 📝 总提示词数: 1,250+
- 🎨 支持模型: 6个
- 🏷️ 分类数量: 12个
- 👥 贡献者: 招募中
- ⭐ GitHub Stars: 持续增长中

## 🔗 相关资源

### 官方文档
- [OpenAI GPT Image 2 Guide](https://platform.openai.com/docs/guides/images)
- [Midjourney Documentation](https://docs.midjourney.com/)
- [Stable Diffusion Guide](https://stable-diffusion-art.com/)

### 工具推荐
- [PromptHero](https://prompthero.com/) - 提示词搜索平台
- [Lexica](https://lexica.art/) - Stable Diffusion 提示词库
- [MidJourney Prompt Helper](https://prompt.noonshot.com/) - Midjourney 提示词工具

### 相关项目

#### FANTASY梵想美学工具集
来自 [dacnay816y62-hub](https://github.com/dacnay816y62-hub) 的创意视觉设计工具：

- [fantasy-life-force-portrait-photography](https://github.com/dacnay816y62-hub/fantasy-life-force-portrait-photography) ⭐32 - Fantasy 生命感人像摄影 skill
- [culture-fragment-poster-engine](https://github.com/dacnay816y62-hub/culture-fragment-poster-engine) ⭐30 - 快速搭建审美优质的海报 kv 平面 视觉
- [regional-culture-poster](https://github.com/dacnay816y62-hub/regional-culture-poster) ⭐11 - 把中国地域文化转译成克制当代的大字海报与编辑海报
- [fantasy-oriental-editorial-poster](https://github.com/dacnay816y62-hub/fantasy-oriental-editorial-poster) ⭐9 - 创意文字极简海报
- [fantasy-photography-simulation-github](https://github.com/dacnay816y62-hub/fantasy-photography-simulation-github) ⭐8 - 全宇宙任意地方完成"摄影"

> 📖 详细介绍请查看：[FANTASY梵想美学相关仓库](docs/fantasy-repos.md)

#### 其他优秀项目
- [awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2)
- [awesome-stable-diffusion](https://github.com/awesome-stable-diffusion/awesome-stable-diffusion)
- [midjourney-prompts](https://github.com/willwulfken/MidJourney-Styles-and-Keywords-Reference)

## 📜 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

## 🙏 致谢

感谢所有贡献者和支持者！

特别感谢以下项目和资源：
- OpenAI 的 GPT Image 2
- Midjourney 社区
- Stable Diffusion 开源社区
- 所有提供提示词的创作者

## 📮 联系方式

- 🐛 **Issues**: [GitHub Issues](https://github.com/AIPMAndy/AndyImage/issues)
- 🐦 **X**: [@AIPMAndy](https://x.com/AIPMAndy)

## ⭐ Star History

如果这个项目对你有帮助，请给个星标支持！

[![Star History Chart](https://api.star-history.com/svg?repos=AIPMAndy/AndyImage&type=Date)](https://star-history.com/#AIPMAndy/AndyImage&Date)

---

<p align="center">
  <b>🎨 用AI创造美好，让创作更简单</b>
</p>

<p align="center">
  Made with ❤️ by <a href="https://github.com/AIPMAndy">Andy</a>
</p>
