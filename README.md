# 2019 年紐約市 (NYC) Airbnb 房源數據分析

## 1. 背景與概述
Airbnb 成立於 2008 年，現已成為全球領先的短租平台。其中，紐約市 (NYC) 作為全球觀光與商業樞紐，擁有極其龐大且複雜的房源生態系統。此分析聚焦在 2019 年的紐約市 Airbnb 公開房源數據。
* 分析目標：
* 主要工具：Python (Pandas, Matplotlib, geopandas, seaborn)

## 2. 數據結構說明
此分析使用數據包含約 4,8000 筆房源資料，涵蓋 16 個欄位：
| 類別 | 關鍵欄位 | 說明 |
|---|---|---|
| **房源資訊** | `id`, `name`, `room_type` | 包含房名稱及類型 |
| **房東資訊** | `host_id`, `host_name`, `calculated_host_listings_count` | 房東相關資訊 |
| **地理資訊** | `neighbourhood_group`, `neighbourhood`, `latitude`, `longitude` | 涵蓋紐約五大行政區 |
| **定價與條件** | `price`, `minimum_nights`, `availability_365` | 房源核心經濟指標 |
| **評論指標** |   `reviews_per_month`, `number_of_reviews`, `last_review` | 用戶活躍度指標 |

## 3. 分析結果
* 市場分佈：
<img width="300" src="/img/img01.jpg">

<img width="300" src="/img/img02.jpg">


<img width="300" src="/img/img03.jpg">


<img width="300" src="/img/img04.jpg">


<img width="300" src="/img/img05.jpg">

* 價格
* 熱門

## 4. 洞察

## 5. 建議
