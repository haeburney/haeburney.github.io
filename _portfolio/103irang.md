---
title: Irang (아이랑)
subtitle: 어린이집 알림장 웹 프로젝트
image: assets/img/portfolio/irang/irangmain.png
alt: Keep Exploring

caption:
  title: 아이랑
  subtitle: 어린이집 알림장 웹 프로젝트
  thumbnail: assets/img/portfolio/irang/irangmain.png
---

{:.list-inline} 
- <strong>Duration</strong> : 2023.04 ~ 2023.06 (약 2달) <br/>
- <strong>Team Members</strong> : 5 <br/>
- <strong>Github Repository</strong> : <a href="https://github.com/haeburney/Irang-1">github.com/haeburney/Irang-1</a><br/>
- <strong>Deploy Site</strong> : 배포사이트 업로드 미정<br/><br/>

<h5>Stack</h5>
- <strong>Front-End</strong><br/> - HTML5, CSS3, JavaScript, JQuery, Bootstrap <br/>
- <strong>Back-End</strong><br/> - Java, Spring Boot <br/>
- <strong>DataBase</strong><br/> - Oracle, SQLDeveloper <br/>
- <strong>Server</strong><br/> - Apache Tomcat <br/><br/>

<h5>Introduction</h5>
Irang(아이랑)은 KOSTA 257기 팀원 5명이 모여서 진행하게 된 사이드 프로젝트입니다.
학부모와 어린이집 선생님 사이에서 오는 갈등을 막고 소통을 향상하기 위해 개발한 웹 사이트입니다.<br/><br/>

<h5>Motivation</h5>
어린이집(유치원)에서는 정보 전달을 위해 다양한 프로그램을 사용합니다. 선생님은 학부모에게 아이 소식을 알리기 위해 일지에 올리는 사진을 다른 플랫폼에도 올리며 일을 두 번 해야 합니다. 특히 메신저 프로그램들 통해 사적인 대화와 공적인 대화가 같이 오가고 있어 채팅창이 혼잡해 중요한 공지나 부모의 연락을 놓치지 않기 위해 주의깊게 살펴야 합니다. <strong>"기존의 알림장 프로그램과 메신저의 역할을 합친 프로그램이 있으면 어떨까?"</strong> 하는 생각을 이번 아이랑 프로젝트를 통해 구현해보았습니다.<br/><br/>

<h5>Goals</h5>
1️⃣ 유치원 및 어린이집에서 사용하는 것<br/>
2️⃣ 학부모가 선생님의 개인적인 일들 (프로필 사진, 상태 메세지 등)을 보고 간섭하는 것을 막기<br/>
3️⃣ 어린이집에서 필요한 일지작성, 원아 기능들을 사용하기 편하게 구현<br/><br/>

<h5>Project Schedule</h5>
5월 19~24일 : Back CRUD 구현 & Miro jsp 경로 설정<br/>
5월 25~28일 : Back 세부 기능 구현<br/>
5월 29일 6월 2일 : Front 구현<br/>
6월 3~4일 : 디버깅 & 최종 테스트<br/><br/>

<h5>Team Member</h5>
- <strong>김혜원</strong> : <a href="https://github.com/haeburney">github.com/haeburney</a>
- 윤해현 : <a href="https://github.com/hennie-yun">github.com/hennie-yun</a>
- 이서연 : <a href="https://github.com/seoyeonDev">github.com/seoyeonDev</a>
- 전준하 : <a href="https://github.com/reacting97">github.com/reacting97</a>
- 최예은 : <a href="https://github.com/YeeBoss">github.com/YeeBoss</a><br/><br/><br/>

