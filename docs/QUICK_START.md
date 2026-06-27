# 快速开始指南

欢迎使用 AndyImage！这是一个5分钟快速上手指南。

## 📋 目录

- [选择你的模型](#选择你的模型)
- [浏览提示词](#浏览提示词)
- [使用提示词](#使用提示词)
- [常见问题](#常见问题)

---

## 选择你的模型

首先，确定你要使用哪个AI图像生成模型：

| 模型 | 特点 | 推荐场景 | 目录 |
|------|------|---------|------|
| **GPT Image 2** | 文字渲染强 | 商业设计、Logo | [📁](prompts/gpt-image-2/) |
| **Midjourney** | 艺术性强 | 艺术创作、插画 | [📁](prompts/midjourney/) |
| **Stable Diffusion** | 高度可控 | 通用场景、个性化 | [📁](prompts/stable-diffusion/) |
| **DALL-E 3** | 安全可靠 | 商业用途 | [📁](prompts/dall-e/) |
| **Flux** | 速度快 | 快速迭代 | [📁](prompts/flux/) |
| **Ideogram** | 文字生成 | Logo、标识 | [📁](prompts/ideogram/) |

---

## 浏览提示词

### 方式1: 按模型浏览

进入对应模型目录，查看该模型专用的提示词：

```
prompts/
├── gpt-image-2/      ← GPT Image 2专用
├── midjourney/       ← Midjourney专用
├── stable-diffusion/ ← SD专用
└── ...
```

### 方式2: 按类别浏览

不确定用什么模型？按场景类别浏览：

```
prompts/categories/
├── portrait/      ← 人物肖像
├── landscape/     ← 风景景观
├── illustration/  ← 插画设计
└── ...
```

### 方式3: 按风格浏览

想要特定艺术风格？按风格分类：

```
prompts/styles/
├── anime/         ← 动漫风格
├── realistic/     ← 写实风格
├── oil-painting/  ← 油画风格
└── ...
```

---

## 使用提示词

### 步骤1: 复制提示词

在提示词文件中找到你想用的提示词，复制完整内容。

**示例**:
```
Professional business portrait, confident executive,
navy blue suit, studio lighting, natural smile,
high-end corporate photography, 8k resolution
```

### 步骤2: 根据模型调整

不同模型有不同的使用方式：

#### GPT Image 2
- 直接粘贴提示词
- 选择质量: HD 或 Standard
- 选择尺寸: 1024x1024, 1792x1024, 1024x1792

#### Midjourney
- 在Discord中输入: `/imagine prompt: [你的提示词]`
- 添加参数: `--ar 16:9 --v 6`
- 示例: `/imagine prompt: beautiful sunset --ar 16:9 --v 6`

#### Stable Diffusion
- 正向提示词框: 粘贴主要提示词
- 负向提示词框: 粘贴负面提示词
- 设置参数: Steps, CFG Scale, Sampler
- 点击Generate

### 步骤3: 微调和优化

第一次生成不满意？试试这些：

**GPT Image 2**:
- 修改文字内容
- 调整描述细节
- 尝试不同的质量设置

**Midjourney**:
- 调整 `--s` (风格化程度)
- 改变 `--ar` (纵横比)
- 使用 `--style raw` (更真实)

**Stable Diffusion**:
- 增加Steps (更多细节)
- 调整CFG Scale (遵循程度)
- 尝试不同Sampler
- 添加/修改负面提示词

---

## 常见问题

### Q1: 生成的图片质量不好？

**解决方案**:
- ✅ 使用质量关键词: `high quality`, `detailed`, `8k`
- ✅ 确保提示词描述清晰
- ✅ (SD) 增加Steps到30-40
- ✅ (SD) 使用高质量模型

### Q2: 生成的内容不符合预期？

**解决方案**:
- ✅ 提示词更具体详细
- ✅ 使用参考风格: `in the style of [艺术家]`
- ✅ 添加更多描述词
- ✅ (MJ) 尝试 `--style raw`

### Q3: 文字渲染不准确？

**解决方案**:
- ✅ 使用GPT Image 2或Ideogram
- ✅ 用引号包裹文字: `text: "YOUR TEXT"`
- ✅ 简化文字内容
- ✅ 避免复杂字体

### Q4: 人物面部有问题？

**解决方案**:
- ✅ 添加质量词: `detailed face`, `perfect face`
- ✅ (SD) 使用面部修复: Face Restore
- ✅ (SD) 增加采样步数
- ✅ (MJ) 使用最新版本: `--v 6`

### Q5: 图片尺寸如何选择？

**推荐尺寸**:
- 🖼️ 头像/Logo: 1024x1024 (方形)
- 📱 手机壁纸: 1024x1792 (竖向)
- 💻 桌面壁纸: 1792x1024 (横向)
- 📄 海报: 1024x1792 (竖向)
- 🎬 视频缩略图: 1792x1024 (16:9)

---

## 🎯 下一步

现在你已经掌握基础了！进一步探索：

1. **浏览更多提示词** - 在 [prompts目录](prompts/) 中探索
2. **学习高级技巧** - 阅读各模型的详细指南
3. **参与贡献** - 查看 [贡献指南](CONTRIBUTING.md)
4. **加入讨论** - 在 [Discussions](../../discussions) 中交流

---

## 💡 提示词写作技巧

### 基础结构

```
[主体] + [细节] + [风格] + [质量词]
```

**示例**:
```
beautiful woman,           # 主体
long flowing hair,         # 细节
oil painting style,        # 风格
highly detailed, 8k        # 质量词
```

### 常用质量词

复制粘贴这些提升质量：

```
masterpiece, best quality, ultra detailed,
professional photography, cinematic lighting,
8k uhd, high resolution, sharp focus
```

### 负面提示词 (仅SD)

复制粘贴避免常见问题：

```
ugly, blurry, low quality, distorted,
bad anatomy, bad hands, watermark, text
```

---

## 🆘 需要帮助？

- 📖 查看 [完整文档](docs/)
- 💬 在 [Discussions](../../discussions) 提问
- 🐛 遇到问题？提交 [Issue](../../issues)
- ✉️ 联系: [your.email@example.com](mailto:your.email@example.com)

---

祝你创作愉快！🎨✨
