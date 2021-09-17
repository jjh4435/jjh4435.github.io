---
layout: post
title:  "Travel-guide-program"
---

# Travel-guide-program

------

## 프로젝트 개요

- 관광지의 사진, 특징, 위치 등을 공유해서 간접적으로 관광지를 탐방하고 나아가 해당 관광지를 즐겨찾기 함으로써 휴일에 여행을 계획하는 국내 여행객이나 외국인 관광객에게 해당 관광지에 대한 접근성을 높이는 것을 목표로 한다.

------

## 프로젝트 상세내용
### 1. 메인 페이지

<img src="/assets/images/travel-guide-program/main1.png">
<img src="/assets/images/travel-guide-program/main2.png">

- 홈페이지는 해당 프로젝트의 메인 페이지이며 해당 메인 페이지에는 한국의 수도인 서울을 소개하는 페이지로 첫 대면 메인 페이지의 내용이 구성되어 있다. 상단의 버튼을 이용해 지역 찾기, 등록된 즐겨찾기, 여행 정보 등을 바로 이용할 수 있으며 하단부에 있는 버튼을 이용하면 다른 메인 페이지로 이동하며 해당 지역의 메인 페이지로 이동, 메인 페이지의 상단 사진뿐 아니라 하단부에 위치한 관광지 추천 사진도 바뀌게 된다.
- 추천 관광지 각 사진 밑에는 여행지 바로가기 버튼이 있어 해당 버튼을 클릭 시 여행지에 대한 상세 정보를 얻을 수 있다. 해당 내용은 여행 정보 페이지의 내용과 중복되게 만들어 여행 정보 페이지에 들어가 해당 추천 관광지의 정보를 찾는 것이 아닌 바로 연결해 추천 관광지에 대한 정보의 접근을 좀 더 빠르고 쉽게 만들었다.

### 2. 로그인 페이지

<img src="/assets/images/travel-guide-program/login.png">

- HOME 버튼을 누르면 다른 JSP/HTML 페이지로 이동하며 다른 기능의 페이지로도 쉽게 이동할 수 있는 메인 페이지로 이동한다.
- 박스에는 미리 가입한 회원 아이디와 비밀번호를 입력해 회원 가입을 통한 DB에 저장되어 있는 아이디와 일치 시 박스 버튼과 동일하게 프로젝트의 메인 페이지로 이동할 수 있다.
- 아이디가 없으신가요? 여기를 클릭해 주세요!는 비회원 시 회원 가입을 유도해 회원 가입 페이지로 이동할 수 있는 기능이 있다.

### 3. 회원가입 페이지

<img src="/assets/images/travel-guide-program/membership.png">

- 로그인 화면에서 회원가입을 위해 여기를 클릭할 경우 넘어가는 페이지로 회원 가입 시 필요한 정보를 입력받아 사진에는 표시되어 있지 않지만 하단부에 위치한 가입하기 버튼을 통해 정보가 SQL에 넘어가 회원 정보가 저장된다. 성공적으로 회원 가입이 성공하면 회원 가입 성공! 메시지와 함께 회원 가입이 성공적으로 완료되었음을 알려주며 앞에서 설명한 로그인 페이지로 이동해 자연스럽게 로그인을 유도하도록 기능을 만들었다. 이후 로그인을 통해 프로젝트의 메인 페이지로 넘어갈 수 있다.

### 4. 지역보기 페이지

<img src="/assets/images/travel-guide-program/search.png">
<img src="/assets/images/travel-guide-program/destination_introduce2.png">

- 지역 보기 페이지는 해당 프로젝트의 메인 기능이 들어있는 페이지로 우선 해당 관광지를 드롭 다운 기능으로 선택하여 검색 버튼을 클릭, 해당 관광지의 지도와 추천 관광지가 나와 있는 서브 페이지로 이동하도록 하는 기능이 메인이다.
- 즐겨찾기 버튼도 있어 해당 관광지를 즐겨찾기 추가할 수 있다.
- 부가적인 기능으로는 아무 관광지를 선택하지 않고 검색 혹은 즐겨찾기 버튼을 눌렀을 시 관광지를 선택해 주세요라는 메시지가 출력된다.
- country 드롭 다운을 선택하지 않으면 관광지의 드롭 다운이 활성화되지 않아 해당 관광지를 가기 위해서는 해당 관광 지의 도시 위치를 기억하고 있어야 한다. 이러한 번거로움을 없애기 위해 해당 관광지를 검색해도 바로 넘어갈 수 있도록 검색 기능도 구현했다. 해당 검색은 영문으로 검색해도 검색이 가능하도록 그 기능을 구현했다.
- 페이지의 이미지에는 버튼 기능을 넣었으며 가장 큰 이미지 버튼을 누르면 해당 관광지의 지역 보기 페이지의 메인 페이지인 지역 소개 페이지로 넘어가 해당 관광지에 대한 정보에 쉽게 접근할 수 있다. 밑에 있는 작은 사진을 누르면 해당 관광지의 지도가 있는 페이지로 이동, 작은 사진이 큰 이미지 사진으로 대체되며 그 큰 이미지 버튼을 누르면 또한 해당 관광지의 지역 보기 페이지로 넘어간다. 즉, 지역 보기 페이지는 즐겨찾기 페이지와 여행 정보 페이지와 연결되어 있다.

