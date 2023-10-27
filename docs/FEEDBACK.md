# <1주차 공통 피드백👀>

## 1. 요구사항을 정확히 준수한다.
- 기능 요구사항
- 프로그래밍 요구사항
- 과제 진행 요구사항

위 세 가지 내용을 모두 지켰는지 점검한다.

## 2. 커밋 메시지를 의미 있게 작성한다.
커밋 메세지에 해당 커밋에서 작업한 내용에 대한 이해가 가능하도록 작성한다.

## 3. git을 통해 관리할 자원에 대해서도 고려한다.
<code>.class</code>파일은 java코드가 있으면 생성할 수 있다. 그러므로 굳이 git을 통해 관리하지 않아도 된다.
추가적으로 IntelliJ의 <code>.idea</code>폴더 역시 git으로 관리하지 않아도 된다.

-> git을 통해 관리할 필요가 있는지 고려해볼 것을 추천한다!

## 4. Pull Request를 보내기 전 브랜치를 확인한다. 
기능 구현 작업을 fork된 Repository의 main branch가 아닌, 기능 구현을 위해 새로 만든 브랜치에서 작업한 후 PR을 보낸다.

## 5.PR을 한 번 작성했다면 닫지 말고 추가 커밋을 한다.
한 번 PR을 보내면, 새로운 PR을 생성할 필요가 없다. 추가 커밋 시 자동으로 반영되기 때문이다.

## 6. 이름을 통해 의도를 드러낸다.
변수 이름, 함수 이름, 클래스 이름을 짓는데 시간 투자가 필요하다.
이름을 통해 역할의 의도를 확실히 드러내기 위해 노력하자.

## 7. 축약하지 않는다.
의도가 확실히 드러난다면 이름이 길어져도 괜찮다.

## 8. 공백도 코딩 컨벤션이다.
if, for, while문 사이의 공백도 코딩 컨벤션이다.

## 9. 공백 라인을 의미 있게 사용한다.
공백 라인을 의미 있게 사용하는 것이 좋아 보이며, 문맥을 분리하는 부분에 사용하는 것이 좋다.

## 10. Space와 Tab을 혼용하지 않는다.
들여쓰기에 space와 tab을 혼용하지 않는다. 둘 중에 하나만 사용한다.

## 11. 의미 없는 주석을 달지 않는다.
코드에 의미 없는 주석을 달기 보다 이름으로 의도를 드러내는 것이 좋다.
의도를 드러내기 힘든 경우처럼 필수적인 경우에 주석을 다는 연습을 하자

## 12. IDE의 코드 자동 정렬 기능을 활용한다.
- IntelliJ IDEA: <code>⌥ ⌘ L, </code>

## 13. Java에서 제공하는 API를 적극 활용한다.
함수(메서드)를 직접 구현하기 전에 Java API에서 제공하는 기능인지 검색을 먼저 해본다.
Java API에서 제공하지 않을 경우 직접 구현한다.


## 14. 배열 대신 Java Collection을 사용한다.