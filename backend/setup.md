# 網站設定

## <Anchor id="basic" text="基本設置" />

### <Icon icon="fa fa-info-circle" text="注意事項" color="info" />

基本設置可依網站語系分開設定 <small>(見下圖：語言標籤)</small>；  
滑鼠點擊語言標籤即可切換該語系設定表單；  
如未依語系設定資料，系統將提取共通標籤設定使用。

語言標籤 |
--|
![語言標籤](/images/manual/setup_lang_tag.png) |

### 設定區塊說明

*   聯絡資訊設定  
    設定網站顯示聯絡資訊，通常顯示於頁尾與聯絡我們表單。

*   金流聯絡資訊設定  
    設定金流相關聯絡資訊，以利交易時使用。

*   結構化資料設定  
    <Blank href="https://support.google.com/webmasters/answer/3069489?hl=zh-Hant" text="結構化資料" />基本設定；  
    WINSHOP 系統會自動產生結構化資料，此處設定相關基本資訊。

    欄位名稱 | 是否必填 | 預設值 | 欄位說明
    --|:--:|:--:|--
    站台類別 | 是 | Corporation | 設定網站所屬組織類型，系統依此類別判斷顯示不同組織結構化資料格式，<Blank href="https://schema.org/Organization" text="查看 Schema.org 查詢更多類型">
    營業時間 | 否 | Mo,Tu,We,Th,Fr,Sa,Su 08:30-17:30 | 設定營業時間，請以 "星期,星期, 起始時間-結束時間" 格式填寫，可設定多組；例：Mo 08:30-17:30 (星期一營業時間)，Su 08:30-17:30 (星期日營業時間)，Mo,Tu,We 08:30-17:30 (星期一至三營業時間)。<Icon icon="fa fa-exclamation-triangle" text="請注意！站台類別如果非商店類別，此營業時間沒有作用" color="warning" />。

*   站台設定  

    欄位名稱 | 是否必填 | 預設值 | 欄位說明
    --|:--:|:--:|--
    網站中繼資料 | 否 | 無 | 提供管理者增加客製化的中繼資料；<Blank href="https://support.google.com/webmasters/answer/79812?hl=zh-Hant" text="查看 Google 說明">。<small>(此欄位可能因您的管理員帳號權限而有所不同)</small>
    Google Analytics | 否 | 無 | 提供管理者增加 Google Analytics；<Blank href="https://support.google.com/analytics/?hl=zh-Hant" text="查看 Google 說明">。<small>(此欄位可能因您的管理員帳號權限而有所不同)</small>
    Google Ads | 否 | 無 | 提供管理者增加 Google Ads；<Blank href="https://support.google.com/google-ads/?hl=zh-Hant" text="查看 Google 說明">。<small>(此欄位可能因您的管理員帳號權限而有所不同)</small>
    站台 Logo 圖片 | 否 | 無 | 網站 Logo 圖片，建議填寫
    站台手機版 Logo | 否 | 無 | 網站於手機解析度下顯示的 Logo，如不設定則沿用 "站台 Logo 圖片"
    上方選單下拉 | 否 | 停用 | 網站主選單顯示下拉次選單切換
    鎖右鍵 | 否 | 停用 | 網站鎖右鍵切換
    返回網頁頂部特效 | 否 | 啟用 | 網站回頂部按鈕
    側邊顯示底層資料 | 否 | 啟用 | 側邊選單是否顯示底層資料
    商品側邊顯示底層資料 | 否 | 啟用 | 商品內頁的側邊選單是否顯示底層資料
    主選單下拉顯示底層資料 | 否 | 啟用 | 主選單展開下拉選單時，是否顯示底層資料
    商品主選單下拉顯示底層資料 | 否 | 啟用 | 主選單中的商品項目，展開下拉選單時，是否顯示底層資料
    逐層分類顯示資料 | 否 | 停用 | 進入列表內頁時，是否要逐層顯示（顯示每一層分類）
    商品詳細頁顯示左圖右文 | 否 | 停用 | 商品詳細頁的內容區塊，是否為左圖右文的呈現方式
    商品詳細頁顯示相關商品 | 否 | 啟用 | 商品詳細頁顯示相關商品切換

