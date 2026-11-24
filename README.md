# inflearn_java_basic — 스프링 핵심 원리 (기본편)

인프런 김영한 님의 **스프링 핵심 원리 - 기본편** 강의를 따라 학습한 코드입니다. (2025.09.03 ~ 2025.09.05)

## 학습 내용

| 위치 | 내용 |
|---|---|
| `main/.../member`, `order`, `discount` | 회원·주문·할인 도메인 설계, 역할과 구현 분리(OCP, DIP), `AppConfig`로 순수 자바 DI |
| `main/.../annotation` | `@MainDiscountPolicy` 커스텀 애노테이션으로 동일 타입 빈 구분 |
| `main/.../web`, `common` | `request` 스코프 빈(`MyLogger`)과 `ObjectProvider` / `proxyMode` 지연 조회 |
| `test/.../beanfind`, `beanDefinition`, `xml` | 스프링 컨테이너 빈 조회, BeanDefinition, XML 설정 |
| `test/.../singleton` | 싱글톤 패턴의 문제, 상태 유지(stateful) 주의점, `@Configuration`과 CGLIB |
| `test/.../scan`, `autowired` | 컴포넌트 스캔 필터, 의존관계 자동 주입 옵션, 같은 타입 빈 전체 조회 |
| `test/.../lifecycle` | 빈 생명주기 콜백 (초기화·소멸 메서드) |
| `test/.../scope` | 싱글톤·프로토타입 스코프 차이와 함께 쓸 때의 문제 |

## 기술 스택

Java 17, Spring Boot 3.5.5, Gradle, JUnit5, Lombok

## 실행

```bash
cd core
./gradlew test
```