### 5. 여행지 정보 페이지

<img src="/assets/images/travel-guide-program/destination_introduce3.png">
<img src="/assets/images/travel-guide-program/destination_introduce.png">

- 여행 정보 페이지는 페이지가 두 개로 나뉘는데 해당 페이지 두 개는 각각 서브 페이지 여행 정보 페이지로 부른다. 처음 상단에 위치한 여행 정보 버튼을 눌러 들어가 마주하게 되는 페이지는 서브 페이지로 해당 페이지에는 지금까지 저장되어 있는 모든 여행지가 나열된다. 나열되어 있는 페이지의 [더 보기] 버튼을 누르면 여행 정보 페이지로 넘어가게 된다 그렇게 넘어간 여행 정보 페이지에는 해당 관광지의 상세 내용이 적혀 있고 더불어 [여행지 찾기 바로 가기] 버튼으로 해당 관광지의 지역 찾기 부분으로 넘어가 지도 위치를 확인할 수 있다.


### 6. 즐겨찾기 페이지

<img src="/assets/images/travel-guide-program/bookmark.png">

- 즐겨찾기 페이지는 처음 들어가 보면 아무것도 존재하지 않는 페이지이다. 해당 페이지는 지역 보기 페이지에 있는 즐겨찾기 버튼을 이용해야 한다.
- 지역 보기 페이지에서 도시와 관광지를 선택하고 즐겨찾기 버튼을 누르면 아무것도 없던 즐겨찾기 페이지에 해당 관광지가 추가되는 것을 볼 수 있을 것이다.
- 해당 관광지를 추가 한 이후에는 삭제도 가능하며 지도 보기 버튼을 이용해 해당 관광지의 지역 보기 페이지로 넘어간다 그리고 그 지역 보기 페이지를 이용해 해당 관광지의 여행 정보 페이지로 이동할 수 있다.
- 즐겨찾기는 즐겨찾기 페이지를 통해 삭제할 수 있으며 삭제는 다음과 같이 진행된다.
>1. [삭제] 버튼을 누른다
>2. 해당 관광지 사진 위에 있는 이름을 클릭한다.
>3. [삭제] 버튼이 활성화된다
>4. 활성화된 삭제 버튼을 누르면 삭제가 완료된다.

### 7. 코멘트 페이지

<img src="/assets/images/travel-guide-program/comment.png">

- 코멘트 페이지는 간단하게 말하자면 익명 게시판의 성격을 띤다. 해당 페이지는 코멘트를 수정 및 삭제가 가능하며 추가 기능은 SQL를 통해 추가할 수 있다.
- 코멘트 페이지는 해당 코멘트를 남기는 관광지 이름과 그 장소에 대한 글이 저장되며 이 기능은 해당 관광지에 대한 느낀 점이나 장/단점 등을 서로 공유하도록 하는 것을 목적으로 두고 있다.

### 8. 홈페이지 소개 

<img src="/assets/images/travel-guide-program/introduce.png">

- 소개 페이지의 상단부에는 메인 페이지들의 이미지가 순서대로 출력된다. 그리고 하단부에 위치한 드롭 다운 버튼은 활성화시키면 해당 페이지에 대한 이미지와 간단한 기능 및 내용이 함께 출력되어 해당 프로그램들의 기능을 간략하게 소개하고 있다. 또한 해당 페이지의 개발자도 알려주어 기능의 이상이 있을 시 문의를 손쉽게 넣을 수 있도록 만들었다. 즉 해당 기능의 담당자라고 보면 될 것이다.

------

## 프로젝트 사용 지침서
1. 메인 페이지를 실행시킵니다.
2. 로그인을 하거나 회원가입을 합니다.
3. 헤더 부분을 통해 여행지의 정보를 보거나 필요로 하는 여행지를 찾아봅니다.