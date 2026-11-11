# Wiki 操作紀錄

本檔案只追加，不回改既有紀錄。每次匯入來源、回答並保存研究問題、或執行健康檢查時新增一個區段。

## [2026-11-10] ingest | 證券服務月刊：集中市場月訊（2026 年 9 月）

- 原始 PDF 保存至 `raw/articles/證券服務月刊.pdf`。
- 建立來源筆記 `wiki/source-notes/2026-09-集中市場月訊.md`。
- 建立並更新 `wiki/markets/taiwan-stock-market.md`、`wiki/overview.md` 與 `index.md`。
- 文件涵蓋 11 頁；主要資料截至 2026-09-30，國際比較資料截至 2026-08。
- 尚未對金融大事紀的所有外部數據逐項核驗；後續引用前應回到各官方原始來源。

## [2026-11-11] query | 臺灣集中市場研究簡報

- 研究筆記保存至 `notes/taiwan-stock-market.md`，只使用 Wiki 已整理內容。
- 建立 9 頁逐頁簡報內容 `slides/taiwan-stock-market.md`。
- 建立 LaTeX Beamer 原始檔與 PDF：`latex/taiwan-stock-market.tex`、`latex/taiwan-stock-market.pdf`。
- 建立可離線開啟的 HTML 簡報：`html/taiwan-stock-market.html`。
- 網路搜尋僅用於列出後續 Wiki 化的官方候選文獻，未將外部內容納入研究結論。

## [2026-11-10] setup | 建立股市分析研究 Wiki

- 建立中文 `AGENTS.md`、三層資料架構、索引、總覽、範本與操作紀錄。
- 目前尚未匯入任何外部研究來源。
- 下一步：將下一批文章、財報、研究報告或資料快照放入 `raw/inbox/`。

## [2026-11-11] revision | 簡報視覺風格調整

- 依使用者提供的數位普普風圖片，將 HTML 簡報改為白底、黑色粗描邊、紫／青／粉局部漸層、半色調與貼紙式卡片。
- LaTeX Beamer 同步改用 Noto Sans TC、標題色塊、描邊數字卡與描邊提醒框，並修正一處長句換行造成的孤立文字。
- 重新編譯 9 頁 PDF，逐頁渲染檢查文字邊界、裁切、溢出與低對比問題。

## [2026-11-11] ingest | IMF 全球金融市場風險文章

- 保存 IMF 官方提供的 Markdown 版本至 `raw/articles/2026-10-13-imf-global-financial-markets-ai-bond-yields-cyberattacks.md`；原始網址的路徑日期為 2026-10-12，文章標示發布日為 2026-10-13。
- 建立來源筆記 `wiki/source-notes/2026-10-13-IMF-global-financial-markets-risks.md`，保留 AI 市場修正、主權債券殖利率、網路攻擊、金融脆弱性與待查證數字。
- 建立 `wiki/macro/global-financial-stability-risks.md`，並更新 `wiki/markets/taiwan-stock-market.md`、`wiki/overview.md` 與 `index.md`。
- 文章是全球金融穩定風險框架，不直接改寫臺灣市場數字或形成買賣結論；GFSR／WEO 與壓力測試細節仍待逐項核對。

## [2026-11-11] ingest | AI、殖利率與科技泡沫相關文章

- 保存可取得正文的 4 篇來源至 `raw/articles/`：經濟日報、商周、永豐金證券與凱基證券。
- 保存 2 個 Yahoo 股市分享連結至 `raw/articles/`，但目前無法解析轉址後的文章，因此來源筆記標示為 `watching`，不納入 Wiki 結論。
- 建立 6 篇來源筆記，分別記錄升息後市場重新定價、10Y−FDTR 利差、AI 獲利與自由現金流、資料中心政策與供應鏈傳導，以及兩個待補 Yahoo 來源。
- 建立 `wiki/macro/ai-valuation-and-rate-risk.md`，整合 AI 產業基本面、股票估值、利率與資料中心供給側的可驗證研究拆解。
- 更新 `index.md`、`wiki/overview.md` 與 `wiki/markets/taiwan-stock-market.md`；媒體與券商文章的數字仍需回到官方資料或原始研究核對。

## [2026-11-11] revision | 簡報圖片與文字層級

- 使用 `raw/assets/beanhead-01.png`、`beanhead-03.png`、`beanhead-04.png`、`beanhead-07.png` 與 `beanhead-10.png` 作為研究角色式裝飾，分散放入 HTML 簡報的封面、基本面、風險、後續問題與結論頁。
- LaTeX 簡報同步加入封面與基本面頁圖片，並加粗市場數字、AI 傳導、研究步驟與結論關鍵字。
- 重新渲染檢查圖片與文字安全邊界；修正圖片靠近頁尾的溢出問題。

## [2026-11-11] revision | 角色圖片去背與標題加粗

- 保留原始 `raw/assets/beanhead-01.png` 至 `beanhead-10.png`，另建立對應的 `*-transparent.png` 透明版本；移除與邊界連通的白色背景，保留角色內部的白色細節。
- HTML 與 LaTeX 簡報改用透明版本並放大角色圖片；LaTeX 移除角色外框，避免角色周圍出現白色方框。
- 提高 HTML 標題字重與描邊，LaTeX 使用較強的假粗體；重新編譯並檢查 9 頁 PDF，確認標題、角色與底部資訊沒有裁切或超出頁面。

## [2026-11-11] revision | 依參考圖重做數位普普風編排