*   圖片設定  
    可分別設定桌機和手機的首頁、內頁廣告解析度；也可以分類圖片和資料圖片的解析度。

*   會員設定  

    欄位名稱 | 是否必填 | 預設值 | 欄位說明
    --|:--:|:--:|--
    會員帳號類別 | 是 | string | 會員帳號資料類別，可選 string、email、numeric
    會員帳號字元長度範圍 | 是 | 4-255 | 限制會員帳號字元長度，建議不要少於 4 個字；如果 "帳號類別" 為 email 時此設定無作用
    會員生日年份範圍 | 是 | 10-120 | 聯絡人資訊欄位如有設定生日類別，將以此指定歲數範圍顯示年份 (此功能尚未實裝)
    會員生日年份預設歲數 | 是 | 30 | 聯絡人資訊欄位如有設定生日類別，將以此指定歲數年份作為預設 (此功能尚未實裝)
    會員密碼字元長度範圍 | 是 | 6-20 | 限制會員密碼字元長度，建議不要少於 6 個字
    會員登入後跳轉路徑 | 是 | member | 當會員登入後自動跳轉指定路徑
    會員登出後跳轉路徑 | 是 | home | 當會員登出後自動跳轉指定路徑，設定 home 則為首頁
    會員註冊是否需要 email 認證 | 是 | 啟用 | 切換會員註冊是否需要 email 認證

*   社群連結設定  
    可分別設定各個社群的連結網址。但某些社群例外，設定的資料形式不是網址。
    
    例外社群|設定資料|示意圖
    --|--|--|
    Line|設定「line.me/」後的文字|![主選單表單截圖](/images/manual/setup_line.png) |
    Skype|設定 Skype 的 ID ||
    Wechat|設定 Wechat 的 ID ||
    Whatsapp|設定 Whatsapp 的 ID ||

----

## <Anchor id="menu_top" text="主選單" />

網站主選單設定介面，可自由設定選單項目，各語系可作不同設定。

<ModuleCheck name="menu_extend_name" isActive={false}>
主選單表單截圖 |
--|
![主選單表單截圖](/images/manual/menu_top.png) |
</ModuleCheck>

<ModuleCheck name="menu_extend_name" isActive={true}>
主選單表單截圖 |
--|
![主選單表單截圖](/images/manual/menu_extend_name.png) |
</ModuleCheck>

### 各號碼說明

<ModuleCheck name="menu_extend_name" isActive={false}>

1.  **主選單標題**  
    顯示目前設定的主選單項目排序，滑鼠按住後移動可更改選單項目順序。

    ----

2.  **選單名稱**  
    選單顯示時出現的名稱。<small>(見下圖)</small>

    網站主選單範例 |
    --|
    ![網站主選單範例](/images/manual/header.png) |
    
    ----

3.  **連結網址**  
    選單超連結網址；如是網站內部的超連結僅需要填寫 / 開頭。

    ----

4.  **啟用切換開關**  
    啟用或關閉選單項目。

    ----

5.  **另開視窗切換開關**  
    啟用或關閉選單超連結另開視窗功能。

    ----

6.  **分類資料連結選取**  
    滑鼠點選此按鈕後選擇各資料模組 <small>(見下圖 "分類資料連結選取-1")</small>；  
    接著選擇該模組下分類資料作為選單項目 <small>(見下圖 "分類資料連結選取-2")</small>。

    分類資料連結選取-1 | 分類資料連結選取-2
    --|
    ![分類資料連結選取-1](/images/manual/menu_cate_1.png) | ![分類資料連結選取-2](/images/manual/menu_cate_2.png)

    ----

7.  **選擇單頁連結**  
    滑鼠點擊此按鈕可選擇預定網站頁面作為選單項目。

    選擇單頁連結範例 |
    --|
    ![選擇單頁連結範例](/images/manual/menu_single.png) |

    ----

