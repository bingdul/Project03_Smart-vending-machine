# Project03_Smart-vending-machine

프로젝트명 : smart_vendingmachine!

프로젝트목적 : 통신가능한 자판기를 개발하여 서버와의 실시간 통신을 통해 재고등 여러 정보파악하는 시스템 개발

개발 팀원 : 박경인(팀장), 이동희, 정승민, 김규태, 이재명

사용 언어 : Python, java

사용 프로그램 : Python IDLE ,android studio

사용 하드웨어 : RaspberryPi

팀 개발기간 : 2021년 6월

맡은 역할 : 팀원 ( 하드웨어 총괄 및 전체적인  시스템설계) 

## 프로젝트 구현내용
  1.  서버/클라이언트구현 
  2. 서버와 오라클 DB와의 연동
  3.  스마트폰 앱으로 간단히 재고등 여러정보 확인가능하게 구현

## 상세설명
  1. 자판기 클라인언트와 판매자 클라이언트 그리고
    서버로 구성되어있다.
  2. 고객이 자판기에서 음료수를 뽑으면 서버로 
     데이터가 전송되고 서버에서는 myspl를 이용한 
     DB에서 뽑은 수량만큼 재고를 제거하고  로그만
     관리하는 DB로 정보를 전송한다. 
  3. 판매자 클라이언트는 실시간으로  (1) 판매자 현황데이터 (2) 누적 판매량  (3) 월별 판매량  (4) 오늘 판매량등으로 구현된 안드로이드 앱으로 실시간으로 데이터를 요청할수있게 만듬


## 프로젝트 결과
  1. 서버와 클라이언트 구현 성공적으로 구현
  2. 서보모터등 여러 부품의 문제점들을 코드로 제어함
  3. DB를 사용하여 재고량,판매량등 여러 데이터들을 클라이언트에서 손쉽게 확인할수있도록 시스템 구축함

## 소감 및 느낀점
우선 수많은 부품들의 사용법에 대해 알게되었고 한층 더 Python과 java사용에 익숙해져서 좋았고 시스템설계를 하면서 (자판기 -- 서버 -- db - 판매자클라이언트) 이런 자판기조차도 여러 구조를 가질수있고 최적의 설계구조를 가지기위해서는 많은 연구와 회의를 거쳐야된다는 것을 알게되었다. 이로인해 현업에서도 우리가 어떤프로그램을 사용만했지 그 구조에 대해서는 생각해볼일이 없는데 이번 기회를 통해 조금이라도 시스템구조에 관심을 가지게되었다.  
이와 별개로 프로젝트선정에 스토리가 있는데..  

