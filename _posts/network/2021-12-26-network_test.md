---
title:  "Chapter1. 인터넷 네트워크" 

categories:
  -  Network
tags:
  - [Network, HTTP]

toc: true
toc_sticky: true

date: 2021-12-26
last_modified_at: 2021-12-26
---

인프런에 있는 김영한님의 **모든 개발자를 위한 HTTP웹 기본 지식** 강의를 듣고 정리한 내용입니다.
중간에 등장하는 ppt 내용들은 모두 강의자료를 캡처한 것입니다.
{: .notice--warning}


# IP

인터넷은 어떻게 통신할까?

![image]](https://user-images.githubusercontent.com/96368476/147408180-b81f315d-9ed6-4488-81e3-86636f93ba70.png){: width="30%" height="20%"}

내가 매일 사용하는 youtube를 예로 들어보자. youtube의 본 서버는 어디에 있을까? 궁금해서 방금 찾아보니 전기료가 싸거나, 온도가 낮거나(발열량이 많다고 한다.)한 여러 나라에 도시만한 데이터 센터들이 있다고 한다. 심지어 유튜브는 거의 모든 나라 통신사에 캐시서버를 가지고 있다고 한다. 

![image](https://user-images.githubusercontent.com/96368476/147408853-f2ac5b8b-48fe-424f-accb-6e77e94137a5.png){: width="30%" height="20%"}

아무튼 내 pc를 서버에 다이렉트로 연결하는 것이 가장 확실한 인터넷 통신 방법일 것이다. 하지만 인생은 실전이다. 
실제로는 광케이블을 통해 바다를 건너기도 하고, 위성을 통해 지구 반대편에 건너가기도 한다. 이렇듯 여러 중간서버(노드)들을 거쳐 origin 서버에 도착하는 구조이다.




[맨 위로 이동하기](#){: .btn .btn--primary }{: .align-right}