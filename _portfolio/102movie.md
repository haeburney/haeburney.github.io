---
title: 조각별
subtitle: 영화 평점 및 후기를 남기는 웹 페이지
image: assets/img/portfolio/movieproject/movie.png
alt: Shirts on a hanger

caption:
  title: 조각별
  subtitle: 영화 평점 및 후기를 남기는 웹 페이지
  thumbnail: assets/img/portfolio/movieproject/movie.png
---
{:.list-inline} 
- <strong>Duration</strong> : 2023.04.19 ~ 2023.05.04 (약 16일) <br/>
- <strong>Team Members</strong> : 5 <br/>
- <strong>Github Repository</strong> : <a href="https://github.com/haeburney/semiproject/tree/master">github.com/haeburney/semiproject/tree/master</a><br/>
- <strong>Deploy Site</strong> : 배포사이트 업로드 미정<br/><br/>
  
<h5>Stack</h5>
- <strong>Front-End</strong><br/> - HTML5, CSS3, JavaScript, JQuery, Bootstrap <br/>
- <strong>Back-End</strong><br/> - Java, JSTL <br/>
- <strong>DataBase</strong><br/> - Oracle, SQLDeveloper <br/>
- <strong>Server</strong><br/> - Apache Tomcat <br/>
- <strong>Open API</strong><br/> - TMDB API, YouTube API <br/><br/>

<h5>Introduction</h5>
조각별 프로젝트는 KOSTA 257기 세미 프로젝트로 진행되었습니다.<br/><br/>

<h5>Motivation</h5>
COVID-19로 인해 영화관 방문자보다 집에서 영화를 감상하는 사람들의 비중이 증가했습니다. 이로 인해 작아진 영화 시장에서는 예전의 영화들이 회자되고 역주행하는 현상이 보여지고 있습니다. 조각별은 이러한 변화를 고려하여 영화 평점을 매기고 자유롭게 영화에 대해 이야기를 나눌 수 있는 사이트를 만들고자 했습니다.<br/>
영화를 보고 후기를 쓰면서 조각을 하나씩 남기고, 영화를 평가하면서 별을 남기는 자는 의미로 조각별이라는 이름을 만들었습니다. 사람마다 각기 다른 조각별을 가지고 영화에 대해 다양한 소통을 하고자 함이 조각별 프로젝트의 목표입니다.<br/><br/>

<h5>Project Schedule</h5>
4월 19일 : 주제 정하기 <br/>
4월 20일 : DB 테이블 설계, 핸들러명 정하기, 시나리오 흐름 짜기<br/>
4월 21일 : 구현 부분 나누기, DB 쿼리 작성, VO & DAO & SERVICE 만들기<br/>
4월 24~28일 : jsp, back, front 구현하기<br/>
4월 29~30일 : 디버깅<br/>
5월 1~2일 : 디버깅 및 디테일 구현<br/>
5월 3일 : 발표 준비 & 프로그램 최종 실행 <br/>
5월 4일 : 발표🌟<br/><br/>

<h5>Team Member</h5>
- <strong>김혜원</strong> : <a href="https://github.com/haeburney">github.com/haeburney</a>
- 윤해현 : <a href="https://github.com/hennie-yun">github.com/hennie-yun</a>
- 박재연 : <a href="https://github.com/etoile0712">github.com/etoile0712</a>
- 손행원 : <a href="https://github.com/sonbankclerk">github.com/sonbankclerk</a>
- 송가영 : <a href="https://github.com/sgyoung96">github.com/sgyoung96</a><br/><br/><br/>

<h5>Team Member Roles</h5>
- 유저 : 회원 관리 + 마이페이지 + 다른 유저의 홈 (<strong>김혜원</strong> + 박재연)
- 영화 : 영화 api 불러오기 + 별점 남기기 + 예고편 재생 (윤해현 + 손행원)
- 후기 : 한 줄 평 작성 + git 관리 (송가영)<br/><br/><br/>

