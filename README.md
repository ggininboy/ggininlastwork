# ggininlastwork
# 資財三乙_107AB0706_鄭御里
---
## 找出需使用之檔案
藉由以下程式碼，我們進入malware_data_science/ch8/code，並顯示其資料夾當中的資料。
```
$ cd malware_data_science
$ cd ch8
$ cd code
$ ls
```
接下來，我們將會用到資料夾當中的complete_detector.py以及run_complete_detector.sh
## 主程式 complete_detector.py
complete_detector.py透過sklearn套件中的RandomForestClassifier還有FeatureHasher來讓機器學習訓練提取惡意程式的特徵。
## 執行程式 run_complete_detector.sh
我們利用以下程式碼來執行run_complete_detector.sh
```
$ sh run_complete_detector.sh
```
## 繪製ROC曲線
