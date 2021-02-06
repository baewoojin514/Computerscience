# Development Common Sense

- 좋은코드 
- 객체 지향 프로그래밍(OOP)
  - OOP의 원칙
- RESTful API
- TDD

## 좋은 코드
~~~
1. 읽기 쉬운 코드
2. 중복이 없는 코드
3. 테스트가 용이한 코드
~~~

## 객체 지향 프로그래밍(OOP)

객체 지향 프로그래밍이란 인간중심적 프로그래밍이다. 즉 현실 세계를 프로그래밍으로 옮겨와 프로그래밍을 하는 것을 의미한다.

### OOP의 장점
~~~
1. 재사용성이 높아진다.
   - 객체 단위로 코드가 나눠져 작성된다.
2. 유지보수가 쉽다.
3. 코드가 간결하다.
~~~

### OOP의 단점
~~~
1. 처리 시간이 비교적 오래 걸린다.
   - 객체간 메세지 교환에서 많은 overhead가 발생한다.
2. 프로그램 설계시 많은 시간이 걸린다.
~~~

### OOP의 5원칙(SOLID)
~~~
1. S(SRP : Single Responsibility Principle) : 한 클래스는 하나의 책임만 가져야 한다.
2. O(OCP : Open/Closed Priciple) : 확장에는 열려(Open) 있으나, 변경에는 닫혀(Closed)있어야 한다.
3. L(LSP : Liskov's Substitution Principle) : 프로그램의 객체는 프로그램의 정확성을 깨뜨리지 않으면서 하위 타입의 인스턴스로 바꿀 수 있어야한다.
4. I(ISP : Interface Segregation Principle) : 특정 클라이언트를 위한 인터페이스 여러 개가 범용 인터페이스 하나보다 낫다.
5. D(DIP : Dependency Inversion Principle) : 추상화에 의존한다. 구체화에 의존하면 안된다.
~~~

## RESTful API

**REST**란 REpresentational State Transfer의 약자이다. 여기에 ~ful 이라는 형용사형 어미를 붙여 ~한 API 라는 의미로 사용된다. 즉 REST 의 기본 원칙을 성실히 지킨 서비스 디자인은 'RESTful'하다라고 표현할 수 있다.

**REST**는 디자인 패턴이다. **Resource Oriented Architecture** 즉 자원(Resource)를 중심으로 한 API 설계이고 HTTP Method를 통해 자원을 처리하도록 하는 것이다.

### REST API 디자인
~~~
1. URI는 정보의 자원을 표현해야 한다.
2. 자원에 대한 행위는 HTTP Method(GET, POST, PUT, DELETE)로 표현한다.
~~~
|Method|역할|
|---|---|
|post|POST를 통해 해당 URI를 요청하면 리소스를 생성한다.|
|GET|GET를 통해 해당 리소스를 조회합니다. 리소스를 조회하고 해당 도큐먼트에 대한 자세한 정보를 가져온다.|
|PUT|PUT를 통해 해당 리소스를 수정한다.|
|DELETE|DELETE를 통해 리소스를 삭제한다.|

## TDD

~~~
Test-Driven Development(TDD)는 매우 짧은 개발 사이클의 반복에 의존하는 소프트웨어 개발 프로세스이다. 

우선 요구되는 기능에 대한 자동화된 테스트를 작성하고 해당 테스트를 통과하는 가장 간단한 코드를 작성한다. 테스트를 통과하는 코드를 일단 작성하고 상황에 맞게 refactoring하는 과정을 거친다.

테스트가 코드 작성을 주도하는 개발방식이다.
~~~
