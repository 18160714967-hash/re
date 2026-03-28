# 黎紫馨个人简历网站

这是一个个人简历网站，展示了黎紫馨的个人信息、科研实习经历、个人能力和兴趣爱好。

## 部署到 Vercel

### 方法一：通过 Vercel 网页界面部署

1. **创建 GitHub 仓库**
   - 访问 [GitHub](https://github.com/) 并登录
   - 点击 "New repository"
   - 输入仓库名称（例如：`lizixin-resume`）
   - 选择 "Public" 或 "Private"
   - 点击 "Create repository"

2. **上传项目文件**
   - 在仓库页面点击 "Add file" → "Upload files"
   - 选择并上传以下文件：
     - `index.html`
     - `vercel.json`
   - 填写提交信息，点击 "Commit changes"

3. **部署到 Vercel**
   - 访问 [Vercel](https://vercel.com/) 并登录
   - 点击 "New Project"
   - 选择 "Import Git Repository"
   - 找到并选择你刚创建的 GitHub 仓库
   - 点击 "Import"
   - 保持默认设置，点击 "Deploy"
   - 等待部署完成，获取部署链接

### 方法二：使用 Vercel CLI 部署（需要 Node.js 环境）

1. **安装 Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **部署项目**
   ```bash
   vercel
   ```

3. **按照提示完成部署**

## 项目结构

- `index.html` - 主页面文件，包含所有内容和交互逻辑
- `vercel.json` - Vercel 配置文件

## 功能特性

- 响应式设计，适配不同屏幕尺寸
- 页面切换导航
- 个人信息展示
- 科研实习经历展示
- 个人能力展示
- 兴趣爱好照片墙
- 留言功能
- 机器人交互效果
- 烟花特效

## 技术栈

- HTML5
- CSS3
- JavaScript
- Vercel（部署平台）