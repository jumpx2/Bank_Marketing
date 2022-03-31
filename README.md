## Portugal_Bank_Marketing
---
### 포르투갈 마케팅 데이터를 활용해 잠재고객 예측
- shap, seaborn으로 시각화 및 데이터 분석
- randomforest, xgboost, Lgbm 모델 사용 후 결과 비교 
---
### 데이터 설명
1 - 연령 (age)  

2 - 직업 (job)  

3 - 결혼 여부 (marital)  

4 - 교육 (education)  

5 - 채무불이행 (default)   

6 - 주택대출 (housing)   

7 - 개인 대출 (loan)   

8 -연락처 통신 유형('휴대전화', '전화') (contact)   

9 - 월: 해당 연도의 연락 월 (month)   

10- 연락한 일 : 일주일 (day_of_week)   

---
### 기타 속성:  

11 - 캠페인: 이 캠페인 동안 및 이 클라이언트에 대해 수행된 컨택 수(campaign)  

12 - 클라이언트가 이전 캠페인에서 마지막으로 컨택된 후 경과한 일 수(숫자, 999는 고객이 이전에 연락한 적이 없음) (pdays)   

13 - 이 캠페인 이전에 이 고객에 대해 수행된 연락 수 (previous)   

14 - 이전 마케팅결과 : ('실패', '존재하지 않음', '성공') (poutcome)   

---

### 사회 경제적 속성:  

15 - 고용 변동률 - 분기별 지표 (emp.var.rate)   

16 - 소비자 물가 지수 - 월별 지표 (cons.price.idx)  

17 - 소비자 신뢰 index - 월별 지표 (cons.conf.idx)  

18 - 금리 3개월 비율 - 일별 지표 (euribor3m)  

19 - 고용 수 - 분기별 지표  (nr.Employee)  

---  

### 20 - y - 고객이 정기 예금에 가입유무  
