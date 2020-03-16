# Selector

- 팀으로 일할때

  > class 말고 pseudo-selector(가상 셀렉터)를 통해서 선택할 수 있다.

- ##### pseudo-selector(가상 셀렉터)

  > element가 아닌 것을 뜻한다.

- input[*required*="required"]{

  ​    background-color: red;

    }

- .box:last-child{}

  > 모든 박스중에 마지막 box를 선택

- *.**box**:nth-child*(3n+2){}

  > 3번째 줄에서 2번째 박스만 고름.

- #### pseudo-selector(가상 셀렉터)

  > 태그 이름이나, class id를 쓰지않고 선택하는 방법이있다.

- input + .box{}

  > 서로가 형제라는 뜻.

- input > box {}

  > direct child(직계)
  >
  > 그 밑에 다른 박스들이 있다면 걔네들한테는 해당되지 않음.

- 연습많이해라 그럼될것이다.