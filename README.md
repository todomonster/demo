# demo

[前端正式區已合併] v0.9.2
- 修復多項錯誤
- 配合拍片 將TDM名稱預設為 Una; 使用者名稱: 劉曉華,預設購物車藥水為藍色
- 更換拍手 icon
- 專案能正確由首頁進入

部署同步至v0.9.2
https://todomonster.github.io/demo


```md
參考:

https://www.html5gamedevs.com/topic/39073-the-spinedata-param-is-required-in-pixie-spine-project-help-help/page/2/

pixi 不會給 react 管理，無法動態拿 pixi-spine 的資料!只能放在 public 裡面

測試部署到https://todomonster.github.io/demo/

注意!

"homepage": "https://todomonster.github.io/demo/",
App.js  HashRouter
注意有沒有亂用href 例如<Navbar.Brand href="/demo">
```
