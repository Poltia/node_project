## node_project(team)

&nbsp;&nbsp;: three.js를 활용해 술래잡기 게임 만들기

#

### Stacks

<div align="center">

<p>
&nbsp;<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">&nbsp;
</p>

<p>
&nbsp;<img src="https://img.shields.io/badge/three.js-000000?style=for-the-badge&logo=three.js&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=Socket.io&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/nodemon-76D04B?style=for-the-badge&logo=nodemon&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/express-000000?style=for-the-badge&logo=express&logoColor=white">&nbsp;
</p>

<p>
&nbsp;<img src="https://img.shields.io/badge/mysql2-4479A1?style=for-the-badge&logo=mysql&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/bcrypt-339933?style=for-the-badge&logo=node.js&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/cookie_parser-339933?style=for-the-badge&logo=node.js&logoColor=white">&nbsp;
</p>

<p>
&nbsp;<img src="https://img.shields.io/badge/.env-ECD53F?style=for-the-badge&logo=.env&logoColor=black">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/ejs-339933?style=for-the-badge&logo=node.js&logoColor=white">&nbsp;
&nbsp;<img src="https://img.shields.io/badge/json_web_tokens-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white">&nbsp;
</p>

</div>

#

### 페이지 구성

- intro 페이지 (로그인/회원가입 선택화면)
- 로그인, 회원가입 페이지
- 대기실(채팅방) 페이지
- 게임 페이지

<br/>

### Database ERD

<img width="50%" src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/DB_ERD.png" />

#

<br/>

## 페이지 소개

- intro 페이지

<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/0_intro.png" />
three.js를 사용해서 화면 구현<br/>
키보드 버튼으로 케릭터 이동 기능 구현<br/>
지정 위치 도달시 화면 이동

<br/><br/>

- login 페이지

<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/1_login.png" />
three.js 사용해 모델 생성 및 출력<br/>
행동 버튼 생성 (default: walking)<br/>

<br/><br/>

- 회원가입 페이지

<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/2_signup.png" />
three.js를 사용해 모델 생성 및 출력<br/>
ID/password에 정규표현식 통과시 submit 가능

<br/><br/>

- Error 페이지

<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/errorpage.png" />
three.js를 사용해 모델 생성 및 출력<br/>
Error 발생시 이동하는 페이지<br/>
error message를 문구로 출력<br/>

<br/><br/>

- 대기실(채팅방) 페이지

<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/3_chatroom.png" />
대기실 입장시 문구 출력<br/>
현재 접속한 계정 출력<br/>
게임방 입장시 alert로 방입장 출력<br/>
<br/>
<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/4_ready.png" />
게임방에 두명 입장시 화면 출력<br/>
버튼 클릭시 페이지 이동<br/>

<br/><br/>

- 게임 페이지

<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/4_ready-1.png" />
게임방 입장시 튜토리얼 띄우고 2명다 버튼 클릭시 게임 시작<br/>
<br/>
<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/5_game.png" />
키보드 버튼으로 모델 움직임 구현<br/>
상대방 모델 클릭시 게임 종료

<br/><br/>

- 게임 종료

<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/6_win.png" />
<img src="https://raw.githubusercontent.com/Poltia/node_project/main/readme_img/6_lose.png" />
종료시 각 플레이어에 승리/패배 출력<br/>
돌아가기 버튼 클릭시 대기실(채팅방)로 이동
