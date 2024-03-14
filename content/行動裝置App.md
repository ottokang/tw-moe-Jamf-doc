# 行動裝置 App

[← 返回首頁](../)

## 設定軟體自動更新時間

設定 → 裝置管理 → App 維護，勾選

* ✅ 自動強制執行 App 更新
  * ✅ 自動更新透過 Self Service 安裝的應用程式
* ✅ 排程 Jamf Pro，使其自動檢查 App Store 是否有應用程式更新
  * App Store 國家或地區請選 Taiwan，App Store Sync Time 可自行設定
* **Force updates** 按鈕可以強制 App 更新

![設定：App 維護](../image/設定：App%20維護.png)

## 如何讓 App 在教師機手動安裝、學生機自動安裝？

* 在行動裝置 App 中，右上角新增 → 輸入 App 名稱，國家或地區選 Taiwan，新增一個同名的 App 到系統中。
  * 記得要勾選管理式發佈 → ✅ 指派大量採購的內容
* 把 2 個 App 分開設定：
  * 一個指派範圍給教師機，發佈方法為 Make Avaiable in Self Service
  * 另一個指派範圍給學生機，發佈方法為 Install Automatically/Prompt Users to Install

![設定：App 分別設定](../image/設定：App%20分別設定.png)
