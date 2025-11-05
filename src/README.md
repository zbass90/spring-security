# 🔐 Spring Security 6.x 완전 정복 스터디

> 🧭 본 스터디는 인프런 강의  
> **[스프링 시큐리티 완전 정복 6.x 개정판](https://www.inflearn.com/course/%EC%8A%A4%ED%94%84%EB%A7%81-%EC%8B%9C%ED%81%90%EB%A6%AC%ED%8B%B0-%EC%99%84%EC%A0%84%EC%A0%95%EB%B3%B5/dashboard)**  
> 을 기반으로 진행합니다.

---

## 📚 학습 목표

- 스프링 시큐리티 6.x의 **전체 구조와 원리**를 완전하게 이해
- 인증(Authentication) / 인가(Authorization) 핵심 컴포넌트 심층 학습
- 6.x에서 새롭게 바뀐 **DSL, AuthorizationManager 구조** 완전 파악
- 실제 프로젝트 수준의 **회원 인증 & 관리 시스템 구현**

---

## 🗂️ 커리큘럼 개요

| Part | 주제 | 요약 |
|------|------|------|
| [1. 초기화 과정 이해](./parts/01-init.md) | 시큐리티 필터 체인 초기화, 빈 설정 | 구조적 이해 |
| [2. 인증 프로세스](./parts/02-authentication.md) | 로그인 흐름, AuthenticationManager, Provider | 인증 전체 플로우 |
| [3. 인증 아키텍처](./parts/03-architecture.md) | 객체 관계, ProviderManager 구조 | 내부 동작 원리 |
| [4. 인증 상태 영속성](./parts/04-persistence.md) | SecurityContext, Session, Remember-Me | 인증 유지 메커니즘 |
| [5. 세션 관리](./parts/05-session.md) | 세션 제어, 고정 보호, 동시 로그인 제어 | 실전 보안 관리 |
| [6. 예외 처리](./parts/06-exception.md) | AuthenticationException / AccessDeniedHandler | 에러 전략 |
| [7. 악용 보호](./parts/07-protection.md) | CORS, CSRF, SameSite | 보안 위협 방어 |
| [8. 인가 프로세스](./parts/08-authorization.md) | URL / 메소드 기반 인가 | 접근 제어 |
| [9. 인가 아키텍처](./parts/09-authorization-architecture.md) | AuthorizationManager 구조 | 새로운 인가 프레임워크 |
| [10. 이벤트 처리](./parts/10-event.md) | 인증/인가 이벤트 | 이벤트 기반 보안 |
| [11. 통합하기](./parts/11-integration.md) | MVC, 서블릿, WebFlux 통합 | 환경별 보안 설정 |
| [12. 고급 설정](./parts/12-advanced.md) | 다중 보안 설정, DSL 확장 | 고급 보안 |
| [13. 실전 프로젝트](./parts/13-project.md) | 회원 인증/관리 시스템 구현 | 실무 적용 |

---

## 🧩 참고

- 실습 환경: Spring Boot 3.x, Java 17+, Gradle
- IDE: IntelliJ Ultimate
- Docs: [Spring Security Reference (6.3)](https://docs.spring.io/spring-security/reference/index.html)

---

📅 **스터디 로그**는 각 Part 파일 하단에 누적됩니다.  
각 파트별로 예제 코드 / 정리 / 메모를 자유롭게 추가해주세요.
