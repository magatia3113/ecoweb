# ECO-WEB
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FCarbonAra-CBA%2Fecoweb&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

<div align="center">
<img width="329" alt="image" src="https://raw.githubusercontent.com/eclipse1228/Githun-User-Content/main/ecoweblogo.png">
</div>

## Eco-web v1.0
> **정부/ 공공기관 웹사이트 저전력 웹페이지 구축 서비스** <br/> **개발기간: 2024.09 ~ 2024.11**

## 배포주소
> **개발 버전** : [http://ecoweb.cs.skku.edu/](http://ecoweb.cs.skku.edu/) <br>
> **프론트 서버** : [http://ecoweb.cs.skku.edu:33307/](http://ecoweb.cs.skku.edu:33307/)<br>
> **백엔드 서버** : [http://ecoweb.cs.skku.edu:2223/](http://ecoweb.cs.skku.edu:2223/)<br>

## Team Info

|      고병수       |          허세진         |       한동규         | 이희수                                                                                                               
| :---------------: | :----------------------: | :------------------: | :---------------------------------------------------------------------: | 
| <img width="160px" src="https://avatars.githubusercontent.com/u/107296751?v=4" /> | <img width="160px" src="" /> | <img width="160px" src=""/> | <img width="160px" src="" /> |
| [@eclipse1228](https://github.com/eclipse1228) | [@jelly1500](https://github.com/jelly1500) | [@dongkyu20](https://github.com/dongkyu20) | [@magatia3113](https://github.com/magatia3113) |
| 동아대학교 컴퓨터공학과 3학년 | 동아대학교 컴퓨터공학과 3학년 | 동아대학교 컴퓨터공학과 3학년 | 동아대학교 컴퓨터공학과 4학년 |

## 프로젝트 소개 

## 시작 가이드
### Requirements
For building and running the application you need:

- [Python 3.10.12](https://www.python.org/downloads/release/python-31012/)
- [Lighthouse 9.1.1](https://github.com/GoogleChrome/lighthouse/releases/tag/v9.1.1)
### Installation
``` bash
$ git clone https://github.com/CarbonAra-CBA/ecoweb.git
$ cd ecoweb
```
#### Backend
```
$ cd ecoweb/app
$ python -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
$ python run.py
```

## Stacks

### Environment
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=for-the-badge&logo=Visual%20Studio%20Code&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)             
### Config
![venv](https://img.shields.io/badge/venv-007ACC?style=for-the-badge&logo=venv&logoColor=white)        

### Development
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=Flask&logoColor=white)
![Lighthouse](https://img.shields.io/badge/Lighthouse-000000?style=for-the-badge&logo=Lighthouse&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=Pandas&logoColor=white)
![Tensorflow](https://img.shields.io/badge/Tensorflow-FF6F00?style=for-the-badge&logo=Tensorflow&logoColor=white)
### Communication
![Notion](https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white)
![GoogleMeet](https://img.shields.io/badge/GoogleMeet-00897B?style=for-the-badge&logo=Google%20Meet&logoColor=white)

## 화면 구성
| 메인 페이지  |  소개 페이지   |
| :-------------------------------------------: | :------------: |
|  <img width="329" src="https://github.com/magatia3113/edit-eco/blob/main/%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%20%ED%85%8C%EC%8A%A4%ED%8A%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EB%A9%94%EC%9D%B8%ED%8E%98%EC%9D%B4%EC%A7%80-%EB%A1%B1.png?raw=true"/> |  <img width="329" src="" alt="제작중"/>|  
| 강좌 소개 페이지   |  강의 영상 페이지   |  
| <img width="329" src=""/>   |  <img width="329" src=""/>     |

---


## 주요 기능
### ⭐️ 탄소발자국 분석, 계산 
- Scratch, Python 2개 강좌 및 각 강좌마다 10개 가량의 강의 영상 제공
- 추후 지속적으로 강좌 추가 및 업로드 예정

### ⭐️ 공기관 별 비교분석
- 웹 표준에 의거한 분류, 빅데이터에 의거한 분류
- 시뮬레이션 (Before & After)
### ⭐️ 솔루션(ML-Classification, LLM Code spliting )
- 머신러닝 분류 모델 제공
- 코드 스플리팅 모델 제공


## 아키텍쳐
<!-- https://img.shields.io/badge/:badgeContent -->


- 동작방식(로직 순서)/데이터 흐름(플로우차트)
<img width="800" src="https://github.com/magatia3113/edit-eco/blob/main/%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%20%ED%85%8C%EC%8A%A4%ED%8A%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EC%95%84%EC%BC%80%ED%85%8D%EC%B3%90%ED%8E%98%EC%9D%B4%EC%A7%801.png?raw=true"/>
<br>

- 구성요소/시스템 구조
<img width="800" src="https://github.com/magatia3113/edit-eco/blob/main/%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%20%ED%85%8C%EC%8A%A4%ED%8A%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%EC%95%84%ED%82%A4%ED%85%8D%EC%B3%90%ED%8E%98%EC%9D%B4%EC%A7%802.png?raw=true"/>
<br>

- 프로젝트 목표
<img width="600" src="https://github.com/magatia3113/edit-eco/blob/main/%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98%20%ED%85%8C%EC%8A%A4%ED%8A%B8%EC%9D%B4%EB%AF%B8%EC%A7%80/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EB%AA%A9%ED%91%9C%20-%20%EC%9D%B4%ED%9D%AC%EC%88%98.png?raw=true"/>







## 디렉토리 구조 
```bash
├───── README.md
│       
├───── ecoweb
|       ├───── app (Flask server)
|       │       ├───── templates   
|       │       ├───── routes.py   (Flask 라우팅)
|       │       ├───── static      
|       │       ├───── __init__.py 
|       │       ├───── config.py   
|       │       ├───── utils       
|       │       ├───── data        (crawling data)
|       │       ├───── lighthouse  (LightHouse code)
|       │       ├───── services    (service code)
|       │       ├───── run.py      (execute Flask)
├───── urls        (url list)
├───── report.json (LightHouse result)
├───── venv        (virtual environment)
├───── virtualenv.md (virtual environment setting)
├───── __init__.py 
```
