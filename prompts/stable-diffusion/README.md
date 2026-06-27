# Stable Diffusion 提示词库

> Stable Diffusion 专用高质量提示词集合

Stable Diffusion 以其**开源免费**、**高度可控**、**社区庞大**而备受欢迎，是最灵活的图像生成解决方案。

## 📋 目录

- [写实人物](#写实人物)
- [动漫角色](#动漫角色)
- [风景摄影](#风景摄影)
- [产品设计](#产品设计)
- [艺术创作](#艺术创作)
- [模型推荐](#模型推荐)
- [参数调优指南](#参数调优指南)

---

## 写实人物

### 1. 专业人像摄影

**正向提示词** (Positive Prompt):
```
professional portrait photography, beautiful young woman, 
natural makeup, soft smile, looking at camera, 
studio lighting, bokeh background, shallow depth of field, 
85mm lens, f/1.4, photorealistic, highly detailed face, 
perfect skin texture, cinematic lighting, high quality, 8k uhd
```

**负向提示词** (Negative Prompt):
```
ugly, deformed, noisy, blurry, distorted, out of focus, 
bad anatomy, extra limbs, poorly drawn face, poorly drawn hands, 
missing fingers, low quality, worst quality, jpeg artifacts, 
watermark, signature, username, text
```

**推荐参数**:
- Model: Realistic Vision V5.1 或 DreamShaper
- Steps: 30-40
- CFG Scale: 7-9
- Sampler: DPM++ 2M Karras
- Size: 512x768 (竖向人像)

**中文描述**: 专业人像摄影，美丽年轻女性，自然妆容，柔和微笑，看向镜头，工作室灯光，散景背景，浅景深，85mm镜头，f/1.4光圈，照片级真实，高度细节面部，完美皮肤质感

**适用场景**: 人像摄影、头像生成、角色设计

---

### 2. 时尚大片

**正向提示词**:
```
high fashion editorial photography, elegant female model, 
avant-garde designer dress, dramatic pose, 
studio lighting with colored gels, vogue magazine style, 
professional fashion photography, sharp focus, 
volumetric lighting, cinematic composition, 
masterpiece, best quality, ultra detailed
```

**负向提示词**:
```
ugly, boring pose, casual clothes, bad lighting, 
amateur photography, distorted face, bad proportions, 
low quality, blurry, noisy, oversaturated
```

**推荐参数**:
- Model: Realistic Vision V5.1
- Steps: 35
- CFG Scale: 8
- Sampler: Euler a
- Size: 512x768

**适用场景**: 时尚摄影、品牌宣传、杂志封面

---

## 动漫角色

### 3. 可爱动漫少女

**正向提示词**:
```
anime girl, cute kawaii style, big expressive eyes, 
colorful hair with twin tails, school uniform, 
cheerful smile, dynamic pose, 
detailed background, cherry blossoms, 
soft pastel colors, cel shading, 
high quality anime art, official art style
```

**负向提示词**:
```
realistic, 3d, photo, ugly, bad anatomy, 
missing limbs, extra fingers, blurry, 
low quality, worst quality, watermark
```

**推荐参数**:
- Model: Anything V5 或 CounterfeitV3
- Steps: 25-30
- CFG Scale: 7
- Sampler: DPM++ SDE Karras
- Size: 512x768
- Clip Skip: 2 (重要！)

**中文描述**: 动漫女孩，可爱卡哇伊风格，大而有表现力的眼睛，彩色双马尾，校服，开朗微笑，动态姿势，细节背景，樱花，柔和粉彩色，赛璐璐阴影

**适用场景**: 动漫插画、角色设计、表情包

---

### 4. 幻想角色

**正向提示词**:
```
fantasy character design, anime style warrior girl, 
detailed armor with magical effects, glowing weapon, 
battle pose, dramatic lighting, 
mystical background with magic circles, 
vibrant colors, epic composition, 
highly detailed, intricate details, 
official character art
```

**负向提示词**:
```
realistic, photo, ugly, bad anatomy, 
simple background, boring pose, 
low quality, blurry, duplicate
```

**推荐参数**:
- Model: Anything V5
- Steps: 30
- CFG Scale: 7-8
- Sampler: DPM++ 2M Karras
- Size: 512x768
- Clip Skip: 2

**适用场景**: 游戏角色、小说插图、同人创作

---

## 风景摄影

### 5. 自然风光

**正向提示词**:
```
landscape photography, majestic mountain range, 
pristine alpine lake reflection, golden hour lighting, 
dramatic clouds, vibrant sunset colors, 
wide angle lens, professional nature photography, 
high dynamic range, ultra sharp focus, 
national geographic style, 8k resolution
```

**负向提示词**:
```
people, buildings, cars, urban elements, 
low quality, blurry, distorted, oversaturated, 
amateur, noise, artifacts
```

**推荐参数**:
- Model: Realistic Vision V5.1
- Steps: 30-35
- CFG Scale: 7
- Sampler: DPM++ 2M Karras
- Size: 768x512 (横向风景)

**中文描述**: 风景摄影，壮丽山脉，原始高山湖泊倒影，黄金时段光线，戏剧性云朵，鲜艳日落色彩，广角镜头，专业自然摄影，高动态范围

**适用场景**: 风景摄影、壁纸、旅游宣传

---

### 6. 城市夜景

**正向提示词**:
```
urban cityscape at night, modern skyscrapers, 
neon lights and reflections, wet streets after rain, 
long exposure photography, light trails from traffic, 
cyberpunk atmosphere, cinematic mood, 
highly detailed architecture, professional photography, 
8k uhd, sharp focus
```

**负向提示词**:
```
daytime, bright sunlight, people in foreground, 
low quality, blurry, distorted buildings, 
amateur, oversaturated, noise
```

**推荐参数**:
- Model: DreamShaper 或 Realistic Vision
- Steps: 35
- CFG Scale: 7-8
- Sampler: Euler a
- Size: 768x512

**适用场景**: 城市摄影、概念设计、电影场景

---

## 产品设计

### 7. 科技产品

**正向提示词**:
```
product photography, futuristic smartphone design, 
sleek minimalist form, glass and metal materials, 
floating on white background, studio lighting, 
reflective surface, professional commercial photography, 
highly detailed, 8k resolution, clean composition
```

**负向提示词**:
```
cluttered background, bad lighting, distorted shape, 
low quality, blurry, amateur, scratches, dirty
```

**推荐参数**:
- Model: Realistic Vision V5.1
- Steps: 30
- CFG Scale: 8
- Sampler: DPM++ 2M Karras
- Size: 512x512

**中文描述**: 产品摄影，未来智能手机设计，流线极简形态，玻璃和金属材料，漂浮在白色背景上，工作室灯光，反射表面

**适用场景**: 产品展示、电商主图、工业设计

---

### 8. 珠宝首饰

**正向提示词**:
```
luxury jewelry photography, diamond ring, 
macro close-up, dramatic studio lighting, 
black reflective surface, sparkling gemstones, 
extreme detail, professional commercial photography, 
high-end advertising style, 8k uhd
```

**负向提示词**:
```
cheap looking, bad lighting, blurry, 
low quality, distorted, amateur, cluttered
```

**推荐参数**:
- Model: Realistic Vision V5.1
- Steps: 35
- CFG Scale: 9
- Sampler: DPM++ 2M Karras
- Size: 512x512

**适用场景**: 珠宝摄影、奢侈品广告、电商详情

---

## 艺术创作

### 9. 油画风格

**正向提示词**:
```
oil painting, impressionist style, beautiful garden scene, 
vibrant flowers, loose brushstrokes, visible paint texture, 
warm color palette, monet style, romantic atmosphere, 
classical french impressionism, masterpiece
```

**负向提示词**:
```
photorealistic, digital art, sharp edges, 
modern, low quality, flat colors, boring composition
```

**推荐参数**:
- Model: DreamShaper 或 Deliberate
- Steps: 30
- CFG Scale: 7
- Sampler: Euler a
- Size: 768x512

**中文描述**: 油画，印象派风格，美丽花园场景，鲜艳花朵，宽松笔触，可见颜料质感，温暖色调，莫奈风格

**适用场景**: 艺术创作、装饰画、墙面装饰

---

### 10. 数字艺术

**正向提示词**:
```
digital art, fantasy landscape, floating islands, 
magical waterfall, dramatic sky with auroras, 
vibrant colors, epic composition, 
concept art style, highly detailed, 
trending on artstation, matte painting
```

**负向提示词**:
```
photorealistic, boring, simple, low quality, 
blurry, amateur, bad composition, flat lighting
```

**推荐参数**:
- Model: DreamShaper
- Steps: 30
- CFG Scale: 7-8
- Sampler: DPM++ 2M Karras
- Size: 768x512

**适用场景**: 概念艺术、游戏背景、幻想插画

---

## 模型推荐

### 写实类模型

| 模型名称 | 特点 | 适用场景 |
|---------|------|---------|
| **Realistic Vision V5.1** | 照片级真实感，人物细节好 | 人像、产品、写实摄影 |
| **DreamShaper** | 平衡性好，适应性强 | 通用场景、风景、产品 |
| **ChilloutMix** | 亚洲面孔优化 | 亚洲人像摄影 |
| **Deliberate** | 艺术感强，细节丰富 | 概念艺术、创意设计 |

### 动漫类模型

| 模型名称 | 特点 | 适用场景 |
|---------|------|---------|
| **Anything V5** | 通用动漫，风格多样 | 角色设计、插画 |
| **CounterfeitV3** | 高质量动漫，色彩鲜艳 | 精美插画、同人创作 |
| **Pastel Mix** | 柔和色彩，梦幻风格 | 少女插画、治愈系 |
| **AbyssOrangeMix** | 细节丰富，表现力强 | 高质量角色、场景 |

### 特殊用途模型

| 模型名称 | 特点 | 适用场景 |
|---------|------|---------|
| **OpenJourney** | Midjourney风格 | 艺术创作 |
| **Protogen** | 科幻风格 | 科幻场景、机甲 |
| **Redshift Diffusion** | 3D渲染风格 | 产品渲染、建筑 |

---

## 参数调优指南

### 基础参数说明

**Steps (采样步数)**:
- 20-25: 快速预览
- 30-40: 标准质量
- 50+: 高质量（收益递减）

**CFG Scale (提示词相关性)**:
- 5-7: 更自由创意
- 7-9: 平衡质量和创意
- 10+: 严格遵循提示词（可能过拟合）

**Sampler (采样器)**:
- `Euler a`: 快速，创意性强
- `DPM++ 2M Karras`: 质量高，推荐
- `DPM++ SDE Karras`: 细节丰富
- `DDIM`: 稳定，可预测

### 高级技巧

**1. 提示词权重**

使用括号调整权重：
```
(keyword:1.2)  # 增强权重
(keyword:0.8)  # 降低权重
((keyword))    # 等同于 (keyword:1.1)
```

**2. 提示词混合**

使用 `AND` 混合概念：
```
cat AND dog   # 同时包含猫和狗的特征
```

**3. 提示词编辑**

使用 `[keyword:steps]` 在特定步数引入/移除：
```
[keyword:10]      # 从第10步开始添加
[keyword::15]     # 到第15步移除
[keyword:other:8] # 第8步从keyword切换到other
```

**4. Clip Skip**

- 1: 更精确，适合写实
- 2: 更风格化，适合动漫（必须！）

### 分辨率建议

**标准分辨率** (SD 1.5):
- 512x512: 方形，通用
- 512x768: 竖向人像
- 768x512: 横向风景
- 512x704: 手机壁纸

**高分辨率技巧**:
1. 先生成512x512
2. 使用 Hires.fix 放大到1024x1024
3. Upscaler: R-ESRGAN 4x+
4. Denoising strength: 0.4-0.6

### 批量生成设置

**探索阶段**:
- Batch size: 4-8
- Steps: 20-25
- 快速测试不同提示词

**精修阶段**:
- Batch size: 1
- Steps: 35-50
- 细调参数获得最佳效果

---

## 💡 提示词写作技巧

### 提示词结构模板

```
[质量词] + [主体] + [细节] + [风格] + [灯光] + [镜头] + [艺术家参考]
```

**示例**:
```
masterpiece, best quality,        # 质量词
beautiful woman,                  # 主体
long flowing hair, elegant dress, # 细节
fantasy art style,                # 风格
soft lighting, golden hour,       # 灯光
portrait, close-up,               # 镜头
trending on artstation            # 质量加成
```

### 常用质量关键词

**通用质量提升**:
```
masterpiece, best quality, high quality, extremely detailed, 
ultra detailed, 8k uhd, professional, sharp focus
```

**特定风格**:
- 写实: `photorealistic, hyperrealistic, lifelike`
- 动漫: `anime style, official art, cel shading`
- 艺术: `trending on artstation, award winning, masterpiece`
- 摄影: `professional photography, cinematic lighting, bokeh`

### 负面提示词模板

**通用负面词**:
```
ugly, deformed, noisy, blurry, distorted, out of focus,
bad anatomy, extra limbs, poorly drawn face, poorly drawn hands,
missing fingers, mutation, mutated, extra fingers, low quality,
worst quality, normal quality, jpeg artifacts, signature,
watermark, username, artist name, text, error
```

**动漫专用**:
```
realistic, 3d, photo, photorealistic, ugly, bad anatomy,
bad hands, missing fingers, extra digit, fewer digits,
low quality, worst quality
```

---

## 🛠️ 工具推荐

### WebUI 界面

- **AUTOMATIC1111** - 最流行的SD界面
- **ComfyUI** - 节点式工作流，更灵活
- **InvokeAI** - 用户友好的界面

### 在线平台

- **Civitai** - 模型下载和分享
- **Lexica** - 提示词搜索和参考
- **PromptHero** - 提示词库

### 辅助工具

- **ControlNet** - 精确控制构图
- **LoRA** - 风格和角色微调
- **Textual Inversion** - 自定义概念
- **img2img** - 图像编辑和变换

---

## 🎯 更多资源

查看其他分类获取更多提示词：
- [GPT Image 2提示词](../gpt-image-2/)
- [Midjourney提示词](../midjourney/)
- [按类别浏览](../categories/)
- [按风格浏览](../styles/)

## 📝 贡献

欢迎提交你的Stable Diffusion提示词！请查看[贡献指南](../../CONTRIBUTING.md)。

## 🔗 相关链接

- [Stable Diffusion官方](https://stability.ai/)
- [AUTOMATIC1111 WebUI](https://github.com/AUTOMATIC1111/stable-diffusion-webui)
- [Civitai模型库](https://civitai.com/)
- [Stable Diffusion艺术](https://stable-diffusion-art.com/)
