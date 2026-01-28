## 📖 Table of contents
  + [Introduction]()
  + [Demo]()
  + [API]()
  + [System Architecture]()
  + [ERD]()
  + [Tech Stack]()
  + [Monitoring]()
  + [Directory Structure]()
  + [How to start]()
  + [Team Members]()
  
## 📣 Introduction
### URL
> 🗝️ [Benefit](url)
### Medium
> 🔎 [Benefit Medium](url)

  + 사용자의 소비량 시각화
  + 각 카드 혜택 확인
  + 이용중인 구독 서비스 확인 가능
  + 챗봇으로 자유롭게 질문 가능

## 🕺🏻 Demo
### Main
> 로그인 이후 메인 화면

이미지
### 소비 차팅 페이지
> Benefit 접속시 가장 먼저 보이는 화면

여기에 이미지

### 카드 리스트(추천)
> 전화번호 기반 로그인 및 회원가입

이미지

### Subscribe
> 구독 화면  

이미지

## 📗 API
<img width="1339" height="764" alt="image" src="https://github.com/user-attachments/assets/a72f5a9f-7664-4066-b9a9-5b5b3592ab89" />
<img width="1328" height="656" alt="image" src="https://github.com/user-attachments/assets/04558e03-e097-4abb-98e6-99a340c6c3c3" />
<img width="1320" height="328" alt="image" src="https://github.com/user-attachments/assets/b930cd30-f02d-47d9-90d7-51447886eca4" />
<img width="1499" height="889" alt="image" src="https://github.com/user-attachments/assets/ffd812e5-b9ce-4cd0-bc8d-838f2e03363d" />
<img width="1490" height="241" alt="image" src="https://github.com/user-attachments/assets/4a927927-fa32-424e-a7be-5eb02ecf0d1f" />


## 🛠 ️System Architecture
제미나이로 수정해야함
<img width="1115" height="526" alt="image" src="https://github.com/user-attachments/assets/ee6bd574-4e0e-4cfd-8bea-63229dd93e15" />

## 🔑 ERD
<img width="2277" height="1171" alt="image" src="https://github.com/user-attachments/assets/496bd8a3-db1f-4531-91c0-ec7fd2f39ba5" />


## 💻 Tech Stack

| Field | Technology of Use |
| :--- | :--- |
| **Frontend** | ![Flutter](https://img.shields.io/badge/Flutter-06B6D4?style=for-the-badge&logo=Flutter&logoColor=skyblue) |
| **Backend** | ![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/Django_REST_Framework-FF1709?style=for-the-badge&logo=django&logoColor=white) |
| **Database** | ![AmazonS3](https://img.shields.io/badge/AmazonS3-569A31?style=for-the-badge&logo=amazons3&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4169E1?style=for-the-badge&logo=mysql&logoColor=white) ![AmazonRDS](https://img.shields.io/badge/AmazonRDS-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white) |
| **AI** | ![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white) |
| **DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white) ![AmazonEC2](https://img.shields.io/badge/AmazonEC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white) ![GitHubActions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white) |
| **ETC** | ![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) |

## 📊 Monitoring
### Prometheus & Grafana
| Django |
| :---: |
| <img src="이미지_주소_1" width="400"> <img src="이미지_주소_2" width="400"> |

| 예시 |
| :---: |
| <img src="이미지_주소_3" width="400"> <img src="이미지_주소_4" width="400"> |

## 🔧 Logging

| Nginx |
| :---: |
| <img src="이미지_주소_1" width="400"> <img src="이미지_주소_2" width="400"> |

## 📂 Directory Structure
<details>
<summary>📌 여기를 클릭하면 내용을 볼 수 있습니다</summary>

이 안에 들어가는 내용은 처음에는 숨겨져 있다가, 클릭하면 나타납니다.
* 리스트도 넣을 수 있고
* **굵은 글씨**도 가능합니다.

</details>

## 🧐 How To Start
### Backend

git clone --recursive https://github.com/2024-Winter-Bootcamp-team-K/AILIBI-Backend.git

### env setting in the Backend folder
  + Backend/.env
    
DB_NAME=
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_PORT=

OPENAI_API_KEY=

CLIENT_ID=
CLIENT_SECRET=

### Run Docker

docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml build
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml up -d
docker-compose -f docker-compose-common.yml -f docker-compose-blue.yml down

docker-compose -f docker-compose-common.yml -f docker-compose-green.yml build
docker-compose -f docker-compose-common.yml -f docker-compose-green.yml up -d
docker-compose -f docker-compose-common.yml -f docker-compose-green.yml down

### Frontend

git clone --Frontend.git

### Install

명령어 작성



## 👨‍👩‍👧‍👦 Team Members

| Name | 한정수 | 김용진 | 김형호 | 정상겸 | 정하밈 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **Profile** | <img src="이미지주소" width="100"> | <img src="이미지주소" width="100"> | <img src="이미지주소" width="100"> | <img src="이미지주소" width="100"> | <img src="이미지주소" width="100"> |
| **Role** | Leader<br>Full Stack<br>DevOps<br>Design | Backend<br>DevOps | Backend<br>DevOps | Frontend<br>Design | Frontend<br>Design | Frontend<br>Design |
| **GitHub** | [![GitHub](https://img.shields.io/badge/깃이름-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/깃주소) | [![GitHub](https://img.shields.io/badge/깃이름-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/깃주소) | [![GitHub](https://img.shields.io/badge/깃이름-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/깃주소) | [![GitHub](https://img.shields.io/badge/깃이름-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/깃주소) | [![GitHub](https://img.shields.io/badge/HaMimJ-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/HaMim-J) |

