# Development Common Sense

- 좋은코드 
- 객체 지향 프로그래밍(OOP)
  - OOP의 원칙

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
