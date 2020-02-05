# ma_john_app
ma john dataset, object recognition, neural network, application

最終目標︰實現算台功能

目前規劃進度

1. 製作麻將資料庫

2. 使用 yoloV3 訓練物件偵測 model 並維持一定的準確率

3. 結合 line bot 做互動，或者是將 model 放上手機做 inference

4. 處理資料庫及多執行緒問題

5. 加入廣告

6. 做成 app

# 20200205 進度

規劃麻將資料庫內容

台灣麻將總共有 42 張不同的牌，包含 1 ~ 9萬桶條，東南西北中發白，8 張花牌

每一張牌取 100 筆樣本，共 4200筆

拍攝 420 張圖片，每張圖片包含 10 張樣本，當作 training data

再拍 80 張 做 validation，100 張做 testing

一共 600 張圖

Label tool 為
https://github.com/tzutalin/labelImg
