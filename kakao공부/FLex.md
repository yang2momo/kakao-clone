# Flex

- ##### 문제점

  >  인라인 블록으로 자동으로 옆으로 붙지않고, 화면을 초과할시 아래로 내려가서 붙는다.
  >
  > 자동으로 완성되는 그리드가 없다.

- 플렉스를 사용할떄는 chidren  박스에 적용하지 않는다. 오직 부모 클래스에만 적용하면 됨.

- justigy-content: center;

  > 가운데로 이동

- flex-direction: column;

  > 수직으로 이동.

- 만약 flex-direction을 row 로하면, (디폴트값) justify-content가 수평으로 적용됨. align-item은 수직.

- 반대로 flex-direction이  column이 되면 justify-content는 수직이되고, 반대로  align-item은 수평이 됨.
- align-item을 center라고쓰면. 수평적으로 적용되어 가운데 정렬함.

- 플렉스 방향 row(디폴트) justify는 수평으로 , align은 수직으로 적용됨. 하지만 방향을 column으로 하면 반대가됨.

- 항상 디스플레이를 플렉스라고 선언하면됨.

- flex-wrap:wrap

  > 폭을 유지하고 밑으로 박스를 떨어뜨리고 싶을때.

- 디폴트값으로 플렉스는 no wrap이다. 그말은 폭은 무시하고 다줄어드는것.

- wrap으로 바꾸면 이렇게 그리드를 다시 볼 수 있다. 화면을 줄여도 폭은 그대로 유지해주는 것을 확인할 수 있다.

- flex-direction: row-reverse;

  > 반대로 출력됨.

- flex-direction: column-reverse;

  > 수직 방향으로 출력

- ### **justify-content**

- `flex-start`: 요소들을 컨테이너의 왼쪽으로 정렬합니다.

- `flex-end`: 요소들을 컨테이너의 오른쪽으로 정렬합니다.

- `center`: 요소들을 컨테이너의 가운데로 정렬합니다.

- `space-between`: 요소들 사이에 동일한 간격을 둡니다.

- `space-around`: 요소들 주위에 동일한 간격을 둡니다.

- ###  `align-items`

- `flex-start`: 요소들을 컨테이너의 꼭대기로 정렬합니다.

- `flex-end`: 요소들을 컨테이너의 바닥으로 정렬합니다.

- `center`: 요소들을 컨테이너의 세로선 상의 가운데로 정렬합니다.

- `baseline`: 요소들을 컨테이너의 시작 위치에 정렬합니다.

- `stretch`: 요소들을 컨테이너에 맞도록 늘립니다.