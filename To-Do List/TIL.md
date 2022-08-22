2022-07-15

### **form**

~~~
<form>
input 요소들을 html로 전송한다
~~~


### **:root**
#### 가상 클래스(pseudo class)란?  
<br/>
Id 선택자나 class선택자로 사용할 수 없는 요소들을 선택하는 선택자.(:hover/:active/:nth-child(n))

#### 구조적 가상 클래스(structural pseudo-class)
웹 문서 구조에서 특정 위치에 있는 요소를 선택하는 가상 클래스(:root/:nth-child(n))

#### :root 가상 클래스
웹 문서 구조에서 가장 상위 요소 선택하는 가상 클래스
최상위 요소에서 변수를 선언->모든 요소에서 변수 사용 가능
:root의 경우 한 번에 수정이 용이   


### **overflow**
요소가 너무 커서 영역 안에 다 들어가지 않으면, 스크롤바를 만드는 등의 기능을 해준다.
* visible: default, 박스 밖으로 요소들 나감
* hidden: 박스 밖의 요소들은 안보이게 처리
* scroll: 스크롤바 형성(항상 가로축 세로축 2개 생성)
* auto: 스크롤바 형성(필요한 경우에만 필요한 축을 생성)


### **Negative Margin(음수 마진)**
* top/left에 음수 : 그 방향으로 요소가 이동
* bottom/right에 음수 : 이 요소 다음에 오는 요소를 끌어당김

### **background-repeat**
* 배경 이미지의 반복 여부, 반복 방향 결정
* background-repeat: repeat | repeat-x | repeat-y | no-repeat | inheri

### **visibility**
요소가 visible할지 정함
* visible: visible(Default)
* hidden: hidden(takes up space)

### **querySelector vs querySelectorAll**
querySelector
* 가장 첫번째 element를 반환
* 일치하는 요소가 없는 경우 null 반환
querySelecorAll
* 일치하는 모든 element를 반환

### **@media (미디어 쿼리)**

### **<section>, <article>**
section태그는 영역을 감싸거나 구분할 때,
article은 영역을 나누지만 언제든 그 영역이 다른 페이지나 영역에 가져다 쓸 수 있을때 쓴다.

### **box-shadow:inset 10px 10px rgba(0,0,0,0.1);**
inset : 박스 안쪽에 그림자를 표현

### **align-self: flex-start;**
align-self : 교차축 아이템 정렬
flex-start : 기준점 felx-start

### **forEach(()=> {})**
forEach() 메서드는 배열에 활용이 가능한 메서드로, 파라미터로 주어진 함수를 배열 요소 각각에 대해 실행하는 메서드이다.

### **small**
<small> : 덧붙임 글 요소

### **overflow-x: hidden;**
x축(왼쪽, 오른쪽)의 내용이 넘칠 때 내용이 잘림(스크롤바X)

### **가상요소**
* :before, :after
* 꾸밈을 위해서 의미없는 태그를 더 추가해야 될 때, 태그 대신에 가상으로 처리해 주는 쓸모 많은 css 기능입니다. 
* 가상 클래스와 구별하기 위해 : 이 아닌 ::
* content: ""; 와 항상 같이 쓰인다.
* content 속성
  * normal: 기본값
  * string: 문자열 생성
  * image; 이미지나 비디오 불러오기(크기조절 불가능)
  * counter: 순서를 매김
  * none: 아무것도 표시 안함
  * attr: 해당 속성의 속성값 표시


###  **position: static;**
https://www.daleseo.com/css-position/
* 브라우저 화면에 어떻게 배치되는가를 결정
* 기본값: static
* relative, absolute, fixed등으로 변경 간으
* absolute
  * 부모 엘리먼트 내부에 속박되지 않고, 독립된 배치 문맥(positioning context)을 가지게 됩니다. 마치 포토샵 같은 그래픽 툴에서 새로운 레이어를 추가하는 효과에 비슷하다고 생각하시면 됩니다.
  * 따라서, 엘리먼트를 기본적으로 브라우저 화면(viewport) 상에서 어디든지 원하는 위치에 자유롭게 배치시킬 수 있으며, 심지어 부모 엘리먼트 위에 겹쳐서 배치할 수도 있습니다.
  * 단, 상위 엘리먼트 중에 position 속성이 relative인 엘리먼트가 있다면, 그 중 가장 가까운 엘리먼트의 내부에서만 엘리먼트를 자유롭게 배치할 수 있습니다. 즉, 전체 화면이 아닌 해당 상위 엘리먼트를 기준으로 offset 속성(top, left, bottom, right)이 적용됩니다.

### **<a target="">**
target: 새로운 웹페이지를 여는 명령어
* target="_blank" 
  새 윈도우창을 열어서 웹페이지를 연다
* target="_slef"
  현재 윈도우창에 그대로 연다
* target="_parent"
  현재 프레임의 부모 프레임에서 연다.
* target="_top"
  최상위 프레임에서 연다.


### **<input required>**
반드시 작성해야지 넘어가진다. 작성을 안할시, alert창이 뜬다.