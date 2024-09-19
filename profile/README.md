# Gansik Shop Project

## 프로젝트 소개

2024.09.02 ~ 2024.09.06까지 진행한 가상의 온라인 쇼핑몰 구축 프로젝트

### UI 모델

- **[배민 상회](https://mart.baemin.com/?utm_source=google_pmax&utm_medium=displayad&utm_campaign=google_pmax&utm_term=main-pc_240311&airbridge_referrer=airbridge%3Dtrue%26event_uuid%3Dff543d59-93c3-4502-ad01-c548ca49422e%26client_id%3D128c7b2c-9cde-473b-9011-195f6c2f3037%26short_id%3Ddtbvkz%26referrer_timestamp%3D1726144829474%26channel%3Dgoogle_pmax%26campaign%3Dgoogle_pmax%26tracking_template_id%3D4bb8308b8aba0c4ca6aba98fc15e2c4a%26ad_group%3Dpmax_main_240311%26ad_creative%3Dmain-pc_240311%26sub_id%3Ddisplayad%26og_tag_id%3D48315338%26routing_short_id%3Dace3sc%26gad_source%3D1%26gclid%3DCjwKCAjwooq3BhB3EiwAYqYoEjrItBZ8EiQTXxgXRw56tM_Re3EBCBfnTl9QzyS-olivNZnb-A3UcBoCzrQQAvD_BwE&gad_source=1&gclid=CjwKCAjwooq3BhB3EiwAYqYoEjrItBZ8EiQTXxgXRw56tM_Re3EBCBfnTl9QzyS-olivNZnb-A3UcBoCzrQQAvD_BwE)**

### 차용한 API

- **[다음 우편번호 서비스](https://postcode.map.daum.net/guide)**

![daumpostcode v2](https://github.com/user-attachments/assets/b21d755e-1888-4df9-81a3-3c29a9773d77)

  본 프로젝트에서는 다음(Daum) 우편번호 서비스를 이용하여 회원 가입 및 수정 시 사용자에게 편리한 주소 검색 기능을 제공합니다.

### 기능
회원 - 가입, 수정, 로그인, 로그아웃

주문 - 등록, 조회

상품 - 등록, 전체 조회, 키워드 별 조회, 카테고리 별 조회, 상세 조회

장바구니 - 등록, 수정, 삭제(선택형), 조회, 장바구니에서 주문

### IDE
### Backend
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)

### Frontend
![Visual Studio Code](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
  
## 기술 스택

### Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-6DB33F?style=for-the-badge&logo=hibernate&logoColor=white)
![QueryDSL](https://img.shields.io/badge/QueryDSL-3498DB?style=for-the-badge&logo=codeigniter&logoColor=white)

### Frontend

![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)

### 실행 방법

### Frontend
git clone https://github.com/TeamGansik/Gansik-Shop-Frontend.git

### Backend
git clone https://github.com/TeamGansik/Gansik-Shop-Backend.git

1. Backend application.properties or application.yml 작성
2. Frontend의 main.html VSCode Live Server로 실행
3. Live Server Port 확인
4. Backend /src/config/SecurityConfig.java에서 cors부분 Port 수정 후 서버 재실행

### 실행 화면 예시

## 메인 화면
![main1](https://github.com/user-attachments/assets/89140489-19e6-46c6-93f7-edb96c5346df)
![main2](https://github.com/user-attachments/assets/09ad261f-3bb7-4be4-91ae-874ec7895546)

## 로그인 전/후 상태바
![Before Login](https://github.com/user-attachments/assets/63d02b81-a1a6-4d9b-863f-cb8dc0bc6a8b)
![After Login](https://github.com/user-attachments/assets/ceab561b-dc11-44cb-a446-870c7e78dba7)

## 로그인창 & 회원 가입(수정폼) (회원 가입과 수정폼은 동일한 형식)
![Login](https://github.com/user-attachments/assets/2208bec7-5b93-4d6f-b1b0-9f5edbc7fd41)
![MemberForm](https://github.com/user-attachments/assets/556d4d72-62fc-40be-8e8c-46519cf99201)

## 회원 가입(수정) 시 이메일 인증
![Email](https://github.com/user-attachments/assets/552a6b9f-7ac6-4281-99d0-41b177de05c1)
![Email2](https://github.com/user-attachments/assets/1ee3d05b-7929-441b-8fde-c511ee39028b)
![Email3](https://github.com/user-attachments/assets/5022482b-6a65-4fd1-928f-84e734f8f0cc)
![Email4](https://github.com/user-attachments/assets/f2ce0f6a-89b7-4483-922d-74771252997e)

## 로그인이 필요한 서비스 접근 시 (로그인 없이 마이페이지, 장바구니, 장바구니 담기, 구매하기 선택 시)
![Alert](https://github.com/user-attachments/assets/4490695c-db6d-49cf-99a2-8f53b9ffab0c)

## 상품 등록 
![Item Upload](https://github.com/user-attachments/assets/2ab64eb7-4a60-403d-be13-270b77bd7511)

## 상품 조회 (전체 검색, 키워드 검색, 카테고리 검색)
![Search Result](https://github.com/user-attachments/assets/9ebaa75c-d5bf-4767-b9c0-8d74c32a89f9)
![No Search Result](https://github.com/user-attachments/assets/e899ed31-24e9-486e-ace8-836231b7fbce)

## 장바구니 & 주문 조회
![Cart](https://github.com/user-attachments/assets/ee59c757-db9b-4610-b5da-717d89ff8c39)
![order](https://github.com/user-attachments/assets/adf5dd2e-b0a4-4408-9598-461926539184)
