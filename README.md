# NLP 自然語言處理 (115 S1) 115-1 NLP 課程專案

本專案為 NLP 課程開發環境與實作練習區。

---

## 開發者資訊 (Developer Info)
* **學號**：[U12627002]
* **姓名**：[王垠錚]

## 硬體與環境狀態 (Environment Setup)
* **PyTorch 執行環境**：[請填寫您安裝的狀態：Windows CUDA 12.1 / Mac Default / Windows CPU]

---

## 課程任務清單 (Task Checklist)

### Week 2：開發環境與專案架構初始化
請在完成下列任務後，將 `[ ]` 改為 `[x]`：
- [x] 成功建立 GitHub 帳號並 Clone 本專案至本機端。
- [x] 成功建立 `.venv` 虛擬環境，並透過 `.gitignore` 隱藏底層檔案。
- [x] 成功於虛擬環境內安裝通用套件清單 (`requirements.txt`) 與專屬硬體版本的 PyTorch。
- [x] 更新本 README 文件，填寫學號、姓名與 PyTorch 環境狀態。
- [x] 成功使用 Git 完成 `commit` 並 `push` 同步至 GitHub 雲端。


### Week 4 / 8: Data Ingestion & Topology-Aware Chunking

- [ ] **環境建置與版控防護**：更新 `.gitignore`，阻擋原始 PDF 與暫存語料，並保留 `.keep` 目錄結構。
- [x] **資料擷取與合併**：
  - [x] 1-A 頁首頁尾清除
  - [x] 1-B 雙語標題合併
  - [x] 1-C 雙語條文合併
- [x] **結構健全度 (Mechanical Sanity)**：
  - [x] 拓撲錨定率
  - [x] 運用中位數計算文本長度
- [x] **語意品質 (Semantic Quality)**：
  - [x] 計算 Shannon Information Entropy，比較 Cleaned 與 Raw 的中位數資訊熵
- [ ] **觀測儀表板與報告**：
  - [x] 成功繪製四張比較圖
  - [ ] 確認核心評估指標已匯出為根目錄的 `metrics.json`
