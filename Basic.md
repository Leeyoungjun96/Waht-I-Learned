Respactor : 필요하면 소스코드도 바꾼다는 말(public class **Exam01**) 진한 색 부분도 같이 바꾸어줌.

While 문을 이용하여 24시간 서버를 가동함.

            추상클래스(상속)           |     인터페이스

           A ←b,c,d                   |      i <-- b,c,d

---------------------------------------------------------------------------------

b,c,d의 공통적인 메소드가 a 에 있다     |      b,c,d를 똑같은 방법으로 사용

공통 스펙을 a에 선언                   |     사용방법을 i 에 선언

A a = new B();                        |      i i1 = new B();

A a = new C();                        |      i i1 = new C();

B & C 를 만들어 놓고 부모타입을 사용    |     B & C 재정의가 무조건 되어있음

재정의가 안되어 있는것도 사용할때        |     재정의 되어있는 것만 사용하고 싶을때