# NCC

I build tools for delivering events, working with Android devices, and debugging MCP servers. These three projects are the best place to start. [Personal site](https://tolkmislk.github.io/) · [中文](#中文)

## Projects

- **[Webhook Delivery Platform](https://github.com/TolkmisLK/webhook-delivery-platform)** — Accept events through an API, retry HTTP deliveries, and inspect each attempt in a web console. [Run the local retry walkthrough](https://github.com/TolkmisLK/webhook-delivery-platform/blob/main/docs/demo.md). [v1.0.0 is public](https://github.com/TolkmisLK/webhook-delivery-platform/releases/tag/v1.0.0); receivers must deduplicate events because delivery is at least once.
- **[ADB Device Desk](https://github.com/TolkmisLK/adb-device-desk)** — A Windows desktop tool for checking ADB device states, wireless pairing, APK installation, screenshots, and logs. [Read the setup guide](https://github.com/TolkmisLK/adb-device-desk#readme). Windows CI has built and started the app; clean Windows machine and physical Android device acceptance are still pending. There is no public download yet.
- **[MCP Trace Lab](https://github.com/TolkmisLK/mcp-trace-lab)** — Record MCP stdio requests and responses, then inspect tool calls, errors, and timing. [Run the bundled local example](https://github.com/TolkmisLK/mcp-trace-lab/blob/main/docs/demo.md). Experimental source version; traces may retain sensitive content, so review them before sharing.

### Still in development

- [Mutual Chat](https://github.com/TolkmisLK/mutual_chat) — A Matrix messaging preview with encrypted sessions and local search. Contact identity verification and first backup are unfinished; mobile acceptance is pending.
- [Mutual Transfer](https://github.com/TolkmisLK/Mutual_transfer) — A LAN file workspace with resumable uploads and hash checks. Physical LAN acceptance is pending, and an intermittent Android issue remains under investigation.
- [Personal website template](https://github.com/TolkmisLK/TolkmisLK.github.io) — Edit one configuration file to make a bilingual project page and publish it with GitHub Pages.

## 中文

我做事件投递、安卓设备管理和 MCP 排障工具。想了解这些项目，可以先看下面三个。[个人网站](https://tolkmislk.github.io/) · [English](#ncc)

### 代表项目

- **[Webhook Delivery Platform](https://github.com/TolkmisLK/webhook-delivery-platform)** — 通过 API 接收事件，重试向 HTTP 接口的投递，并在网页控制台查看每次请求。[在本地运行重试演示](https://github.com/TolkmisLK/webhook-delivery-platform/blob/main/docs/demo.md)。[v1.0.0 已公开发布](https://github.com/TolkmisLK/webhook-delivery-platform/releases/tag/v1.0.0)；投递语义为至少一次，接收方需要去重。
- **[ADB Device Desk](https://github.com/TolkmisLK/adb-device-desk)** — 在 Windows 桌面查看 ADB 设备状态，进行无线配对、安装 APK、截图和导出日志。[查看使用准备](https://github.com/TolkmisLK/adb-device-desk#readme)。Windows CI 已完成构建与启动；普通 Windows 电脑和安卓真机验收待完成，目前没有公开下载包。
- **[MCP Trace Lab](https://github.com/TolkmisLK/mcp-trace-lab)** — 记录 MCP stdio 请求与响应，查看工具调用、错误和耗时。[运行仓库内的本地示例](https://github.com/TolkmisLK/mcp-trace-lab/blob/main/docs/demo.md)。目前是实验阶段的源码版本；追踪文件可能保留敏感内容，分享前需要检查。

### 持续开发

- [Mutual Chat](https://github.com/TolkmisLK/mutual_chat) — 基于 Matrix 的加密聊天预览，支持会话恢复和本地搜索。联系人身份验证和首次备份尚未完成，移动端验收待完成。
- [Mutual Transfer](https://github.com/TolkmisLK/Mutual_transfer) — 支持断点续传和文件校验的局域网共享空间。局域网真机验收待完成，间歇性的 Android 故障仍在排查。
- [个人网页模板](https://github.com/TolkmisLK/TolkmisLK.github.io) — 修改一份配置文件，制作中英文项目页面并通过 GitHub Pages 发布。
