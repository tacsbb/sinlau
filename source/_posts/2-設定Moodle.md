---
title: 2-設定Moodle
categories: 測試
date: 2017-08-21 11:45:05
timestamp: 2017-08-24 11:45:05
tags:
---
## Moodle基礎設定
本業將介紹Moodle網站運作的最基本設定
### 登入Moodle平台
首先，在瀏覽器輸入剛剛設定的Ip位址，就會看到以下畫面
![點選右上角的Login，進入登入畫面](/images/2-1-1.jpg)
在這邊輸入預設帳號密碼 user bitnami
![](/images/2-1-2.jpg)
### 設定網站語言
登入完成後，點選左側的Site administration
![](/images/2-1-3.jpg)
往下移動畫面，在Language那排，點選Language Packs
![](/images/2-1-4.jpg)
在右側 Available Language packs ，找正體中文zh_tw，接著按下Install selected language packs
![](/images/2-1-5.jpg)

接著回到Site Administration，找到剛剛的Language，點選Language Setting
![](/images/2-1-6.jpg)
在Default Language選擇正體中文
![](/images/2-1-7.png)
另可在Languages on language menu 輸入zh_tw，能夠選擇的語言就會固定在正體中文
![](/images/2-1-8.png)

這時候，回到首頁，還沒有更改成英文，這是因為管理員帳戶預設是英文導致

右上角圖像的部分，點一下，找Preferences
![](/images/2-1-9.jpg)
下方User Account > Preferred language
![](/images/2-1-10.jpg)
選擇正體中文，再按下Save Changes
![](/images/2-1-11.jpg)
屆時，就會看到中文畫面了。

### 設定網站資料
回到Site administration（中文化的名稱是：網站管理）
![](/images/2-1-12.jpg)
滾輪滾到下方，點選 首頁設定
![](/images/2-1-13.jpg)
修改首頁的相關資料
![](/images/2-1-14.png)

### 建立新使用者
回到網站管理。選擇 用戶 頁籤，下方的 新增一位用戶
![](/images/2-1-15.jpg)
完成以下資訊
![](/images/2-1-16.png)
建立完成
![](/images/2-1-17.png)

| 身份 | 預設帳號 | 預設密碼 |
| ----- | ----- | ----- |
| 教師 | teacher01 ～05 | Teacher!1~Teacher!5 |
| 學生 | student01~05 | Student!1~Student!5 |


