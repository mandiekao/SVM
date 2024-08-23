將下述丟入websim:
展示支持向量機(SVM)分類器的交互式演示網頁。它使用RBF核函數來分類兩類點：內圓（半徑<3）和外環（3<=半徑<=6）。網頁包含兩個圖表：一個2D散點圖和一個3D表面圖，用來可視化SVM的決策邊界
•	創建一個websimHTML文件，設置基本結構和必要的庫引用。"
•	"實現generatePoints函數，生成圓形分佈的隨機點。"
•	"實現rbf函數作為SVM的核函數。"
•	"使用SMO算法實現trainSVM函數。"
•	"實現predict函數用於SVM預測。"
•	"創建generateAndTrain函數，整合數據生成、SVM訓練和圖表繪製。"
•	"使用Plotly.js創建2D散點圖和等高線圖。"
•	"創建3D表面圖展示SVM決策邊界。"
•	"為生成新數據的按鈕添加事件監聽器。"
•	"優化樣式和佈局，確保良好的用戶體驗。
Websim demo:
https://websim.ai/c/uZlhUsLLcT1p7JgQL
