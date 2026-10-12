# Agent Instructions

## Google Drive Build 交付規範（所有 Agent 必須遵守）
- 此 Repo 的 Build 專屬 Google Drive 為 `AI Project/zstellar/`，名稱必須與 GitHub Repository 同名（AI Project folder ID `1Yhfro6Ss5TSCXCVIZIHEu5h7V1gL8b27`）；不在 AI Project 根目錄散放壓縮包。
- **最新完整且已驗證的 Build 直接放專案根目錄**：ZIP／EXE、SHA-256、所有分割檔、必要還原／安裝工具一併上傳；不同平台最新版本可並存。檢查 Drive 檔名、parent、大小、checksum；缺 ZIP 或分片、只有 checksum 的新版不完整，不得取代前一完整版本。
- **僅重要功能、架構、重大美術或平台相容性差異才另建 `vX.Y.Z-說明/`** 保存版本；普通舊版非破壞性移到 `歷史封存/`，不刪除，不每次 Build 建版本資料夾。
- 所有新開發推送 GitHub；昂貴 Actions Build／發布優先 `workflow_dispatch` 或 `release: published`，不要每次 push main 都觸發。只有實際 Build 成功、測試、上傳驗證後才宣稱完成，並回報專案連結、版本與校驗。
**English:** Current verified complete build(s) directly in `AI Project/zstellar/`; milestones under version folders only for substantial differences, routine older versions in `歷史封存/`; never promote incomplete files.