<h5>Features</h5>
<strong>영화</strong><br/>
인기순으로 보기, 평점순으로 보기, 장르별로 보기<br/>
별점 남기기, 찜하기<br/>
장르별 검색, 작품으로 검색<br/>
<strong>후기</strong><br/>
영화 감상평 남기기, 감상평 스포일러 방지 기능<br/>
베스트 댓글 보기, 최신순으로 보기<br/>
<strong>유저</strong><br/>
팔로잉 기능, 자신의 한 줄 조각(한 줄 소개) 남기기<br/>
마이페이지 (별점, 찜, 후기 목록 보기)<br/><br/><br/>

<h5>Design-Prototype</h5>
miro를 이용하여 prototype을 만들었습니다.<br/>
각각 페이지마다 필요한 핸들러도 적어주면서 설계를 진행했습니다.<br/><br/>
<strong>전체</strong><br/>
<img src="assets/img/portfolio/movieproject/prototypemain.png">
전체적인 페이지는 이렇게 생겼습니다.<br/>
흐름에 따라 화살표를 만들어주어 흐름을 알기 쉽도록 설계해봤습니다.<br/>
이제 하나씩 자세히 보겠습니다.<br/><br/><br/>
<strong>영화</strong><br/>
<img src="assets/img/portfolio/movieproject/prototypemovie.png">
index 페이지는 상단 메뉴와 슬라이드로 구성되어 있고 유명한 영화의 포스터를 가져왔습니다.<br/>
다음은 영화 목록 페이지입니다.<br/>
영화 목록은 인기순, 평점순, 장르별로 볼 수 있으며 검색하는 기능도 들어가있습니다.
하나의 영화를 클릭하면 디테일 페이지로 넘어가게 되는데 영화에 대한 정보와 예고편을 볼 수 있습니다.
여기서 후기를 남기고 찜하기 버튼과 별점을 남길 수 있습니다.
또한 다른 사람이 쓴 후기도 볼 수 있습니다.<br/><br/><br/>
<strong>마이페이지</strong><br/>
<img src="assets/img/portfolio/movieproject/prototypemypage.png">
마이페이지에는 내 정보 수정, 한 줄 소개가 있고, 찜 & 후기 & 별점 목록은 7개씩 보여줬습니다.
+(더보기) 버튼을 누르면 해당 목록의 전체 영화 목록을 볼 수 있습니다.<br/><br/><br/>
<strong>리뷰 작성</strong><br/>
<img src="assets/img/portfolio/movieproject/prototypereview.png">
영화 디테일페이지에서 후기를 작성할 수 있는데, 스포일러가 담긴 코멘트이면 스포일러 체크 버튼을 눌러줍니다. 그럼 다른 사용자는 후기를 바로 보는 것이 아니라 "스포일러가 들어간 후기입니다. 계속해서 보시겠습니까?"라는 문구에 '확인'버튼을 눌렀을 때 스포일러가 있는 후기를 볼 수 있게 만들었습니다.<br/><br/><br/>

