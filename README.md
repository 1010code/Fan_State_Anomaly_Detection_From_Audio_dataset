

## 資料集描述
這個資料集是 SensiML 展示的一個風扇運轉訊號的音頻資料集。這些音頻數據是通過麥克風收集的，用來識別風扇運轉時的不同狀態。每一份音檔都是 16kHz 的採樣率，長度為 5 秒。資料集中包含了 5 個不同的類別或標籤，分別是：

- 'ON': 0，代表風扇開啟運轉狀態。
- 'OFF': 1，代表風扇關閉狀態。
- 'FAN': 2，代表正常運轉的風扇聲音。
- 'BLADE FAULT': 3，代表風扇葉片故障或異常聲音。
- 'TAPPING': 4，代表敲擊或碰撞風扇機體的聲音。

這個資料集中的訓練集包含 140 個音頻樣本，測試集包含 28 個音頻樣本。這些樣本可用於訓練和測試機器學習模型，以識別風扇運轉時的不同狀態，例如確定風扇是否正常運轉、是否有異常聲音或故障。這對於監控和維護風扇設備以及預防故障具有重要意義。
- Train(140)
    - ON             60
    - OFF            40
    - BLADE FAULT    15
    - TAPPING        15
    - FAN            10
- Test(28)
    - ON             12
    - OFF             8
    - BLADE FAULT     3
    - TAPPING         3
    - FAN             2


## Reference
- [sensiml](https://sensiml.com/documentation/application-tutorials/audio-anomaly-detection.html)