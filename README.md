# Operation-System-project-

한국기술교육대학교 운영체제 (process scheduling) 팀프로젝트 


## 👋🏻 프로젝트 소개 

Process Scheduling Simulator 프로젝트는 Basic five scheduling algorithms과 Your own algorithm을 구현하여 Process Scheduling을 동작한다.

Process Scheduling은 Muti-core Processor로 이루어져, P core와 E core를 각 사용자에 맞추어 사용할 수 있다. 

코드로 구현된 Process Scheduling algorithm을 Visualization하여 Process Scheduling을 보기 쉽게 한다.


### 💻 개발 환경 

`Back end`
- `Python`

`front end`
- `python tkinter`


## 개발 기간 ⏰
####

- 2021.05.01 ~ 2021.06.05

## 주요 기능 🏅
####


### 메인 홈페이지 gif 

<img src="https://user-images.githubusercontent.com/91319157/208422512-67f748aa-7a7a-4071-ad80-16edfb27c486.gif" width="65%">

### 기능
- 상단 애니메이션 배너
- 최근 상품(DB 저장 기준) 대표 3가지만 전시 
- 대학교 과 별 커뮤니티 선택 요소
- IFrame 태그를 이용한 한국기술교육대학교 날씨와 학식 정보 


## 상품 View 페이지

<img src="https://user-images.githubusercontent.com/91319157/208429052-58ff0703-99c2-4c9a-9080-453f89797e81.png" width="50%">

### 기능
- 카테고리 별 물품 조회 기능 
### DB Table
| Num | category |  subject | content | name | regist_day | hit | id | price | file |
| :---:  | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | 
| PK  |  상품 카테고리 | 제목 | 판매글 | 이름 | 등록날짜 | 조회수 | 닉네임 | 가격 | 파일정보 | 

데이터베이스에 저장된 카테고리를 이용해 각각의 조회 페이지를 만들어 SQL을 다르게 하여 조회하였다. 

- 수정 (DB sql) 
- 삭제 (DB sql) 
- 글 작성 (DB sql)

> 각각 php에서 세션을 통해서 값을 전달하여 전달받은 데이터를 DB sql문을 통해서 저장




## 개발자 페이지 

<img src="https://user-images.githubusercontent.com/91319157/208431126-c997bb8d-b8ef-41c8-aa04-ecf7cd1c955b.png" height="20%">

if문을 통해서 저장된 맴버 admin으로 접속 시 숨겨진(hidden) 관리자 모드 제공

### 기능
- 배너 수정 & 삭제
- 회원 관리(탈퇴 = 삭제) 
- 모든 게시글 삭제 권한

<img src="https://user-images.githubusercontent.com/91319157/208431687-ee09de01-9ebd-4640-b101-a70d1267a403.png" width="40%">


## 그외

- javascript를 이용한 로그인 확인 검사 (로그인 후 글쓰기) 
- 게시글 작성 후 포인트 부여 ( 회원 마다 포인트 DB +100) 
- 상품 개수 9개 이상 페이지 다음 이전 버튼 
- 쪽지 송신 수신 기능 
<br>
<br>
<br>
<br>
<br>





## 개발 후기 🤔

컴퓨터공학부 2학년 웹프로그래밍 수업에서 배운 것을 토대로 제작했습니다. 



제가 이 과목을 들으면서 가장 좋았던 점은 정말 아무것도 없는 백지에다가 내가 원하는 무엇이든지 나만의 세상을 만들 수 있다는 점이었습니다.


상상력을 마음 껏 표출할 수 있었고 제한이 없었기 때문입니다. 저의 색을 마음 껏 칠할 수 있어
더욱 흥미롭게 진행 할 수 있었던 것 같습니다. 

html & css 에서 제가 반영한 수정사항이 바로바로 눈에 확인 할 수 있었던 것이 
공부를 하는 데 많이 도움이 되었습니다. 


제 프로젝트에 부족한 부분이 많습니다. 
하지만 앞으로 더욱 발전해가며 이 프로젝트를 보며 참 귀여웠다는 생각이 들 수 있는 날이 
올 때까지 더욱 노력하겠습니다.


### 부족한 부분
- 코드 정리
- 중복 코드 관리
- 주석 부족
- 회원 닉네임이 매우 길 경우 메뉴와 겹치는 현상


<br>
<br>

## 감사합니다 

<img src="https://user-images.githubusercontent.com/91319157/208434073-c834c893-2aed-4ded-a079-dff65540063f.gif" width="30%"> 
