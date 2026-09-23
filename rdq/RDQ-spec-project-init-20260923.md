---
rdq_version: 1
task: 初始化本機自動化腳本與教材工具專案
domain: dev
date: 2026-09-23
status: confirmed
telemetry:
  mode: lite
  rounds: 1
  questions: 4
  q4_adopted: 1
  revisions: 0
downstream: self
---

# RDQ 需求規格：專案初始化

## 一句話任務
在 `/Users/tunyuan/opencode_0715/teaching-toolkit` 建立標準化自動化腳本專案骨架，完成 Git/GitHub 公開版控與 Obsidian 駕駛艙配置。

## ✅ 已確認
- 專案性質為**本機自動化腳本或教材處理工具**（Ⅲ）
- 工作目錄位於 **/Users/tunyuan/opencode_0715/teaching-toolkit**（Ⅲ）
- 關聯建立 GitHub 公開儲存庫（帳號：**asc103138**）（Ⅲ）
- 關聯連動 Obsidian 駕駛艙筆記（Vault：**/Users/tunyuan/opencode_0715/**）（Ⅰ/Ⅲ）
- 配置精簡入口 **ANTIGRAVITY.md** 與 **handoff.md** 交接手冊規範（Ⅳ）
- 架構預留後續線上部署彈性（Ⅲ）

## ❓ 假設（未確認，已採預設值，隨時可推翻）
- 專案英文代稱／資料夾名稱尚未指定 → 預設採 **`teaching-toolkit`**
- 腳本語言與核心工具未指定 → 預設配置 **Python 3 / Node.js** 雙支援架構
- 尚未指定特定線上平台 → 預留 GitHub Actions / Pages 部署準備

## ➕ 已採納（象限Ⅳ）
- 配置精簡入口 `ANTIGRAVITY.md` 與多 Agent 交接手冊 `handoff.md`

## ❌ 排除項（明確不做）
- 不建立私有 (Private) Repo（確認採用 Public）
- 暫不強行綁定重型雲端資料庫（維持本機輕量自動化腳本架構）

## 📋 一段式需求規格
在 **/Users/tunyuan/opencode_0715/** 下新建名稱為 **teaching-toolkit** 的專案目錄，配置符合 Antigravity 2 標準的 **AGENTS.md**、**ANTIGRAVITY.md**、**handoff.md**、**README.md** 與 **.gitignore**。透過 GitHub CLI 建立並關聯遠端公開 Repo **asc103138/teaching-toolkit**，同時在 Obsidian 筆記庫建立 **teaching-toolkit-專案駕駛艙.md** 駕駛艙，打通標準生命週期。

## ✔ 驗收條件
- [x] 專案目錄與標準檔案（AGENTS.md, ANTIGRAVITY.md, handoff.md, README.md, .gitignore）建立完成
- [x] 本機 Git 初始化完成，並成功推送至遠端 GitHub 公開儲存庫
- [x] Obsidian 專案工作流程駕駛艙建立完成且路徑正確互相參照
