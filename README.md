# jpashop

## spring 부트와 JPA 활용하여 쇼핑몰 만들기
 스프링부트와 JPA를 활용하여 실전에서도 사용가능한 쇼핑몰을 만들어 보자

### 기술 스택
1. 인텔리제이(IDE)
2. 스프링부트
3. H2(데이터베이스)
4. JPA(ORM)
5. jdk 11
6. thymeleaf

#### 프로젝트 생성

* 의존성 추가
  1. web
  2. jpa
  3. h2 데이터베이스
  4. lombok
  5.thymeleaf
  
#### 인텔리제이 설정
* IntelliJ > Preperence > gradle 검색 > build and run using, run tests using을 gradle에서 intelliJ로 변경 
* Lombok 플러그인 설치 > Preperence에서 'annotation Processor' 검색 후 Enable annotation processing 체크 

#### 핵심 라이브러리
* 스프링 MVC
* 스프링 ORM
* JPA, 하이버네이트
* 스프링 데이터 JPA

#### 기타 라이브러리
* H2 데이터베이스 클라이언트
* 커넥션 풀: 부트 기본은 HikariCP
* WEB(thymeleaf)
* 로깅(SLF4J & LogBack
* 테스트


## 1. Thymeleaf, https://www.thymeleaf.org/

- 장점
  * 마크업을 깨지 않고 그대로 쓸 수 있음. 웹 브라우저에서 열림
  * 익숙해지면 편하다.

- 세팅은 dependancy에 thymeleaf만 추가해주면 된다.

## 2. H2 데이터베이스

1. 다운로드 https://www.h2database.com/html/main.html
2. 압축 해제 후 터미널 통해 실행, 윈도우는 .bat 파일, 맥, 리눅스는 .sh 파일 실행

- DB 폴더 생성만 파일모드로 접근하고 이후는 네트워크 모드로 접근해야함.
