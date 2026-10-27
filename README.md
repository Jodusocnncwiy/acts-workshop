# ActS 活動集服務設計：理論導讀與互動工作坊

**by Jodus**

這是 MBA「服務業管理」課程使用的教學網頁，介紹活動集映射（Activity-Set Mapping, ActS）這套服務設計方法，並提供一個可以實際操作的互動工作坊。學生可以用它完成 ActS 分析，作為期中報告的主要工具。

## 線上使用

👉 **https://jodusocnncwiy.github.io/acts-workshop/**

不需要安裝或註冊，用電腦或平板的瀏覽器開啟即可。

## 功能

### 理論導讀

- 服務設計的三種視角：雙元互動、系統互動、顧客活動
- 人類活動集（human activity set）的三項前提
- 四象限與設計方向：乏味型、挑戰型、無聊型、享受型
- ActS 的四個階段、十個步驟
- 論文試行案例（招募 App）與教學示意案例
- 與服務體驗藍圖（Service Experience Blueprint, SEB）的對照
- 方法限制與批判思考

### 互動工作坊

- **四象限氣泡圖**：X 軸為有趣程度，Y 軸為犧牲，圓圈大小代表重要性，外框粗細代表頻率。
  - 可直接拖曳氣泡調整位置。
  - 點選氣泡可編輯；選取後可用方向鍵微調。
- **「為什麼？」欄位**：記錄使用者自己說的理由，回應 ActS 無法解釋原因的方法限制。
- **第二利害關係人圖層**：分別建立兩方的活動集，並可疊加比較（ActS 步驟 8）。
- **參與者構想清單**（ActS 步驟 6）。
- **構思引導底稿**：依象限產生提問，協助擬定關鍵問題與服務概念（ActS 步驟 9、10）。
- **匯出與匯入**：
  - 下載 PNG 圖檔，可直接貼進報告。
  - 匯出 TXT 完整報告。
  - 匯出、匯入 JSON 檔，用來存檔或與組員交換進度。
- **範例資料**：職涯發展（依論文 Figure 2 估計）與健康餐飲（教學示意）。

## 學生使用步驟

1. 開啟網頁，切換到「互動工作坊」，按「清空」開始新的分析。
2. **步驟 2**：輸入活動目標或主題。請寫顧客想達成的目標，而不是某項服務的使用流程。
3. **步驟 5**：找真實使用者，列出他們為了目標而反覆進行的活動，並為每項活動標示有趣程度、犧牲、重要性、頻率，以及「為什麼」。
4. **步驟 6**：記下使用者自己提出的服務構想。
5. **步驟 7**：在氣泡圖上檢查各活動的位置，必要時拖曳調整。
6. **步驟 8**：切換到第二利害關係人圖層，例如第一線員工，建立對方的活動集。
7. **步驟 9、10**：產生構思引導底稿，用使用者的理由回答提問，寫出關鍵問題、價值主張，以及要放在哪個服務介面。
8. 匯出 PNG、TXT 與 JSON，放進期中報告。

## 資料與隱私

- 所有資料只儲存在使用者自己電腦的瀏覽器中（localStorage），不會上傳到任何伺服器。
- 換電腦、換瀏覽器或清除瀏覽紀錄後，資料就會消失。請養成每次操作完就**匯出 JSON** 存檔的習慣。

## 技術說明

- 單一 HTML 檔（`index.html`），不需安裝任何套件。
- 使用 Tailwind CSS（CDN）與 Google Fonts，開啟時需要網路連線。
- 瀏覽器主控台可能出現 Tailwind CDN「不建議用於正式環境」的提示，不影響使用。

## 部署到 GitHub Pages

1. 將 `index.html` 與 `README.md` 上傳到 repository 根目錄。
2. 進入 **Settings → Pages**。
3. 在 **Build and deployment** 的 Source 選擇 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 **Save**。
4. 約一兩分鐘後，即可透過上方網址開啟。

## 參考文獻

Gummerus, J., Mickelsson, J., Trischler, J., Härkönen, T., & Grönroos, C. (2021). ActS – Service design based on human activity sets. *Journal of Service Management, 32*(6), 28–54. https://doi.org/10.1108/JOSM-09-2019-0275

Patrício, L., Fisk, R. P., & Falcão e Cunha, J. (2008). Designing multi-interface service experiences: The service experience blueprint. *Journal of Service Research, 10*(4), 318–334. https://doi.org/10.1177/1094670508314264

## 使用聲明

- 本網頁僅供教學使用。
- ActS 論文以 CC BY 4.0 授權發表，網頁中引用的概念與改編圖表均已標示出處。
- 本 repository 不收錄任何論文全文或原始圖檔；請透過上方 DOI 連結查閱原文。

## 作者

© 2026 Jodus
