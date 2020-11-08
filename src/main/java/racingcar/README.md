# 구현할 기능 목록

## 3단계 - 자동차 경주

- 초간단 자동차 경주 게임을 구현한다.
- 주어진 횟수 동안 n대의 자동차는 전진 또는 멈출 수 있다.
- 사용자는 몇 대의 자동차로 몇 번의 이동을 할 것인지를 입력할 수 있어야 한다.
- 전진하는 조건은 0에서 9 사이에서 random 값을 구한 후 random 값이 4이상일 경우이다.
- 자동차의 상태를 화면에 출력한다. 어느 시점에 출력할 것인지에 대한 제약은 없다.

## 4단계 - 자동차 경주(우승자)

- [0] 각 자동차에 이름을 부여한다.
- [0] 자동차 이름은 쉼표(,)를 기준으로 구분한다.
- [0] 전진하는 자동차를 출력할 때 자동차 이름을 같이 출력한다.
- [0] 자동차 이름이 5자를 초과하면 IllegalArgumentException 을 발생시킨다.
- [0] 자동차 경주 게임을 완료한 후 누가 우승했는지를 알려준다. 우승자는 한명 이상일 수 있다.

## 5단계 - 자동차 경주(리팩토링)

### 요구사항

- [0] 패키지 분리: controller, domain, view
- [0] domain 과 view 가 서로 의존하지 않도록 리팩토링
- [0] 단위 테스트 작성

### 피드백

- [0] Car 에서 정적 팩토리 메서드 활용
- [0] convertWinnerList 개선
- [0] Memento 일급 컬렉션 작성
- [0] cars 가 read only 되도록 하기