# 🏴‍☠️ ルフィとの航海 — One Piece AI Chat

路飞 AI 对话聊天网页。日语 + 中文翻译，DeepSeek API 驱动。

## 🚀 部署到 GitHub Pages

### 方法一：一键部署（推荐）

1. 访问 [GitHub](https://github.com) 创建一个新仓库
2. 将本文件夹内容推送到仓库：

```bash
git init
git add .
git commit -m "first commit"
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin main
```

3. 进入仓库 Settings → Pages
4. Source 选择 **Deploy from a branch**
5. Branch 选择 `main`，目录选择 `/ (root)`
6. 点击 **Save**
7. 等待 1-2 分钟，你的页面就会出现在 `https://你的用户名.github.io/你的仓库名`

### 方法二：使用 GitHub Desktop

1. 下载 [GitHub Desktop](https://desktop.github.com/)
2. 登录 GitHub 账号
3. File → New repository → 取名 → Create
4. 把本文件夹的文件复制进去
5. Commit + Publish
6. 仓库 Settings → Pages → 开启 GitHub Pages

## 🔧 如何使用

1. 打开页面后，点击右上角 ⚙️ 设置
2. 输入你的 **DeepSeek API Key**
3. 点击保存
4. 路飞会自动打招呼！开始聊天吧 🎉

## 📌 注意事项

- API Key 仅保存在你的浏览器本地存储（localStorage），不会上传到任何服务器
- 需要 DeepSeek API 密钥，可在 [platform.deepseek.com](https://platform.deepseek.com) 获取
- 目前使用 `deepseek-chat` 模型

## 💡 功能

- 路飞角色扮演 AI 对话（日语 + 中文翻译）
- 🏴‍☠️ 路飞标志性台词和语气
- 🗣️ 自动聊海贼王世界的话题
- ⏰ 45 秒无操作后路飞会主动发起话题
- ⚙️ 可配置 API Key、模型、Endpoint
- 📱 适配手机端

---

*想要当海贼王吗？那就出海吧！*
***End of File
