<p align="center">
  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/b89de100-d51d-4841-abf4-5769aa07f7f4" width="10%" height="10%">
</p>
<p align="center">
  For short meeting Web Application<br/>
  bbang<br/>
  Server gateway입니다.
</p>

### 서버 구조도

+ Spring Cloud Eureka

  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/0b8b333a-d3a9-43b1-972e-c3635156016c" width="70%" height="60%">

+ K8S
  
  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/8ba8b34f-8a26-42f1-8cf0-b07c6258a086" width="70%" height="60%">

### API 명세서

https://personal-study-space.notion.site/API-3af82b35861b4f96b639cd537fd7b813

### 사용 기술, 개발 환경

+ Java, Spring Boot, Gradle, Spring Cloud Eureka
+ JPA(Spring Data, Hibernate), QueryDSL, JIB
+ JWT, Swagger
+ JUnit5, AssertJ
+ MySQL, H2, RDS, S3
+ Jenkins, ArgoCD
+ Docker, Kafka, WebClient
+ AWS (Code Build, GitOps, ECR, Cloud Watch)
+ IntelliJ, Postman, Jira, Slack

### ERD
MSA 기준 각 테이블이 다른 서버에 있지만 편의상 한 페이지에 출력

<img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/6e66c6e6-698d-4a7d-8a75-a20de1aa6531" width="60%" height="40%">

### 프로젝트 목표

+ 짧은 기간 다양한 기능을 사용할 수 있는 블로그 형식의 웹 애플리케이션 개발
+ 음성 채팅, 채팅, 게시글 등 다양한 기능 구현
+ Spring Cloud와 K8S를 이용한 MSA 구현
+ WebClient를 이용한 서버 간 통신 구현

### 새로 얻은 경험

+ WebClient, RestTemplate, FeignClient 비교
+ React, Spring Boot 간 쿠키 공유
  <br>https://manchandiary.tistory.com/17</br>
+ Spring Cloud, K8S에 대한 이해 및 구현 방법
+ Jira, Slack을 이용한 커뮤니케이션

### 문제 해결

+ 세션 및 Cors 문제
  <br>https://manchandiary.tistory.com/5</br>
+ JWT Refresh 토큰 쿠키 관리
  <br>https://manchandiary.tistory.com/11</br>
+ MSA에서 Swagger UI를 Gateway로 하나의 Url로 관리하기
  <br>https://manchandiary.tistory.com/14</br>
+ Controller에서 @WebMVCTest를 이용한 API 테스팅에서 Exception 문제
  <br>https://manchandiary.tistory.com/19</br>

### UI 및 협업 자료 모음

+ 애플리케이션 주요 화면

  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/e0aa175d-ddb6-49f5-9495-95bf5f3b3044" width="60%" height="40%">

  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/935a1c0d-60d8-4df0-8e81-428e61b7d4d0" width="60%" height="40%">

  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/ea2ffa90-d196-4666-b538-1c3880d7c64e" width="60%" height="40%">

+ 팀 노션 캡쳐

  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/11f83f9c-cdce-43fe-bd82-51847521b28c" width="60%" height="40%">

+ 팀 칸반 보드

  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/e28d1588-aff6-4c3c-a9db-f7e05a5075ca" width="60%" height="40%">

+ 팀 지라 캡쳐

  <img src="https://github.com/kea-semicolon/MeetOnBE_GateWay/assets/127479677/da00113a-e148-41bb-bbbd-54cdb7a757a6" width="60%" height="40%">

### Connected Client Server

##### Client Server의 주소입니다.

- 채널 Server
  
  [채널 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Channel)

- 회의 Server

  [회의 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Meeting_Minutes)

- 게시글 Server

  [게시글 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Board)

- 멤버 Server

  [멤버 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Member)

- 웬투밋 Serever

  [웬투밋 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_WhenToMeet)

- 일정 Server

  [일정 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Schedule)

- 댓글 Server

  [댓글 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Reply)

- 메모 Server

  [메모 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBe_Memo)


