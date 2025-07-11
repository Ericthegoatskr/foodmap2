# 美食地圖推薦 FoodMap

一個結合 Google Maps API 的美食地圖推薦網頁，支援地點搜尋、分類篩選、餐廳評論、收藏、輪盤抽選等功能，讓你輕鬆找到附近好吃的店！🍜🍰☕

## 主要功能特色
- 📍 依據使用者定位搜尋附近餐廳
- 🔍 支援分類（火鍋、日式、甜點、咖啡廳）快速篩選
- 📝 查看 Google 地圖餐廳評論
- ❤️ 收藏喜歡的店家（本地儲存）
- 🎲 輪盤抽選隨機選店，還有咔咔音效
- ✨ 響應式設計，手機/桌機都好用

## 安裝與啟動方式
1. 下載或 clone 此專案
2. 於專案根目錄建立 `config.js`，內容如下：
   ```js
   const config = {
     GOOGLE_MAPS_API_KEY: '你的 Google Maps API 金鑰'
   };
   ```
3. 於本機直接開啟 `index.html` 即可使用

## Google Maps API 金鑰申請教學
- 前往 [Google Cloud Console](https://console.cloud.google.com/)
- 建立專案並啟用 Maps JavaScript API、Places API、Geolocation API
- 建立 API 金鑰並填入 `config.js`

## 主要技術
- HTML / CSS / JavaScript
- Google Maps JavaScript API
- LocalStorage（收藏、暫存）

## 畫面截圖


## 作者
- Ericthegoat

---
有任何建議或問題歡迎開 issue！ 
