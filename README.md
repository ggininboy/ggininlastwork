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
![](https://github.com/ggininboy/ggininlastwork/blob/main/ROC.jpg?raw=true)
## 總結
我們利用py中機器學習的套件，提取惡意程式的特徵並繪製roc曲線，接著藉由roc曲線來檢查檢測器的檢測閾值之間的關係，還有這個檢測會出現偽陽性的機率。
## 心得
老師的課跟以往上過的資安課程有很大的區別，之前都是上一些理論或者是惡意程式的分類，這個課卻是結合的資訊的技術(程式)，來分析惡意程式，尤其是期末這個利用機器學習_隨機森林來提取惡意程式的特徵，這真的是太酷了！我從以前就很希望學習跟機器學習有關的東西，這堂課能夠學習到這麼多真的是太棒了！
