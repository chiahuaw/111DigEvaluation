# 110年度國營事業管線挖掘市區道路施工回填復舊考評計畫

此為內政部營建署之全國規模道路挖掘施工後的復舊品質考評計畫，抽查完工時間介於109年9月1日至110年8月31日間之道路挖掘許可案。

因此為減低主觀認知偏差及爭議，抽選案件原則上採電腦隨機抽樣，並將抽樣方式公開於Github平台。

## 抽選原則

1. 未滿15件者，全選。
2. 大於15件者，抽選15件，抽選規則如下：
  + 大於15件、小於30件者，依面積排序後，由大至小依序選15件。
  + 超過30件者，從大於面積中位數的案件中隨機抽選15件。
  
## 檔案說明

+ 01Data_alldig.RData：以API從道路挖掘管理系統下載之資料
+ 01Data_case1.RData： 清理案件後之資料
+ 01Data_case2.RData： 按抽選原則抽選後之資料
+ 01lottery.R： 資料取得、清理及抽選之原始碼
+ 02toXML.R： 抽選後檔案轉XML格式
+ 03toKPI.R：指標計算

## 指標計算結果

|單位                          |  件數| 已申報完工|  比例|
|:--------------------------------|--:|----------:|------:|
|中華電信公司金門營運處           | 10|         10| 1.0000|
|台灣電力股份有限公司金門區營業處 | 99|         98| 0.9899|
|金門縣自來水廠                   | 26|         19| 0.7308|


|單位                          |  件數| 應辦理圖資更新| 已辦理圖資更新|  比例|
|:--------------------------------|--:|--------------:|--------------:|------:|
|中華電信公司金門營運處           | 10|             10|             10| 1.0000|
|台灣電力股份有限公司金門區營業處 | 99|             99|             56| 0.5657|
|金門縣自來水廠                   | 26|             24|              4| 0.1667|