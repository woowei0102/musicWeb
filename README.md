# 資料庫系統 - 音樂分享網頁

## 介紹
利用SQL資料庫作一個音樂收集網頁，有新增、刪除以及修改的功能，並可用語言來作搜尋，可針對主頁進行語言分類。

## 使用語言
* JavaScript
* PHP
* SQL

## 使用方式
當時使用學校的環境實作資料庫系統，現在無法顯示，請詳看`實作細節`。

## 製作細節
* 主頁新增按鈕
    * Show: 可選擇各種語言，透過此按鈕，可對歌曲進行分類
    * Revise: 跳到另一個頁面
    * 新增: 跳到另一個頁面
    * 刪除此資料: 刪除該行的歌曲，並對網頁歌曲做整理

* 新增歌曲頁面
    * SongName:可填寫歌曲名稱
    * Language: 下拉式選單
    * Source: 可填寫網址，日後到主頁上便可直接轉成`超連結`
    * 提交: 把上方三列資料寫進資料庫，並回到主頁
    * 返回: 回到主頁
* 修改歌曲頁面
    * SongName必須符合至資料庫中的`$songname`要一致才可以針對Language、Source作修改，並更新資料庫

## 網頁頁面
### index.php
![](https://i.imgur.com/UFeQa6Z.png)

### insert.html
![](https://i.imgur.com/kpC26RY.png)

### insert.php
![](https://i.imgur.com/ZWF9AVn.png)

### revise.php
![](https://i.imgur.com/NzhG7rS.png)

### revising.php
![](https://i.imgur.com/1C5hnGI.png)

## 結論
寫了這份小專案，讓我對JS、PHP以及SQL有一定的認識，是一個不錯的經驗，感謝老師的教導。