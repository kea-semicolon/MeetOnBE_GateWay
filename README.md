# Connected Client Server

- Channel Server
  
  [채널 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Channel)

- 회의 Server

  [회의 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Meeting_Minutes)

- 게시글 Server

  [게시글 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Board)

- Member Server

  [멤버 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Member)

- WhenToMeet Serever

  [웬투밋 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_WhenToMeet)

- 일정 Server

  [일정 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Schedule)

- 댓글 Server

  [댓글 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBE_Reply)

- Memo Server

  [메모 서버 레포지토리](https://github.com/kea-semicolon/MeetOnBe_Memo)

# Spring Boot Version

### 3.2.4

# Eureka

### 실행

##### Spring 프로젝트 경로에서

./gradlew build

C:\Users\lych0\kakaoEnt\eureka\build\libs> java -jar .\eureka-0.0.1-SNAPSHOT.jar

# 실행

### version 2.13-3.7.0

### 실행

C 기본 경로에 있다고 가정

</br>
1. Zookeeper 서버 실행

##### PS C:\kafka_2.13-3.7.0> .\bin\windows\zookeeper-server-start.bat .\config\zookeeper.properties
</br>
2. Kafka 서버 실행
</br>

##### PS C:\kafka_2.13-3.7.0> .\bin\windows\kafka-server-start.bat .\config\server.properties

</br>
3. Eureka Server 실행
</br></br>
4. Gateway Server 실행
</br></br>
5. 나머지 Service 서버 실행

# ERD

![image](https://github.com/kea-semicolon/MeetOnBE_Member/assets/127479677/121182c3-0744-4c87-a30a-61eab96ffb16)
