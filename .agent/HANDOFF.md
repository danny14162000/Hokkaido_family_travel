# Handoff

## 2026-07-11：7/15、7/18 時間已重排

- 7/15：15:00 大通公園、15:30 狸小路、18:00 湯咖哩；Parfaiteria PaL 改約 19:15、回 CHALEUR 改約 20:15。
- 7/18：不在上午分組，退房後全員先在札幌市中心自由活動至 15:30；萬萬名組再搭與大姨丈組同時段的 Airport JR 前往 CTS，留下 5 人才前往 home.g。
- `#jr-sapporo-airport-0716` 現為 7/16、7/18 共用機場 JR 小卡；home.g 卡與航班總覽已同步。
- 本次尚未 commit／push。

## 2026-07-11：なごやか亭評論導向改寫

- 神宮茶屋卡片與當日行程已移除「參拜／境內」等宗教導向用語，改成散步與附近描述。
- なごやか亭白石本通店已依近期評論改寫：魚料厚大新鮮、北海道海鮮、平板出餐快與服務；卡片也有具體點餐和候位／分桌方向。
- 本次尚未 commit／push。

## 2026-07-11：神宮茶屋評論摘要已寫入

- 神宮茶屋卡片已依 Google Maps 評論摘錄改寫：福レ餅為現烤主角、外脆內 Q，霜淇淋也常被推薦；定位為參拜後短暫補給，並保留排隊、少量座位與戶外烏鴉提醒。
- 本次尚未 commit／push。

## 2026-07-11：Notion「wait to do 2」已套用

- 現行 `hokkaido-travel-guide.html` 已完成 Notion「wait to do 2」的內容、圖片與連結調整。
- 新增本地圖片：`notion-parfaiteria-pal.png`、`notion-chaleur.png`、`notion-home-g.png`、`notion-jingu-chaya.png`、`notion-nagoyakatei-shiroishi.png`。
- 7/15 第一次出現 CHALEUR 時已有住宿卡與地圖；7/18 home.g 卡也已有圖片與地圖。
- 森彦本店已完全改為神宮茶屋；萬萬新組已完全改為萬萬名組；白色戀人相關狀態改為待決定。
- 7/17 JR 改成全員一起搭，7/18 自由活動可再逛狸小路或地下街，7/20 兩個回程航班標題不再連到航班總覽。
- 本次尚未 commit／push；發布時只 stage 這次確認的 HTML、5 張新增圖片與必要 `.agent/` 記憶檔。

## 2026-07-11：去程航班卡標籤

- 航班總覽去程卡現在顯示 `2026/07/13 · Thai Lion Air`；航空公司名稱跟其他航班一樣放在日期／組別小標籤後方，說明句不再重複航空公司名稱。

## 2026-07-10：颱風改期版 HTML 已在本機完成

- Notion「wait to do」的最新指示已套用：7/17 17:00 到南小樽站、17:21 搭函館本線普通車往白石，Google Maps 使用 `https://maps.app.goo.gl/kzvjjtU1NYGWHdJD6`。
- 7/16 大姨丈組已在行程表與航班區連到 `#jr-sapporo-airport-0716`：可選 15:30 特別快速 Airport 128（16:06 抵達 CTS）或 15:33 區間快速 Airport 130（16:17 抵達 CTS）。
- 「尚待確認／預約」共用卡已移除；哲哲組 SL393 不再 highlight，也不顯示「泰國萊昂航空 · 直飛」，版型與其他返台組相同。
- 回程現在分四組：大姨丈組 7/16 TR893、萬萬新組 7/18 TR893、綸倫組 7/20 BR115、哲哲組 7/20 SL393（CTS → KHH）；航班總表與三個日期的每日行程均已同步。
- 7/15 抵達 CHALEUR 只標示「11:00 後寄放行李」，不再把約 13:30 寫成入住完成。
- 7/15 晚間甜點已指定為夜パフェ専門店 Parfaiteria PaL（パフェテリア パル），行程表可跳到店家卡，並使用使用者提供的 Google Maps 短網址。
- 現行 `hokkaido-travel-guide.html` 已依使用者提供的 `hokkaido-itinerary-replan.md` 重建為 2026/07/13–07/20 八天版本，仍沿用 Garden field-guide 設計、每日頁籤、景點卡、地圖按鈕、緊湊版與列印互動。
- 去程為 7/13 SL392：KHH 10:50 → CTS 16:00（Thai Lion Air，飛行約 4 小時 10 分）；回程不再用單一航班或單一路徑概括，應按四組與三個日期顯示。
- 已重排全部每日動線；森彦本店明確標示 4 人一組／10 人需分流；なごやか亭只保留白石本通店，沒有沿用錯誤分店照片。
- 白色戀人改為 7/19、5 人手作、暫排 15:20，票券區標示待改期；7/14 洞爺湖固定分乘約 3 台計程車，7/17 小樽改搭 JR 往返，7/20 機場接送仍待預約。
- 7/13 乃之風自助餐依官方 FAQ 標示最晚點餐 20:30；以約 17:00 出關、17:30 上車、1 小時 30 分車程計，約 19:00 可抵達用餐。
- 舊 7/10–7/12 行程、VZ570、CI131、JX851、發寒店、札幌啤酒博物館與舊首日 JR 小卡已從現行 HTML 移除。
- 靜態驗證：8 tabs / 8 panels、無重複 ID、無缺少錨點／圖片、舊詞搜尋為零、內嵌 JS 可解析、標籤成對、`git diff --check` 通過。
- in-app browser 安全政策阻擋 `file://` 自動導覽，因此視覺與 console 尚未自動驗證；下一步應讓使用者刷新本機頁面確認，確認後才可依發布 runbook commit／push 到 `main`。
- 本次未 commit、未 push；工作樹另有其他 unrelated dirty / untracked 檔，發布時只 stage `hokkaido-travel-guide.html` 與使用者確認要納入的設計文件。

