# ☀ 날씨 일기 프로젝트
> 외부 API를 이용해서 날씨 데이터를 가져와 일기를 작성하는 프로젝트입니다.


# 💻 Tech Stack
- Language : `Java`
- JDK : `JDK 17.0.13`
- Build : `gradle`
- DataBase : `MySQL`
- Library : `Lombok`, `spring-web`, `swagger`, `logback`
- `Spring Boot 3.3.5`
- `Spring Boot Data JPA`
- `Spring Boot JDBC`

# 📌 주요기능 및 체크사항
✅ DB와 관련된 함수들을 트랜잭션 처리
✅ 매일 새벽 1시에 날씨 데이터를 외부 API 에서 받아, DB에 저장해두는 로직을 구현
✅ logback 을 이용하여 프로젝트에 로그 기록 남기기
✅ ExceptionHandler 을 이용한 예외처리
✅ swagger 을 이용하여 API documentation
