# Analysis-of-the-determinants-of-the-kimchi-premium-in-the-cryptocurrency-market

## 개요

### 1. 김치프리미엄에 영향을 미치는 요인 파악을 위해 회귀분석을 진행했습니다.

### 2. 김치프리미엄은 다음과 같습니다. 
### $kimchi premium = \frac{Upbit(Price)*ExchangeRate-Binance(Price)}{Binance(Price)}$

### 3. 회귀식의 적합성을 따지기 위해 수정 $R^{2}$을 사용했고 VIF지수를 활용하여 다중공선성을 확인했습니다.

기존 모델과의 비교

![image](https://github.com/user-attachments/assets/13a0f3fd-d14b-4ac5-9cf8-5141eb602bca)

다중공선성 확인

![image](https://github.com/user-attachments/assets/35c17e87-aecb-4a19-9f9f-d57281b2a1cc)


### 4. 요인을 선정한 뒤 산점도를 통해 상관관계를 확인했습니다.
![image](https://github.com/user-attachments/assets/3ced9b1c-fe8c-49f3-9aa6-b7a76e755c18)

### 5. 회귀식의 가정 확인을 위해 정규성, 독립성을 확인했습니다.

#### 정규성 확인
![image](https://github.com/user-attachments/assets/5f2ea9be-7faa-4618-9481-154684c76544)
![image](https://github.com/user-attachments/assets/d864ce64-aeba-411a-b3eb-bbb774de4eeb)
![image](https://github.com/user-attachments/assets/2ce657e7-ec59-4fe4-be15-5e2ac0ceba5a)

#### 독립성 확인
![image](https://github.com/user-attachments/assets/4e1b0aa2-4b02-4abf-a621-0c0f1b8d71e5)


### 6.회귀계수를 통해 경제학적 해석을 진행했습니다.
