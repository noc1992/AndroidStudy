# LinearLayout 리니어 레이아웃

## 리니어 레이아웃의 방향 속성과 정렬 속성

- 뷰를 정렬할 때 layout_gravity와 gravity 속성이 사용됨
- Gravity는 지구의 ‘중력’처럼 끌어당기는 힘을 의미( layout_gravity 속성의 값이 left이면 뷰를 왼쪽으로 끌어당겨 정렬하라는 의미)
- 주의할 점 1 : layout_gravity는 뷰를 정렬하는 데 사용되고 gravity는 뷰 안에 들어있는 내용물을 정렬할 때 사용됨.
	        (예 : 버튼 안에 들어있는 글자 -> 글자가 내용물이 되니 gravity 속성을 주면 그 글자를 정렬하겠다는 의미가 됨.
- 주의할 점 2 : 여유 공간이 있어야 정렬할 수 있음
               (예 : 버튼의 가로 크기 속성인 layout_width의 값을 wrap_content로 해놓으면 gravity 속성의 값으로 가로 방향 왼쪽이나 
                   오른쪽으로 정렬하라는 값을 주더라도 움직일 공간이 없기 때문에 정렬은 아무 의미가 없음.
