# 📚 Time Library System

一個基於 Spring Boot + Vue 的圖書館藏查詢系統，支援簡易搜尋(Elasticsearch 全文檢索)、進階搜尋、會員管理、圖書借閱、座位預約、評論反饋等多項功能。

![畫面預覽](https://your-image-url-if-any.com) <!-- 如有系統畫面可以放這裡 -->

---

## 🧾 專案特色

- 🔍 關鍵字與多條件進階搜尋（類別、語言、出版年）
- 🖼️ 顯示書籍封面與摘要（整合 Google Books）
- ⚡ 書籍封面預先快取，前端快速載入
- 🔎 後端支援 Elasticsearch 全文檢索與 欄位權重
- 📘 前端使用 Vue + Nuxt 

---

## 🛠️ 使用技術

| 分類           | 技術 / 工具                                                   |
|----------------|---------------------------------------------------------------|
| 📦 前端         | Nuxt3 + Vue 3（單頁式應用 SPA） |
| ⚙️ 後端         | Spring Boot（Java 17）、Spring Data JPA、RESTful API         |
| 🧮 資料庫       | MySQL（儲存結構化資料）、Elasticsearch（全文檢索）            |
| 🔄 資料前處理   | Python（清洗與轉換，批次寫入 MySQL 與 Elasticsearch）         |
| 📦 部署         | Docker（容器化部署所有元件）                                  |
| 📡 通訊格式     | JSON（前後端透過 API 傳輸資料）                               |
| 🔁 版本控管     | Git + GitHub                                                  |

---


## 🚀 如何啟動專案

### ✅ 後端（Spring Boot）

```bash
cd spring-library-backend
./mvnw spring-boot:run
