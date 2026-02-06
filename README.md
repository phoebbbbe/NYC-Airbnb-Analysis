# 2019 年紐約市 (NYC) Airbnb 房源數據分析

## 1. 背景與概述
Airbnb 自 2008 年創立以來，憑藉其創新的共享住宅模式，成功建構了連結全球房東與旅客的橋樑，提供深具在地特色的住宿體驗。其中，紐約市 (NYC) 作為全球觀光與商業樞紐，擁有極其龐大且複雜的房源生態系統，本專案透過對 2019 年紐約市 Airbnb 公開房源數據的系統性分析，挖掘隱藏在定價、區域背後的關鍵洞察，為房東與平台運營者提供數據驅動的決策支持。

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
#### 2019 年紐約市房源供給地理分佈
透過地理熱力圖，可以觀察到 2019 年紐約市 Airbnb 市場高度集中在布魯克林 (Brooklyn, 42.3%) 與 曼哈頓 (Manhattan, 41.6%)，兩區合計甚至佔據了全紐約超過 80% 的房源供給。相較之下，史泰登島 (Staten Island) 僅佔 0.9%，顯示出市場重心極度偏向商業與文化機能發達的核心區域。

進一步分析供給量的前30名，布魯克林區超過三成的房源集中在 Bedford-Stuyvesant (2,736 筆, 20.5%) 與 Williamsburg (2,384 筆, 17.9%) 為首，曼哈頓區則以 Harlem (1,900 筆) 與 Hell's Kitchen (1,310 筆) 最為密集。

<img width="1200" src="/img/img01.jpg">

<img width="600" src="/img/img02.jpg">


<img width="600" src="/img/img03.jpg">


<img width="800" src="/img/img04.jpg">


<img width="800" src="/img/img05.jpg">

* 價格
* 熱門

## 4. 洞察

## 5. 建議
