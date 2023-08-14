# Power-consumption-forecast
**短期太陽能用電量預測**  
專案執行期間2022/6~2022/12  
透過用電量的預測，進行微電網內儲能系統日前排程與即時最佳調度  

1.使用 bs4, request 等 python 模組串接氣象局、政府開放 API 資料  
2.使用 python 連結 MySQL 資料庫  
3.使用 numpy、pandas、json 等python 模組進行資料前處理  
4.使用 Scikit-learn之python 模組訓練機器學習模型進行發電量預測  
5.使用 matplotlib、plotly 等 python 繪圖套件進行數值可視化  

**預測模式**
隔日逐時預測  
當日提前1小時預測  
當日提前15分鐘預測  


