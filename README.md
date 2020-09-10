# springBootExample
스프링부트 스터디1(맛보기: springBoot시작하기, mysql 연동, jpa설정) 입니다.

## 개발환경
### Springboot + Gradle
- Spring Web : 웹 개발에 필요한 스타터 제공 
- Thymeleaf : SpringBoot에서 권장하는 서버사이드 렌더링 템플릿 엔진(순수 html 문서에 html5문법으로 서버사이드 로직을 수행가능케 함, 기존의 JPA사용법과 유사) 
  [참고사이트](https://cyberx.tistory.com/132)
- Spring data JPA : Spring 진영의 대표적 ORM (객체와 DB의 테이블이 매핑을 이루는 것, 
                                           자바에만 국한된 것이 아님, 
                                           장점으로는 쿼리대신 메소드 호출만으로 쿼리가 수행이되 생산성이 높아짐.
                                           단점으로는 쿼리가 복잡해지면 ORM으로 표현하는데에 한계가 있고, raw 쿼리에 비해 느리다는 단점.
                                           단점의 극복방안으로는 JPQL,QueryDSL의 사용 또는 Mybatis와 같이 사용하는 방법이다.)
                    
- MySql : 대표적인 RDBMS 
