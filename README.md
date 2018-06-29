# InsiderDevTour18-Office365

https://github.com/08Alan/InsiderDevTour18-Office

### 建立一個Teams Tab App
開啟Teams 開發人員權限
https://docs.microsoft.com/zh-tw/microsoftteams/platform/get-started/get-started-tenant

`npm i -g npm`

安裝Yeoman和Gulp Yeoman創建新項目，
使用Microsoft團隊的Yeoman生成器快速創建基於JavaScript的解決方案。 
輸入以下命令安裝Yeoman和gulp：
`npm install -g yo gulp`

`npm install generator-teams@preview -g`

### download ngrok
https://dashboard.ngrok.com/get-started

### 利用yeoman建立teams專案
`md AlanApp1`
`cd AlanApp1`
`yo teams`

### build a tab
https://tbd.ngrok.io

### Authentication 
`npm install msal@0.1.1`

### 新增auth.ts , auth.html , client.ts
`請查閱我Commit上去的code`

### 執行監聽
`ngrok http 3007`

### 修改manifest的有效監聽位置
manifest.json > tbd.ngrok.io > ngrok的url

### 打包及編譯
`gulp manifest`
`gulp build`
`gulp serve`
http://localhost:3007/

Teams 新增app

## 安裝Teams - App Studio
https://docs.microsoft.com/en-us/microsoftteams/platform/get-started/get-started-app-studio\

