# Ajax-Type-Head
[DEMO](https://chihtsunglu.github.io/Ajax-Type-Head/ajax-type-ahead.html)


## 建立搜尋列表
#### 1.陣列建立並使用fetch()
使用預先建立之Json檔案。
建立空陣列`cities`並透過`fetch()`存取資料

#### 2.findMatched()
創建一個正規表達式，用於全局、不區分大小寫地匹配輸入值 wordToMatch。
對 cities 陣列使用 filter。
檢查城市及州名是否與正規表達式匹配。

#### 3.numberWithCommas(x)
用於將數字格式化為帶有千位分隔符的字串，以提升可讀性，例如將 1000000 格式化為 1,000,000。

#### 4.displayMatches()
顯示與輸入值匹配的城市資訊，利用`addEventListener`監聽輸入框的change & keyup
