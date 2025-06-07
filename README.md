# ai_miniproject


### 1. 문제 정의

정형 데이터 회귀

실내.외 온도, 습도, 조명 등 다양한 환경, 기상 데이터를 바탕으로
가정 내 가전제품의 에너지 소비량(Wh)를 예측하는 회귀 모델


 입력 변수 :  	실내/외 온도(T1T9), 습도(RH_1RH_9), 조도(lights), 외부 기상 데이터(기온, 기압, 습도, 풍속 등) - (총 26개 입력 변수)
 출력 변수: 	Appliances (가전제품의 에너지 소비량, Wh)


### 2. 데이터셋 설명

저에너지 주택에서 가전에너지 사용량 모델링을 위해 수집한 데이터이며,
4.5개월동안 10분 간격으로 데이터를 기록

실외 기상정보는 인근 공항 기상대의 공개 데이터를 시간 별로 받아 날짜/시간 기준으로 실험 데이터와 병합

총 19,736개 인스턴스와 28개의 속성으로 구성된 데이터셋
-> 훈련데이터 : 80%, 약 15,788개
-> 테스트 데이터 : 20% 약 3,947개
-> 검증 데이터 비율 : 16% 약 3,157개

데이터셋
개수
비율
전체 데이터
19,735
100%
학습(Train)
15,788
80%
 ㄴ 실제 학습
12,631
64%
 ㄴ 검증(Validation)
3,157
16%
테스트(Test)
3,947
20%
<img width="290" alt="image" src="https://github.com/user-attachments/assets/7f72573d-975b-43ba-9986-68d43a32158f" />


### <img width="559" alt="image" src="https://github.com/user-attachments/assets/41d7731b-9ac2-4228-8bd1-964d9be23577" />

<img width="568" alt="image" src="https://github.com/user-attachments/assets/6b2334e2-4483-4b99-9fd7-309876f81c60" />

<img width="496" alt="image" src="https://github.com/user-attachments/assets/4ca6d01d-d948-405d-8069-63a66947b647" />

<img width="705" alt="image" src="https://github.com/user-attachments/assets/837a8258-8754-49bf-bcab-fcb8e0ac515b" />

<img width="751" alt="image" src="https://github.com/user-attachments/assets/478060ac-0a38-4289-ae33-4ebe654d9f9a" />

<img width="898" alt="image" src="https://github.com/user-attachments/assets/5afb2e30-7a01-4e1a-9f2c-5842bf59ec56" />