8.  **刪除**  
    點擊此按鈕將刪除目前區塊的選單項目。

    ----

9.  **儲存**  
    選單資料填寫完畢後點擊此處儲存。

    ----

10.  **增加主選單**  
    增加選單項目。

    ----

11.  **複製**  
    點擊此按鈕可選擇複製其他語系選單設定至目前語系，減少各語系間選單重複設定次數  
    <Icon icon="fa fa-exclamation-triangle" text="可設定的語系可能因您的管理員帳號權限而有所變化" color="warning" />。

    複製介面範例 |
    --|
    ![複製介面範例](/images/manual/menu_copy.png) |

</ModuleCheck>

<ModuleCheck name="menu_extend_name" isActive={true}>

1.  **主選單標題**  
    顯示目前設定的主選單項目排序，滑鼠按住後移動可更改選單項目順序。

    ----

2.  **選單名稱**  
    選單變換後出現的名稱。<small>(見下圖)</small>
    
    網站主選單範例 |
    --|
    ![網站主選單範例](/images/manual/menu_extend_name_hover.png) |
    
    ----

3.  **延伸名稱**  
    選單變換前顯示的名稱。<small>(見下圖)</small>
    
    網站主選單範例 |
    --|
    ![網站主選單範例](/images/manual/menu_extend_name_default.png) |

    ----

4.  **連結網址**  
    選單超連結網址；如是網站內部的超連結僅需要填寫 / 開頭。

    ----

5.  **啟用切換開關**  
    啟用或關閉選單項目。

    ----

6.  **另開視窗切換開關**  
    啟用或關閉選單超連結另開視窗功能。

    ----

7.  **分類資料連結選取**  
    滑鼠點選此按鈕後選擇各資料模組 <small>(見下圖 "分類資料連結選取-1")</small>；  
    接著選擇該模組下分類資料作為選單項目 <small>(見下圖 "分類資料連結選取-2")</small>。

    分類資料連結選取-1 | 分類資料連結選取-2
    --|
    ![分類資料連結選取-1](/images/manual/menu_cate_1.png) | ![分類資料連結選取-2](/images/manual/menu_cate_2.png)

    ----

8.  **選擇單頁連結**  
    滑鼠點擊此按鈕可選擇預定網站頁面作為選單項目。

    選擇單頁連結範例 |
    --|
    ![選擇單頁連結範例](/images/manual/menu_single.png) |

    ----

9.  **刪除**  
    點擊此按鈕將刪除目前區塊的選單項目。

    ----

10.  **儲存**  
    選單資料填寫完畢後點擊此處儲存。

    ----

11.  **增加主選單**  
    增加選單項目。

    ----

12.  **複製**  
    點擊此按鈕可選擇複製其他語系選單設定至目前語系，減少各語系間選單重複設定次數  
    <Icon icon="fa fa-exclamation-triangle" text="可設定的語系可能因您的管理員帳號權限而有所變化" color="warning" />。

    複製介面範例 |
    --|
    ![複製介面範例](/images/manual/menu_copy.png) |
</ModuleCheck>

----

## <Anchor id="menu_bottom" text="頁尾選單" />

