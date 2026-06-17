# 視覺影像辨識之無人車自動倒車入庫

## 專題簡介  

本專題結合深度學習影像辨識、ROS機器人系統以及模糊控制技術，
開發具備自動倒車入庫能力之無人車。

系統透過攝影機擷取即時影像，
利用SSD(Single Shot Detector)模型辨識停車格位置，
並透過ROS進行資料整合與傳輸，
結合模糊控制演算法計算車輛轉向角度與車速，
最終完成自動倒車入庫功能。

## 使用技術

- Python
- OpenCV
- SSD (Single Shot Detector)
- Jetson Nano
- ROS
- Fuzzy Control
- Arduino 1284P
- Ubuntu Linux

## 系統架構

1. 蒐集大量停車格影像資料並進行 Bounding Box 標註
2. 使用 SSD 模型訓練停車格辨識系統
3. CSI Camera 擷取即時影像
4. Jetson Nano 執行即時推論
5. ROS 整合影像辨識與控制資料傳輸
6. Fuzzy Control 計算轉向角度與車速
7. Arduino 1284P 控制馬達與轉向機構
8. 完成自動倒車入庫

##個人負責內容

1. 收集相關無人車資料參考
2. 訂購無人車缺少材料資源以及CSI鏡頭裝設
3. 拍攝大量停車格不同角度照片以及用Bounding Box標註
4. 了解部分SSD模型並測試調整模糊控制的參數
5. 實際跑並測試調整車子輪胎的轉速

## 展示影片

(https://www.youtube.com/watch?v=XVhJ-I6XpU8)
