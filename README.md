# COVID19-commercial-area-Dashboard

## 코로나로 인한 상권의 유동인구 및 매출 예측 분석 대시보드 제작

### 21학년 1학기 광운대 정보디자인 팀프로젝트

---

> 상권 매출과 유동인구의 상관관계를 구하고, 코로나로 인한 유동인구의 감소가 매출에 미치는 영향을 시각화

### 1. 데이터 시각화

- HTML
- CSS
- Javascript
- D3.js

### 2. 데이터 출처

- [상권 추정 매출](https://data.seoul.go.kr/dataList/OA-15572/S/1/datasetView.do)
- [상권 추정 유동인구](https://data.seoul.go.kr/dataList/OA-15568/S/1/datasetView.do)
- 국내 코로나 확진자 데이터

### 3. 데이터 분석

- Python
- R

---

### 대시보드 설명

대시보드 실행 시, 비교 분석에 사용한 강남구와 종로구 중에서 선택하여 데이터를 볼 수 있다.
그래프로 제공되는 데이터는 다음과 같다.

1. 구별 매출 상위 업종 3가지 : 꺾은 선 그래프📈
2. 구별 요일 / 시간대 / 연령대별 총 유동인구 : 막대 그래프📊
3. 구별 연도별 / 분기별 확진자 수 : 막대 그래프📊
4. 구별 연도별 / 분기별 유동인구 : 막대 그래프📊
5. 구별 연도별 / 분기별 총매출 : 막대 그래프📊
6. 상권별 매출 상위 업종 3가지 : 꺾은 선 그래프📈

또한 지도에 표시된 상권을 선택했을 때, 해당 상권의 활성 예측 정도를 확인하고 코로나 확진자에 따른 유동인구와 매출에 대한 예측 추이를 살펴볼 수 있다.

<메인화면>
![메인 화면](./main.png)
