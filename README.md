# CSS-notepad-Part4

___
## 문자
1. color
2. text-align
3. text-decoration
4. text-indet
___
### color : 글자의 색상
rgb(0,0,0) : red, greed, blue 세 종류의 강원을 이용하여 색을 혼합해서 섞을수 있도록 해주는것 <br/>
색상은 기타 지정 가능한 색상을 사용할수가 있다.
___
### text-align : 문자의 정렬 방식
left(왼쪽 정렬), right(오른쪽 정렬), center(가운데 정렬)
___
### text-decoration : 문자의 장식(선)
none: 장식 없음<br/>
underline: 밑줄<br/>
line-through<br/>
___
### text-indet : 문자 첫 줄의 들여쓰기
단위로 로 지정 할수가 있고 outdent 는 음수를 입력하면 사용할수가 있다.
___
## 배경
1. background-color
2. background-image
3. background-repeat
4. background-position
5. background-size
6. background-attachment
___
### background-color
transparent: 투명함<br/>
color 처럼 지정 가능한 색상을 사용할수가 있다.
___
### background-image
uil("경로") : 이미지 경로
___
### background-repeat
repeat: 이미지를 수직, 수평 반복
repeat-x: 이미지를 수평 반복
repeat-y: 이미지를 수직 반복
no-repeat: 반복 없음
___
### background-position
방향 : top, bottom, left, right, center 방향 을 지정할수 있다.
단위 : px, 등등 단위로 지정 가능
___
### background-size
auto: 이미지 실제 크기 지정
cover: 비율을 유지, 요소의 더넓은 너비에 맞춤
contain: 비율을 유지, 요소의 더 짧은 너비에 맞춤
___
### background-attachment
scroll: 이미지가 요소를 따라서 같이 스크롤
fixed: 이미지가 뷰포트에 고정, 스크롤 x
___
## 배치
### position
relative : 요소 자신을 기준
absolute : 위치 상 부모 요소를 기준 
fixed: 뷰포트 를 기준
*css 속성들을 모두 음수 사용 가능*
z-index : 요소의 쌓임 정도를 지정
___
