# ML_Final_109612041

## 環境
 python:  3.9.7  
 torch:   1.13.1+cu116  
 sklearn: 1.2.0  
## 使用的libraies
 numpy == 1.22.4  
 pandas == 1.5.2  
 joblib == 1.2.0  
 csv  
## Training
 1. 將`train.csv`, `test.csv`放在主要的資料夾下命名為`tabular-playground-series-aug-2022`的資料夾(或是你可以在)`109612041_Final_train.ipynb`中修改檔案路徑  
 2. 執行`109612041_Final_train.ipynb`  
 3. `109612041_Final_train.ipynb`將會產生`my_model`在同一個資料夾  
## Evaluation
 1. 執行`109612041_Final_inference.ipynb`  
 2. `109612041_Final_inference.ipynb`將會產生預測結果的csv檔`109612041.csv`  
## Pre-trained Models 
[ `pre-trained model`](https://drive.google.com/file/d/1FYc74MSekEqXtqDeYGk58zxb8uQRCBTe/view?usp=share_link)  
## Result
![109612041_Final](https://user-images.githubusercontent.com/103819868/211599424-db164f82-90cc-4689-a99f-cb1ff02bb17c.jpg)
| Model name         | Private Accuracy| Public Accuracy|
| ------------------ |---------------- | -------------- |
|      my_model      |     0.59031     |     0.58296    |
