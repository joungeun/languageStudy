제네릭 타입 클래스에 타입 지정을 안 해주면 어떻게 되지 하고 궁금했는데 Raw Type이라는 게 있었다.

## Raw Type

타입 파라미터가 없는 제네릭 타입이다.  제네릭 타입을 하나 정의하면 그에 딸린 raw type도 함 께 정의된다. 

>  List<T>의 raw type은 List다. 

raw type은 타입 선언에서 제네릭 타입 정보가 전부 지워진 것처럼 동작한다.

Raw Type은 일단 쓰면 안 된다. java5 이전과 호환성이 있기 때문에 있는 것이다.  와읻르 카드 타입을 다시 한 번 공부하고 Raw Type을 보면 이해가 더 잘 될 것 같다.