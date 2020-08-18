# 2020 Software.Developer-I
請依照下面虛擬情境的需求以及要求之技術，完成該情境需求的系統

**因應即時性資訊對於生產監控的重要性，因此，需要能做到即時監控機台資訊，並將資訊呈現於Web，讓使用者可以了解目前現場設備的狀況，且透過Web也可以對於遠距管理也是有相當大的幫助。**

##### 原始需求
1. 建立一個Console Application模擬三條生產線，每條生產線一機台的產出資料，需模擬的資料有
   - 不同產品(三條線最少三種產品)的投入與產出數量
   - 機台運行狀態
   - 機台異常狀態
2. 即使資訊最少要包含每條線別的設備運行狀態、異常資訊顯示、機台內目前WIP數和當日累積WIP量
3. 建立一個報表可以查詢WIP生產數量，其用長條圖顯示，並可以將結果下載成Excel檔案
4.  WEB請用SPA架構設計，最少要做到Web <--> API <--> DB 架構

# Skill Requirement
> 環境
- 請將開發之系統，佈署至Micrsoft Azure (可免費使用30天)
- 請將程式碼透過Azure DevOps Service進行版控 (可免費使用)，請將專案設定公開
> 技術
- Web : 請使用ASP.Net Core 3.1 開發
- 前端框架: 請使用Vue.js 開發
- Web API : 請使用.Net Core 3.1開發
- DataBase : MS SQL，務必使用SQL Project管理SQL Script
請用signalr技術完成即時通訊的需求，所有開發都必須有版控機制

# Acceptance Criteria
> 時間
- 依照HR指定時間完成，並再跟HR約第二次面談時間

> 成果展示
- 於第二次面試時間的前一週，分享自己在Azure DevOps Service的`Repository`給主考官，Repository須設定為公開

> 第二次面試時，請現場Demo作品及說明系統架構
- Demo時，請直接使用Azure Web Site成品展示
- 當天顯示Azure DevOps Service版控歷史紀錄

> 請依照`Description`，發揮創意、設計解決方案

> 第二次面試時，請你所認知的`DevOps`如何在團隊運行
