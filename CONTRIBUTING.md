# 贡献指南

感谢你对 AndyImage 项目的关注！我们欢迎所有形式的贡献。

## 🤝 如何贡献

### 提交新提示词

1. **Fork 本仓库**
2. **创建新分支**
   ```bash
   git checkout -b add-prompts-[类别名]
   ```

3. **按格式添加提示词**
   
   在对应目录下创建或编辑Markdown文件，使用以下模板：

   ```markdown
   ### [编号]. [提示词标题]

   **提示词**:
   ```
   [完整的提示词内容]
   ```

   **中文描述**: [中文说明]

   **推荐参数**: 
   - [参数1]: [值]
   - [参数2]: [值]

   **适用场景**: [使用场景]

   **示例图片**: (可选)
   ![示例](../../examples/xxx.png)
   ```

4. **提交更改**
   ```bash
   git add .
   git commit -m "Add: [提示词类别] - [简短描述]"
   ```

5. **推送到你的 Fork**
   ```bash
   git push origin add-prompts-[类别名]
   ```

6. **创建 Pull Request**

### 提交示例图片

如果有生成的示例图片：

1. 图片放在 `examples/` 目录
2. 命名格式: `[模型名]-[类别]-[编号].png`
3. 图片大小控制在 2MB 以内
4. 确保图片质量清晰

### 改进文档

- 修正错别字
- 完善说明
- 添加使用技巧
- 翻译成其他语言

### 报告问题

发现问题请创建 Issue，包含：
- 问题描述
- 复现步骤（如适用）
- 建议的解决方案（可选）

## 📝 提示词质量标准

### 必须满足

- ✅ 提示词可以实际使用
- ✅ 已经测试过效果
- ✅ 描述清晰准确
- ✅ 分类正确

### 建议包含

- 💡 推荐参数设置
- 💡 适用场景说明
- 💡 效果预期描述
- 💡 示例图片（如有）

## 🎨 提示词分类指南

### 按模型分类

提示词应放在对应模型目录：
- `prompts/gpt-image-2/` - GPT Image 2
- `prompts/midjourney/` - Midjourney
- `prompts/stable-diffusion/` - Stable Diffusion
- `prompts/dall-e/` - DALL-E 3
- `prompts/flux/` - Flux
- `prompts/ideogram/` - Ideogram

### 按类别分类

也可以按场景分类到：
- `prompts/categories/portrait/` - 人物肖像
- `prompts/categories/landscape/` - 风景景观
- `prompts/categories/abstract/` - 抽象艺术
- `prompts/categories/illustration/` - 插画设计
- `prompts/categories/photography/` - 摄影风格
- `prompts/categories/3d-render/` - 3D渲染

### 按风格分类

或按艺术风格分类到：
- `prompts/styles/anime/` - 动漫风格
- `prompts/styles/realistic/` - 写实风格
- `prompts/styles/oil-painting/` - 油画风格
- `prompts/styles/watercolor/` - 水彩风格
- `prompts/styles/pixel-art/` - 像素艺术
- `prompts/styles/minimalist/` - 极简风格

## ✍️ 提示词写作规范

### 语言规范

- **英文提示词**: 使用标准英语，避免语法错误
- **中文描述**: 提供清晰的中文翻译和说明
- **关键词**: 使用常见和有效的关键词

### 格式规范

```markdown
**提示词**:
```
清晰的提示词内容，一行一个要点
```

**中文描述**: 准确的中文翻译

**推荐参数**:
- 参数名: 值和说明
```

### 命名规范

- 标题简洁明了
- 描述具体场景
- 避免模糊词汇

## 🔍 代码审查流程

提交的 PR 将经过以下审查：

1. **格式检查** - 是否符合模板
2. **内容审查** - 提示词是否有效
3. **分类验证** - 是否放在正确目录
4. **质量评估** - 描述是否清晰

审查通过后会合并到主分支。

## 📜 许可协议

提交内容即表示你同意：
- 你的贡献使用 MIT License
- 你拥有所提交内容的权利
- 允许项目自由使用你的贡献

## 🙏 行为准则

请保持：
- 友善和尊重
- 建设性的反馈
- 包容和开放的态度

不欢迎：
- 攻击性言论
- 骚扰行为
- 垃圾信息

## 💬 交流渠道

- **GitHub Issues**: 问题和建议
- **GitHub Discussions**: 讨论和交流
- **Pull Requests**: 代码和内容贡献

## 🎁 贡献者福利

- 贡献者名单展示
- 项目 Credits 中致谢
- 社区认可和互动

感谢你的贡献！🎉
