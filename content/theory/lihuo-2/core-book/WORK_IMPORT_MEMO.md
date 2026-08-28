# WORK IMPORT MEMO｜理火 2.0 核心書整合

請將本資料包整合到「理火理論總網站」。

## 必做

- 將《AI，你到底在急什麼？》標記為 `LIHUO 2.0 / 生成動力學 / CORE BOOK`。
- 依 `book.yaml` 的順序建立閱讀頁。
- 每一章使用獨立 URL。
- 保留三個部別。
- 保留附錄 QA。
- 建立上一章／下一章導覽。
- 建立部別目錄與全書目錄。
- 原文章節全文直接讀取 Markdown，不得用 AI 摘要覆蓋。
- 手機與桌面均需可閱讀。
- 支援章節 anchor / 深連結。

## 建議路由

```text
/theory/lihuo-2/
/theory/lihuo-2/book/
/theory/lihuo-2/book/part-1/chapter-01
...
/theory/lihuo-2/book/part-3/final
/theory/lihuo-2/book/appendix
```

## 來源與完整性

- `book.yaml` 是章節順序與檔案對照表。
- `sources/AI-你到底在急什麼-original.md` 是未改動原始備份。
- `BOOK_INDEX.md` 是人類可讀目錄。
- 拆章內容已執行全文重新串接驗證。
- 若 Work 解析結果與原書有差異，以原始備份為核對來源。

## 禁止

- 不得刪除重複段落。
- 不得自行「修正文風」。
- 不得因為某章有推測性陳述就偷偷改寫原文。
- 不得把本書提升為理火協議。
- 不得把書中的功能性／生成層模型直接宣稱為已證實 hidden mechanism。
