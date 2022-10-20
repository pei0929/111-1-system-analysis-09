**小組作業1** : 
顯示在小組的github上，請列出專案的
- 組長與組員之姓名
- 個別組員的任務
- 專題題目
- 內容
- 甘特圖與PERT/CPM圖 (期限: A班 10/10 , B班10/11)

## 專案組別: 9

### 組員介紹與分工

|     第9組     |  姓名  |                   個別任務                   |
| :------------: | :----: | :------------------------------------------: |
| **組長** | 林澤權 | 題目構想、流程設計、功能構想、後端開發、測試 |
|      組員      | 潘沛儀 |    需求構想、市場調查、前端開發、企劃發想    |
|      組員      | 李翊翎 |    需求構想、市場調查、前端開發、企劃發想    |
|      組員      | 陳宥諺 |          資料庫設計、後端開發、測試          |
|      組員      | 林貞智 |         題目構想、功能構想、後端開發         |

### 專題題目

- 失蹤人口分析與找尋(暫定)
- 車輛拖吊分析與找尋

### 內容

1. 依據[國家人口失蹤資料集為來源](https://data.gov.tw/dataset/14420)，可以透過其資料集，分析年齡層、失蹤性別、地區比例等... 提供相關研究人員參考
2. 透過平台，可以依據失蹤地點、特徵、年齡、時間去篩選可能的人選

### 甘特圖



- mermaid繪製版本

```mermaid

gantt
    title 第九組小組作業甘特圖

    section 第一階段
    題目構想     :a1, 2022-10-4, 7d
    需求構想     :a2,after a1  , 8d
    功能構想     :a3 , after a2  , 6d
    section 第二階段
    市場分析     :b1, 2022-11-1, 8d
    客群分析     :b2, after b1, 8d
    評估可行性   :b3, after b2  , 8d
    section 第三階段    
    前端開發      :c1,after b3 , 12d
    資料庫建立      :c2 ,after b3, 12d
    後端開發	:c3 ,after b3, 12d
    section 第四階段    
    系統整合:d1,2022-12-2 , 7d
    測試、修改: d2, after d1 , 10d
    成品展示:d3, after d2 , 5d
  
```

### PERT/CPM圖

- google繪製版本
![image2](https://user-images.githubusercontent.com/57654809/194913530-bee24e8f-ccb6-407b-832b-d13519a7ea62.png)

- mermaid繪製版本

[PERT圖繪製版本連結](https://hackmd.io/@cjqBX7RDSMSJUP0adJLUmw/rkDcmRbmj)
![image1](https://user-images.githubusercontent.com/57654809/194921178-9523aca4-c214-4174-aa56-570bd8a2b2ea.png)

