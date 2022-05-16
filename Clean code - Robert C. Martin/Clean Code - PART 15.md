# Clean Code - Robert C. Martin : PART 15

### PART 15 : JUnit 들여다보기

해당 파트에서는 JUnit Framework의 ComparisonCompactor 모듈을 리팩토링하는 과정을 보여준다.

1. 클래스 멤버 변수 앞에 있는 접두어를 제거한다.
2. 의도를 명확히 하기 위해 조건문을 캡슐화한다. 
3. 이름은 무조건 정확하게 하고, 부정문은 긍정문보다 이해하기 약간 어렵다. 따라서 조건문을 캡슐화할때 긍정문으로 변경한다.
4. 전체 함수는 위상적으로 정렬되어 각 함수가 사용된 직후 정의된다. 분석 함수가 먼저 나오고 조합 함수가 그 뒤를 이어서 나온다.
    1. 추후 함수를 리팩토링하는 과정에서 꽤 좋은 방식일 듯 하다.