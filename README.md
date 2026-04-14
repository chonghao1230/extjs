# Ext JS 7.0.0 GPLv3
```
Ext JS 7.0 GPLv3 為2020年產品，如果需要支援現代化JS語法，請謹慎使用
官網的連結已經很難找到正確的SDK
該資料夾可以做為找到GPL的一個媒介
```

## GPLv3
```
使用 GPLv3，需滿足許多條件
GPLv3 相較於 LGPL 的限制衍生作品開源範圍：GPLv3： 修改後的程式碼加上「連結的程式」，整套都要開源。LGPL： 若僅是連結（特別是動態連結）LGPL 函式庫，你的應用程式程式碼不需要公開。商業應用限制：GPLv3： 商業應用需極度小心，幾乎無法閉源銷售。LGPL： 商業閉源軟體可廣泛使用，僅需在修改函式庫本身時公開修改處。
```

## 授權嚴謹度比較
```
較寬鬆
Level 1. MIT
Level 2. BSD 2/3
Level 3. Apache 2.0
Level 4. MPL 2.0
Level 5. LGPL 3.0
Level 6. GPL 2.0
Level 7. GPL 3.0
Level 8. AGPL 3.0
較嚴謹
```

## 使用方法如下
```
1. 安裝 Git (https://git-scm.com/)
2. 在你的電腦建立一個空的資料夾
3. 執行 cmd 命令提示字元，透過 cd 命令，將路徑到你在步驟2 建立的資料夾
4. 執行以下命令 git clone https://github.com/chonghao1230/extjs
5. 透過 Gemini、Claude Code 將你的構想告訴他
6. 記得要導入ext-7.0.0
```

## 在 index.html 導入 ext-7.0.0
```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>資訊系統名稱</title>
    <link rel="stylesheet" type="text/css" href="../ext-7.0.0/build/classic/theme-triton/resources/theme-triton-all.css">
    <script type="text/javascript" src="../ext-7.0.0/build/ext-all.js"></script>
    <script type="text/javascript" src="../ext-7.0.0/build/classic/theme-triton/theme-triton.js"></script>
    <script type="text/javascript" src="app.js"></script>
</head>
<body></body>
</html>
```
## 相關原廠連結
```
或者可以採用連結進行下載，避免有惡意程式遭植入
http://cdn.sencha.com/ext/gpl/ext-7.0.0-gpl.zip
https://cdn.sencha.com/cmd/7.0.0.40/jre/SenchaCmd-7.0.0.40-windows-64bit.zip
https://cdn.sencha.com/cmd/7.0.0.40/no-jre/SenchaCmd-7.0.0.40-linux-amd64.sh.zip
```
## Sencha CMD
```
C:\Windows\System32>cd /d C:/extjs

# 指向你的 SDK 路徑，並初始化當前目錄為 workspace
# sencha -sdk C:\path\to\your\ext-sdk generate workspace .

sencha -sdk C:/extjs/ext-7.0.0 generate workspace .

# 語法：sencha -sdk [SDK路徑] generate app [App名稱] [App存放路徑]
# sencha -sdk C:\path\to\your\ext-sdk generate app MyApp ./MyApp

C:\extjs>sencha -sdk C:/extjs/ext-7.0.0 generate app MyApp ./MyApp

cd MyApp
sencha app refresh
sencha app watch
```

## dev.bat
```
@echo off
title Sencha Watch - MyApp
cd /d C:\extjs\MyApp
echo 正在啟動 Sencha App Watch...
sencha app watch
pause
```
