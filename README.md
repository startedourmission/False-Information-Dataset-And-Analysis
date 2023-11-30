# False Information Dataset And Analysis

### Source : SNU factcheck

![](img1.png)

## Label data ratio

- Original Data : 사실, 대체로 사실, 판단 유보, 절반의 사실, 대체로 사실 아님, 전혀 사실 아님
- Transformed Data : 사실, 거짓

![](judge_pie.png)
## Date frequency

![](sequence_line.png)

## Word frequency analysis


#### Title
![](title_bar.png)
#### Source
![](source_bar.png)
## Word Crowd

#### Title
![](title_wc.png)
#### Source
![](source_wc.png)
## Machine Learning

### Classification - Logistic Regression

|       | Precision | Recall | F1 Score | Accuracy |
| ----- |:---------:| ------ | -------- | -------- |
| True  |   0.73    | 0.99   | 0.84     |          |
| False |   0.57    | 0.02   | 0.04     |          |
|       |           |        |          | 0.73     | 

### Sequencial analysis - ARIMA

| MSE  | RMSE | MAE  |
| ---- | ---- | ---- |
| 3.41 | 1.85 | 1.61 | 


