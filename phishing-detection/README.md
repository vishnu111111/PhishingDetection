# Online viewer
- [CNN-LSTM.ipynb](https://nbviewer.jupyter.org/github/hjcian/CNN-LSTM-phishing-detection/blob/master/CNN-LSTM.ipynb)
# 參考資料
- CNN-LSTM Keras 架構參考自[Keras » Examples » Sentiment classification CNN-LSTM](https://keras.io/examples/imdb_cnn_lstm/)
- 參數參考自[Phishing website detection based on multidimensional features driven by deep learning](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8610190)
    - max_features = 96 (怎麼算都算不出 paper 中的 97個)
    - maxlen = 400 (參考選用邏輯，paper 中的 L = 200)
    - batch_size = 64
    - epochs = 20
    - pool_size = 2 (從圖說上畫的猜的)
    - 其餘參數皆先使用 Keras eample 上的建議
