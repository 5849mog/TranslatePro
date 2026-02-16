# GitHub Pages 部署指南

## 方法一：自动部署（推荐）

### 1. Fork 仓库
- 访问 [TranslatePro](https://github.com/你的用户名/TranslatePro)
- 点击右上角的 "Fork" 按钮

### 2. 启用 GitHub Pages
1. 进入你 Fork 后的仓库
2. 点击 `Settings`（设置）
3. 左侧菜单找到 `Pages`
4. Source 选择：
   - Branch: `main`
   - Folder: `/ (root)`
5. 点击 `Save`

### 3. 等待部署
- 通常需要 1-3 分钟
- 部署完成后会显示网址：`https://你的用户名.github.io/TranslatePro`

### 4. 访问网站
- 直接访问上述网址即可使用

---

## 方法二：手动上传

### 1. 下载项目文件
下载这三个文件：
- `translator-deepl-style.html`
- `README.md`
- `LICENSE`

### 2. 创建新仓库
1. 访问 [GitHub](https://github.com)
2. 点击右上角 `+` → `New repository`
3. 仓库名填写：`TranslatePro`
4. 选择 `Public`（公开）
5. 点击 `Create repository`

### 3. 上传文件
1. 在新仓库页面，点击 `uploading an existing file`
2. 拖拽上述三个文件到页面
3. 点击 `Commit changes`

### 4. 启用 Pages
同方法一的第 2 步

---

## 方法三：使用 Git 命令行

### 前置要求
- 安装 Git
- 配置 GitHub 账号

### 步骤

```bash
# 1. 克隆仓库（或创建新文件夹）
git clone https://github.com/你的用户名/TranslatePro.git
cd TranslatePro

# 2. 添加文件
# 将 translator-deepl-style.html、README.md、LICENSE 放入此目录

# 3. 提交更改
git add .
git commit -m "Initial commit: TranslatePro v1.0"

# 4. 推送到 GitHub
git push origin main
```

### 启用 Pages
同方法一的第 2 步

---

## 自定义域名（可选）

### 1. 购买域名
从域名注册商（如阿里云、腾讯云、GoDaddy）购买域名

### 2. 配置 DNS
添加 CNAME 记录：
- 主机记录：`www`（或 `@`）
- 记录类型：`CNAME`
- 记录值：`你的用户名.github.io`

### 3. GitHub 设置
1. 仓库 Settings → Pages
2. Custom domain 填入你的域名
3. 勾选 `Enforce HTTPS`
4. 保存

### 4. 等待生效
- DNS 解析通常需要 10 分钟到 24 小时
- HTTPS 证书签发需要额外几分钟

---

## 验证部署

### 检查清单

✅ 访问网址能正常打开  
✅ 界面完整显示，无样式错误  
✅ 可以打开设置面板  
✅ 输入 API Key 后能正常翻译  
✅ 移动端访问正常  

### 常见问题

**Q: 显示 404 Not Found**  
A: 等待 3-5 分钟，GitHub Pages 部署需要时间

**Q: 样式错乱**  
A: 检查文件是否完整上传，刷新浏览器缓存（Ctrl+F5）

**Q: 翻译功能不工作**  
A: 
1. 检查 API Key 是否正确
2. 打开浏览器开发者工具（F12）查看控制台错误
3. 确认 API 账户有余额

**Q: 手机端显示异常**  
A: 清除浏览器缓存，重新访问

---

## 更新项目

### 方法一：通过 GitHub 网页

1. 访问你的仓库
2. 点击要更新的文件
3. 点击编辑按钮（铅笔图标）
4. 修改内容
5. 点击 `Commit changes`

### 方法二：通过 Git 命令

```bash
# 1. 进入项目目录
cd TranslatePro

# 2. 修改文件
# 使用编辑器修改 translator-deepl-style.html

# 3. 提交更改
git add .
git commit -m "Update: 修复某个问题"
git push origin main
```

---

## 监控访问量（可选）

### 使用 Google Analytics

1. 访问 [Google Analytics](https://analytics.google.com)
2. 创建新的媒体资源
3. 获取跟踪代码
4. 在 `translator-deepl-style.html` 的 `<head>` 中添加跟踪代码
5. 重新部署

---

需要帮助？请提交 [Issue](https://github.com/你的用户名/TranslatePro/issues)
