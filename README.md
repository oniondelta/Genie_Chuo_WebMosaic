# 鑲嵌 WebMosaic 測試

### 效果：
- https://oniondelta.github.io/genie_chuo_webmosaic/

### 相關網址：

- 圖片來源：卓文萱 ( genie_chuo ) Instagram https://www.instagram.com/genie_chuo/

- WebMosaic 處理軟體：AndreaMosaic https://www.andreaplanet.com/andreamosaic/

- Instagram 抓圖套件：instaloader https://github.com/instaloader/instaloader

### 說明：

- 電腦「右鍵」/ 手機「長按」，顯示彈出框：〔大圖〕、〔日期〕、〔ShortCode〕、〔鑲嵌次數〕。

> * 點彈出框〔大圖〕：圖檔 jpg。

> * 點彈出框〔ShortCode〕：連結 Instagram 該圖 PO 帖。

- 左側 🔍 輸入日期（格式：2022-05-20）：搜尋該日期 PO 圖，以 ⭕️ 紅圈標示。

### 製作：

1. Python 套件 instaloader 下載「 卓文萱 ( genie_chuo ) Instagram 」，最初 2013-06-26 ~ 2022-05-20，共 1642 張。

2. AndreaMosaic 產生鑲嵌 Mosaic 網頁。

3. 修改 index.html，連結 Instagram PO 帖。

### 備註：

- Python 套件 instaloader 需使用 Instagram 帳號登錄。

- 承上，注意❗️區間抓圖太多，會封鎖該帳號抓取圖片，連正常網頁瀏覽 PO 帖也被封鎖。
