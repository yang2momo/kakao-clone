# Position property

- 디폴트로 모든 박스의 포지션은 static이다.

- #### position : static;

  > element를 거기 놓으면 거기있을것이다.라는뜻.

- #### position : fixed;

  > 고정
  >
  > 고정된 포지션이기때문에 그대로 붙어있음.
  >
  > element가 그 위치에 오버램해서 고정됨. 그렇기 때문에 스크롤해도 볼 수 있다.

- 포지션을 고정하고 4가지 설정값을 줄수있다. 상하좌우간격

- 포지션 static은 디폴트 값이다. element를 붙이면 거기 그대로 있는다.

- ### absolute

  > fixed랑 비슷. 어디에든 붙일 수 있지만 스크롤한다고 보이지 않는다.
  >
  > html상에서 해당 element와 관계가 있는 (relative- 부모박스) element를 살펴보고 이에 상응해서 포지션이 결정된다.

- #### Position fixed

  > 고정 어디든 오버램해서 계속 해당 위치에 고성시키기 위한것.

- #### Position relative

- #### Position absolute

  > 포지션 relative에 상대적으로 포지션을 잡는것. relative 포지션이 없을 경우, absolute는 문서의 본문 body에 맞춰서 포신셔을 잡음.

- #### Position static

  > 디폴트