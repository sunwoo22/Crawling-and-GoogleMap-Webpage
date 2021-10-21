## 'HRD-Net' 훈련 정보 및 지도 제공 웹페이지
<br>

✔ 프로젝트 개요
<br>

**사용언어**
![](https://img.shields.io/badge/Python-3776AB?style=flat&logo=Python&logoColor=white)
![](https://img.shields.io/badge/Java-007396?style=flat&logo=Java&logoColor=white)
![](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=HTML5&logoColor=white)
![](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=CSS3&logoColor=white)
![](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=JavaScript&logoColor=white)

**개발환경**
![](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=Jupyter&logoColor=white)
![](https://img.shields.io/badge/Eclipse-2C2255?style=flat&logo=Eclipse&logoColor=white)
![](https://img.shields.io/badge/VisualStudioCode-007ACC?style=flat&logo=VisualStudioCode&logoColor=white)
![](https://img.shields.io/badge/MariaDB-003545?style=flat&logo=MariaDB&logoColor=white)
<br>

**환경설정** JDK 9.0.4 / Eclipse Java EE (Oxygen 2) / apache-tomcat-9.0.2

**개발기간**  21.04.20 - 21.05.07 
<br><br>

✔ 디렉토리 구조
<br>

    WebContent
    ㄴdbconn.jsp
    ㄴmain-form.jsp
    ㄴmain-server.jsp
    ㄴmarker-form.jsp
    
<br>


✔ 사용시 변경할 부분
<br>

**dbconnect.jsp**

- MariaDB 연결 (line 14-16)   
url: port번호, DB이름
user: 사용자이름
pw: 사용자비밀번호

**main-server.jsp**   

- DB 테이블명 / 컬럼명   
sql 쿼리문의 테이블명과 컬럼명   


**crawling.ipynb**   
- hrd-net 크롤링 범위   
lastpage 변경
