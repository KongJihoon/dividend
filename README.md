## 주식 배당금 API 서비스

## ✔️ 프로젝트 소개
- 주식 데이터를 가져와 배당금을 알아보는 프로젝트.

## ✔️ 기술 스택
- Language: Java
- Build: gradle
- DataBase: H2 DataBase
- JDK: jdk11
- Library: LomBok, spring-web, logback, Jsoup, Jwt

## ✔️ 구현 API

### 배당금

✅ GET /finance/dividend/{companyName}

`GET` 요청을 사용해서 특정 회사의 배당금을 조회할 수 있습니다.

✅ GET /company/autocomplete?keyword=O

`GET` 요청을 사용해서 검색할 회사명을 자동완성할 수 있습니다.

✅GET /company

`GET` 요청을 사용해서 회사 리스트를 조회할 수 있습니다.

### 관리자

✅ POST /company

`POST` 요청을 사용해서 종목을 저장할 수 있습니다.

✅ DELETE /company?ticker=GOOD

`DELETE` 요청을 사용해서 해당 종목을 삭제할 수 있습니다.

### 회원

- 회원가입
- 로그인
- 로그아웃

  
