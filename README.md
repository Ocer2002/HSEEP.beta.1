# HSEEP 演習規劃工作台 · Exercise Planner — Release Notes（v0.3 → v0.9 beta）
張維達 Wei Ta Chang（AEIF）｜🐞 問題回報 Report issues: cyfd026@gmail.com｜單一 HTML 檔・離線可用 Single-file, offline-first

---

## v0.9 beta（2026-07）— 簡報與發布整備 Briefing & Launch Readiness

**中文**
- 📱 **簡報模式**：一鍵產生唯讀演習摘要（危害、情境、任務領域、目標、九階段完成度條），手機遞給長官直接看；「列印」僅輸出簡報頁，適合會議書面資料。
- 🐞 **問題回報**：頂欄蟲圖示、⌘K 指令、使用說明內連結三處入口，郵件自動帶入版本與環境資訊。
- 🌐 **語言切換全面延伸**：English／中文現涵蓋啟動頁、世界地圖、側欄、授權畫面、說明章節標題、⌘K 與情境實驗室（表單與目標維持中英對照，屬設計）。
- ✍️ **160 則 SMART 目標全面校訂**：改用白話（去除 ICS-201/205、COML、PAR、START、THIRA 等術語）、時限貼近實務（如收容所備援供電 30→60 分鐘）。
- 🇹🇼 **臺灣用語總體檢**：匯報→回報、反餽→回饋、熱洗→即時檢討（Hotwash）、態勢板→狀況板、防護崗→警戒哨等 19 處修訂；13 項大陸用語標記全數零檢出。
- 🖨️ 列印樣式表（去除介面元素）、📖 使用說明新增 What's New、📱 手機輸入不再放大跳動（<760px 字級 ≥16px）、程式清理與 v0.9 測試清單。

**English**
- 📱 **Briefing Mode**: one-tap read-only exercise summary (hazard, scenario, mission areas, objectives, nine-stage readiness bars) — hand your phone to a senior officer, or Print to get a clean paper handout (briefing page only).
- 🐞 **Problem reporting** from three places (top bar, ⌘K, in-app guide); emails pre-fill version and environment info.
- 🌐 **Language switch extended** across all navigation chrome — launcher, world map, rail, license screen, guide section headers, ⌘K, and the Scenario Lab (forms and objectives stay bilingual by design).
- ✍️ **All 160 SMART objectives revised** for plain language (ICS form numbers and acronyms removed) and realistic first-hour timings.
- 🇹🇼 **Taiwan terminology audit**: 19 fixes aligning wording with Taiwan emergency-management usage; zero hits across 13 mainland-usage markers.
- 🖨️ Print stylesheet, 📖 in-app What's New, 📱 mobile inputs no longer trigger iOS zoom, code cleanup, and an updated v0.9 manual test plan.

---

## v0.8 beta（2026-07）— 世界地圖與情境實驗室 World Map & Scenario Lab

**中文**
- 🗺️ **真實世界地圖之旅**：以實際大陸海岸線繪製，九大階段對應九座城市與地標（台北101、東京鐵塔、雪梨歌劇院、金門大橋、自由女神、大笨鐘、桌山、濱海灣、寶塔），卡通疊圖風（亮色海洋、沙灘描邊、山丘樹木、船與飛機、雲朵），鏡頭平滑縮放跟隨，跨換日線正確環繞；修正橫貫地圖的接縫直線與地名重疊、凍結等問題。
- 🧪 **情境實驗室**：17 種災害（含颱風、地震、土石流、輻射、動植物疫災、爆炸物攻擊、森林火災、海洋污染…）× 32 項 FEMA 核心能力（附代表圖示）→ 自動生成針對性情境；**SMART 目標庫每項能力 5 則、共 160 則**，勾選後一鍵匯入建立新演習，直接落在第 1 階段供向長官初報。啟動頁、側欄、⌘K 三入口。
- ⌘K **快速跳轉**：搜尋並跳至任一階段、切換演習、執行常用動作。
- ✅ **階段完成度**：每階段頂部即時顯示達成/缺項條件。
- 🌐 啟動頁 **English／中文** 選擇（記憶偏好）；作者署名統一加註（AEIF）。

**English**
- 🗺️ **A real world-map journey**: actual continent coastlines, nine stages mapped to nine cities with hand-drawn landmarks, cartoon-overworld art (bright sea, sandy coasts, hills/trees, ships & planes, clouds), smooth camera follow with a proper date-line wrap; fixed the cross-map seam line, label collisions, and a freeze bug.
- 🧪 **Scenario Lab**: 17 hazards × 32 FEMA core capabilities (with icons) → auto-composed scenarios; a **SMART objective bank of 5 per capability (160 total)** — tick your picks and import as a new exercise landing on Stage 1 for the initial leadership briefing. Three entry points (launcher, rail, ⌘K).
- ⌘K **Quick Jump** command palette; ✅ **Stage Readiness** checklists on every stage; 🌐 launcher **English／中文** selector (remembered); author credit updated with (AEIF).

---

## v0.5–0.7（開發期累積，未正式編號 · development builds, unnumbered）— 專業化與旅程 Professionalization & the Journey

**中文**
- 📋 AAR/IP 導入 **POETE 架構**、SMART 目標檢核器、情境地圖上傳、SVG 標誌、即時統計列與動畫細節打磨。
- 🎮 **旅程地圖初版**：關卡式版圖、9 種機關角色（消防、警察、國軍、醫療、搜救犬…）採 3/4 視角卡通風，行走／慶祝動態、金色完成軌跡、鍵盤完整操作（含減少動態支援）。

**English**
- 📋 **POETE framework** in AAR/IP, SMART objective validator, scenario-map upload, SVG logo, live stats bar and animation polish.
- 🎮 **Journey map v1**: level-style board with 9 original agency avatars (fire, police, military, medic, USAR dog…) in a 3/4 cartoon style, walk/celebrate animations, golden completed-path trail, full keyboard access with reduced-motion support.

---

## v0.4 beta（2026-06）— 資料安全 Data Safety

**中文**：加密亂數 ID、localStorage 損毀復原、刪除可復原、**備份／還原**、Ctrl+S 快捷鍵與儲存狀態列（含容量指示）。
**English**: crypto-random IDs, localStorage corruption recovery, undo-delete, **backup/restore**, Ctrl+S shortcut with a persist-status bar and storage meter.

---

## v0.3 beta（2026-06）— 首發 Initial Release

**中文**：九階段 HSEEP 演習規劃流程、雙語單檔架構、多演習資料庫、FEMA 32 核心能力選單、研討型／實作型分流、Excel/CSV 匯出入、四款主題。
**English**: the nine-stage HSEEP planning lifecycle in one bilingual offline HTML file — multi-exercise library, FEMA 32 core-capability picker, discussion/operations branching, Excel/CSV import-export, four themes.

---

版權所有 © 2026 張維達 Wei Ta Chang（AEIF）· All rights reserved.
