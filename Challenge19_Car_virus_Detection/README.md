## 주제 : 자동차용 침입 탐지 

기간 :  2019.10.01 ~ 2019.11.22

결과 

- 본선 진출 5등 

구조

```
.
├── code
│   │   └── Data Exploration.ipynb
│   │   └── Tree Based Model.ipynb
│   │   └── Full Model.ipynb
│   │   └── Ensemble.ipynb
├── CAR_VIRUS_TEAM-EDA.pptx 
└── Experience
```

### 실행 환경

- python3.6 

### 필요 라이브러리

- Catboost 0.16.5
- pandas 0.25.1
- numpy 1.16.4

### 피쳐 설명

- DiffTime : 이전 신호와 현 신호간의 차이 
- DataField : 데이터 필드의 임베딩 

### 모델 설명

- Rule Based : 기존에 나왔던 유형의 경우 CANID, DataField으로 분류 
- Tree Based : catboost를 사용해서 침입탐지인지 아닌지 분류 