頁尾選單設定方法同主選單，[按此前往說明](#menu_top)

----

## <Anchor id="contacts" text="聯絡人資訊欄位管理" />

管理網站各類表單欄位，可自由調整欄位名稱、排序、類型、是否必填 等... 功能。

聯絡人資訊欄位表單截圖 |
--|
![聯絡人資訊欄位主選單表單截圖](/images/manual/contacts_form.png) |

### 各號碼說明

1.  **<Anchor id="block_2-1" text="增加設定" ordered sub />**  
    增加一項聯絡人資訊欄位表單。

    ----

2.  **<Anchor id="block_2-2" text="表單標題" ordered sub />**  
    顯示欄位表單標題，滑鼠按住標題後移動可更改欄位排序。

    ----

3.  **<Anchor id="block_2-3" text="欄位類別" ordered sub />**  
    設定欄位類別；系統將以此類別決定顯示的欄位表單格式。

    聯絡人資訊欄位類別截圖 |
    --|
    ![聯絡人資訊欄位類別截圖](/images/manual/contacts_type.png) |

    ----

4.  **<Anchor id="block_2-4" text="欄位名稱" ordered sub />**  
    設定欄位顯示名稱。

    ----

5.  **<Anchor id="block_2-5" text="所屬模組" ordered sub />**  
    設定欄位顯示於哪項模組表單下，可複選。

    ---

6.  **<Anchor id="block_2-6" text="欄位定義" ordered sub />**  
    設定欄位作用，供系統確認欄位的意義；例：設定欄位為 "會員 email"，則此欄位紀錄的資料會用於發送信件給予會員。<small>(見下圖)</small>

    聯絡人資訊欄位定義截圖 |
    --|
    ![聯絡人資訊欄位定義截圖](/images/manual/contacts_mean.png) |

    ----

7.  **<Anchor id="block_2-7" text="必填切換開關" ordered sub />**  
    設定欄位是否必填。

    ---

8.  **<Anchor id="block_2-8" text="啟用切換開關" ordered sub />**  
    設定欄位是否顯示。

    ---

9.  **<Anchor id="block_2-9" text="表單顯示切換" ordered sub />**  
    因欄位表單佔用較多畫面，不容易利用滑鼠拖移排序，故滑鼠點擊此按鈕後，將隱藏表單內容方便排序。<small>(見下圖)</small>

    表單顯示切換截圖 |
    --|
    ![表單顯示切換截圖](/images/manual/contacts_toggle.png) |

    ---

10.  **<Anchor id="block_2-10" text="預設欄位" ordered sub />**  
    系統已預設幾組可快速設定的欄位組合，滑鼠點擊即可自動填入資料於欄位表單。<small>(見下圖)</small>

    預設欄位截圖 |
    --|
    ![表單顯示切換](/images/manual/contacts_default.png) |

    ---

11.  **<Anchor id="block_2-11" text="刪除" ordered sub />**  
    點擊此按鈕將刪除目前區塊的欄位表單設定。

    ----

12.  **<Anchor id="block_2-12" text="儲存" ordered sub />**  
    欄位表單資料填寫完畢後點擊此處儲存。

    ----

13.  **<Anchor id="block_2-13" text="增加設定" ordered sub />**  
    增加欄位設定項目。

    ----

14.  **<Anchor id="block_2-14" text="全部表單顯示切換" ordered sub />**  
    功能同[表單顯示切換](#block_2-9)，此按鈕可切換全部欄位表單顯示。

----

## <Anchor id="redirect" text="重新導向管理" />

設定網址路徑自動導向至目標網址。

重新導向管理截圖 |
--|
![重新導向管理截圖](/images/manual/redirect.png) |

### 各號碼說明

1.  **<Anchor id="block_3-1" text="增加" ordered sub />**  
    增加一項重新導向設定。

    ----

2.  **<Anchor id="block_3-2" text="導向類型" ordered sub />**  
    設定使用 301 轉址或 302 轉址，有關說明請參考以下文章：  
    <Blank href="https://zh.wikipedia.org/wiki/HTTP_301" text="HTTP 301 維基百科" /><br />
    <Blank href="https://zh.wikipedia.org/wiki/HTTP_302" text="HTTP 302 維基百科" />

    ----

3.  **<Anchor id="block_3-3" text="啟用切換開關" ordered sub />**  
    啟用或關閉轉址。

    ----

4.  **<Anchor id="block_3-4" text="來源網址" ordered sub />**  
    指定要"被"導向的網址

    ----

5.  **<Anchor id="block_3-5" text="導向網址" ordered sub />**  
    指定導向目標的網址

    ----

6.  **<Anchor id="block_3-6" text="刪除" ordered sub />**  
    點擊此按鈕將刪除目前區塊的轉址設定。

    ----

7.  **<Anchor id="block_3-7" text="儲存" ordered sub />**  
    轉址資料填寫完畢後點擊此處儲存。

<Footer />