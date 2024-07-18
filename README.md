역방향 프록시란?
웹 서버 앞에 위치하여 클라이언트  요청을 해당 웹 서버에 전달합니다. 

기대효과 
 -보안
 -성능
-안정성

foward Proxy 

![image](https://github.com/user-attachments/assets/ec23f30f-bfa7-40b4-b938-03d4c4d1e4d9)

BreadcrumbsReversProxy
![image](https://github.com/user-attachments/assets/5850c4cb-28bb-41e4-9910-19d2be6fe593)



작업 : 기존 bmw iis 서버와  신규로 생성한 웹서버를 리버스 프록시 설정.


![image](https://github.com/user-attachments/assets/5f8a7e03-aa3e-4b44-91e1-bcb5ff1b5d8c)


같은 IP 엔드포인트를 가지더라도 foo.com으로 접속했을 때와 bar.com으로 접속했을 때 다른 사이트로 라우팅이 되게 할 수 있음.


bws iis 버전은 7.0 이하기 떄문에  ARR   (라우팅 라이브러리) 를 외부에서 받아 별도로 설치함.

# ARR 설정

![image](https://github.com/user-attachments/assets/49cd9483-a845-4c86-bbeb-ac1e2d9842b0)



# URL ReWriter 설정

![image](https://github.com/user-attachments/assets/81e5c49b-4aa1-41d0-b5e5-2e64a1262f5d)


윈도우 내 inbound , outbound 설정과 iis내 inbound , outbound  Rule 규칙 추가.



