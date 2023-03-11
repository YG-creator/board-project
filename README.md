# 요구사항 분석

- [use-case](./document/use-case.svg)



# 설계

* [아키텍처 구조](./document/architecture.svg)
* [ERD](./document/erd.svg)
* [API]()



# Features

* 회원 로그인
  * DB인증
  * 로그인 실패
* 게시판 보기
  * 일반게시판
    * 게시글 쓰기
    * 게시판 정렬
    * 게시판 검색
  * 해시태그 게시판
    * 게시판 정렬
    * 게시판 검색
* 게시글 보기
  * 내가쓴 글 수정, 삭제
  * 댓글
    * 보기
    * 내가 쓴 댓글 수정, 삭제



# Tech Stack

Spring Boot

- Spring Boot Actuator
- Spring Web
- Spring Data JPA
- Rest Repositories
- Rest Repositories HAL Explorer
- Thymeleaf
- Spring Security
- H2 Database
- MySQL Driver
- Lombok
- Spring Boot DevTools
- Spring Configuration Processor

그 외

- QueryDSL 5.0.0

- Bootstrap 5.2.0-Beta1

- Heroku

  
