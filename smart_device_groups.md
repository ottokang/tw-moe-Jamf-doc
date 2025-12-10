# 智慧裝置群組

[← 返回首頁](./)

智慧裝置群組可以使用條件，管理裝置群組，例如：

* ## 過久沒有上網的裝置

  * 設定規則設定為 `上次資產更新`，運算子設定為 `超過 x 天前`，可以尋找超過 x 天沒有上網跟 Jamf 報到的數量

* ## 尚未更新 iOS 版本的裝置

  * 設定規則設定為 `iOS Version`，運算子設定為 `小於版本號`，可以統計尚未完成某版本 iOS 裝置的數量

* ## 透過正規表示法管理智慧裝置群組

  * 運算子設定設定為 `與規格運算式相符`，就可以使用正規表達式統計裝置，可參考 [Jamf 官方說明文件](https://learn.jamf.com/zh-TW/bundle/technical-articles/page/Using_Regex_with_Smart_Groups_and_Advanced_Searches.html)，例如：

    * 裝置名稱開頭為 moe-TCH：規則設定為`顯示名稱`，值設定為`^moe-TCH`
