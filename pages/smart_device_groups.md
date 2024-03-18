# 智慧裝置群組

[← 返回首頁](../)

## 尋找過久沒有上網的裝置

* 設定規則為「**Last Inventory Update**」，運算子為「**超過 x 天前**」，超過 x 天沒有上網跟 Jamf 報到的數量

## 尋找尚未更新 iOS 版本的裝置

* 設定規則為「**iOS Version**」，運算子為「**小於版本號**」，就可以統計尚未完成某版本 iOS 裝置的數量

## 透過正規表示法管理智慧裝置群組

* 規則類型選擇「**與規格運算式相符**」，可以參考 [Jamf 官方說明文件](https://learn.jamf.com/zh-TW/bundle/technical-articles/page/Using_Regex_with_Smart_Groups_and_Advanced_Searches.html)，範例參考：

  * 開頭為 moe-TCH：^moe-TCH