- 依使用者提供的參考圖，將 HTML 與 LaTeX/PDF 改為白底滿版、四角漸層造型、半色調點陣、黑色粗描邊與左文右主視覺的編排。
- 移除原本密集的卡片網格，改用每頁一個主要訊息、大數字、單一主圖或清楚的研究問題列表；保留 9 頁與 Wiki 既有數據和來源。
- LaTeX 重新編譯為 9 頁，渲染檢查封面、數據頁、風險頁、研究問題頁與結論頁，未發現 overfull 或 missing character 訊息。
- HTML 已完成同版型重構；目前環境的 Chrome headless 預覽因權限限制未能啟動，尚待在使用者瀏覽器中確認實際互動效果。

## [2026-11-11] revision | 行距、數字間距與來源頁平衡

- 調小 HTML 與 LaTeX 的大數字與標題字級，增加行距、數字與色條／底線之間的留白。
- 調整價格、規模與營收頁的數據排列，避免數字貼在線條上；LaTeX 重新編譯後仍維持 9 頁且無 overfull 警告。
- 將 HTML 與 LaTeX 的最後一頁改為平衡的雙欄來源編排，避免內容全部集中在左側。

## [2026-11-11] revision | PDF 細部字級與安全邊界

- 進一步縮小封面標題、主數字、風險數字與結論文字，重新分配主標、數字、說明文字的垂直層級。
- 修正規模、價格、集中度、營收、風險與後續問題頁的行距、上下留白與無謂換行；將最後一頁改為左右平衡的來源區塊。
- 重新編譯並渲染檢查 9 頁 PDF，確認沒有 overfull、缺字或內容貼近頁面邊界的警告。

## [2026-11-11] revision | 依批註修正結論與各頁留白

- 將結論頁主句改為同一行、單一顏色且移除句號；資料範圍框與角色圖重新排列並放大。
- 刪除後續研究頁多餘的紫色線，縮小風險數字與營收／規模統計，增加集中度說明與上方表格的間距。
- 封面標題改用 Microsoft JhengHei 顯示字體，並調整主視覺大小與頁面安全邊界。
- LaTeX 重新編譯並渲染檢查 9 頁 PDF，無 overfull、缺字或 invalid font 警告。

## [2026-11-11] setup | 建立 GitHub Pages 入口

- 建立根目錄 `index.html`，提供專案簡介、目前 Wiki／簡報入口與 AI 延伸規則說明。
- 建立 `.gitignore`，排除 LaTeX 編譯暫存檔、本機暫存資料與編輯器設定檔。
- 尚未建立 GitHub Repository、設定 Pages 或推送遠端；等待使用者建立公開 Repository 後再進行上傳。

## [2026-11-11] deployment | 上傳 GitHub

- 使用者提供 `https://github.com/tzuyin-19/-LLM-Wiki.git`，已將完整專案初始化為 Git repository，建立 `main` 分支並推送初始提交。
- GitHub Pages 尚未完成設定；目前瀏覽器未登入 GitHub，需由使用者登入後在 Repository 的 Settings → Pages 選擇 `main` 與 `/(root)`。

## [2026-11-11] revision | 對照課程網站範例調整首頁

- 將根目錄首頁改為「研究成果庫」形式，加入主要導覽列、研究成果卡片與 GitHub Repository 入口。
- 明確呈現作業需要的專案簡介、Repository、網站、`AGENTS.md` 與 AI 延伸規則，並保留未來新增研究主題的入口。

## [2026-11-11] revision | 首頁改為股市研究知識庫

- 移除首頁主視覺中的作業說明與 AI 維護流程，改以市場快照、研究主題、研究產出與待研究問題作為主要內容。
- 新增臺灣集中市場的上市公司家數、市值與 TAIEX 快照，並連結至既有市場頁、宏觀頁、研究筆記與簡報。
- 保留完整索引、來源資料與 Repository 連結於頁尾，首頁不再把專案規則當成展示主體。

## [2026-11-11] revision | 首頁聚焦 HTML 簡報展示

- 移除首頁的研究主題、研究筆記、PDF 下載與待研究問題區塊。
- 將首頁改為單純的 HTML 簡報庫，目前以臺灣集中市場簡報作為第一個展示項目。
- 保留可延伸的簡報卡片結構，未來新增 HTML 簡報時直接增加卡片與連結即可。

## [2026-11-11] revision | 恢復市場簡介區塊

- 在 HTML 簡報庫前加入「臺灣集中市場」簡介，保留上市公司家數、總市值與 TAIEX 快照。
- 首頁仍不放研究筆記、PDF 下載或研究主題導覽，維持「市場簡介＋HTML 簡報庫」的展示結構。

## [2026-11-11] output | 新增三份 HTML 研究簡報

- 新增 `html/ai-stock-bubble.html` 與 `slides/ai-stock-bubble.md`，內容依 AI 估值與利率風險、凱基來源筆記與全球金融穩定風險整理。
- 新增 `html/fed-and-stocks.html` 與 `slides/fed-and-stocks.md`，內容依聯準會升息來源筆記與既有宏觀頁整理。
- 新增 `html/esg-stock-performance.html` 與 `slides/esg-stock-performance.md`；因 Wiki 尚無 ESG 績效頁面，明確標示為資料待建立，不下未經整理的績效結論。
- 更新首頁與 `index.md`，將三份簡報加入 HTML 簡報庫入口。

## [2026-11-11] revision | 修正簡報文字與裝飾重疊

- 移除臺灣集中市場「價格與交易活躍度」頁面文字後方的點狀裝飾，避免文字壓到背景圖案。
- 將 AI 股市泡沫簡報研究邊界頁的來源描述改為「券商觀點與官方分析」，讓證據層級更直接。
