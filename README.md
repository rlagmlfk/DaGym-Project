# DaGym-Project
KH Semi-Project 헬스장 홈페이지 만들기

### 1️⃣ 프로젝트 소개
* 기간: 22년 7월 19일 ~ 22년 8월 26일
* 팀장: 이유리
* 팀원: 김희라, 최경진, 황산하

### 2️⃣ 사용 기술 및 환경

<img src="https://res.cloudinary.com/dgtqsljjl/image/upload/v1669725130/%ED%99%94%EB%A9%B4_%EC%BA%A1%EC%B2%98_2022-11-29_211205_jva8xx.png"/>

### 3️⃣ 구현 화면

<p align="center">
<img src="https://res.cloudinary.com/dgtqsljjl/image/upload/v1669725193/localhost_5500_220822_semi_final_member_about_intro.html_vsayzo.png" width="45%" height="50%">
<img src="https://res.cloudinary.com/dgtqsljjl/image/upload/v1669725193/localhost_5500_220822_semi_final_member_branch.html_hqaicx.png" width="45%" height="50%">
<img src="https://res.cloudinary.com/dgtqsljjl/image/upload/v1669725191/127.0.0.1_5500_220822_semi_final_member_private_register.html_smf9dc.png" width="45%" height="50%">
<img src="https://res.cloudinary.com/dgtqsljjl/image/upload/v1669725193/localhost_5500_220822_semi_final_member_private_purchase.html_nljsjr.png" width="45%" height="50%">
<p/>

### 4️⃣ 주요 기능

|이름|담당 기능|
|----|------------|
|**희라**|헬스장 소개 페이지, 지점 찾기(지점 검색, 지역명 클릭 시 해당 지역으로 지도 이동), 지점 상세조회 페이지, 회원전용(GX시간표 확인 후 해당 수강신청 기능, 클릭시 모달창으로 이동하여 정보 입력후 db저장, 이용권 결제 정보 DB저장), 수강신청페이지, 구매페이지|
<br>

<br>

<유리>
로그인 구현하기(+회원가입 , 구글, 깃헙), 로그아웃, 마이페이지 (프로필 조회, 수정, 신체 정보 확인, 1:1 문의 글 확인, 내 강좌, 구매내역, 회원탈퇴), CEO페이지 기능구현(chartjs를 통한 수입조회, 회원관리(페이징처리, 검색, db에 저장된 전체 회원 불러오고 클릭시 회원정보+등록지점과 기간 조회), 직원관리)
<br>

<경진>
헤더 완성 및 반응형으로 바꿔주기, CEO 정적페이지 구현, 관리자 로그인 시 공지사항에서 관리자는 수정,삭제 버튼 on/ 회원일 경우는 조회만, 1:1문의는 둘다 수정 삭제 가능하게 함, 후기에서 관리자는 조회+삭제 / 회원일 경우 조회+등록
<br>

<산하>
공지사항, qna(1:1문의와 자주묻는질문) , 후기는 권한에 따라 할 수 있는 기능이 다름( 회원의 경우 대부분 조회와 등록, 관리자의 경우 후기를 제외한 나머지 조회, 등록, 수정, 삭제 가능), 페이징 처리와 검색기능 추가
