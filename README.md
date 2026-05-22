# 📅 12週培訓課程

## 🎯Week01 需求分析與使用案例圖
- ☐ 能從試題文件中識別所有系統使用者(Actor)
- ☐ 能識別至少15個有意義的使用案例(Use Case)
- ☐ 能正確繪製Use Case圖，包含關聯線與《include》《extend》關係
- ☐ 了解55分區 ZCharge Plan 與 56分區 LinkOne 的系統範疇

## 🎯Week02 ER 圖設計與資料庫正規化
- ☐ 能識別系統中的主要實體(Entity)及其屬性
- ☐ 能正確定義主鍵(PK)、外鍵(FK)和候選鍵
- ☐ 能驗證資料表是否符合第三正規形式(3NF)
- ☐ 能繪製含基數(Cardinality)的ER圖

## 🎯Week03 T-SQL 語法與測試資料建立
- ☐ 能正確撰寫帶有各種約束條件的 CREATE TABLE 語法
- ☐ 能使用 SQL 批次插入100筆以上真實感測試資料
- ☐ 能撰寫基礎 SELECT、JOIN、GROUP BY 查詢
- ☐ 能建立簡單的 Stored Procedure 封裝業務邏輯

## 🎯Week04 Entity Framework Database-First + 可繼承表單架構
- ☐ 能安裝 EF Core NuGet 套件並執行 Scaffold-DbContext 產生 Model
- ☐ 能建立 AppDb 靜態類別統一管理 DbContext
- ☐ 理解 BaseDetailForm 繼承模式，子表單只覆寫必要方法
- ☐ 能設計 CrudToolbar UserControl 供所有管理表單共用

## 🎯Week05 Entity Framework LINQ CRUD 完整操作
- ☐ 能使用 LINQ .Where() .OrderBy() .ToList() 實作多條件搜尋
- ☐ 能用 AppDb.Context.Add() / Remove() + SaveChanges() 完成 CRUD
- ☐ 能用 .Include() 載入關聯資料（避免 N+1 查詢）
- ☐ 能在刪除前用 .Any() 檢查關聯資料，改為軟刪除（IsActive=false）

## 🎯Week06 C# 進階功能：EF 認證、計時器與角色控管
- ☐ 能使用 EF LINQ 查詢驗證帳號密碼（SHA256 雜湊比對）
- ☐ 能實作閒置2分鐘自動登出（含30秒倒數警告）
- ☐ 能根據角色動態顯示/隱藏 MenuStrip 與 TabPage
- ☐ 能實作符合規則的自動產生強密碼功能

## 🎯Week07 Android/Kotlin Jetpack Compose UI 設計與導航
- ☐ 能建立 Android Studio + Kotlin + Compose 專案
- ☐ 能以 @Composable 函式組合 UI，取代 XML layout
- ☐ 能用 LazyColumn 顯示清單，取代 RecyclerView
- ☐ 能用 NavigationBar + NavHost 實作底部多頁切換

## 🎯Week08 Android REST API 整合（內建函式庫）
- ☐ 能使用 HttpURLConnection 發送 GET / POST 請求
- ☐ 能使用 org.json.JSONArray / JSONObject 解析 JSON 回應
- ☐ 能建立 ApiClient singleton 統一管理 HTTP 請求
- ☐ 能在 Coroutines withContext(Dispatchers.IO) 執行網路操作

## 🎯Week09 55 分區模擬競賽 — ZCharge Plan
- ☐ 在限定時間內完成SA&DB模組（建議：2小時）
- ☐ 限定時間內完成Software模組（建議：3小時）
- ☐ 在限定時間內完成App模組（建議：2.5小時）
- ☐ 找出個人弱點並制定補強計畫

## 🎯Week10 56 分區 — LinkOne 資料庫設計
- ☐ 理解56分區 LinkOne 的業務需求與資料庫改造範疇
- ☐ 能設計符合 New_ 前綴規範的新增資料表
- ☐ 能撰寫CSV資料匯入與資料轉換SQL腳本
- ☐ 能設計內容安全審核的狀態機資料結構

## 🎯Week11 56 分區 — LinkOne 軟體與 App 整合
- ☐ 能實作內容審核工作流程（AI評分顯示 + 人工批准/拒絕）
- ☐ 能實作貼圖商城的瀏覽與購買流程
- ☐ 能在Android App中顯示二層留言結構
- ☐ 能整合所有模組完成56分區完整系統

## 🎯Week12 全國賽模擬 — 系統整合與競賽策略
- ☐ 能在全國賽時間限制內完成所有模組的核心功能
- ☐ 能在1.5-3分鐘內清晰說明系統設計決策
- ☐ 能識別並避免常見扣分錯誤
- ☐ 建立個人化的競賽當日執行清單