항상 유치원,초등학생때부터 막연히 자판기의 구동원리와 시스템에 궁금해하면서 종이상자를 잘라서 수동으로 동전을 넣으면 수동으로 음료수를 내주는 겉만 흉내낸 자판기를 만들어 동생과 놀곤했다.  
마침 이번에 프로젝트주제(라즈베리파이와 아두이노를 이용한 시스템구축)를 듣자마자 어릴때 꿈을 실현시킬 절호의 기회라고 생각했고 주제선정때 팀원들에게 강력주장을 해서 스마트자판기를 만들기로 결정했다.  
팀원들에게 민폐를 끼치지않기위해 외관을 정식프로젝트 시작하기전에 4일을 투자해 조잡하지만 구동가능한 수준으로 만들었다. 또한 단순히 하드웨어적인면만 아니라 소프트웨어면에서도 발전을 이루기위해 시스템 설계를 철저히 하였고 2차프로젝트에서도 결과적으로 1등을 하여 좋은 결과를 얻었던거같다. 팀원으로 참여했지만 많은 부분에 기여 할 수있어서 지금까지 했던 프로젝트중에서 가장 만족스러웠다.
## 자판기 확대사진
![image17](https://user-images.githubusercontent.com/59175200/170864619-4fce5e0f-a87c-4eb1-a538-e83558e7fa5a.png)
![image18](https://user-images.githubusercontent.com/59175200/170864622-36790f99-337a-4cb7-a29a-f7f33b4594c2.png)

## ppt
![슬라이드1](https://user-images.githubusercontent.com/83994580/127095256-3cc7e234-8312-4da0-82a5-86a5bb5d963a.PNG)
![슬라이드2](https://user-images.githubusercontent.com/83994580/127095263-7fc8f9f4-0578-430a-b098-b1d4b941f536.PNG)
![슬라이드3](https://user-images.githubusercontent.com/83994580/127095270-544bc82e-ec9f-4259-ba2c-229207e5ccc0.PNG)
![슬라이드4](https://user-images.githubusercontent.com/83994580/127095279-9c2afbd1-bf5c-4044-9b38-fbe8fdd2e63f.PNG)
![슬라이드5](https://user-images.githubusercontent.com/83994580/127095382-d792d1a0-797c-4be0-9b14-08930141a511.PNG)
![슬라이드6](https://user-images.githubusercontent.com/83994580/127095424-67744949-bdc4-4fe4-8f01-1a32a01b1d95.PNG)
![슬라이드7](https://user-images.githubusercontent.com/83994580/127095427-62bb758c-ce0a-4887-a768-6269ac8634dc.PNG)
![슬라이드8](https://user-images.githubusercontent.com/83994580/127095433-c210cf8e-4142-4c6a-815d-d5276b6dc553.PNG)
![슬라이드9](https://user-images.githubusercontent.com/83994580/127095434-01ca0cd3-9cc3-4514-8e71-aa26ac5d9f49.PNG)
![슬라이드10](https://user-images.githubusercontent.com/83994580/127095436-04a40e27-837e-45d0-9acc-c26a37e3e525.PNG)
![슬라이드11](https://user-images.githubusercontent.com/83994580/127095437-e174f1ac-e836-4d3a-8991-14b4ac4964f5.PNG)
![슬라이드12](https://user-images.githubusercontent.com/83994580/127095439-a36045a3-2ff2-44a2-afa0-b7c642370784.PNG)
![슬라이드13](https://user-images.githubusercontent.com/83994580/127095442-3df6cc8c-ce69-4c75-969f-222ca8f72ac3.PNG)
![슬라이드14](https://user-images.githubusercontent.com/83994580/127095443-56f0d460-410c-47ee-808d-4b1d04930b5f.PNG)
![슬라이드15](https://user-images.githubusercontent.com/83994580/127095444-2c473fa2-4367-4b8b-bef3-5912481e87db.PNG)
![슬라이드16](https://user-images.githubusercontent.com/83994580/127095445-67ebaf78-b29c-4fed-8a60-53dbbdcdebe8.PNG)
![슬라이드17](https://user-images.githubusercontent.com/83994580/127095446-ec1196ac-eea3-4817-addc-45b2b5dc9de0.PNG)
![슬라이드18](https://user-images.githubusercontent.com/83994580/127095447-d6133dd3-0678-4ed2-b142-9b537c5fbdd8.PNG)
![슬라이드19](https://user-images.githubusercontent.com/83994580/127095448-b44727f5-4ede-450a-8b67-a690f3d679c1.PNG)
![슬라이드20](https://user-images.githubusercontent.com/83994580/127095450-54d67994-f4e3-40ef-a79b-8d9a917ddb58.PNG)


https://user-images.githubusercontent.com/59175200/170864587-17e9a38a-f660-4b58-826a-880ca5f6be89.mp4


https://user-images.githubusercontent.com/59175200/170864590-4e56456f-ed6b-4faa-bb37-728965727f52.mp4




https://user-images.githubusercontent.com/59175200/170864593-e04357f1-7c86-441e-84fe-4389d7558e05.mp4




![슬라이드21](https://user-images.githubusercontent.com/83994580/127095452-95e65565-3f18-4bb2-b3e9-9600326864a9.PNG)
![슬라이드22](https://user-images.githubusercontent.com/83994580/127095453-a66fe7cd-9f0e-42d0-9561-64481657adc9.PNG)
![슬라이드23](https://user-images.githubusercontent.com/83994580/127095454-ec51e952-6cdb-433c-8b95-671adf32c00c.PNG)

