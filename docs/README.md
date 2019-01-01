# Documentation

## 차례

- 스프링 IoC

## 용어

DAO
: Data Access Object. DB 접근 전담하는 객체.

JavaBean
: 재사용이 가능한 소프트웨어 컴포넌트.  
- 파라미터가 없는 생성자
- getter, setter로 접근, 수정 가능.

JDBC
: Java Database Connectibity. Java API  
1. Connection
1. SQL Statement, PreparedStatement
1. Execute Statement
1. ResultSet -> Object
1. Resource(Connection, Statement, ResultSet) Close
1. Exception Catch, Throw

객체지향 설계 원칙
: 로버트 마틴. SOLID
- SRP: Single Responsibility Principle. 단일 책임 원칙
- OCP: Open Closed. 개방 폐쇄 -> 높은 응집도(high coherence), 낮은 결합도(low coupling)
- LSP: Liskov Subsitution. 리스코프 치환
- ISP: Interface Segregation. 인터페이스 분리
- DIP: Dependency Inversion. 의존관계 역전

Inversion of Control
: 제어의 역전. 제어 권한을 위임.  
- 깔끔한 설계
- 유연성 증가
- 확장성 향상
- 컴포넌트의 생성과 관계설정, 사용, 생명주기 관리 등을 관장하는 존재 필요
