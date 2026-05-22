## 프로그램 소개
체험활동 연계한 일정관리, 기록 서비스

## 📅 프로젝트 기간
2022.08.16 ~ 2022.09.07

## ⭐ 주요 기능
- 캘린더
  - 일정 확인, 관리
  - 날짜 별 후기 작성

- 체험학습
  - 테마 별, 날짜 순, 인기 순 정렬
  - 검색
  - 좋아요, 찜, 알림
  - 예약 페이지 연결
  - 일자, 요금, 위치, 편의정보 표기
  - 관련 체험 리뷰 연계
 
## ⛏ 기술 스택
<table>
    <tr>
        <th>구분</th>
        <th>내용</th>
    </tr>
    <tr>
        <td>사용언어</td>
        <td>
             <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>Frontend 프레임워크</td>
        <td>
             <img src="https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=Android&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>Backend 프레임워크</td>
        <td>
            <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white"/> 
            <img src="https://img.shields.io/badge/PyCharm-000000?style=for-the-badge&logo=PyCharm&logoColor=white"/>
        </td>
    </tr>
        <tr>
        <td>라이브러리</td>
        <td>
            <img src="https://img.shields.io/badge/Naver-03C75A?style=for-the-badge&logo=Naver&logoColor=white"/>
            <img src="https://img.shields.io/badge/Google-4285F4?style=for-the-badge&logo=Google&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>개발도구</td>
        <td>
            <img src="https://img.shields.io/badge/Eclipse-2C2255?style=for-the-badge&logo=Eclipse&logoColor=white"/> 
            <img src="https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white"/>
            <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>서버환경</td>
        <td>
            <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white"/>
        </td>
    </tr>
    <tr>
        <td>데이터베이스</td>
        <td>
            <img src="https://img.shields.io/badge/Oracle 11g-F80000?style=for-the-badge&logo=Oracle&logoColor=white"/>
        </td>
    </tr>
        <tr>
        <td>협업도구</td>
        <td>
            <img src="https://img.shields.io/badge/GitLab-F05032?style=for-the-badge&logo=GitLab&logoColor=white"/> 
            <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/>
        </td>
    </tr>
    </tr>
        <tr>
        <td>디자인</td>
        <td>
            <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"/>
        </td>
    </tr>
</table>

## 📌 ER다이어그램
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/1f7920ee818fd6fd201ec9c4185e34a3/%EB%B8%94%EB%9E%99_play_outside_ERD_2.png)
<br>

## ⚙ 화면 UI
![화면 UI](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/1c57367249d3bfbd93eda40480648188/%ED%99%94%EB%A9%B4UI.png)
<br>

## 📌 서비스 흐름도
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/a790d39ac84c1ba5d8e891a6b0de8dfb/%ED%99%94%EB%A9%B4%ED%9D%90%EB%A6%84%EB%8F%84.png)
<br>

## 🖥 화면 구성

### 로그인/회원가입/회원괸리/회원수정
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/ea0aa105c40335fe4e189cace9526ba2/image__4_.png)
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/1ebd606d0d9644409e5d7f44f1e2249d/image__6_.png)
<br>

### 메인페이지/검색/캘린더
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/b5c108602352e60cdd97bad58c63a58e/image__5_.png)
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/da47b9abb44c01f667ddc1d4e3969381/image__7_.png)
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/8a5ac15f566b21a4a756e06bde2bc700/image__8_.png)
<br>

## 👨‍👩‍👦‍👦 팀원 역할
![image](https://gwangju-ai-gitlab.elice.io/app/black/black_playoutside_android/uploads/cc2c2ec26812710117b82da0316bfaac/image__3_.png)



## 🤾‍♂️ 트러블슈팅
  
* 문제1<br>
     - 캘린더 기능 구현에 있어 VO와 어댑터를 중첩하여 사용함에 있어서 지속 오류가 발생함
        - 구글에서 검색하고 자식부터 추적하여 올라가서 오류를 찾아 수정
 
* 문제2<br>
     - 안드로이드에서 서버 연동 시 지속적인 문제 발생으로 연동이 안되거나 잘못 처리되는 오류 발생
        - 로그를 찍어보고, 에러 이력을 찾아서 추적하여 해결

* 문제3<br>
     - 안드로이드에서 페이지 구성 시 하나의 페이지안에 다양한 레이아웃을 구현하는 데 있어 어려움을 겪음
        - 구글 검색 및 안드로이드 책을 통해 하나하나 구현

* 문제4<br>
     - 클라이언트에서 서버로 이미지 보내는 것과 DB설계에 대한 고찰
        - DB의 경우 일일이 하나씩 따져보고 구상, 서버의 경우 구글에 검색 후 다양한 시도를 통해 구현

* 문제5<br>
     - 맵 API구현시 지속적인 오류 발생
        - 구글 검색과 다양한 시도를 통해 구현, 지속적인 집착으로 일구어냄

