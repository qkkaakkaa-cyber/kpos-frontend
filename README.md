# KPOS 前端对接包

下载同目录的 `kpos-frontend-source.zip` 并解压。`webui/kpos-desktop` 是新版界面，`webui/kpos-web` 可用于参考现有接口接法。

新版仍需完成真实后端对接。KPOS 正式服务的 API 基址为 `https://kpos.com/api/mobile/v1`。`GET /health` 可用来检查服务状态，`GET /me` 需要登录。

在 `webui/kpos-desktop` 运行 `npm ci`、`npm run typecheck` 和 `npm run build` 可验证前端构建。
