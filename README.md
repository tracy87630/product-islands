# 產品有事群島 PRODUCT ISLES.

劉美伶 Tracy Liu 的產品經理作品集，做成一座可以逛的 3D 微縮城市。

每座六角群島是一段經歷，每一格是一個我處理過的產品問題。點一格，就能看到當時的問題、我做了什麼、結果數字，以及它目前的狀態（上線、預估、原型等）。

## 畫面上有什麼

- **六座群島**：起點群島、PChome、KKday、91APP、實驗室（side projects），以及中間的 Tracy 港（關於我）。
- **專案格**：27 個專案，各有一棟對應主題的小建築，例如 AI 專案是機器人、金流是銀行、上架流程是工廠。
- **詳細卡片**：點格子後鏡頭飛過去，左側打開卡片，可以切上一格、下一格。
- **右側索引面板**：搜尋專案、依群島瀏覽，或切到「能力」分頁篩選 AI、數據、結帳金流等能力；被選中的專案會浮起來，並用弧線依時間順序串起來。
- **航線導覽**：沿職涯航線，依時間把五座群島走一遍。
- **島民**：依團隊合照做的同事公仔，會在島上走動、揮手；名字預設隱藏，用工具列「島民」開關顯示。
- **時段切換**：清晨、白天、黃昏、夜晚；晚上窗戶會亮、燈塔會掃光。
- **其他工具**：名牌開關、航線開關、暫停動畫、鳥瞰、全景重置。
- 支援手機版版面。

## 在本機跑起來

整個網站只有一個 `index.html`，不需要安裝或打包。因為用了 ES module，請用本機伺服器開啟，不要直接雙擊檔案：

```bash
python3 -m http.server 4321
```

然後打開 <http://localhost:4321/>。需要連網，才能載入下方的外部資源。

## 用到的外部服務

全部是公開 CDN，沒有後端、沒有 API 金鑰，也不收集訪客資料。

| 服務 | 用途 |
|---|---|
| [jsDelivr](https://www.jsdelivr.com/) | 載入 [three.js](https://threejs.org/) r160（3D 場景、OrbitControls、移軸後製效果） |
| [Google Fonts](https://fonts.google.com/) | Noto Sans TC、Roboto Slab、Nunito、Fraunces、JetBrains Mono、Bricolage Grotesque |

## 製作方式

用 [Claude Code](https://claude.com/claude-code) 協作完成。專案內容取自我自己的經歷素材庫，數字口徑照原始資料標註（預估、原型、適用範圍）。

## 聯絡

- LinkedIn：<https://www.linkedin.com/in/tracy-liu-218225a7>
