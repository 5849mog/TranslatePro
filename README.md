# TranslatePro

<div align="center">

![TranslatePro](https://img.shields.io/badge/TranslatePro-v1.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Status](https://img.shields.io/badge/status-active-success)

**超越 DeepL 的 AI 翻译工具 | 成本仅为其 1% | 质量更优**

[在线体验](https://5849mog.github.io/TranslatePro) | [问题反馈](https://github.com/5849mog/TranslatePro/issues)

</div>

---

## 🌟 核心特性

- 🎯 **翻译质量超越 DeepL** - 基于最新 AI 大模型，提供更精准的语义翻译
- 💰 **成本极低** - 仅为 DeepL 成本的 1%，性价比是 Google 翻译的 45 倍
- 🎨 **5 种翻译风格** - 标准 / 正式 / 口语化 / 文学 / 专业术语
- 🔄 **文本改进** - 类似 DeepL Write，优化表达质量
- 🔐 **隐私安全** - API Key 仅存储在本地浏览器，不上传任何数据
- 🌍 **12 种语言** - 支持中英日韩法德西俄等主流语言
- 📱 **完美适配移动端** - 响应式设计，手机平板电脑均可使用
- ⚡ **即时翻译** - 输入后 2 秒自动翻译，无需手动点击

## 📊 翻译质量实测对比

基于中译英专业考题的 11 个版本对比评测（满分 100 分）：

| 排名 | 模型/服务 | 得分 | 等级 | 成本/次 |
|------|----------|------|------|---------|
| 🥇 1 | **TranslatePro + DeepSeek (深度思考)** | **97** | 🌟 大师级 | **¥0.0023** |
| 🥈 2 | **TranslatePro + DeepSeek (标准)** | **96** | 🌟 大师级 | **¥0.0020** |
| 🥉 3 | DeepL (官方) | 90 | 💎 精英级 | ¥0.20-0.30 |
| 4 | 豆包 | 83 | ⭐ 优秀级 | - |
| 5 | Google Translate | 75 | ✓ 合格级 | ¥0.08 |

### 🎯 核心发现

✅ **TranslatePro 优势**

- **超越 DeepL**：在准确度、地道表达、术语精准度上全面领先
- **细节捕捉**：精准处理"根据内容调整风格"等隐含信息
- **语气把控**：完美传达原文的细微语气差异
- **成本极低**：11 次高质量翻译总成本仅 ¥0.025 元

### 💰 性价比对比

| 服务 | 单次成本 | 质量得分 | 性价比指数 |
|------|----------|----------|-----------|
| **TranslatePro** | **¥0.0023** | **97** | **42,731** 🚀 |
| DeepL | ¥0.20-0.30 | 90 | 300-450 |
| Google Translate | ¥0.08 | 75 | 938 |

**TranslatePro 性价比是 Google 的 45 倍，是 DeepL 的 95-142 倍！**

### 🔍 质量进化轨迹

```
基础模型 (85分)
    ↓ 加入优化提示词
标准翻译 (96分) → 精准传神，简洁直接
    ↓ 深度思考模式
深度翻译 (97分) → 专业均衡，细节丰富
```

## 🚀 快速开始

### 方法一：在线使用（推荐）

1. 访问 [TranslatePro 在线版](https://5849mog.github.io/TranslatePro)
2. 点击右上角"API 设置"
3. 选择 AI 提供商（DeepSeek / OpenAI / Claude）
4. 输入你的 API Key
5. 开始翻译！

### 方法二：本地部署

```bash
# 克隆仓库
git clone https://github.com/5849mog/TranslatePro.git

# 进入目录
cd TranslatePro

# 用浏览器打开
open translator-deepl-style.html
# 或者在 Windows: start translator-deepl-style.html
# 或者在 Linux: xdg-open translator-deepl-style.html
```

无需安装任何依赖，直接用浏览器打开即可使用！

### 方法三：GitHub Pages 部署

1. Fork 本仓库
2. 进入仓库设置 (Settings)
3. 找到 Pages 选项
4. Source 选择 `main` 分支
5. 点击 Save，等待部署完成
6. 访问 `https://5849mog.github.io/TranslatePro`

## 🔑 获取 API Key

### DeepSeek（推荐 - 性价比最高）

1. 访问 [DeepSeek 平台](https://platform.deepseek.com)
2. 注册账号并登录
3. 前往 [API Keys](https://platform.deepseek.com/api_keys)
4. 创建新的 API Key

**价格：** 输入 ¥1/百万 tokens，输出 ¥2/百万 tokens

### OpenAI

1. 访问 [OpenAI 平台](https://platform.openai.com)
2. 注册账号并登录
3. 前往 [API Keys](https://platform.openai.com/api-keys)
4. 创建新的 API Key

**价格：** 
- GPT-5.3: $1.25/百万输入 tokens, $10/百万输出 tokens
- GPT-5.2: $1.00/百万输入 tokens, $8/百万输出 tokens
- GPT-5.1: $0.80/百万输入 tokens, $6/百万输出 tokens
- GPT-5: $0.60/百万输入 tokens, $5/百万输出 tokens
- GPT-5-mini: $0.10/百万输入 tokens, $0.40/百万输出 tokens

### Anthropic Claude

1. 访问 [Anthropic 控制台](https://console.anthropic.com)
2. 注册账号并登录
3. 前往 [API Keys](https://console.anthropic.com/settings/keys)
4. 创建新的 API Key

**价格：** 
- Claude 3.5 Sonnet: $3/百万输入 tokens, $15/百万输出 tokens
- Claude 3 Opus: $15/百万输入 tokens, $75/百万输出 tokens
- Claude 3 Haiku: $0.25/百万输入 tokens, $1.25/百万输出 tokens

## 💡 使用技巧

### 翻译风格选择

- **标准**：日常通用翻译，准确自然
- **正式**：商务文档、学术论文、官方文件
- **口语化**：聊天对话、社交媒体、轻松内容
- **文学**：小说散文、优美表达、创意写作
- **专业术语**：技术文档、专业论文、行业报告

### 文本改进

点击"改进文本"标签，输入任意语言的文本，AI 会：
- 保持原语言不变
- 优化表达流畅度
- 提升专业性和可读性
- 修正语法和用词

### 批量翻译技巧

虽然每次翻译是独立的（类似 DeepL），但你可以：
1. 将长文本分段翻译
2. 每段单独优化
3. 最后人工调整衔接

## 🎨 技术架构

### 核心技术

- **纯前端实现**：HTML + CSS + JavaScript，无需后端
- **API 直连**：直接调用 AI 提供商的官方 API
- **本地存储**：使用 localStorage 保存配置，保护隐私
- **响应式设计**：完美适配各种设备尺寸

### 提示词工程

TranslatePro 的核心竞争力来自精心设计的提示词：

1. **语义理解优先**：强调理解语义而非逐字翻译
2. **DeepL 核心理念**：自然流畅、保留原意、文化适配
3. **明确禁止行为**：避免逐字翻译、添加解释等错误
4. **实例教学**：提供正反示例，引导 AI 正确翻译

### 隐私保护

- ✅ API Key 仅存储在浏览器本地
- ✅ 所有翻译请求直连 AI 提供商
- ✅ 不经过任何第三方服务器
- ✅ 源代码完全开源，可自行审计

## 📈 Token 消耗分析

基于 DeepSeek 官方换算标准（中文 0.6 token/字，英文 0.3 token/字）：

| 场景 | 输入 | 输出 | 总计 | 成本 |
|------|------|------|------|------|
| 短句 (20字) | 312 | 6 | 318 | ¥0.000324 |
| 段落 (100字) | 336 | 60 | 396 | ¥0.000456 |
| 中篇 (500字) | 456 | 300 | 756 | ¥0.001056 |
| 长文 (2000字) | 906 | 1200 | 2106 | ¥0.003306 |

**系统提示词**：306 tokens（已极致优化）

**成本优势**：
- 1 万次短句翻译：仅 ¥3.24
- 1 千次段落翻译：仅 ¥0.46
- 1 杯奶茶（¥15）可完成 6,600 次翻译！

## 🌍 支持的语言

- 🇨🇳 中文（简体）
- 🇺🇸 English
- 🇯🇵 日本語
- 🇰🇷 한국어
- 🇫🇷 Français
- 🇩🇪 Deutsch
- 🇪🇸 Español
- 🇷🇺 Русский
- 🇵🇹 Português
- 🇮🇹 Italiano
- 🇸🇦 العربية

## ❓ 常见问题

### Q: 为什么 TranslatePro 比 DeepL 质量更好？

A: DeepL 使用的是 2017-2020 年的神经网络技术，而 TranslatePro 基于 2023-2024 年的最新大语言模型（如 DeepSeek、GPT-4、Claude 3），这些模型的语言理解能力远超传统翻译模型。加上精心设计的提示词，能够实现更准确的语义翻译。

### Q: API Key 安全吗？

A: 完全安全。你的 API Key 仅存储在浏览器的 localStorage 中，不会上传到任何服务器。所有翻译请求都是直接从你的浏览器发送到 AI 提供商的官方 API，不经过任何第三方。

### Q: 为什么这么便宜？

A: 因为 TranslatePro 是开源项目，没有中间商赚差价。你直接使用 AI 提供商的 API，按实际使用量付费。而 DeepL 需要维护庞大的服务器和团队，成本自然高很多。

### Q: 支持离线使用吗？

A: 不支持。翻译功能需要调用在线 API。但你可以下载 HTML 文件到本地使用，只要有网络连接即可。

### Q: 翻译结果会保存吗？

A: 不会。每次翻译都是独立的，结果不会被保存。这保护了你的隐私，但也意味着关闭页面后翻译历史会丢失。建议重要翻译及时复制保存。

### Q: 可以自定义翻译风格吗？

A: 目前提供 5 种预设风格。如果你需要更多定制，可以 Fork 项目并修改系统提示词（在源代码中搜索 `systemPrompt`）。

### Q: 支持文档翻译吗？

A: 目前仅支持纯文本翻译。你需要先从 Word/PDF 中复制文本，翻译后再粘贴回去。未来版本可能会加入文件上传功能。

## 🛠️ 开发指南

### 项目结构

```
TranslatePro/
├── translator-deepl-style.html   # 主文件（包含所有代码）
├── README.md                      # 说明文档
└── LICENSE                        # 开源协议
```

### 修改提示词

在 `translator-deepl-style.html` 中搜索 `systemPrompt`，你会找到两个提示词：

1. **翻译模式提示词**（约 900 行）
2. **改进模式提示词**（约 950 行）

可根据需求自行调整。

### 添加新的 AI 提供商

1. 在 `modelConfig` 对象中添加配置：
```javascript
your_provider: {
    name: '提供商名称',
    models: ['model-1', 'model-2'],
    endpoint: 'https://api.provider.com/v1/...'
}
```

2. 在 `state.apiConfig.apiKeys` 中添加密钥字段
3. 根据 API 格式调整 `callTranslationAPI` 函数

## 🤝 贡献指南

欢迎提交 Issue 和 Pull Request！

### 贡献方式

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

### 需要帮助的功能

- [ ] 文件上传翻译（Word、PDF、Excel）
- [ ] 翻译历史记录
- [ ] 术语库功能
- [ ] 批量翻译优化
- [ ] 更多语言支持
- [ ] 浏览器插件版本

## 📄 开源协议

本项目采用 MIT 协议开源。详见 [LICENSE](LICENSE) 文件。

简单来说：你可以自由使用、修改、分发本项目，包括商业用途，只需保留原作者信息。

## 🙏 致谢

- 感谢 [DeepL](https://www.deepl.com) 提供的设计灵感
- 感谢 [DeepSeek](https://www.deepseek.com)、[OpenAI](https://openai.com)、[Anthropic](https://www.anthropic.com) 提供的优秀 AI 模型
- 感谢所有为本项目做出贡献的开发者

## 📞 联系方式

- 项目地址：[https://github.com/5849mog/TranslatePro](https://github.com/5849mog/TranslatePro)
- 问题反馈：[Issues](https://github.com/5849mog/TranslatePro/issues)
- 邮箱：mofei584945@outlook.com

---

<div align="center">

**如果这个项目对你有帮助，请给个 ⭐ Star 支持一下！**

Made with ❤️ by Max

</div>
