<h4 align="center"> 2024-Winter-Bootcamp-Team-A 🔥

<h1 align="center"> BookClip </h1>
<div align="center"> 
<h3><b>📚 도서 미리보기 쇼츠 제공 크롬 익스텐션 </b></h3><br>
<img width="1503" src="https://github.com/user-attachments/assets/0174fcb7-1e6e-4c98-8a17-a1d3217b113b">

<br>

</div>
<br><br>

# 📖 Table of contents
* [Introduction](#-introduction)
* [Demo](#-demo)
* [API](#-api)
* [System Architecture](#-system-architecture)
* [ERD](#-erd)
* [Tech Stack](#-tech-stack)
* [Monitoring](#-monitoring)
* [How to start](#-how-to-start)
* [Directory Structure](#-directory-structure)
* [Team Members](#-team-members)

<br>

# 📣 Introduction
### Medium
> 🔎 [Bookclip Medium](https://medium.com/@rlaqhqo9372/2024-winter-silicon-valley-bootcamp-bookclip-a01518b8bbf7) &nbsp;

🔹 교보문구 사이드패널 기능
- 도서 상세 페이지에서 해당 책의 쇼츠 영상이 있으면 즉시 제공
- 기존 쇼츠가 없을 경우 "요청하기" 버튼으로 즉시 생성하여 제공
  
🔹 뉴탭 기능
- 인기 도서 순위를 기반으로 책 추천
- "오늘의 쇼츠" 페이지에서 랜덤하게 추천된 두개의 책 중 하나의 핵심 문장을 고르면 책 추천
- 내가 찜한/공유한/문장카드를 저장한 쇼츠를 한곳에서 모아보기
- 내가 본 도서 장르 비율을 퍼센트로 시각화
<br>

# 🎥 Demo
### Side Pannel
> 교보문고 도서 상세 페이지에서 사이드 패널을 열면 해당 도서의 쇼츠를 바로 시청할 수 있습니다.<br>
> '찜하기' 버튼을 누르면 마이페이지에서 찜한 쇼츠에서 확인 가능합니다.<br>
> 쇼츠로 통해 본 줄거리가 마음에 들었다면 '공유하기' 버튼을 통해 도서링크도 공유가 가능합니다.
<img src="https://github.com/user-attachments/assets/f6f3bc10-c0a3-4b8c-953e-9877e5cef941" />
<br>

### Main Page
<blockquote>타이틀별로 도서를 나열하여 취향에 맞는 쇼츠를 바로 시청할 수 있습니다.</blockquote>

<img src="https://github.com/user-attachments/assets/fae8df54-d290-46cf-919d-70a65dc5f11d"/>
<br>
<blockquote>표지를 누르면 쇼츠가 재생되며 재생카드 뒷면에는 해당 도서와 쇼츠에 대한 상세정보가 있습니다.</blockquote>

<img src="https://github.com/user-attachments/assets/46ce4959-0a34-4045-83b2-41cc517f6d2a"/>
<br>


### Search
> 검색 기능을 통해 원하는 도서를 쉽게 찾을 수 있습니다.
<img src="https://github.com/user-attachments/assets/d26f38e9-d433-41a8-8a40-02cb894ddd06"/>
<br>
<br>

### Stats Page
> 전체 쇼츠 중 각각 가장 많은 조회수, 찜, 댓글을 받은 쇼츠를 보여줍니다.
> 표지를 누르면 상세한 통계정보를 볼 수 있습니다.
<img src="https://github.com/user-attachments/assets/47a5f3d8-6aa0-4b7f-b5da-057699db257c"/>
<br><br>

### Today's shorts
> 랜덤으로 두 책의 핵심문장 중 하나를 고르면 그에 해당하는 도서의 정보를 보여줍니다.<br>
> 하루동안은 선택된 도서만 볼 수 있으며 시간이 지나면 자동으로 갱신됩니다.
<img src="https://github.com/user-attachments/assets/7b541af9-c7c6-4d07-a209-49cd151a60a1">
<br>
<br>

### My Page
> 사용자는 마이페이지에서 자신이 최근에 시청한 도서를 확인할 수 있습니다.<br>
> 읽은 책의 갯수를 바탕으로 분야별로 통계를 내어 사용자의 도서 취향도 확인할 수 있습니다.
<img src="https://github.com/user-attachments/assets/cbfc3bb8-5fdf-4c7d-80d9-5f4b5c61d2f0"/>
<br>
<br>

## 💻 System Architechture
<img src="https://github.com/user-attachments/assets/1f7f435b-e86d-4e76-aa6d-48f220e347b6" />

## 💾 ERD
<p align="center">
 <img src="https://github.com/user-attachments/assets/f218d781-65a9-4a1d-80fa-f9d97ff027b0" />
</p>

## 🛠️ Tech stack

|Area|Tech Stack|
|:---:|:---:|
|<b>Frontend</b>|<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white"> <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white"> |
|<b>Backend</b>|<img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"> <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"> <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"> <img src="https://img.shields.io/badge/Celery-%233782A6.svg?style=for-the-badge&logo=celery&logoColor=white"> |
|<b>AI</b>|<img src="https://img.shields.io/badge/openai-74aa9c?style=for-the-badge&logo=openai&logoColor=white"> <img src="https://img.shields.io/badge/Runway-FF385C?style=for-the-badge&logo=runway&logoColor=white"> |
|<b>DevOps</b>|<img src="https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefikproxy&logoColor=white"> <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"> <img src="https://img.shields.io/badge/gunicorn-%298729.svg?style=for-the-badge&logo=gunicorn&logoColor=white"> |
|<b>DB</b>|<img src="https://img.shields.io/badge/PostgreSQL-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white"> <img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=amazonaws&logoColor=white"> |
|<b>Monitoring</b>|<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white"> <img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/cadvisor-2196F3?style=for-the-badge&logo=cadvisor&logoColor=white"> <img src="https://img.shields.io/badge/Node Exporter-FF9900?style=for-the-badge&logo=prometheus&logoColor=white"> <img src="https://img.shields.io/badge/Loki-7F52FF?style=for-the-badge&logo=loki&logoColor=white"> <img src="https://img.shields.io/badge/Promtail-FFA500?style=for-the-badge&logo=prometheus&logoColor=white"> |
|<b>etc</b>|<img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white"> <img src="https://img.shields.io/badge/Swagger-%2385EA2D.svg?style=for-the-badge&logo=swagger&logoColor=black"> <img src="https://img.shields.io/badge/Zoom-2D8CFF?style=for-the-badge&logo=zoom&logoColor=white"> <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"> |


## ✨ API
 <img src="https://github.com/user-attachments/assets/e47c5bae-7010-46eb-a212-157cc54ee735" />
</p>
 <img src="https://github.com/user-attachments/assets/3280ae09-9ed8-44f2-97c1-5219c3b103af" />
</p>


# 📊 Monitoring

<h3 align="left">Prometheus & Grafana</h3>
<table>
    <tr>
        <th colspan="2">Django</th>
    </tr>
    <tr>
        <td><img src="https://github.com/user-attachments/assets/758f42b0-23a9-4907-a921-0bff27cccf62" alt="Django"></td>
        <td><img src="https://github.com/user-attachments/assets/f8fcb2c3-aba5-48c1-8ef1-94bd7024af44" alt="Django2"></td>
    </tr>
    <tr>
    <tr>
        <th colspan="2">cAdvisor</th>
    </tr>
    <tr>
        <td><img src="https://github.com/user-attachments/assets/d4959403-dd27-4c9a-a4bd-db25f4adcd07" alt="cAdvisor2"></td>
    </tr>
    <tr>
        <th colspan="2">Node Exporter</th>
    </tr>
    <tr>
        <td><img src="https://github.com/user-attachments/assets/7b27b9ad-1f94-4ec1-981e-a62c21042838" alt="Node Exporter"></td>
        <td><img src="https://github.com/user-attachments/assets/fecbbc64-af15-4a79-851b-a22aa7b27a89" alt="Node Exporter2"></td>
    </tr>
</table>


<br>

</div>

# 🔧Logging
<h3 align="left">Loki</h3>
<img src="https://github.com/user-attachments/assets/6e4bd6ad-6d0d-4ddd-ae21-b944184e263b" />


## 🚀 How to Start
#### 1. Clone The Repository
```
https://github.com/2024-Winter-Bootcamp-Team-A/backend.git
https://github.com/2024-Winter-Bootcamp-Team-A/frontend.git
```
#### 2. ENV Setting
- Backend/.env
```
POSTGRES_DB=
POSTGRES_USER=
POSTGRES_PASSWORD=
POSTGRES_HOST=
POSTGRES_PORT=
OPENAI_API_KEY = ""
TYPECAST_API_KEY = ""
S3_ACCESS_KEY = ""
S3_SECRET_KEY = ""
S3_BUCKET = ""
RUNWAY_API_KEY = ""

```
#### 3. Run Docker
```
docker-compose up --build
```
#### 4. Chrome Extension
##### 1. 확장 프로그램 빌드
```
pnpm i
pnpm run dev
```
  - 위 명령어를 실행하면 dist 폴더에 배포 가능한 파일들이 생성
##### 2. Chrome 확장 프로그램 로드
  1. chrome://extensions/ 접속
  2. 페이지 우측 상단에 있는 “개발자 모드” 토글 활성화
  3. “압축 해제된 확장 프로그램 로드” 버튼을 클릭
  4. 빌드된 dist 폴더의 경로를 선택
  5. 확장 프로그램이 정상적으로 로드되면 확장 프로그램 목록에 새 확장 프로그램이 생성

## 👥 Member
| Name | 김보배 | 이다하 | 양현민 | 이현빈 | 송지우 | 이슬 |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Profile | <img width="100px" height="110px" src="https://github.com/user-attachments/assets/16504f09-e45c-4cb9-b307-210ee362a0e1" /> | <img width="100px" height="110px" src="https://github.com/user-attachments/assets/efd39965-a4f0-46b6-a5a5-154ddffb7996" /> | <img width="100px" height="110px" src="https://github.com/user-attachments/assets/ca376052-4300-484b-b326-4e5ff22fb63b" /> | <img width="100px" height="110px" src="https://github.com/user-attachments/assets/c8343d41-bff3-43ef-8bbe-237a30927eb7" /> | <img width="100px" height="110px" src="https://github.com/user-attachments/assets/c32756fc-32e6-4717-8f17-5a55ab3de872" /> | <img width="100px" height="110px" src="https://github.com/user-attachments/assets/896ec2cd-e668-430d-bb2a-74e2978cb46c" />
| Role | Backend, DevOps | Backend, DevOps | Backend, DevOps | Frontend, UI/UX | Frontend, UI/UX | Frontend, UI/UX |
| GitHub | <a href="https://github.com/Kimbobae1"><img src="http://img.shields.io/badge/Kimbobae1-green?style=social&logo=github"/></a> | <a href="https://github.com/daha-lee"><img src="http://img.shields.io/badge/daha--lee-green?style=social&logo=github"/></a> | <a href="https://github.com/Yanghyunnmin"><img src="http://img.shields.io/badge/Yanghyunnmin-green?style=social&logo=github"/></a> | <a href="https://github.com/leeHB-1007"><img src="http://img.shields.io/badge/leeHB--1007-green?style=social&logo=github"/></a> | <a href="https://github.com/JiWoo12161"><img src="http://img.shields.io/badge/JiWoo12161-green?style=social&logo=github"/></a> | <a href="https://github.com/Seul-github"><img src="http://img.shields.io/badge/Seul--github-green?style=social&logo=github"/></a> |
