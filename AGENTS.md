# teaching-toolkit - AGENTS.md

## 專案資訊
- **專案名稱**：teaching-toolkit（教學自動化腳本與教材處理工具包）
- **專案用途**：提供教師在教學與行政上的本機自動化腳本、文件批次處理、教材生成與格式轉換工具。
- **主要工作目錄**：`/Users/tunyuan/opencode_0715/teaching-toolkit`
- **GitHub Repo**：[https://github.com/asc103138/teaching-toolkit](https://github.com/asc103138/teaching-toolkit)

## Obsidian 關聯筆記
- **Vault 路徑**：`/Users/tunyuan/opencode_0715`
- **專案駕駛艙**：`/Users/tunyuan/opencode_0715/04-專案/teaching-toolkit-專案駕駛艙.md`

## 工作與安全規則
- 回應使用繁體中文（台灣）。
- **開工流程**：讀取本檔、讀取 `handoff.md`、讀取 Obsidian 專案駕駛艙、檢查 `git status` 與最近變更。
- **收工流程**：掃描敏感金鑰與隱私資料、更新 Obsidian 駕駛艙、更新 `handoff.md`、精準 stage 並經確認後 commit 與 push。
- **資安與個資合規**：
  - 嚴禁 commit API Key、Token、密碼或個人隱私資料。
  - 學生資料僅記錄班級代號與座號，不儲存真名。
  - 敏感環境設定抽離至 `.env`，不得推送到公開 Repo。
