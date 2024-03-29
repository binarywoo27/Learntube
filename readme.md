### 🎤 서비스 소개: (졸업작품: '21년 2학기 캡스톤 디자인 프로젝트)

서비스명: Learntube <br/>

누구나 쉽게 온라인 학습 시스템(LMS)를 활용하고, <br/>
다양한 양질의 Youtube 영상들을 교육용 컨텐츠로 활용할 수 있고, <br/>
자동 출결을 처리해주는 LMS 플랫폼입니다. 

<!-- 웹 사이트 링크: <a href="https://learntube.kr"> Learntube.kr </a> -->

### 📅 개발기간:
<p> 2021.07 ~ 2021.12 </p>

### ✨ 사용한 기술스택:
HTML, 
CSS, 
JavaScript, 
Ajax,
JSP, 
Spring, 
MyBatis,
MariaDB


### 💻 팀원 및 담당파트
이예원 : ‘YouTube 동영상 강의컨텐츠 제작 및 관리’, '공지/강의 캘린더', '프런트엔드' <br/>
이진우 : ‘YouTube 동영상 강의컨텐츠 제작 및 관리’ 및 ‘구성원 초대 및 관리’<br/>
조하영 : '학생의 강의시청 기록을 통한 출결관리' 및 'Zoom csv파일을 통한 자동 출결관리' <br/>

### 2021년 2학기 캡스톤 페스티벌 Learntube 포스터
<details markdown="1">
<summary> 포스터 이미지 보기!!  ←  클릭!! </summary>
<img src="https://user-images.githubusercontent.com/49421143/203787618-1a1ea056-eb28-46f4-a53a-d48a96f2acdf.jpg" width="60%"> 
</details>

### 😎  제가 맡은 파트 구현 화면은 다음과 같습니다:
<p> </p>

## 1) Youtube 동영상 검색 및 동영상 짜깁기 :

### (i) Youtube 동영상 검색
<img src = "https://user-images.githubusercontent.com/49421143/159110173-69c99255-2741-450d-8f72-781bcb307e26.png" width="60%">

🔍 동영상 검색 후 선택 (왼쪽 목록) > 선택된 동영상 제목, 태그, 재생구간 설정 후 장바구니에 추가하기

### (ii) Youtube 동영상 추가
<img src = "https://user-images.githubusercontent.com/49421143/159110175-ef38756c-57cb-4ad5-a920-f6eddbefc43c.png" width="60%">

🔍 장바구니에 담긴 여러 동영상들을 한꺼번에 저장하여 한 학습컨텐츠 강좌(Playlist)로 만들기

## 2) 학생 초대 및 학생 관리 : 

### (i) 구성원 관리
<img src = "https://user-images.githubusercontent.com/49421143/159110182-7c8ce991-b1ff-4038-837b-00006382ecb7.png" width="60%">

🔍 학생초대 방법: 학생초대 버튼 클릭하여 (초대 링크 복사하기) 강의실에 추가하고자 하는 학생들에게 링크 공유!

### (ii) 강의실 학생 초대 페이지 
<img src = "https://user-images.githubusercontent.com/49421143/159110183-45a939e2-8a0f-4f1b-8b3b-1b93018bc59f.png" width="60%">

🔍 초대된 학생에게 보여지는 페이지 > 여기서 학생은 '수강신청하기' 버튼을 통해 강의 신청 가능!

## 3) 자동출결처리 기능 (기획 및 구현 방법) :
< Zoom 화상강의 csv파일 등록 > <br>
<img src = "https://user-images.githubusercontent.com/49421143/159110180-304749d9-7a69-41c5-81c5-1bd96db6161b.png" width="60%">

🔍 출결 인정 시작 시간과 끝 시간을 설정하고 Zoom CSV 파일 (온라인 화상 강의 참여자 기록)을 업로드하여 차시별 자동 출결 처리 가능! </br> 🎉 (대략 3분~5분의 업무시간을 단 30초 이하로 단축!!)

### 캡스톤 프로젝트 (졸업 작품) 실제 레포지토리는 아래와 같습니다!

https://github.com/OnepageLMS/youtubePlaylist.git

<details markdown="2">
<summary> <h1> 구현 화면 (전체): </h1> </summary>

#### 로그인
<img src = "https://user-images.githubusercontent.com/49421143/159110158-0990e816-7cd7-4dff-8fdf-30929a67db06.png" width="60%">

#### 대시보드
<img src = "https://user-images.githubusercontent.com/49421143/159110160-305e0685-d299-4e16-b068-8ab389f45efc.png" width="60%">

#### 공지 
<img src = "https://user-images.githubusercontent.com/49421143/159110164-dce12d48-9a06-45c9-a646-4de700ebdb9e.png" width="60%">

#### 캘린더
<img src = "https://user-images.githubusercontent.com/49421143/159110167-914c5649-cd20-4656-885c-fac5a280232c.png" width="60%">

#### 강의컨텐츠
<img src = "https://user-images.githubusercontent.com/49421143/159110169-4c38adad-77ec-42bf-90e2-23d75541df66.png" width="60%">

#### 강의컨텐츠 상세페이지
<img src = "https://user-images.githubusercontent.com/49421143/159110170-7ea61f4b-9762-4b73-adb0-68053aec46e2.png" width="60%">

### Youtube 동영상 검색
<img src = "https://user-images.githubusercontent.com/49421143/159110173-69c99255-2741-450d-8f72-781bcb307e26.png" width="60%">

### Youtube 동영상 추가
<img src = "https://user-images.githubusercontent.com/49421143/159110175-ef38756c-57cb-4ad5-a920-f6eddbefc43c.png" width="60%">

### 교육컨텐츠 (Playlist) 관리
<img src = "https://user-images.githubusercontent.com/49421143/159110176-f2b7462a-3d7e-4215-aca6-47308925bce2.png" width="60%">
<img src = "https://user-images.githubusercontent.com/49421143/159110177-c197c7d0-a7a2-43e0-b935-c099bf3d0247.png" width="60%">

### 선생님 출결/학습현황:
<img src = "https://user-images.githubusercontent.com/49421143/159110179-cdf89078-09dd-4e8f-97bf-cc055c8df1e1.png" width="60%">

### Zoom 화상강의 csv파일 등록:
<img src = "https://user-images.githubusercontent.com/49421143/159110180-304749d9-7a69-41c5-81c5-1bd96db6161b.png" width="60%">

### 학생 출석/학습현황
<img src = "https://user-images.githubusercontent.com/49421143/159110181-29b44cd6-c909-4b2e-9f2b-edec78812028.png" width="60%">

### 구성원 관리
<img src = "https://user-images.githubusercontent.com/49421143/159110182-7c8ce991-b1ff-4038-837b-00006382ecb7.png" width="60%">

### 강의실 학생 초대 페이지 
<img src = "https://user-images.githubusercontent.com/49421143/159110183-45a939e2-8a0f-4f1b-8b3b-1b93018bc59f.png" width="60%">

### (학생) 강의실 신청 현황
<img src = "https://user-images.githubusercontent.com/49421143/159110185-c15e7baf-ec8e-4e89-b926-a2abf06e627a.png" width="60%">

</details>



