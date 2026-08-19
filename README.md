# 帶 AI 做事 — 工作坊教材

給**完全沒有程式經驗**的同仁的兩堂 AI 工作坊。每一堂都是一份自帶樣式與互動的單一 HTML 檔，用瀏覽器直接打開就能放 —— 不需要安裝任何東西、不需要簡報軟體，離線也能跑（字型載不到會自動退回系統字型）。

| | 內容 | 檔案 |
|---|---|---|
| **Level 01** | 把工作說清楚 —— AI 猜不到你沒講的。交代五件事：我是誰、問題是什麼、要什麼、不要什麼、怎樣算完成 | [`vibe-coding-guide-level-01.html`](vibe-coding-guide-level-01.html) |
| **Level 02** | 把工具養起來 —— 健檢你的設定、看懂東西壞在哪一段、把做法存成一份可以交接的 SOP | [`vibe-coding-guide-level-02.html`](vibe-coding-guide-level-02.html) |

[`index.html`](index.html) 是兩堂課的入口頁。

## 放映方式

用電腦開，按 <kbd>F</kbd> 進全螢幕 —— 版面是照全螢幕比例調的。

| 按鍵 | 作用 |
|---|---|
| <kbd>→</kbd> <kbd>空白</kbd> | 下一段／下一頁 |
| <kbd>←</kbd> <kbd>Backspace</kbd> | 上一頁 |
| <kbd>A</kbd> | 一次攤開這一頁所有分段 |
| <kbd>F</kbd> | 全螢幕 |
| <kbd>Esc</kbd> | 關閉彈窗 |
| <kbd>Home</kbd> / <kbd>End</kbd> | 第一頁／最後一頁 |
| <kbd>1</kbd>–<kbd>9</kbd> | 在有頁籤的那一頁切換頁籤 |

每一頁的內容是**分段出現**的，按 → 會先把這一頁剩下的段落放完，才換到下一頁。往回翻頁時整頁直接攤開。

## 結構

```
index.html                          入口頁
vibe-coding-guide-level-01.html     第一堂（14 頁）
vibe-coding-guide-level-02.html     第二堂（13 頁）
assets/                             四張內嵌截圖
```

樣式與互動全部內嵌在各自的 HTML 裡，沒有建置步驟、沒有相依套件。唯一的外部資源是 Google Fonts 的 Noto Sans TC，而且是非阻擋載入 —— 載不到不影響放映。

## 相容性

在 1280×720、1366×768、1600×900、1920×1080、2560×1440 實測過，每一頁都不會溢出。視窗高度低於 1010px 時（例如忘了按全螢幕）版面會自動再收一階。

## 授權

內部教育訓練用途。
