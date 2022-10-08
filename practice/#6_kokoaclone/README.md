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