## 2026-07-09：Garden Skill 設計基準

- 已查證舊 Codex thread「按日期排序北海道行程」（`019ee91c-26cb-74e0-9751-767db533cb44`）。
- 該 thread 明確提到「再以 garden-skills 的原則設計一遍卡片圖片」；後續卡片設計原則是圖片與內容一起構成旅行卡片，重點景點／商品要清楚，而不是只保留完整未裁切圖片。
- 使用者於 2026-07-09 再次確認：之後旅遊網站設計都用 Garden Skill 原則；除非使用者明確要求換風格，不要重新選 visual direction。
- `DESIGN.md` 與 `.agent/DECISIONS.md` 已記錄：後續網站視覺調整以 Garden Skill 原則為基準；`web-design-engineer` 或 Open Design 只是執行工具，不能取代這個設計判斷。

## 2026-07-05：GitHub Pages 發布規則

- 網站內容經使用者確認後，應直接進入 `main`，不得只留在分支或 PR。
- 發布完成需確認 GitHub Pages workflow 成功，並從公開 URL 驗證新內容。
- Push 後若公開頁仍是舊內容：先查 raw GitHub main 是否已更新，再查 `pages build and deployment` workflow / deployment statuses。raw 新、workflow queued/in_progress 時是 Pages 延遲，等待即可，不要重推或重新分析。
- 本 repo 工作樹常有 unrelated dirty / untracked 檔；發布時只 stage intended files，避免 `git add .`。
- 札幌買衣資訊已由 PR #2 合併至 `main`，提交為 `ce6d4c3`。

## 2026-07-09：航班資訊本機更新待確認

- `hokkaido-travel-guide.html` 已在本機把「大姨丈組／主要組」分開顯示的航班資訊去掉。
- 航班表改為「航班資訊」：去程同班；回程列 CI131 與哲哲組 JX851。
- 哲哲組 JX851 已依 Garden Skill 原則重設為 postcard / field-note 卡片：保留「哲哲組｜晚回程」標籤，加入柔和紙張背景與郵戳感；午餐購物與同包車交通提醒已依使用者要求移除。
- 7/11 行程路線、時間表與景點卡順序已調整為「北之寶 → 北之漁場」。
- 已直接推送到 `main`：`caabe5b`（`Update Hokkaido guide itinerary and flight notes`）。
- GitHub Pages workflow 已成功，公開 URL 已驗證新內容。

## 歷史：2026-07-09 7/10 JR 搭乘小卡（已被改期版取代）

- 已在 7/10 行程表後新增 Garden-style `JR 搭乘小卡`，說明新千歲機場 → 小樽快速 Airport 35：4 號車 U-seat 是指定席，其餘車廂作自由席使用；Suica / PASMO / ICOCA / Kitaca 可用於基本車資。
- 行程表「新千歲機場 → 小樽 JR」已改成連到 `#jr-airport-otaru`，跟景點卡一樣可點擊跳轉。
- 已新增小樽 → 札幌 CHALEUR / Airbnb 的第二張 JR 小卡 `#jr-otaru-sapporo`，並加入使用者提供的 Google Maps 行程連結 `https://maps.app.goo.gl/scqQiYNQpWTo6fxx5`。
- 該小卡已補上：小樽 → 白石方向、函館本線普通車、Local train 全車自由席、後段可接公車；Google Maps 按鈕使用與景點一致的 `map-link` 樣式。
- 行程表「小樽 → 札幌」已改成連到 `#jr-otaru-sapporo`。
- 此段曾在本機完成但未發布；2026-07-10 改期後首日改為機場包車直達洞爺湖，現行 HTML 已移除這兩張 JR 小卡。

