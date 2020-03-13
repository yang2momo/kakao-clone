# CSS Syntax

- ### selector

  > 만약 property를 내 html의 h1에 연결하고싶다면,
  >
  > h1{
  >
  > ​	property-name: value;
  >
  > }
  >
  > - h1이 selector다.
  > - 태그, 링크, 헤더, 푸터가 될수있다. 모든 태그이름들이 해당됨.
  >
  > 괄호를 열고 그 사이에 수많은 property를 원하는 만큼 넣을 수 있다.
  >
  > - ID를 쓰는경우
  >
  >   > 앞에 #을 붙여야함.
  >
  > - Class를 쓰는경우
  >
  >   > 앞에 . 을 붙여야함.
  >
  > - 둘다 섞는 경우
  >
  >   > h1. name 이런식으로  태그 + .Class 를 쓰면됨.
  >
  > - selector (id, class, tag name)
  >
  >   > 안에는  property를 작성하면됨.

- ### property

  > - property-name: value;
  >
  > 무조건 소문자, 중간에 공백없음, 그리고 value 를 마지막에 넣음

- ##### extension (확장)

- ### CSS HTML연결

  1. #### inline

     > style 사용
     >
     > 장점은 바로적용이 가능하지만 같은 배경색을 쓴다고 할 때, 해당 css를 모든 html문서에 복사 - 붙여넣기 해야함.(비효율적임)

  2. #### external(외부)

     > css 파일따로 생성
     >
     > - <link *href*="styles.css" *rel*="stylesheet"
     >
     >   > 링크 를 걸어주면됨

- #### style

  > css를 html파일 상단에 붙이는 걸 가능하게함.

- ##### efficient (실력있는)