# 股市分析研究 LLM Wiki

這是一個以 Karpathy LLM Wiki 模式建立的中文股市研究知識庫：原始資料保存於 `raw/`，LLM 維護的摘要、實體頁、宏觀脈絡與投資論點保存於 `wiki/`，規則集中在 [AGENTS.md](AGENTS.md)。

## 開始使用

1. 將文章、財報、研究報告或資料快照放入 `raw/inbox/`。
2. 告訴 LLM「請匯入這個來源」，並指定你希望它關注的公司、產業或問題。
3. LLM 依 [AGENTS.md](AGENTS.md) 建立來源筆記、更新相關 Wiki 頁、索引與紀錄。
4. 之後直接詢問研究問題；值得保留的比較與洞見會存回 `wiki/analyses/` 或 `wiki/theses/`。

## 研究範圍

目前結構涵蓋公司、產業、宏觀、市場、事件、估值概念與投資論點。資料應始終標示來源與截至日；本 Wiki 是研究工具，不構成個人化投資建議。

## 入口

- [內容索引](index.md)
- [研究總覽](wiki/overview.md)
- [操作紀錄](log.md)
- [原始來源說明](raw/README.md)
- [頁面範本](templates/)
