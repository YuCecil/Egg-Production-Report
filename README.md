# 牧場營運報表

雞蛋牧場每日營運數據報表，從 Google Sheets 讀取資料並呈現各雞舍的產蛋量與死亡數。

## 功能

- 依日期範圍查詢各雞舍資料
- 報表視覺化與數據彙整
- 手機優化介面（Sticky header、觸控友善）

## 技術

- HTML + Tailwind CSS + Font Awesome，單一 HTML 檔案
- Google Apps Script 後端，資料來源為 Google Sheets

## 使用方法

1. 建立 Google Sheets 並部署對應的 GAS Web App
2. 將部署 URL 填入 `Egg-Production-Report.html` 的 API 設定
3. 直接開啟 HTML，或部署至靜態主機
