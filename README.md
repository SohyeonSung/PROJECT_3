# MEDIPRIME 병원

<img width="789" height="470" alt="Image" src="https://github.com/user-attachments/assets/8d190b67-4652-47b1-b401-1b7f7a205c11" />

---

## 👋 소개

> **환자·의료진·관리자를 위한 병원 통합 관리 시스템**  
> 단순한 병원 안내 웹페이지를 넘어, **환자 예약·진료 기록·증명서 발급**부터  **의료진 스케줄 관리 및 병원 간 협진 요청·회신**, **관리자용 통합 데이터 관리**까지 지원하는 **병원 통합 포털 시스템**입니다.  

### 선정 배경
1. 기존 병원 웹사이트가 단순 정보 제공에만 치중되어 있어 **환자·의료진 간 상호작용과 통합 관리가 어려움**  
2. **예약, 진료 기록, 증명서 발급** 등 환자 서비스가 여러 시스템으로 분산되어 불편함이 존재  
3. **의료진 스케줄 관리와 병원 간 협진 요청·회신 기능**이 부족해 의료진의 협력 진료 및 정보 공유 효율성이 떨어짐  
4. 관리자는 **회원·진료·협진 데이터**를 한 곳에서 통합적으로 관리할 수 있는 시스템 필요성이 대두됨  
5. 이를 통해 **환자는 예약부터 진료·증명서 발급까지 원스톱 서비스**를 이용하고,  
   **의료진은 협진 및 스케줄 관리 효율성을 개선**하며,  
   **관리자는 전체 병원 데이터 흐름을 통합 관리**할 수 있도록 목표를 설정함  

---

## 🛠 개발 환경

### 개발 언어
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/jsp-FF6C37?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/AJAX-1C1C1C?style=for-the-badge&logo=javascript&logoColor=white">

### 프레임워크 & 라이브러리
<img src="https://img.shields.io/badge/Spring%20MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/MyBatis-000000?style=for-the-badge&logo=mybatis&logoColor=white"> <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white">

### 개발 도구
<img src="https://img.shields.io/badge/eclipse-2C2255?style=for-the-badge&logo=eclipseide&logoColor=white"> <img src="https://img.shields.io/badge/apache%20tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white"> <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white">

### 아키텍처
<img src="https://img.shields.io/badge/MVC%20Pattern-232F3E?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/Controller-00599C?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/Service-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> <img src="https://img.shields.io/badge/DAO/Mapper-000000?style=for-the-badge&logo=mybatis&logoColor=white"> <img src="https://img.shields.io/badge/DTO-FF6F00?style=for-the-badge&logo=java&logoColor=white">

### API & 외부 서비스
<img src="https://img.shields.io/badge/Kakao%20Map-FFCD00?style=for-the-badge&logo=kakao&logoColor=black"> <img src="https://img.shields.io/badge/Kakao%20Login-FFCD00?style=for-the-badge&logo=kakaotalk&logoColor=black"> <img src="https://img.shields.io/badge/Toss-0064FF?style=for-the-badge&logo=toss&logoColor=white"> <img src="https://img.shields.io/badge/Apache%20POI-2496ED?style=for-the-badge&logo=apache&logoColor=white">

---

## 🏛 시스템(아키텍쳐) 구조

<img width="1218" height="480" alt="Image" src="https://github.com/user-attachments/assets/02e0f3ff-2be4-4056-937c-c439937d9ca2" />


---

 ## 🗄️ 테이블 구조

| 유저 | 의료진 | 협진의 |
|------|--------|--------|
| <img width="549" height="469" alt="유저 테이블" src="https://github.com/user-attachments/assets/5380f27b-9058-4c72-982c-70b2857d9512" /> | <img width="483" height="420" alt="의료진 테이블" src="https://github.com/user-attachments/assets/8f1290ce-9cd5-4829-b77c-a10048dd20c8" /> | <img width="522" height="469" alt="협진의 테이블" src="https://github.com/user-attachments/assets/ce82d330-5260-4a11-9f72-deac615a2e26" /> |

| 게시판 | 공지 | 공통 |
|--------|------|------|
| <img width="456" height="468" alt="게시판 테이블" src="https://github.com/user-attachments/assets/2d0bd5b7-aa70-4fa2-89fa-7018a57033da" /> | <img width="360" height="469" alt="공지 테이블" src="https://github.com/user-attachments/assets/619b2d9a-4088-4105-bb25-e58ee611b1ab" /> | <img width="458" height="469" alt="공통 테이블" src="https://github.com/user-attachments/assets/05be2dc7-a73a-45d7-ac27-0283ead34f5c" /> |



---

## 🖥 화면 구성