<h5>Team Member Roles</h5>
- <strong>김혜원</strong> : 선생님 일지 작성, 댓글 작성, 상세보기, 전체리스트 보기<br/>
- 윤해현 : 공지사항, 사이드 메뉴와 공통 페이지의 뼈대를 만듦 <br/>
- 이서연 : 리더, Git 관리,  반(calss) & 선생님 백/프론트 구현<br/>
- 전준하 : 어린이집 원생 관리<br/>
- 최예은 : 학부모가 작성하는 그날의 아이 특이사항 (아이 일지) 작성, 댓글 작성, 상세보기, 아이 별 일지 전체리스트 기능 및 뷰페이지 담당<br/><br/><br/>

<h5>Features</h5>
<strong>학급(class)</strong><br/>
반 추가/수정/삭제<br/><br/>
<strong>선생님</strong><br/>
선생님 학급 생성/변경 가능<br/>
선생님이 원아의 기본 정보를 추가하여 학부모에게 전달<br/><br/>
<strong>어린이</strong><br/>
어린이 목록 - 카드형식으로 배치<br/>
카드 뒷면에는 알러지 정보 & 일지 & 상세정보 링크 배치<br/><br/>
<strong>알림장 기능</strong><br/>
선생님 : 알림장 작성 가능<br/>
아이(학부모) : 알림장 확인<br/><br/>
<strong>일정 관리</strong><br/>
학사 일정, 행사 일정 쉽게 확인 가능 & 관리<br/><br/>
<strong>일지</strong><br/>
<strong>선생님</strong> : 일지 작성 가능 (사진)<br/>
일지 리스트 검색 기능 (아이 이름으로, 특정 날짜로, 월별로 검색)<br/>
<strong>아이</strong> : 일지 관람 가능<br/>
일지 리스트 검색 기능 (특정 날짜로, 월별로 검색) <br/><br/>
<strong>댓글</strong><br/>
일지에 댓글 작성/수정/삭제 가능<br/>
메신저 앱처럼 사용자는 <strong>오른쪽</strong>에, 상대방은 <strong>왼쪽</strong>에 댓글이 보이게 만듦 <br/><br/><br/><br/>



<h5>Design-Prototype</h5>
miro를 이용하여 prototype을 만들었습니다.<br/>

<strong>전체</strong><br/>
<img src="assets/img/portfolio/irang/miroall.png">
전체적인 페이지<br/><br/><br/>
<strong>① 선생님</strong><br/>
<img src="assets/img/portfolio/irang/mirotmain.png">
<strong>선생님으로 로그인할시</strong><br/>
아이 일지 확인 가능, 체크하면 아이 일지는 사라짐<br/>
메뉴 : ①일지 관리, ②공지사항, ③아동 관리<br/>
(아이 일지 : 보호자가 아이의 특이 사항을 적어 제출하는 곳)<br/><br/><br/>
<img src="assets/img/portfolio/irang/miroteacherlog.png">
선생님 일지 리스트, 작성하기<br/><br/><br/><br/>
<strong>② 아이</strong><br/>
<img src="assets/img/portfolio/irang/mirochildnotice.png">
공지사항 확인 가능<br/><br/><br/>
<img src="assets/img/portfolio/irang/mirochildlog.png">
아이 일지 작성/수정/삭제 가능<br/>
선생님 일지 카드 형식으로 확인 가능<br/>
카드 클릭시 디테일 페이지로 이동 & 댓글 작성 가능<br/><br/><br/>

<hr/><br/>
<h5>The Feature I Developed</h5>
<strong>① 선생님 일지</strong><br/>
일지 등록/수정/삭제<br/> 
일지 리스트 : 검색<br/><br/>
<strong>② 아이 일지</strong><br/>
댓글 작성/수정/삭제<br/>
메신저 앱처럼 사용자는 오른쪽, 상대방은 왼쪽에 배치<br/><br/>

<h5>The Feature Team Developed</h5>
<strong>Main Page</strong><br/>


<h5>Development Reflections (KPT)</h5>
<strong>[Problem]</strong><br/>
<br/>

<strong>[Try]</strong><br/>
<br/>
<br/>

<strong>[Keep]</strong><br/>
<br/>