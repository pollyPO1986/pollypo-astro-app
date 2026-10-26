# CLAUDE.md — pollypo-astro-app

語言硬規則：全程使用正體中文（台灣）回覆；若你正用英文，立即切回。

## 專案事實

- **框架**：Astro（content-driven websites 的 web framework）`^7.4.2`；Node `>=24.22.1`。
- **樣式／語言**：SASS `^1.106.1` ＋ TypeScript `^7.0.2`（`devDependencies`，以 `package.json` 為準）。
- **指令**：`npm run dev`／`build`／`preview`（定義見 `package.json`）。
- **dev server**：依 `AGENTS.md`，用 `astro dev --background` 啟動，以 `astro dev stop／status／logs` 管理。
- **查 Astro 用法**：優先用 `.mcp.json` 的 `astro-docs` MCP 或 https://docs.astro.build，不要憑記憶猜 API。

## 工作流

個人工作流制度（rules／skills／筆記架構）由 `claude-workflow` 佈署，入口與路由表見下方 import 的個人層檔案 §0。新 session 開工打 `/ko`。

@~/.claude/personal/pollypo-astro-app.md
