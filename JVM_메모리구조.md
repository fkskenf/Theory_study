1. 메서드 영역 (Method Area)
> - 클래스 정보와 클래스변수가 저장되는 곳

2. 호출스택 (Call Stack)
> - 메서드의 작업 공간.
> - 메서드가 호출되면 메서드 수행에 필요한 메모리공간을 할당받고 메서드가 종료되면 사용하던 메모리를 반환한다.

3. 힙 (Heap)
> - 인스턴스가 생성되는 공간.
> - new 연산자에 의해서 생성되는 배열과 객체는 모구 여기에 생성된다.
> - GC : 가비지 컬렉터가 일어나는 공간 (참조되지 않는 객체를 제거한다.)