<h5>API</h5>
<strong>① [TMDB API](https://developers.themoviedb.org/3/getting-started/introduction)</strong><br/>
TMDB API를 이용하여 영화를 가져왔습니다.<br/><br/>
<strong>② [YouTube API](https://developers.google.com/youtube/v3/getting-started?hl=ko)</strong><br/>
YouTube API를 이용하여 영화 예고편 영상을 가져왔습니다.<br/><br/><br/>

<hr/><br/>
<h5>The Feature I Developed</h5>
<strong>① 회원가입 (비동기)</strong><br/>
<img src="assets/img/portfolio/movieproject/join.gif"><br/>
<strong>② 내 정보 수정 (비동기)</strong><br/><br/>
<strong>③ 마이페이지</strong><br/>
찜한 기록 보기 + 찜 취소 기능 (비동기)<br/>
별점 기록 보기 + 별점별로 기록 보기 (비동기)<br/>
코멘트 기록 보기 (한 줄만 출력되게)<br/>
팔로우 추가 + 취소  <br/>
한 줄 소개 추가 + 수정 + 삭제 <br/><br/>
<strong>④ 다른 유저 페이지</strong><br/> 
팔로우 추가 + 취소 <br/>
찜한 기록 보기 <br/>
별점 기록 보기 <br/>
코멘트 기록 보기 <br/><br/><br/>

<h5>The Feature Team Developed</h5>
<strong>Main Page</strong><br/>
<img src="assets/img/portfolio/movieproject/main.gif">
index 페이지 입니다.
처음 페이지는 슬라이드 형식으로 대표 영화를 소개하는 구성을 보여주고 있고, 메뉴바 외의 공간을 클릭하면 "인기순"으로 영화 리스트를 보여주는 페이지로 넘어가게 됩니다.<br/><br/><br/>
<strong>장르별로 보기</strong><br/>
<img src="assets/img/portfolio/movieproject/genre.gif"><br/><br/><br/>
<strong>인기순, 평점순, 개봉예정작으로 보기</strong><br/>
<img src="assets/img/portfolio/movieproject/type.gif">
인기순, 평점순, 개봉예정작별로 영화 리스트를 볼 수 있으며 페이징 구현했습니다.<br/><br/><br/>
<strong>리뷰 작성하기</strong><br/>
<img src="assets/img/portfolio/movieproject/review.gif">
영화 디테일 페이지에서 리뷰를 작성할 수 있습니다.
스포일러가 표시된 후기를 작성할 경우에 😀같이 생긴 이모티콘 버튼을 클릭하고 작성할 수 있습니다.<br/><br/>

<h5>Development Reflections (KPT)</h5>
<strong>[Problem]</strong><br/>
아쉬웠던 점은 CSS였다. 
테마와 글씨체나 색을 정했긴 했지만 각자 맡은 부분을 각자 구현을 했는데 사람마다 스타일이 달라서 조금은 다른 느낌의 디자인이 나왔다. 
그리고 z-index와 bootstrap에 대해 알게 됐다.
내가 쓴 CSS코드가 제대로 작동이 안 돼서 왜 그런가하고 찾아봤더니 z-index 순위에 밀려난 것도 있었고, 부트스트랩 때문에 밀려난 것도 있었다.
부트스트랩의 우선순위에 대해서 알게 됐고, CSS에서 z-index를 쓸 때 팀원분들과 잘 상의해서 써야 할 필요성을 느꼈다.<br/>

<strong>[Try]</strong><br/>
디버깅 중 영화 제목으로 검색하는 기능이 있었는데 띄어쓰기가 들어갈 경우 제대로 검색이 되지 않았던 문제가 있었다. 만약 공백이 들어가 있다면 "%20"으로 치환하여 검색하는 기능을 다시 돌려봤는데 제대로 돌아갔다.<br/>

```
String text = request.getParameter("query");
String[] array=text.split("");
String text2="";
		
for(int i=0; i<array.length;i++) {
	if(array[i].equals(" ")) {
		text2+="%20";
	}else {
		text2+=array[i];
	}
}
```
<br/>

<strong>[Keep]</strong><br/>
① 매번 프로젝트를 하면서 느끼지만 설계가 가장 중요한 것 같다. 이번 프로젝트에서는 테이블명, 변수명, 핸들러명을 다 정하고 시작해서 수월하게 진행이 된 것 같다. <br/>
② 일정을 정하는데 이상적인 목표에서 80% 정도만 잡으라는 조언을 보고 딱 내가 할 수 있을 만큼의 80%로 계획을 세웠다. 
여기서 조금만 더 빡센 일정이었다면 시간과 마음의 여유가 없었을 것 같다. <br/>
③ 구현한 걸 비동기로 보여주고 싶어서 Jquery를 이용했는데 익숙치 않아서 여러번 고쳐야 했었다.
하루에 몇 시간 동안 잡고 있었기 때문에 Jquery와 ajax에 대한 이해도가 올라가게 됐다.<br/><br/>