# Presets ｜ 成品的做法

`templates/` 給的是版面；preset 給的是**「這份東西以前怎麼做的」**。

不是「A4 講義」這種體裁，是「Sound Engineering 的課，做成什麼樣」。
拿到一份材料，先找一個長得像的 preset，照它的規矩做。

## 目前有這幾個

| preset | 材料 → 成品 | 一句話 |
|---|---|---|
| [`sound-engineering/`](sound-engineering/) | 投影片 → 原稿對照（橫式） | 原稿在上、中文在下，一節一頁 |
| [`jazz-harmony/`](jazz-harmony/) | 投影片 → 中文版講義（直向） | 中文在上、原稿在下 |
| [`max-msp/`](max-msp/) | patch → handoff | 編號找到方塊，★ 標可動參數 |
| [`dance-music/`](dance-music/) | 課件 → 中文整理 | 節奏畫成格，重點放大數字 |
| [`western-culture/`](western-culture/) | 圖和日文 → 圖解 | 一頁一張圖，圖說寫來源 |

## 怎麼挑

- 投影片、橫式、原稿要**同時看到** → `sound-engineering`
- 投影片、直向、**先讀中文再看原稿** → `jazz-harmony`
- 要**動手接線** → `max-msp`
- **沒有原稿可貼**，但要講聲音 → `dance-music`
- **圖很多**，目的是看懂圖 → `western-culture`

找不到像的，就照下面寫一個新的。

## 每個 preset 都長這樣

- **一句話**　這是什麼成品
- **必須有**　缺一不可（踩過坑才知道的那些）
- **絕對不要**　最常見的做壞方式
- **參照**　真的做過的那一份，看它
- **判斷**　怎麼知道做對了

`preview.png` 放在最上面，是實際印出來的一頁。

## 新增一個 preset

開一個資料夾，名字是「這個成品叫什麼」（課名或專案名，不是體裁名），
放一張真的印出來的 `preview.png`，照上面五段寫完。不要放程式碼。
