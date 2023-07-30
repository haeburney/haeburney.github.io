---
caption: #what displays in the portfolio grid:
  title: 유스크림
  subtitle: 매장 & 상품 관리 프로그램
  thumbnail: assets/img/portfolio/uscream/login.png
  
#what displays when the item is clicked:
title: Uscream
subtitle: 매장 & 상품 관리 프로그램
image: assets/img/portfolio/uscream/login.png #main image, can be a link or a file in assets/img/portfolio
alt: image alt text

---
{:.list-inline} 
- <strong>Duration</strong> : 2023.06.12 ~ 2023.07.12 (31일) <br/>
- <strong>Team Members</strong> : 6 <br/>
- <strong>Github Repository main</strong> : <a href="https://github.com/haeburney/final_uscream">github.com/haeburney/final_uscream</a><br/>
- <strong>Github Repository kiosk</strong> : <a href="https://github.com/haeburney/final_kiosk">github.com/haeburney/final_kiosk</a><br/>
- <strong>Deploy Site</strong> : 배포사이트 업로드 미정<br/><br/>
 
<h5>Stack</h5>
- <strong>Front-End</strong><br/> - HTML5, CSS3, JavaScript, Jquery, Vue.js, Bootstrap, Vue-FullCalendar <br/>
- <strong>Back-End</strong><br/> - Java, Spring Boot, Spring Data JPA <br/>
- <strong>DataBase</strong><br/> - Oracle, SQLDeveloper <br/>
- <strong>Server</strong><br/> - Apache Tomcat <br/>
- <strong>Open API</strong><br/> - Kakao Map API, Kakao Login API, NHN 결제 API <br/><br/> 

<h5>Introduction</h5>
유스크림 프로젝트는 KOSTA 257기 파이널 프로젝트로 진행되었습니다.<br/><br/>

<h5>Motivation</h5>

<h5>Project Schedule</h5>
<strong>Main</strong><br/>
6월 12~15일 : 주제 선정, 설계<br/>
6월 16~25일 : Back 구현<br/>
6월 26일~7월 6일 : Front 구현<br/>
7월 7~11일 : 디버깅<br/><br/>
<strong>Kiosk</strong><br/>
6월 27일 : 설계<br/>
6월 28일 ~ 7월 4일 : Kiosk Back 구현<br/>
7월 5~8일 : Kiosk Front 구현<br/><br/>

<h5>Team Member</h5>
- <strong>김혜원</strong> : <a href="https://github.com/haeburney">github.com/haeburney</a>
- 김희수 : <a href="https://github.com/Hee-Soo">github.com/Hee-Soo</a>
- 박재연 : <a href="https://github.com/etoile0712">github.com/etoile0712</a>
- 방현중 : <a href="https://github.com/nonghtt">github.com/nonghtt</a>
- 원유경 : <a href="https://github.com/wyk160">github.com/wyk160</a>
- 양승혁 : <a href="https://github.com/Seung-hyuck">github.com/Seung-hyuck</a><br/><br/><br/>

<h5>Team Member Roles</h5>
- <strong>김혜원</strong> : 직원 관리, 근태 관리, 인건비 계산 기능<br/>
- 김희수 : 계정, 지점 기능, 카카오 맵 API 구현, 추가적인 KIOSK 프로그램 기능 구현<br/>
- 박재연 : 공지사항, 고객의 소리 기능<br/>
- 방현중 : GIT 관리, 메일 시스템 구현<br/> 
- 원유경 : 매출 관리 기능 (매출, 순매출)<br/> 
- 양승혁 : 조장님, 발주 및 상품 관리 기능, 추가적인 KIOSK 프로그램 기능 구현, 카카오 로그인 API, NHN 결제 구현<br/><br/><br/>

<h5>Features</h5>

|구분|관리자(본사)|지점(매장)|
|---|---|---|
|계정 관리|가맹점 아이디 생성|비밀번호 변경|
|공지사항|등록(안내 or 이벤트)|안내, 이벤트(파일 게시판)|
|상품관리|구매/발주 승인, 신제품 등록|구매/발주, 재고 현황 파악|
|직원 관리|표출 메뉴 없음|직원 등록, 업무 스케줄 노출, 출퇴근 시간 노출|
|매출 관리|연도별/월별 매출, 전체, 지점별|연도별/원별/일별 매출, 순매출|
|고객의 소리|전체글|전체글(지점에서 댓글로 답변)|
|메시지|메신저함(발송 가능)|메신저함(발송 가능)|

<br/><br/>

<h5>Design-Prototype</h5>
miro를 이용하여 prototype을 만들었습니다.<br/>

<h5>API</h5>
<strong>① [KAKAO Maps API](https://apis.map.kakao.com/)</strong><br/>
KAKAO Maps API를 이용하여 가맹점 지도로 검색하는 기능과 지점별 지도 위치를 볼 수 있는 기능을 넣었습니다.<br/><br/>
<strong>② [KAKAO Login REST API](https://developers.kakao.com/docs/latest/ko/kakaologin/rest-api)</strong><br/>
KAKAO Login REST API를 이용하여 KIOSK 페이지에서 카카오 로그인 기능을 구현했습니다.<br/><br/>
<strong>② [NHN KCP API](https://developer.kcp.co.kr/)</strong><br/>
NHN KCP API를 KIOSK 페이지에서 결제 기능을 구현했습니다.<br/><br/><br/>

<hr/><br/>
<h5>The Feature I Developed</h5>

<h5>Development Reflections (KPT)</h5>
<strong>[Problem]</strong><br/>

<strong>[Try]</strong><br/>

<strong>[Keep]</strong><br/>