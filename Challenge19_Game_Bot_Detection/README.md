## 주제 : 아이온 게임봇 탐지 

기간 :  2019.10.01 ~ 2019.11.22

결과 

- 본선 진출 / 최종 4등 

구조

```
.
├── code
│   │   └── 01. Feature Engineering - pyspark(sampling).ipynb
│   │   └── 02. Action information features1.ipynb
│   │   └── 02. Action information features2.ipynb
│   │   └── 02. Action information features3.ipynb
│   │   └── 02. Group information features.ipynb
│   │   └── 02. JOIN TABLE.ipynb
│   │   └── 02. Network features.ipynb
│   │   └── 02. Player information features.ipynb
│   │   └── 02. Social information features.ipynb
│   │   └── 03. Model.ipynb
├── algorithm_gamebot_TEAM-EDA.pdf
└── Experience
```

### 실행 환경

- python3.6 

### 필요 라이브러리

- Catboost 0.16.5
- LightGBM 2.3.0 
- pandas 0.25.1
- numpy 1.16.4
- Pyspark 2.4.4

### 전처리 

- Pyspark를 이용해서 로그정보 추출 

### 피쳐 설명

- Action Features : sit, Exp, item, Money, Portal, kill 
- Group Features : Guild, Party 
- Netwrok Features : PageRank, Degree, Centrality 
- Social Features : 사회적인 정보(Mail, Trade, Friend, Dual)
- Player Features :  플레이어에 대한 정보(ip, login, logout, playtime, level)

### 모델 설명

- LightGBM, Catboost 

