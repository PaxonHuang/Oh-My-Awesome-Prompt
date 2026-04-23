我们先看如何安装官方示例:

![[assets/SkiLLs/file-20251224010909286.png]]

### 先升级claude code:

```Plaintext
npm install -g @anthropic-ai/claude-code
```

或者

```Plaintext
claude update
```

然后启动之(到笔者写作的时间点, 最新版本是v2.0.37)

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=NmU5ZmYxYTgyMzZmOGViYzQyMzFmNmM2YTA3ZGViMzFfTlZjeld1bmZJeEVTUm9lVDhYeWMxTmpha2FaWXRCaWZfVG9rZW46WGR5UGJNZ0pMb3lQMXh4YW12QWN0QzFRbmZkXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

### 然后添加市场

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=ZmM3NGZlOWUwZjhiZWI1MTg4ODIzODI2MDcyYzY4ZmJfVE5BdHBtY3N5b0V1cU90cFdJMGpGSjBLTlVOcEtMNVFfVG9rZW46SXRaUWJIRWFXb2w3Q3J4dGhxMGNnUWdOblFnXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

添加市场是第三个选项, Add Marketplace

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=ZThhNzU1MWNjNmRkMjI3NmU5ZmI1YjQ5ODAzZjJjMjBfU2VwZTV4RjJzN2FqZXpuSHhPVTA4eklCaE5IdDY5NWFfVG9rZW46TkhIdGIzeWFZbzdNTkV4UnduN2N4ZGh1blFiXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

### 然后是添加官方示例:

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=MDA2NDhhMzY2ZDc1NGU0MGIxZGMwNmQ3Nzc0ZDA0M2VfQllSYkNwRFpWeThJTjNKWkhPTlNHek93QURZVWplWmxfVG9rZW46RG5EMmJJOEpNb3g5R054TG5rY2NvdkV0blNkXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

这个时候输入是一个官方示例网址:

https://github.com/anthropics/skills

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=OTAxM2YxNjE5OTc0NWJmNjM0Mjc0ZDVkZGIzZDQ5ODdfa1AzdVFEWTFFdVlMeE13UmJZUXh3cTVIOFFhTUtiWmtfVG9rZW46TXpramJ5c3Njb01wNnR4MGVvQ2N4cEVMbnZkXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

可能需要翻墙. 成功后是这样的:

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=MWM2ZTYzNWUyMGI2NDZiMWYyNjQyMDQwNTExNjRhMzNfM0dvckphNzduVHRUTEc1VXJTTE90dTFkNGxaTW9heTlfVG9rZW46RDJ4WWJhYVhrb0ROWjV4cHpDcmNua3ZvbkVoXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

按回车会出现细节, 以及确认添加(Install now)

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=ZTBjYWMxMDg5M2ZhYWFhZDhmYTg5ZmU1NDk0YzA4NmFfZjF3NFNieWdFamVLbGEyRjFnZGxsbzUxS2hPaGNPZnVfVG9rZW46T0swU2J6aFZ6bzRoZm14bm9WZGNLeHJ0bnFmXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=MzA3Y2VkNTZjN2YxOGQyMjZkZTZjN2FjZjMwYjI4ZDJfRzBodEZlbW5BMUMyVXZab0p6TkdzM2dHVFUxdk5pTEJfVG9rZW46UWNQbGJMRjBZb3FMeGN4ZW1rNWNPQmFJbjZjXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

再来一遍可以添加另外一个示例sample.

添加成功后会在.claude文件夹plugins下出现一个叫marketplace的新文件夹:

![img](https://dwkmrfbfkko.feishu.cn/space/api/box/stream/download/asynccode/?code=OWE4ZjY1MTBlYzFiMTVmNTg2MjE4YmQ2ZTA3YjEwYmFfMXNGNldrakttWWRqSGNXeE45TW9sS210V2VsRmZEa1dfVG9rZW46UkZ2dWJybVBQb3VVbk54OG9YWGNxaldjbnhnXzE3NzY5NTgwNTA6MTc3Njk2MTY1MF9WNA)

最后重启一下Claude code就完成了.

### 预装内容:

安装这个示例会包容很多能力：

### 创意设计

- **algorithmic-art** —— 使用带种子随机性的 p5.js，通过流场和粒子系统生成[算法艺术](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=算法艺术&zhida_source=entity)
- **canvas-design** —— 基于设计哲学生成精美的 .png 与 .pdf 视觉作品
- **[slack-gif-creator](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=slack-gif-creator&zhida_source=entity)**
- —— 生成满足 Slack 尺寸约束的动图

### 开发与技术

- **[artifacts-builder](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=artifacts-builder&zhida_source=entity)**
- —— 使用 React、Tailwind CSS 与 shadcn/ui 组件构建复杂的 claude.ai HTML 成品
- **[mcp-server](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=mcp-server&zhida_source=entity)**- —— 指导如何创建高质量的 MCP 服务器，以整合外部 API 与服务
- **[webapp-testing](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=webapp-testing&zhida_source=entity)**
- —— 借助 Playwright 对本地网页应用执行 UI 验证与调试

### 企业与沟通

- **[brand-guidelines](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=brand-guidelines&zhida_source=entity)**
- —— 应用 Anthropic 官方品牌色与字体到各类产出物
- **[internal-comms](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=internal-comms&zhida_source=entity)**- —— 撰写内部沟通材料，如状态更新、内部刊物与常见问题
- **[theme-factory](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=theme-factory&zhida_source=entity)**
- —— 使用 10 套专业预设主题，或即时生成自定义主题以美化产出物

### 元技能

- **[skill-creator](https://zhida.zhihu.com/search?content_id=266302859&content_type=Article&match_order=1&q=skill-creator&zhida_source=entity)**
- —— 指导如何设计扩展 Claude 能力的高效技能
- **template-skill** —— 创建新技能时可用作起点的基础模板

### 文档技能

`document-skills/` 子目录收录的是 Anthropic 为帮助 Claude 生成各类文档格式而设计的技能，展示了处理复杂文件格式与二进制数据的高级范式：

- **docx** —— 创建、编辑与分析 Word 文档，支持修订、批注、格式保持与文本抽取
- **pdf** —— 全面的 PDF 工具箱，可提取文本与表格、创建新 PDF、合并/拆分文档并处理表单
- **pptx** —— 创建、编辑与分析 PowerPoint 演示文稿，支持版式、模板、图表与自动化幻灯片生成
- **xlsx** —— 创建、编辑与分析 Excel 表格，支持公式、格式、数据分析与可视化

### 正式使用

安装插件后，只需提及即可使用该技能。例如，如果你从市场安装了`document-skills`插件，你可以要求 Claude Code 执行类似操作："使用 PDF 技能从 path/to/some-file.pdf 中提取表单字段"

![[assets/SkiLLs/file-20251226125341872.png]]

![[assets/SkiLLs/file-20251226125353925.png]]

![[assets/SkiLLs/file-20251226125401582.png]]

![[assets/SkiLLs/file-20251226125410367.png]]

![[assets/SkiLLs/file-20251226125418145.png]]

![[assets/SkiLLs/file-20251226125430912.png]]

![[assets/SkiLLs/file-20251226125438599.png]]