| 의료진 | 협진 신청 |
|-------------|-----------|
| <img width="715" height="450" alt="Image" src="https://github.com/user-attachments/assets/26aae736-a47f-492e-9127-3748b53eb4b5" /> | <img width="613" height="579" alt="Image" src="https://github.com/user-attachments/assets/334035df-1079-462b-b2fc-94efe92a44b2" /> |

| 진료 예약 | 예약 확인 |
|-----------|-----------|
| <img width="747" height="327" alt="Image" src="https://github.com/user-attachments/assets/0fdce3d5-fe49-43fd-8f16-5dcc6e6f8b0e" /> | <img width="670" height="562" alt="Image" src="https://github.com/user-attachments/assets/60b9cf9d-cde4-4d7f-8b03-d40a6146266a" /> |

| 증명서 발급 | 관리자 대시보드 |
|-------------|----------------|
| <img width="686" height="569" alt="Image" src="https://github.com/user-attachments/assets/9bed36ed-d614-4232-b188-3e314a0df344" /> | <img width="934" height="442" alt="Image" src="https://github.com/user-attachments/assets/6c723e02-a467-46d5-9188-8d7483f6a37e" /> |


---

## ✨ 주요 기능

- **환자**
  - 진료 예약 (회원/비회원 예약 지원)
  - 진료 기록 열람 및 증명서 발급

- **의료진**
  - 개인 스케줄 관리 (진료, 회의, 휴가 등)
  - 타 병원과의 협진 요청 및 회신 시스템 구축

- **관리자**
  - 관계자(의료진·협력의 등) 가입 신청 승인 및 관리
  - 유저 데이터 통합 관리 (회원 정보, 진료·협진 데이터, 시스템 접근 제어)

---

## 🧩 추가 적용 기술

- **DB 암호화 (SHA-512)**  
  사용자 비밀번호를 안전하게 저장하기 위해 SHA-512 해시 알고리즘 적용

- **카카오 로그인 & 지도 API**  
  카카오 OAuth 기반 간편 로그인 지원 및 병원 위치/주변 편의시설 지도 표시

- **실명 인증**  
  사용자 가입 시 실명 기반 인증을 통한 보안 강화 및 정보 신뢰성 확보

- **Highcharts**  
  통계 및 데이터 시각화를 위해 Highcharts 라이브러리 적용 (학습 시간/예약 현황 등 그래프 제공)

- **네이버 스마트에디터**  
  공지사항·게시판 글 작성 시 WYSIWYG 에디터 제공으로 사용자 편의성 향상

- **CAPTCHA**  
  회원가입 및 로그인 시 자동화된 악성 접근을 방지하기 위한 캡차 적용

- **이메일 기반 임시 비밀번호 발급**  
  비밀번호 분실 시 등록된 이메일로 임시 비밀번호를 발급해 계정 복구 지원



---

## 💡 마무리

### 배운 점
- 초기 기획 단계에서 **환자 / 의료진 / 관리자** 역할을 명확히 정의하고 시스템 요구사항을 설계하는 경험을 쌓음  
- **DB 설계 → Spring MVC 구조 설계 → MyBatis 연동 → 서비스 구현**까지 백엔드 개발 전 과정을 경험  
- **SSL 세션 만료 관리, 실시간 알림, 데이터 구조 확장** 등 실무형 기능을 직접 구현하며 보안과 확장성의 중요성을 깨달음  
- 짧은 기간(6주) 안에 팀원들과 협력하며 **역할 분담과 협업 역량**을 키움  

### 추가적으로 구현한 / 구현하고 싶은 기능
- ✅ **보안 강화 (SSL 세션 만료 관리)** — 구현 완료  
- ✅ **실시간 알림 기능 (협진 요청/회신, 예약/진료 변경 알림)** — 구현 완료  
- 실제 의료 데이터 구조를 기반으로 한 **확장 기능 추가** (더 많은 의료 프로세스 반영)  
- 통합 테스트 자동화 및 **QA 프로세스 개선**  

### 회고
- **기획부터 구현까지 전 과정을 직접 경험**하며, 개발자로서 설계 능력과 협업 역량을 크게 향상시킬 수 있었음  
- 짧은 프로젝트 기간 동안 **통합 테스트 시간이 부족**해 오류 수정이 늦어진 점이 아쉬움으로 남음  
- 실무 수준의 보안, 알림, 데이터 구조 확장 등을 직접 구현해 **서비스 품질과 안정성**에 대한 감각을 익힐 수 있었음  
- 이번 프로젝트를 통해 **백엔드 개발자로서의 성장 기반**을 다질 수 있었으며, 이후 더 체계적이고 안정적인 시스템 설계를 목표로 하고자 함  




