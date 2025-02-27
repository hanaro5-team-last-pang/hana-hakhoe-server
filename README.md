# 하나학회 API 서버 레포지토리

[![Unit test on Pull Request](https://github.com/hanaro5-team-last-pang/hana-hakdang-server/actions/workflows/unit-test-on-pr.yml/badge.svg)](https://github.com/hanaro5-team-last-pang/hana-hakdang-server/actions/workflows/unit-test-on-pr.yml)
[![Code Style](https://img.shields.io/badge/Code_Style-intellij_google-8A2BE2)](https://github.com/google/styleguide/blob/gh-pages/intellij-java-google-style.xml)
[![Spring](https://img.shields.io/badge/Spring_Boot-v3.4.1-green?logo=spring)](https://github.com/spring-projects/spring-boot/releases/tag/v3.4.1)
![JWT](https://img.shields.io/badge/Json_Web_Token-black?logo=jsonwebtokens)


<div align="center">
<img width="825" alt="image" src="https://github.com/user-attachments/assets/6a101a04-06ea-4f1d-bcdd-11d09e654ad2" />
</div>

<br>
<br>
<br>

<div align="center"><h1>🧑🏻‍🏫 <span style="color: #0B9B97;">하나학회</span> - 실시간 화상 금융 멘토링 플랫폼 </h1></div>

**"실시간, 비대면, 금융, 세미나"** 라는 네 가지 키워드를 하나로 더해, 금융 전문가와 함께하는 온라인 금융 멘토링 서비스를 지원하는 플랫폼입니다.

<br>

## 목차
- [목차](#목차)
- [프로젝트 소개](#프로젝트-소개)
  - [💡 프로젝트를 왜 시작하게 되었나요?](#-프로젝트를-왜-시작하게-되었나요)
  - [🔑 프로젝트의 핵심은 무엇인가요?](#-프로젝트의-핵심은-무엇인가요)
  - [🎁 프로젝트가 가져올 수 있는 기대 효과는 무엇인가요?](#-프로젝트가-가져올-수-있는-기대-효과는-무엇인가요)
- [팀 소개](#팀-소개)
- [개발 기간](#개발-기간)
- [기술 스택](#기술-스택)
- [ERD](#erd)
- [API 명세](#api-명세)
- [시스템 아키텍처](#시스템-아키텍처)
- [핵심 기능 소개](#핵심-기능-소개)
  - [👩🏻‍💻 다양한 멘토링 강의 조회 및 수강신청](#-다양한-멘토링-강의-조회-및-수강신청)
  - [🧑🏻‍🏫 실시간 화상 멘토링 강의](#-실시간-화상-멘토링-강의)
  - [📰 최신 금융 뉴스 모아보기](#-최신-금융-뉴스-모아보기)


---

<br>

## 프로젝트 소개
하나학회는 금융에 관심이 있는 사람이라면 누구나 멘티가 되어

하나은행 행원이 직접 진행하는 금융과 관련된 다양한 주제의 소규모 화상 멘토링에 참여할 수 있는

비대면 실시간 금융 멘토링 플랫폼입니다.

<br>

### 💡 프로젝트를 왜 시작하게 되었나요?

<div align="center" style="margin-bottom: 20px;">
    <img width="600" alt="금융 멘토링 필요성 1" src="https://github.com/user-attachments/assets/7f14a4a3-e8cd-4002-b1c7-19f225a42b8c" />
    <img width="600" alt="금융 멘토링 필요성 2" src="https://github.com/user-attachments/assets/589782e2-c02d-42bf-b3f1-96374452db4b" />
</div>

금융, 투자에 대한 관심도는 계속 높아지는 데에 반해 우리나라 사람들의 금융이해력은 상당히 낮다고 합니다.

관심도에 비해 부족한 금융이해력은 결국 공격적인 투자, 더 나아가 금융 피해로 이어집니다. 

또한 투자자의 금융이해력이 부족한 것 이외에도, 전문적인 조언을 들을 수 있는 곳이 잘 없어 주변 소문 등에 의지할 수 밖에 없다는 점 역시 금융 피해를 키우는 주요 원인 중 하나라고 할 수 있습니다.

그렇기에 생애주기별 맞춤형 금융 교육의 필요성이 높아지고 있으며, 자유롭게 질문 할 수 있으면서 믿을 수 있는 금융 멘토링이 필요하다고 생각하여 **하나학회** 프로젝트를 기획하게 되었습니다.

<br>

### 🔑 프로젝트의 핵심은 무엇인가요?
금융에 대한 관심과 열정을 가진 대한민국 국민이라면 누구나! 하나은행 행원과의 소규모 화상 멘토링을 통해 실시간으로 소통하며, 평소 알고 싶었던 금융 분야에 대해 더욱 친숙해지는 기회를 만들어 주는 것입니다.

<br>

### 🎁 프로젝트가 가져올 수 있는 기대 효과는 무엇인가요?
- **손님 측면**
  - 궁금했던 금융 주제에 대해 전문가의 멘토링을 들으며 금융이해력을 높일 수 있습니다.
  - 일방적인 강의가 아닌 양방향 소통이 가능하기에 더욱 효과적인 금융 교육이 가능합니다.
  - 최신 금융 뉴스를 한 곳에서 모아볼 수 있습니다.
- **하나은행 측면**
  - 하나의 브랜디드 컨텐츠로 발전시킬 수 있습니다. 
    - 금융 상담이 필요할 때 언제든지 찾고 싶게 만드는 서비스로 발전시켜 하나은행에 대해 긍정적인 이미지로 이어나갈 수 있습니다.
  - 어떤 주제에 대한 멘토링이 인기가 있는지 등 손님의 금융 관심사에 대한 수요 데이터를 수집할 수 있습니다.
  - 직간접적으로 금융 범죄를 예방하고, 피해를 최소화하는데 일조할 수 있습니다.
  - 손님과의 접점 확대를 통한 하나은행이라는 브랜드의 신뢰도 상승을 기대할 수 있습니다.

<br>

## 팀 소개

<div align="center">
    <h3> 🎉 라스트팡(Last Pang!) 🎉 </h3>
    <div>Last Pang!은</div>
    <div>개성과 열정 가득한 팀원들이</div>
    <div>마지막까지 함께 고민하고 노력하며, 팡! 하고 우리의 열정을 크게 터뜨려보자는 의미가 담긴 팀명입니다!</div>
</div>

<br>
<br>

<div align="center">

|                                                           **👑 정중일**                                                           |
| :------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://avatars.githubusercontent.com/u/38873022?v=4" height=120 width=120> <br/> @magae1](https://github.com/magae1) |
|                                                             **팀장**                                                             |
|                                                CI/CD, 프론트엔드, 웹소켓, WebRTC                                                 |

|                                                            **육지은**                                                            |                                                             **한성민**                                                              |
| :------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://avatars.githubusercontent.com/u/96432798?v=4" height=120 width=120> <br/> @6jieun](https://github.com/6jieun) | [<img src="https://avatars.githubusercontent.com/u/115688628?v=4" height=120 width=120> <br/> @kkx7787](https://github.com/kkx7787) |
|                                                          **프론트엔드**                                                          |                                                           **프론트엔드**                                                            |
|                                                  CI/CD, 컴포넌트 개발, API 연동                                                  |                                                     컴포넌트 개발, WebRTC 연동                                                      |

|                                                                       **김동연**                                                                        |                                                                          **양지은**                                                                           |                                                            **이하늘**                                                             |
| :-----------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------: |
| [<img src="https://avatars.githubusercontent.com/u/158025327?v=4" height=120 width=120> <br/> @commaengddongyeon](https://github.com/commaengddongyeon) | [<img src="https://github.com/user-attachments/assets/40ca6d59-3e1b-4be0-af4e-3359b323f58a" height=120 width=120> <br/> @yje9802](https://github.com/yje9802) | [<img src="https://avatars.githubusercontent.com/u/121336350?v=4" height=120 width=120> <br/> @hani-i](https://github.com/hani-i) |
|                                                                       **백엔드**                                                                        |                                                                          **백엔드**                                                                           |                                                            **백엔드**                                                             |
|                                                                 뉴스 크롤링, 리뷰, FAQ                                                                  |                                                                    멘토링, JWT, 검색, 알림                                                                    |                                                        유저 및 프로필 관리                                                        |

</div>

<br>



## 개발 기간

- **프론트엔드 개발** : 2025년 1월 13일 ~ 2025년 2월 6일
- **백엔드 개발** : 2025년 1월 13일 ~ 2025년 2월 6일
- **배포** : 2025년 1월 16일
- **최종 발표 및 평가** : 2025년 2월 6일

---

<br>

## 기술 스택 
기술 스택 선정에 대한 이유는 [Wiki](https://github.com/Hanaro-OMNM/Hanasset-BE/wiki/%EA%B8%B0%EC%88%A0-%EC%8A%A4%ED%83%9D-%EC%A0%95%EC%9D%98)를 참고해주세요!

| **분류**          | **스택**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ----------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Language**      | ![Java](https://img.shields.io/badge/Java-17-007396?style=flat&logo=openjdk&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-4.5-3178C6?style=flat&logo=typescript&logoColor=white)                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Framework**     | ![SpringBoot](https://img.shields.io/badge/SpringBoot-3.4.1-6DB33F?style=flat&logo=springboot&logoColor=white) ![Next.js](https://img.shields.io/badge/Nextjs-15.1.3-000000?style=flat&logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-19.0.0-61DAFB?style=flat&logo=react&logoColor=black)                                                                                                                                                                                                                                                                                                                                                        |
| **Build**         | ![Gradle](https://img.shields.io/badge/Gradle-8.11.1-02303A?style=flat&logo=gradle&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-4.0-646CFF?style=flat&logo=vite&logoColor=white)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Front-end**     | ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.2-06B6D4?style=flat&logo=tailwindcss&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-5.0.3-3578E5?style=flat&logo=zustand&logoColor=white) ![Axios](https://img.shields.io/badge/Axios-0.21.1-5A29E4?style=flat) ![Web RTC](https://img.shields.io/badge/WebRTC-API-333333?style=flat&logo=webrtc&logoColor=white)                                                                                                                                                                                                                                                                                  |
| **Back-end**      | ![Spring Security](https://img.shields.io/badge/Spring%20Security-6.4.2-6DB33F?style=flat&logo=springsecurity&logoColor=white) ![Spring Data JPA](https://img.shields.io/badge/Spring%20Data%20JPA-3.4.1-6DB33F?style=flat&logo=spring&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-3.9.0-231F20?style=flat&logo=apachekafka&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-API-4A90E2?style=flat) ![STOMP](https://img.shields.io/badge/STOMP-Protocol-800000?style=flat) ![Spring Mail](https://img.shields.io/badge/Spring%20Mail-3.4.1-6DB33F?style=flat) ![QueryDsl](https://img.shields.io/badge/QueryDsl-5.0.0-0769AD?style=flat) |
| **Data**          | ![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=flat&logo=python&logoColor=white) ![BeautifulSoup4](https://img.shields.io/badge/BeautifulSoup4-WebScraping-4B8BBE?style=flat)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Database**      | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17.2-4169E1?style=flat&logo=postgresql&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-7.4.1-DC382D?style=flat&logo=redis&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS%20S3-Database-569A31?style=flat&logo=amazons3&logoColor=white)                                                                                                                                                                                                                                                                                                                                                        |
| **Test**          | ![Storybook](https://img.shields.io/badge/Storybook-8.5.0-FF4785?style=flat&logo=storybook&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit5-5.10.2-25A162?style=flat&logo=junit5&locoColor=white)                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Tool**          | ![Postman](https://img.shields.io/badge/Postman-API%20Testing-FF6C37?style=flat&logo=postman&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-Design-FF7262?style=flat&logo=figma&logoColor=white) ![Swagger](https://img.shields.io/badge/Swagger-API%20Docs-85EA2D?style=flat&logo=swagger&logoColor=white) ![Github](https://img.shields.io/badge/Github-Code%20Hosting-181717?style=flat&logo=github&logoColor=white) ![VSCode](https://img.shields.io/badge/VSCode-Frontend-007ACC?style=flat&logo=visualstudiocode&logoColor=white) ![IntelliJ](https://img.shields.io/badge/IntelliJ%20IDEA-Backend-000000?style=flat&logo=intellijidea&logoColor=white)    |
| **Deploy**        | ![Docker](https://img.shields.io/badge/Docker-Container-2496ED?style=flat&logo=docker&logoColor=white) ![EC2](https://img.shields.io/badge/AWS%20EC2-Cloud-orange?style=flat&logo=amazonaws&logoColor=white) ![AWS RDS](https://img.shields.io/badge/AWS%20RDS-Database-527FFF?style=flat&logo=amazonrds&logoColor=white) ![Lambda](https://img.shields.io/badge/AWS%20Lambda-Data-FF9900?style=flat&logo=awslambda&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-CI/CD-D24939?style=flat&logo=jenkins&logoColor=white)                                                                                                                                     |
| **Communication** | ![Notion](https://img.shields.io/badge/Notion-Docs-000000?style=flat&logo=notion&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-Alarm-4A154B?style=flat&logo=slack&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-Project%20Management-0052CC?style=flat&logo=jira&logoColor=white)                                                                                                                                                                                                                                                                                                                                                                  |



<br>


## ERD


![hana_hakhoe_erd](https://github.com/user-attachments/assets/d8275cf1-a2d8-4cef-9702-c9486f2e1b8d)

<br>

## API 명세
swagger-ui를 활용해 자동화된 문서로 관리했습니다. 자세한 API 명세는 [Wiki](https://github.com/Hanaro-OMNM/Hanasset-BE/wiki/API-%EB%AA%85%EC%84%B8%EC%84%9C)를 참고해주세요.

![hana_hakhoe_api](https://github.com/user-attachments/assets/6bdceb25-6eed-441d-8461-5e75442485a7)

<br>

## 시스템 아키텍처

![hana_hakhoe_infra_architecture](https://github.com/user-attachments/assets/a2fb283d-041e-4af4-9671-61b7cfa34eb5)


<br>

## 핵심 기능 소개 

### 👩🏻‍💻 다양한 멘토링 강의 조회 및 수강신청
- **여러 금융 주제에 대한 멘토링 강의 검색과 조회**  
  - 다양한 금융 주제에 맞는 멘토링 강의 개설 가능  
  - 원하는 주제에 맞는 멘토링 강의 검색과 조회
  - 관심 가는 멘토링에 대해 수강신청
    

  <img src="https://github.com/user-attachments/assets/660799ad-068d-48a8-81bb-f920999f4cad" alt="멘토링 개설" />
  <br>
  <img src="https://github.com/user-attachments/assets/72bf069f-e030-48ee-8bbe-88f0c1d07a66" alt="멘토링 목록 조회" />
    


<br>



### 🧑🏻‍🏫 실시간 화상 멘토링 강의
- **실시간으로 진행되는 비대면 멘토링 강의 지원**  
  - 실시간 화면 공유를 이용한 보다 시각적인 멘토링 제공
  - 채팅과 음성 소통을 제공하여 양방향 소통 가능
  - 수강생은 언제든지 자유롭게 질문 가능
  
<img src="https://github.com/user-attachments/assets/70595303-beea-4897-8dc5-4ab1c04689ba" alt="멘토링 시작" />
  <br>
<img src="https://github.com/user-attachments/assets/25e52e0e-7314-4b79-abd1-c35c11df7d12" alt="실시간 멘토링" />
  <br>
<img src="https://github.com/user-attachments/assets/bcc67a22-31be-4941-b1d8-34e5c3b8fbbc" alt="멘토링 종료" />

<br>


### 📰 최신 금융 뉴스 모아보기
- **주기적으로 업데이트 되는 금융 뉴스 제공**  
  - 최신 금융 뉴스를 한 눈에 확인
  
<img src="https://github.com/user-attachments/assets/edf4ac70-3416-46df-b747-2848fb6900b7" alt="금융 뉴스 조회하기" />

[def]: #-최신-금융-뉴스-모아보기
