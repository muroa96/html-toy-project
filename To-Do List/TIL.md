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

### **@media (미디어 쿼리)**
