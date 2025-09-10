# Claude Code Mobile

一个为移动端优化的 Claude Code 助手网页应用。

## 功能特性

- 📱 响应式移动端设计
- 💬 实时聊天界面
- 🎨 深色/浅色主题支持
- ⚡ 快速响应和流畅体验
- 🔧 专业的代码助手功能

## 环境变量

在部署前，请设置以下环境变量：

```
ANTHROPIC_API_KEY=your_anthropic_api_key_here
```

## 本地开发

1. 安装依赖：
```bash
npm install
```

2. 设置环境变量：
创建 `.env.local` 文件并添加你的 API 密钥。

3. 启动开发服务器：
```bash
npm run dev
```

4. 在浏览器中打开 [http://localhost:3000](http://localhost:3000)

## Vercel 部署

1. 将代码推送到 GitHub 仓库
2. 在 Vercel 中导入项目
3. 配置环境变量 `ANTHROPIC_API_KEY`
4. 部署

## 技术栈

- Next.js 14
- TypeScript
- Tailwind CSS
- Anthropic Claude API