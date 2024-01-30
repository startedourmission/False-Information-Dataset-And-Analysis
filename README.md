# False Information Dataset And Analysis

인하공업전문대학 2023_2 학년도 데이터분석 프로젝트

인터넷 상의 허위 정보, 기사, 발언 등의 진위와 출처를 종합하여 총 5194개의 데이터셋을 구축함

### Attributes

| ID        | Data                 | Title       | Source                              | Judge     |
| --------- | -------------------- | ----------- | ----------------------------------- | --------- |
| 고유 번호 | snu 업로드 기준 날짜 | 데이터 제목 | 데이터 출처 추출을 위한 내용 크롤링 | 허위 여부 | 
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
## Using for ML

해당 데이터셋만을 사용하여 머신 러닝을 진행할 경우 데이터 비대칭성으로 인한 문제가 발생할 수 있음
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


