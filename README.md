
# 리소프트 홈페이지 만들기 1차 프로젝트  
  
bracket팀의 클론코딩 프로젝트 개인 파트 저장소  
저장소 사이트 바로가기 : https://igit322.github.io/bracket_b_wrap/  
  
### <프로젝트 일정>  
7월 1일 - 7월 15일 (총 2주)  


------------  

**팀 저장소** : https://github.com/jwon11/bracket/  

**팀 사이트** : https://jwon11.github.io/bracket/   

------------  
  
### <담당파트>  
리소프트 사이트(http://www.resoft.kr/) 의 '카드 섹션'  

### <파트 주문사항>   
마우스를 올렸을 때 카드가 뒤집히며 이미지와 글이 나타납니다.  

![이미지](https://velog.velcdn.com/images/igit322/post/6a13e974-2c5c-43b5-b8ff-fcc30a7cb665/image.gif)

### <기능>
#### 1. 마우스를 올렸을 때 : 카드가 뒤집히며 이미지와 글이 나타납니다.
#### 2. 반응형 : 950px 이상에서 가로 1줄, 950px~ 480px에서 2줄, 480px 이하에서 세로 1줄로 바뀝니다.
#### 3. 이미지에 방사형 그라디언트를 사용하여 글씨 주목도를 높임
#### 4. transition 을 써서 박스 크기 변경 시 서서히 변하도록 제작

### <사용한 방법>
#### 1. `display: flex;` 사용하여 카드 정렬
#### 2. `position` 을 이용한 이미지 겹치기
#### 3. `transform : rotate(angle)`, `transition : 1s;`을 이용하여 요소를 회전하는 효과를 보여줍니다.
