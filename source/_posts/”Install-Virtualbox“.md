---
title: 1-2_安裝Bitnami Moodle
categories: 第一節
date: 2017-08-23 11:22:48
timestamp: 2017-08-23 11:22:48
tags:
---
## 去官網下載Bitnami Moodle
![搜尋Bitnami Moodle](/images/1-1-1.png)
![點擊進入官網](/images/1-1-2.jpg)
![點選右下角的Moodle Virtual Machines](/images/1-1-3.jpg)
![點Download](/images/1-1-4.jpg)
![點下方的No Thanks](/images/1-1-5.jpg)
他就會開始下載了。。。。

## 安裝Bitnami Moodle
![這是下載下來的樣子，雙擊開啓](/images/1-1-6.png)
![這個頁面可以設定虛擬機的資源，也可以不更改就按下匯入](/images/1-1-7.png)
![匯入完成，點選上方的啓動](/images/1-1-8.png)

## 啓動後的設定

### 預設賬號密碼
首次啓動，簡單介紹畫面：
![](/images/1-1-9.jpg)

| 項目 | 預設帳號/密碼 |
| ----- | ----- |
| Moodle | user/bitnami |
| VM端管理 | bitnami/bitnami |

### 靜態IP設定
如需更改成靜態IP，請輸入以下指令

瀏覽目前的IP
```sh
$ sudo ifconfig
```

更改IP

```sh
$ sudo ifconfig eth0 [你的ip] netmask [子網域遮罩]
$ sudo route add default gw [匝道IP]
```

範例：

```sh
$ sudo ifconfig eth0 192.168.1.253 netmask 255.255.255.0
$ sudo route add default gw 192.168.1.254
```



