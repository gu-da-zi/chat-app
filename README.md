# Chat Application with ChatEngine and OpenAI

本项目旨在使用 ChatEngine 和 OpenAI 构建聊天应用程序。前端使用 ChatEngine 构建聊天应用程序，Redux Toolkit 进行状态管理，Redux Toolkit Query 用于 API 调用，Hero 图标库用于图标显示，React Router 用于导航。后端使用 Node.js 作为运行时，Express.js 作为后端框架，并使用 OpenAI 进行 AI 集成。用户可以通过聊天应用程序与 ChatGPT 进行交互对话。

## 前置条件

- Node.js (v12+)
- Git
- OpenAI API Key (可在[OpenAI 官网](https://openai.com/)注册并获取)

## 安装

1. 克隆此项目

```bash
git clone https://github.com/gu-da-zi/chat-app.git
```

2. 进入项目文件夹并安装依赖

```bash
cd chat-app/client
cd chat-app/server
npm install
```

3. 在 client 文件夹中创建`.env.local`文件，设置您的 ChatEngine 项目 密钥：

```
VITE_PROJECT_ID=<your-api-key>
```

1. 在 server 文件夹中创建`.env`文件，设置您的 OpenAi Key 密钥：

```
VITE_PROJECT_ID=<your-api-key>
```

5. 启动应用程序

```bash
npm run dev
node index.js
```

## 技术栈

- 前端：ChatEngine, React, Redux Toolkit, Redux Toolkit Query, Hero Icons, React Router
- 后端：Node.js, Express.js, OpenAI

## 贡献

欢迎贡献您的代码，让这个项目变得更加完善！如果您想要进行贡献，请按照以下步骤：

1. Fork 此项目
2. 创建您的分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交拉取请求

## 许可证

本项目使用[MIT 许可证](https://opensource.org/licenses/MIT)。
