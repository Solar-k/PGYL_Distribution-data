![header](https://capsule-render.vercel.app/api?type=waving&color=auto&height=100&section=header&fontSize=90)
# PGYL: [Retail Data Utilization Competition](https://festa.kdlc.or.kr/circulation)

### Analysis Topic

---

Enhancing operational efficiency in small retail companies through accurate demand forecasting



### Analysis Objective

---

The current reality of low competitiveness in small retail companies and local stores is attributed to inefficient inventory management and inaccurate demand forecasting. Therefore, there is a need to introduce advanced demand forecasting models to enhance competitiveness.



## Overall Project Contents

To achieve accurate demand forecasting, we utilized additional data in the preprocessing stage and performed filtering, handling missing values, and merging specifically for the target items to be predicted. In the modeling phase, we employed time series decomposition, multivariate analysis, and clustering to identify key variables, ultimately selecting the Prophet model as our final choice. During model training, we incorporated seasonality, trend, residuals, and trends into the process to enhance accuracy, emphasizing the importance of data preprocessing in improving prediction accuracy.

---

##  Expected Effects

#### 1. Optimization of warehouse leasing solution

- Currently, the majority of small logistics companies face serious spatial inefficiency due to fixed space leasing.
- To address this, we classify products into seasonal and non-seasonal items through demand forecasting.
- For non-seasonal items, we derive optimal warehouse space utilization patterns through regular ordering.
- For seasonal items, we use the predictive model to forecast and assess prosperity and downturn, enabling the derivation of optimal storage and diversification strategies based on periods and timing.
- By implementing these approaches, we aim to enhance the competitiveness of small retail companies and achieve cost reduction effects in leasing.

#### 2. CPG marketing support for small businesses

- Currently, many retail stores rely on personal intuition or fragmented data for marketing activities.
- We provide small businesses with estimated demand and CPG marketing effects based on the characteristics of retail stores.
-  we offer periodic marketing guidance based on environmental changes.
- Through the provision of marketing support, we anticipate increased sales for small businesses and activation of local consumption.

---

### Utilized Data and Reference Sources

1. [코로나 확진자 수 데이터](https://www.mohw.go.kr/)
2. [일일 강수량 데이터](https://bd.kma.go.kr/kma2020/svc/main.do)
3. [소비자 물가지수 데이터](https://kosis.kr/statisticsList/statisticsListIndex.do?menuId=M_01_01&vwcd=MT_ZTITLE&parmTabId=M_01_01&statId=1964001&outLink=Y&entrType=#P2_6.2)
4. [소비자 심리지수 데이터](https://kosis.kr/statisticsList/statisticsListIndex.do?menuId=M_01_01&vwcd=MT_ZTITLE&parmTabId=M_01_01&statId=1964001&outLink=Y&entrType=#P2_6.2)
5. [기상청데이터를 활용한 유통수요예측 보고서](https://bd.kma.go.kr/kma2020/svc/main.do)

---
🛠 Tech Stack
