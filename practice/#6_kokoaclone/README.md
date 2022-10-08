### BEM 규칙
- Blcok Element Modifiler 
- 해당 규칙은 많은 사람들이 적용시키는 규칙이다.
- 좀 더 쉽게 읽히는 css 를 가지는것.
- Bem example 
```css
/* Block component */
.btn {}

/* Element that depends upon the block
- 버튼 안에 price 정보가 있어서 그 부분의 클래스 이름을 btn__price 라고 정의.
*/
.btn__price {}

/* Modifier that changes the style of the block 
가끔 modifier 를 가지는 경우가 있는데, 아래처럼 정의.
*/
.btn--orange {}
.btn--big {}
```

### SVG
- SVG 는 픽셀이 없는 이미지 파일형식이다.
- 수학으로만 구성된 형식.
- 좌표로 되어있어서, 원하는 만큼 늘릴수도 있다.

### css 파일을 쪼개고 쪼개고 ... 
- 나폴레옹의 분할 정복법 


### css 의 not 속성
- 뭔가가 적용되는 걸 원하지 않을때.

### To-Do BEM style's

- #login-form -> .login-from___ 
- 더 편한 방식을 택하면 된다.
- styles.css 파일에는 font-family와 같이 모든 스크린에 적용될 수 있는 스타일을 써놓는다.( or 모든 스크린의 background-color) 이는 하나의 방식이고, 자신만의 편한 방식을 택하면 된다.

### Form Tag
- form은 중요한 2가지 속성(attribute)을 가지고 있다. *하나는 action이고, 다른 하나는 method이다.*
- *action* 은 어떤 페이지로 data를 보낼건지 지정할 수 있다.
- *action* 에 적어 놓은 URL에 해당하는 파일이 반드시 존재해야한다.
- *method* 는 2가지 방식 중 하나를 쓸 수 있다. 하나는 *POST* 이고, 다른 하나는 *GET* 이다.
- *POST* 는 백엔드 서버에 정보를 전송하는 방식이라 이번 강의에서는 사용할 수 없다.
- *GET* 방식은 보안에 취약하다. username이랑 password를 GET 방식으로 보내선 안된다. URL에 포함되어도 상관없는 정보들을 GET 방식으로 보내는 것이다.


### 위치 고정하기
- position : fixed
- 배열이 깨지는 경우 width : 100% 설정
- 고정할 위치 (아래 인 경우 bottoom : 0;)과 같이 설정
- box-sizing:border-box를 사용해 아이콘들이 한 줄로 보이게 함