## 目前狀態

- `hokkaido-travel-guide.html` 目前是尚未發布的 2026/07/13–07/20 颱風改期版；需先讓使用者刷新本機頁面確認，再決定是否推送 `main`。
- `hokkaido-travel-guide.html` 的航班資訊去重、7/11 北之寶／北之漁場換序與哲哲組 Garden field-note 樣式修改已發布到 `main` commit `caabe5b`，公開頁已驗證。
- 狸小路與札幌站買衣資訊已合併到 `main`（`ce6d4c3`），GitHub Pages 已部署。
- GitHub Pages 已從 `main` 根目錄成功部署 commit `599fc43`；公開 `hokkaido-travel-guide.html` 與北之寶圖片均回應 HTTP 200，最新內容已在線上。
- 北海道神宮簡介已依使用者指定，補上抽御神籤、買御守與屬主者不需要此類物品的句子。
- 北之寶使用從其 Notion 頁面取得的店面／餐點拼圖 `assets/notion-kitanotakara.png`；北之漁場使用活蟹水槽圖 `assets/notion-kitanoryoba.png`。
- 北之漁場與北之寶已拆成獨立行程／卡片，並各自使用正確的 Notion 圖片與 Google Maps 連結。
- 北海道神宮提醒已移除「尊重參拜動線」，保留步行與停留時間建議。
- 「札幌に在る教会」卡片已依使用者要求恢復成原本的聚會導向介紹，不採用 Google Maps 評論改寫文字。
- `hokkaido-travel-guide.html` 的 21 張 Google Maps 景點卡已依公開評論重寫，包含更貼近現場的排隊、人潮、價位、動線、天氣與熱門品項提醒；原 22 個地圖連結均保留。
- 專案可開發、可測試；核心功能是個人旅館價格紀錄與受控擷取。
- Airbnb stay URL 已是 first-class 來源；支援 first-party `airbnb.com` / `airbnb.com.tw` 的 `/rooms/...`，不支援 Airbnb 搜尋頁。
- 最新 Booking.com DOM 優先修正已讓 Quintessa 實際輸出 `TWD 24,082`。
- 低 token agent 記憶系統已建立第一版，入口為 `AGENTS.md` + `.agent/MEMORY_INDEX.md`。
- `npm run memory:check` 已可驗證入口長度、索引連結與 handoff 必要章節。
- 低頻外部工具規則放在 `.agent/RUNBOOK.md`，目前包含 Heptabase CLI 使用方式。

## 已驗證

- 北海道景點卡結構檢查通過：22 個 Google Maps 連結、21 張卡、0 張缺少必要介紹欄位。
- `npm run memory:check` 通過。
- `npm test` 通過，35 tests。
- `npm run typecheck` 通過。
- `npm run build` 通過。
- Airbnb URL normalizer smoke 通過：Notion `札幌CHALEUR` 形狀的 `/rooms/<id>?check_in=...` URL 被接受，搜尋頁與 fake domain 被拒絕。
- Edge/API smoke 產生 `webwright/hotel-url-batch/final_runs/run_19/captured-records.json`，Quintessa `displayedPrice` / `totalPrice` 為 `24082`。

## 阻塞

- 無程式阻塞。
- 使用者 UI 可能仍有舊 localStorage 紀錄；需重新按 App 的「直接擷取 Edge 目前分頁」覆蓋。

## 下一步

1. 若是旅遊網站發布任務，直接按 `.agent/RUNBOOK.md` 的「Hokkaido travel guide / GitHub Pages 發布」流程走。
2. 若使用者仍看到 `26,757`，先確認是否已重新按 App 擷取，並檢查最新 `final_runs/run_<n>/captured-records.json`。
3. 任務開始讀 `AGENTS.md` + `MEMORY_INDEX.md`；再按需讀 `ACTIVE.md`、`RUNBOOK.md`、`ERROR_LOG.md`。
4. 任務收尾更新 `PROGRESS.md` 與本檔。

## 風險

- Booking.com DOM 會變，parser 修改需 snapshot/API smoke。
- Airbnb parser 目前使用通用文字價格擷取；若 Airbnb 頁面價格格式變複雜，需用真實 snapshot 對照再調整。
- PowerShell 可能亂碼顯示 API JSON；以 UTF-8 檔案內容為準。
- 不要讀一般瀏覽器 profile/session/cookie 檔。
