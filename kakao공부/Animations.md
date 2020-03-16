# Animations

-  *@keyframes* 이름 {}

  > 키프레임은 css로 하여금 너가 애니메이션을 생성했다는 것을 알려준다.
  >
  > *@keyframes scaleAndRotateSquare {*
  >
  > ​      *from{*
  >
  > ​      *}*
  >
  > ​      *to{*
  >
  > ​      }
  >
  > From 아무것도 없는 상태에서 - To 어떤 변화된 모습까지.
  >
  > *@keyframes* scaleAndRotateSquare {
  >
  > ​      0%{
  >
  > ​        transform:none;
  >
  > ​      }
  >
  > ​      50%{
  >
  > ​        transform: rotate(1turn) scale(.5, .5);
  >
  > ​        color:white;
  >
  > ​      }
  >
  > ​      100%{
  >
  > ​        transform: none;
  >
  > ​        color:blue;
  >
  > ​      }
  >
  > ​    }

- #### infinite(무한)

  > 무한으로 반복하고 싶을때 사용.

- 키프레임에 애니메이션 이름을 작성하고 스테이지별로 0 - 50 - 100 을 정함.(마음대로 정할 수 있음.)
- 스테이지가 2개만 있으면 from - to를 쓰면됨.