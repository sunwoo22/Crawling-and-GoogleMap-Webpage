# Python-Crawling-and-Google-Map-Web-Service-with-JSP
### Python을 이용한 'HRD-Net' 크롤링 및 JSP 기반의 지도 정보 제공 웹페이지 구축
입니다.   
<br>
<hr>

## 🔥 프로젝트 개요
SQL, Java를 비롯하여 Python 크롤링, R 텍스트마이닝, 통계분석, 프론트엔드 개발(html, css, js), JSP 등 여러가지 언어를 학습했다.
현재 대한상공회의소 서울기술교육센터의 자바기반 빅데이터 시각화 시스템 개발 반에서 국비지원교육과정을 수강하고 있기에
시각화에 초점을 맞추었고, 따라서 구글맵을 이용하여 국민내일배움카드의 훈련과정 정보를 제공하고자 했다.         
<br>
   
## 🛠 프로젝트 환경
✅ **사용 언어**: Python / JSP / HTML5 / CSS3 / JavaScript   
✅ **개발 환경**: Jupyter Notebook / Eclipse / Visual Studio Code   
✅ **개발 기간**: 21.04.20. – 21.05.07.   
✅ **데이터베이스**: MariaDB 10.5.9   
✅ **JSP 환경 설정**: JDK 9.0.4 / Eclipse Java EE (Oxygen 2) / apache-tomcat-9.0.2   
<br>

## ✨ 프로젝트 목표   
✔ **Python**: HRD-Net의 훈련과정 및 기관 정보 수집   
✔ **HTML5·CSS3·JavaScript**: 웹페이지 디자인 및 지도 정보 제공   
✔ **JSP·MariaDB**: DB와 서버 연결을 통한 동적 웹사이트 구현   
<br>
   
## 💻 화면 구성
💨 **main-form.jsp**: 검색 전   
<br>
<img src="https://user-images.githubusercontent.com/84164109/120572754-78a1ca80-c457-11eb-94b4-f3c6f499b9f8.png">
<br>
<img src="https://user-images.githubusercontent.com/84164109/120572759-7a6b8e00-c457-11eb-82f7-e0db215da3ec.png">
<br><br>
💨 **marker-form.jsp**: 검색 후   
<br>
<img src="https://user-images.githubusercontent.com/84164109/120572761-7b042480-c457-11eb-97be-1216cf9bb09f.png">
<br>
<img src="https://user-images.githubusercontent.com/84164109/120572763-7b9cbb00-c457-11eb-9dda-892c4449cd8b.png">
<br><br>

## 💾 서버 구성
💨 **main-server.jsp**: 조건에 맞는 검색   
💨 **dbconn.jsp**: MariaDB와 연결   
<br>
   
## 🎬 시연 영상
> https://youtu.be/bRMCDFCnfhk
<br>
<img src="https://user-images.githubusercontent.com/84164109/120572765-7c355180-c457-11eb-97be-7d63c3bd2f71.png">
<br>

## 💦 보완할 점
Python과 DB연동의 어려움으로 실시간 데이터를 불러오지 못했다...   
(이미 저장되어 있는 정보만 지도에 표시)   
왜인지 데이터가 많으면 지도(마커) 표시가 되지 않는다.   
검색창이나 마커 꾸미는 부분, 지오코더 기능 활용   
훈련기관과 내 장소의 거리 비교 기능 추가하면 좋겠다.      
<br>
   
## 🍺 일기장
> https://mygummy2.tistory.com/46
<br>
   
## 💎 주요 코드
PPT에 잘 정리되어 있습니다.   
