# 功能清單手冊

系統版本：v1.4.2-alpha

<Icon icon="fa fa-exclamation-circle" text="後台功能可能因您的帳號權限而有所改變" color="info" />

----

## 網站設定

**網站各類設定**；<small>(ex: Logo、鎖右鍵、Google Analytics)</small>、**選單設定**、**版位保留** 等...

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 基本設置 | /shopadmin/setup/list | 網站基本設定；聯絡資訊、Logo、其他系統設定 |
| 主選單 | /shopadmin/menu/top | 網站主選單設定；設定主選單連結
| 頁尾選單 | /shopadmin/menu/bottom | 網站頁尾選單設定；設定頁尾選單連結
| 聯絡人資訊欄位管理 | /shopadmin/contact_columns | 管理各表單欄位；會員、訂單、聯絡我們、詢價；表單欄位自訂管理
| 重新導向管理 | /shopadmin/moved/list | 版位保留設定

----

## 首頁設定

首頁相關設定管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 設定 | /shopadmin/home/setup | 首頁 SEO 設定 |

----

## 權限群組管理

後台管理員所屬權限管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 新增權限群組 | /shopadmin/permission/create | 增加權限群組組別 |
| 權限群組列表 | /shopadmin/permission/list | 已設定權限群組組別列表

----

## 管理員管理

後台管理員管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 新增管理員 | /shopadmin/admin/create | 新增管理員；只能新增與您的後台帳號相同或更低權限的管理員 |
| 管理員列表 | /shopadmin/admin/list | 顯示您的後台帳號權限可管理的管理員列表
| 聯絡信箱 | /shopadmin/admin/info_mail | 各類信件發送管理員設定

----

## 內容管理

各類內容資料管理；<small>(ex: 關於我們、商品管理、最新消息 等...)</small>

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 關於我們管理 | /shopadmin/aboutus/list | 關於我們分類 / 資料管理 |
| 商品管理 | /shopadmin/products/list | 商品分類 / 資料管理
| 訊息管理 | /shopadmin/message/list | 訊息分類 / 資料管理
| 最新消息管理 | /shopadmin/news/list | 最新消息分類 / 資料管理
| 檔案下載管理 | /shopadmin/download/list | 檔案下載分類 / 資料管理
| 常見問題管理 | /shopadmin/qa/list | 常見問題分類 / 資料管理
| 單頁訊息管理 | /shopadmin/singleton | 客戶權利義務、隱私權政策、免責聲明、退貨說明 內容管理

----

##  商品規格群組管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 商品規格群組管理 | /shopadmin/spec | 購物功能商品規格群組管理 |

----

## 運費管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 新增運費 | /shopadmin/ship/create | 增加運費管理資料 |
| 運費管理 | /shopadmin/ship | 購物功能運費管理
| 商品運送規格 | /shopadmin/ship/scale | 建立商品運送規格資料

----

## 贈品管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 贈品管理 | /shopadmin/gift/list | 管理商品關聯贈品，顯示於商品頁面與購物車，可設定 VIP 專屬贈品 |

----

## 會員管理

會員人員管理；<small>(ex: 後台手動建立會員、會員停用、Excel 會員資料匯入匯出 等....)</small>

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 會員群組 | /shopadmin/users/group | 手動建立會員群組 |
| 新增會員 | /shopadmin/users/create | 手動建立會員資料
| 會員列表 | /shopadmin/users/list | 會員資料列表、搜尋、匯出 Excel 檔案
| 會員匯入 | /shopadmin/users/import | 從 Excel 匯入會員資料

----

## 會員卡管理

建立會員卡號後供會員領取，領取的會員將具有 VIP 資格

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 新增會員卡 | /shopadmin/card/create | 建立會員卡，可設定卡號、過期日、指定會員 |
| 會員卡列表 | /shopadmin/card/list | 會員卡資料列表、搜尋、並且從此設定批次新增會員卡

----

## 金流管理

設定串接金流服務必要資料、設定付款方式與非金流付款選項

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 金流設定 | /shopadmin/epay/setup | 選擇金流服務、設定金流必要資料 |
| 付款管理 | /shopadmin/epay/payment | 啟用、關閉付款功能、設定非金流付款選項

----

## 訂單管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 訂單管理 | /shopadmin/order/list | 訂單資料列表、搜尋、匯出 Excel 檔案、管理付款、出貨狀態 |

----

## 折價管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 折價管理 | /shopadmin/discount/setup | 各類折價活動設定 |

----

## 聯絡我們管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 聯絡我們管理 | /shopadmin/contactus/list | 網站使用者聯絡信列表、查詢 |

----

## 詢價單管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 詢價單管理 | /shopadmin/inquiry/list | 網站使用者詢價信列表、查詢 |

----

## 橫幅廣告管理

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 橫幅廣告管理 | /shopadmin/banner/list | 網頁上方橫幅廣告管理，可自訂各頁面廣告 |

----

## 檔案總管

| 系統名稱 | 後台路徑 | 說明 |
|--|--|--|
| 檔案總管 | /shopadmin/filemanager | 管理上傳檔案 |