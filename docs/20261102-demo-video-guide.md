# BMR & TDEE 熱量計算機操作流程示範影片說明文件

> **專案倉庫**：[https://github.com/41147b019/tdee-calculator](https://github.com/41147b019/tdee-calculator)  
> **影片檔案**：`workspace/outbox/20261102-tdee-calculator-demo.mp4`  
> **製作日期**：2026-11-02  
> **製作成員**：太魯閣（Taroko，隊員）

---

## 1. 影片規格資訊 (Video Specifications)

| 項目 | 規格參數 |
| :--- | :--- |
| **檔案格式** | MPEG-4 (.mp4)，相容 QuickTime、Windows Media Player、Keynote、PowerPoint 與各主流瀏覽器 |
| **編碼格式** | H.264 High Profile (AVC1) |
| **視訊解析度** | 1920 × 1080 (1080p Full HD，16:9 橫向標準寬螢幕) |
| **影格率 (Frame Rate)** | 30.00 fps (影格平滑無卡頓) |
| **影片總長度** | 39.83 秒 (1,195 影格) |
| **檔案大小** | 約 8.8 MB |
| **字幕語言** | 繁體中文台灣用語 + 英文同步雙語對照 (Bilingual Subtitles) |
| **特色特效** | 擬真滑鼠游標軌跡、輸入欄位焦點光暈、按鈕點擊漣漪動畫、場景平滑淡入淡出、底部動態進度條 |

---

## 2. 影片分鏡與時間軸 (Storyboard Timeline)

影片以現代化高質感瀏覽器模擬框架呈現，清楚演示計算機自開啟至完成各項生理目標運算的完整操作流程：

| 時間區間 | 分鏡步驟 | 畫面展示內容與操作動作 | 雙語字幕說明 |
| :--- | :--- | :--- | :--- |
| **00:00 - 00:03** | **INTRO** 開場導引 | 乾淨清爽的計算機起始頁面，展示頂部專案名稱、Mifflin-St Jeor 公式說明與 GitHub 倉庫標籤。 | **歡迎使用 BMR & TDEE 智慧熱量計算機**<br>*Welcome to BMR & TDEE Calorie Calculator Walkthrough* |
| **00:03 - 00:07** | **STEP 1** 生理性別與年齡 | 滑鼠游標移至性別核選「男 (Male)」，接著移至年齡欄位並聚焦發光，輸入 `25` 歲。 | **第一步：確認生理性別（男），並輸入年齡（25 歲）**<br>*Step 1: Confirm biological sex (Male) and enter age (25 years)* |
| **00:07 - 00:10** | **STEP 2** 身高數值 | 滑鼠游標移至身高輸入欄位，外框呈現主題藍綠色光圈，輸入 `175` 公分。 | **第二步：輸入身高數值（175 公分），系統將據此推算體表面積**<br>*Step 2: Enter height (175 cm) for body surface area estimation* |
| **00:10 - 00:14** | **STEP 3** 體重數值 | 滑鼠游標移至體重輸入欄位，聚焦並輸入 `70` 公斤。 | **第三步：輸入目前體重（70 公斤）**<br>*Step 3: Enter current body weight (70 kg)* |
| **00:14 - 00:17** | **STEP 4** 活動量係數 | 滑鼠游標移至日常活動程度下拉選單，選取「中度活動量（每週運動 3～5 天，PAL 係數 1.55x）」。 | **第四步：選擇日常活動程度 — 中度活動（每週運動 3～5 天，PAL 1.55x）**<br>*Step 4: Select daily activity level — Moderate Exercise (1.55x)* |
| **00:17 - 00:21** | **STEP 5** 計算與即時回饋 | 滑鼠游標移動至「開始計算 TDEE」按鈕，觸發點擊縮放與漣漪波紋，運算結果面板瞬間展開，精確呈現 BMR (1,674 kcal)、TDEE (2,594 kcal) 與 BMI (22.9 正常體位)。 | **第五步：點擊「開始計算」，以 Mifflin-St Jeor 公式精確產出 BMR 與 TDEE！**<br>*Step 5: Click Calculate to compute BMR & TDEE via Mifflin-St Jeor formula!* |
| **00:21 - 00:25** | **STEP 6** 五大目標熱量規劃 | 游標滑動瀏覽目標建議表格，逐一展示維持體重 (2,594 kcal)、溫和減脂 (2,294 kcal)、積極減脂 (2,094 kcal)、溫和增肌 (2,894 kcal) 與積極增肌 (3,094 kcal)。 | **第六步：檢視個人化 5 大目標熱量（維持 2,594 kcal、減脂 2,294/2,094、增肌 2,894/3,094）**<br>*Step 6: Review 5 customized target intakes (Maintain, Cut, and Bulk options)* |
| **00:25 - 00:29** | **STEP 7** 一鍵即時雙語切換 | 滑鼠游標移動至右上角「English」按鈕並點擊，介面所有文字瞬間無縫切換為全英文，且計算數據完整保留。 | **第七步：點擊右上角 English 即時切換雙語介面，所有計算數值完美保存！**<br>*Step 7: Instant one-click English switch while preserving all active numbers!* |
| **00:29 - 00:33** | **STEP 8** 健康安全防護機制 | 切換情境示範：女性 46kg / 158cm / 久坐，當積極減脂熱量低於 BMR 底線時，主動跳出珊瑚紅色「⚠️ 健康警示防護標籤」，提醒不可長期低於基礎代謝率。 | **第八步：安全防護機制 — 積極減脂低於 BMR 時，主動觸發健康警示！**<br>*Step 8: Safety Guardrail — Automatically alerts user if intake dips below BMR floor!* |
| **00:33 - 00:39** | **FINISH** 專案成果總結 | 畫面平滑轉至結尾成果卡片，彙整專案四大特點（Mifflin-St Jeor 公式、單一離線 HTML 零相依、衛福部安全警示、即時雙語切換），並顯著呈現 GitHub 專案倉庫網址。 | **示範完成！感謝觀看 — 歡迎至 GitHub 下載使用或整合！**<br>*Walkthrough Completed! Visit our GitHub repository to download or fork!* |

---

## 3. 如何觀看與播放 (Playback Guide)

1. **本機直接播放**：
   - 雙擊 `workspace/outbox/20261102-tdee-calculator-demo.mp4` 即可透過 macOS 內建 **QuickTime Player**、VLC 或其他播放器以 1080p 高畫質播放。
2. **投影片簡報嵌入**：
   - 可直接拖曳本 `.mp4` 檔案至 Apple Keynote 或 Microsoft PowerPoint 投影片中，設定為「按一下開始播放」或「自動循環播放」，作為 11/02 成果發表會的動態展示焦點。
3. **GitHub 與線上展示**：
   - 檔案大小僅 8.8 MB，符合 GitHub 儲存與網頁展示建議大小，可直接上傳或嵌入 GitHub Issue/Release/README 中展示。
