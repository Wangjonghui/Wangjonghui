<div align="center">

# JongHui Wang

**Backend Developer | Java & Spring Boot**

서비스의 기능뿐 아니라 **데이터 정합성, 인증·인가, 예외 상황, 테스트**를 함께 고민합니다.

[GitHub](https://github.com/Wangjonghui) · [NOSPO](https://github.com/GyoseungKu/NOSPO_Back) · [DOMO](https://github.com/Wangjonghui/domo-be)

</div>

---

### About Me

안녕하세요. Java와 Spring Boot를 중심으로 백엔드 개발을 경험하고 있는 컴퓨터공학 전공 학생입니다.

팀 프로젝트에서 회원 인증·계정 관리, API 설계, 데이터베이스 처리, 외부 API 연동 및 서버 배포를 경험했습니다. 단순히 기능을 완성하는 데 그치지 않고, **문제가 발생하는 경계 조건과 변경 이후의 안정성**을 중요하게 생각합니다.

- **Focus** — Backend Development / Authentication & Authorization / Data Integrity
- **Exploring** — Cloud Infrastructure / DevOps / CI/CD
- **Experience** — 멋쟁이사자처럼 13기, 14기 운영진(트랙장)

### Tech Stack

**Backend**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-333333?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Database & Testing**  
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white) ![JUnit5](https://img.shields.io/badge/JUnit5-25A162?style=flat-square&logo=junit5&logoColor=white) ![Testcontainers](https://img.shields.io/badge/Testcontainers-222222?style=flat-square&logo=docker&logoColor=white)

**Infrastructure & Tools**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white) ![Swagger](https://img.shields.io/badge/OpenAPI-6BA539?style=flat-square&logo=swagger&logoColor=white)

---

### Featured Projects

#### 01. [NOSPO — 독서 및 지식 관리 플랫폼](https://github.com/GyoseungKu/NOSPO_Back)
**Capstone Design · Backend Developer · 진행 중**  
`Java` `Spring Boot` `Spring Security` `JWT` `MySQL` `JDBC` `Flyway` `Docker` `Testcontainers`

회원 인증·계정 관리와 공지사항 API의 설계 및 구현을 담당했습니다.

- 이메일 인증과 카카오 OAuth 기반 회원가입·로그인, JWT Access/Refresh 토큰 관리
- 회원 탈퇴 후 **30일 이내 복구**, 닉네임 선점 방지 및 개인정보 파기 정책 처리
- 약관 개정 시 기존 인증 사용자도 **필수 재동의 전까지 접근 제한**하도록 구현
- **공지사항 API 8개** 구현: 관리자 CRUD, 이미지 업로드, HMAC 서명 기반 Keyset Cursor
- DB의 **현재 관리자 권한**을 기준으로 접근 검증; Flyway로 스키마 버전 관리
- H2·MySQL Testcontainers 기반 통합·회귀 테스트 및 Swagger/OpenAPI 문서화

**검증:** 프로젝트 전체 회귀 테스트 **1,413건 통과 확인** (H2 625 / MySQL 751 / 단위 37, 팀 전체 기준으로 직접 작성한 테스트 수와 다름)

#### 02. [DOMO — AI 기반 일정·장소 추천 서비스](https://github.com/Wangjonghui/domo-be)
**Team Project · Backend**  
`Spring Boot` `PostgreSQL` `Supabase` `AI API` `AWS EC2`

- 이용자의 위치·시간·예산·선호 카테고리를 고려한 일정 추천 API 개발
- 장소 간 거리, 카테고리 분산, 중복 장소 제외 등을 반영한 추천 로직 구현
- 프론트엔드 연동 및 클라우드 환경 배포 경험


#### 03. [Career-HI — 개발자 채용공고 서비스](https://github.com/syu-HackathonTeam/career-hi-back)

**Team Project · Backend**  
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-30363d?style=flat-square)
![Java](https://img.shields.io/badge/Java-30363d?style=flat-square)
![REST API](https://img.shields.io/badge/REST%20API-30363d?style=flat-square)
![Database](https://img.shields.io/badge/Database-30363d?style=flat-square)

- 개발자 채용공고 관련 데이터베이스 설계 및 REST API 개발
- API 명세서를 기반으로 백엔드 기능 구현
- 프론트엔드 API 연동 및 로그 기반 오류 분석·수정


#### 04. [Foodmap — 푸드트럭 위치 공유 서비스](https://github.com/Wangjonghui/SwProject-be)
**Team Project · Backend**  
`Spring Boot` `MySQL` `Kakao Map API` `AWS EC2` `Nginx`

- 푸드트럭 등록·조회, 리뷰, 찜, 알림 관련 백엔드 기능 개발
- 지도 기반 서비스 API 연동 및 서버 배포·운영 과정의 문제 해결

#### 05. 멋쟁이사자처럼 삼육대학교 홈페이지
**Team Project · Backend**  
[Repository](https://github.com/GyoseungKu/Likelion_SYU_Homepage) *(접근 권한에 따라 열리지 않을 수 있음)*

- 공지사항 관련 기능 개발 및 Cloudflare R2 연동 문제 해결
- 과제 기능 추가 및 `UserRoleRepository` 일부 수정
- 출석 관련 로직 개발과 변경사항 롤백 경험

---

### How I Work

- **정합성과 보안** — 권한, 계정 상태, 약관 동의 여부 등 실제 서비스의 예외 조건을 고려합니다.
- **검증 가능한 구현** — 통합 테스트와 회귀 테스트로 변경에 따른 영향을 확인합니다.
- **협업과 기록** — API 계약을 문서화하고 변경사항과 문제 해결 과정을 공유합니다.

<sub>더 나은 설계와 운영 방법을 꾸준히 학습하고 있습니다.</sub>
