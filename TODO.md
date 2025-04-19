# 📱 H2OHero-App 開發待辦清單（ToDo List）

> Swift + SwiftUI + Apple Watch + AI + 雲端同步 + 健康分析

---

## 🧱 第一階段：基礎功能構建

- [ ] 設定 SwiftUI 專案架構 `H2OHeroApp`
- [ ] 建立基本畫面 `ContentView`
- [ ] 建立 `UserProfile` 結構（性別、年齡、身高、體重、運動量）
- [ ] 設計 `HydrationEntry` 模型
- [ ] 建立 `HydrationManager` 控制器（包含每日目標計算）
- [ ] 在主頁顯示進度條、已喝水量 / 今日目標
- [ ] 提供快捷飲水按鈕（100ml / 250ml / 500ml）
- [ ] 提供選擇溫度（冷、溫、熱）與飲品類型（如：氣泡水、果汁）

---

## 🌐 第二階段：使用者資料與雙語支援

- [ ] 設計個人設定畫面（編輯 `UserProfile`）
- [ ] 儲存與讀取個人資料（使用 `UserDefaults` or `CoreData`）
- [ ] 加入中文 / 英文語言支援（使用 `Localizable.strings`）

---

## 📊 第三階段：日誌與統計分析

- [ ] 顯示每日飲水紀錄列表（以時間排序）
- [ ] 每週 / 每月總量與平均水量統計
- [ ] 使用 Swift Charts 顯示趨勢（折線圖 / 長條圖）
- [ ] 提供健康建議句（例如：「你昨天喝得太少了」）

---

## ☁️ 第四階段：雲端同步與帳號管理

- [ ] 導入 CloudKit + CoreData 同步架構
- [ ] 飲水紀錄與使用者設定自動儲存至 iCloud
- [ ] 支援多裝置同步（iPhone / iPad）
- [ ] 加入匿名字登入與資料初始化選項

---

## ⌚️ 第五階段：Apple Watch 支援

- [ ] 新增 WatchKit Extension 子專案
- [ ] 設計 Watch UI：今日進度、快速紀錄按鈕
- [ ] 實作 Watch ↔ iPhone 資料同步（`WatchConnectivity`）
- [ ] 加入心率與步數資料擷取（`HealthKit`）

---

## 🧠 第六階段：AI 分析與建議

- [ ] 設計簡單 rule-based 飲水建議模型
- [ ] 根據長期趨勢自動建議每日飲水目標
- [ ] 實作提醒過久未喝水或喝太少（推播提示）
- [ ] 預備 CoreML 模型導入（可離線訓練後上線）

---

## 🧪 額外構想（未列入主流程，可後續加入）

- [ ] 拍照辨識水壺或馬克杯容量
- [ ] 將喝水紀錄同步到 Apple Calendar
- [ ] GPT 健康小幫手：輸入「我昨天喝得太少怎麼辦？」
- [ ] 喝水任務打卡系統（達標領取獎章）
