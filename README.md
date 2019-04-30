# Lab14

*각각의 코드에 각주로 적어놨습니다*

**Polymorphism**

Cat, Dog는 Animal을 상속하고있다.
`Animal myAnimal = myCat`
`Animal myAnimal2 = myDog`
와 같이 자식이 부모 타입에 들어가지며 자식의 각각의 method또한  접근할 수 있는 것에서 Polymorphism 확인 할 수 있다.


**overriding**

 `myAnimal.testInstanceMethod();`
 과 같이 각각의 객체에 대한 같은 이름을 가진 메소드를 호출 했을 때, 결과 값은
 각각의 클래스에 정의 된 메소드로 나오는 것을 볼 수 있다.
 여기서 오버라이딩을 확인 할 수 있다.

**hiding**ㅅㄷ

testClassMethod() 는 Animal과 하위 클래스들 모두 static으로 선언되어있다. 따라서

`myAnimal.testClassMethod();`
`myAnimal2.testClassMethod();`
는 각각 Animal 클래스에 있는 메소드 Hiding이 일어나 하위 클래스에 있는 method의
결과값이 나온다.
