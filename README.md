# AIChat-Android

一个轻量级 Android AI 聊天客户端起步项目，使用 Kotlin + Jetpack Compose。

## 当前版本范围

- 原生 Android 聊天界面骨架
- 设置页面入口
- API Key 本地加密存储工具（Android Keystore + AES/GCM）
- GitHub Actions 云端 Debug APK 构建工作流

**说明：** 当前是可继续开发的第一版工程骨架，尚未接入 GPT、Claude、DeepSeek 的真实网络请求，也尚未实现会话数据库、流式输出和 Markdown 渲染。不要把 API Key 提交到 GitHub。

## 构建

在 Android Studio 中打开项目，等待 Gradle Sync 后运行 `app`。

也可以将项目上传到 GitHub，使用 Actions 页面中的 `Build Android APK` 工作流构建 Debug APK。
