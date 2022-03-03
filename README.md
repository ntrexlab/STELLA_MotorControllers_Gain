# STELLA_MotorControllers_Gain
자사 제품 모터드라이버는 GUI를 이용하여 간단하게 모터를 튜닝 할 수 있습니다. STELLA 중량이 크게 변경되거나 모터 제어가 비정상적인 경우 게인을 변경하셔야 합니다.


***
## 1. 사용 하드웨어 및 Tool
 * #### 사용 하드웨어 
    - StellaN1_Motor - [소형 유성 DC 엔코더 모터 12V 1:27 500PPR](https://smartstore.naver.com/phonepong/products/5897519502)
    - StellaN2_Motor - [소형 기어드 DC 엔코더 모터 12V 1:30 500PPR](https://smartstore.naver.com/phonepong/products/5747732463)
     - STELLAN1_MDC24D100D-v2 - [MW_MDC24D100D-v2](http://www.devicemart.co.kr/goods/view?no=1077424)
     - STELLAN2_MDC24D50D-v1 - [따로 판매하지 않는 상품]
     - STELLAN1_배터리 -[KC인증 충전식 고용량 농업용 분무기 리튬이온배터리](https://www.weled.co.kr/goods/goods_view.php?goodsNo=1000034222)
    - STELLAN2_배터리 - [따로 판매하지 않는 상품]
* #### 사용 Tool
    - Mobile_Ui -> [다운로드 경로](https://github.com/ntrexlab/MW_MotorControllers_Manual/blob/main/Mobile_UI.exe)</br>
***
## **모터와 모터드라이버 배선도**
#### 1. 100D_배선도
![100D_회로](https://user-images.githubusercontent.com/85467544/155084736-b8d0f172-a15e-4104-bf24-bd55e7e87d66.png)

#### 2. 50D_배선도
![50D_회로](https://user-images.githubusercontent.com/85467544/155084730-378111ea-2681-4fc5-9665-cb57aaf575a6.png)

***
## **모터 게인  방법**
***
#### 1.  모터드라이버를 USB를 통해 PC에 연결합니다.  
#### 2. Mobile_UI를 실행 후 Scan Devices 버튼을 클릭합니다.
![md_1](https://user-images.githubusercontent.com/85467544/155093378-fb8caea4-ba94-4661-afa1-39a70140872f.png)
#### 3. Real-time Plot 버튼을 클릭합니다.
![GAIN_1](https://user-images.githubusercontent.com/85467544/155251568-0e65b651-3c10-43e9-b941-242ed161e523.png)
#### 4. Objects Selection 버튼을 클릭합니다. 
![GAIN_2](https://user-images.githubusercontent.com/85467544/155251574-8eb47117-74fd-4183-b31d-20f661293c54.png)
#### 5. Objects Selection Dialog를 화면과 같이 세팅해줍니다. 만약 모터 하나씩 해주고 싶은 경우는 Velocity Command와 Veloctiy 를 채널 1로 하나씩만 하고 다음에 채널 2로 하나씩 설정 후 진행하면 됩니다.
![GAIN_3](https://user-images.githubusercontent.com/85467544/155251576-e5a432f3-f242-46c8-9100-23e6a87abbd7.png)
#### 6. 모터 게인 튜닝이 잘 된 경우 – 속도 에러율이 높을 때 빠른 시간 내에 값을 찾아갑니다.
![GAIN_4](https://user-images.githubusercontent.com/85467544/155251577-c2398416-774e-40f8-915d-19a4b0d4445c.png)
#### 7. 모터 게인 튜닝이 이상한 경우 – 속도 에러율이 높을 때 시간 내에 빨리 찾아가지 못하고 튀는 모습을 볼 수 있습니다. 이런 경우 게인을 다시 튜닝 해야합니다. 
![GAIN_5](https://user-images.githubusercontent.com/85467544/155251579-877b9627-d765-4c03-9508-f137536805a9.png)
***
