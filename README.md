# Road To Machine Learning
제가 지금까지 공부한/할 머신러닝/딥러닝 관련 로드맵 입니다. (추가 -ing)

## Contents

- [Mathematics](#mathematics)
  * [Calculus](#calculus)
  * [Linear Algebra](#linear-algebra)
  * [Statistics](#statistics)
- [Machine Learning](#machine-learning)
  * [Machine Learning](#machine-learning)
  * [Deep Learning](#deep-learning)
- [Projects](#projects)
  * [대외 활동](#대외-활동)
  * [대회](#대회)
  * [개인 프로젝트](#개인-프로젝트)
  * [연구 인턴](#연구-인턴)
  * [논문 관련 사이트](#논문-관련-사이트)
- [Programming](#programming)
  * [Python](#python)
  * [Algorithm](#algorithm)
  * [Database](#database)
  * [Operating System](#operating-system)
- [Etc](#etc)
## Mathematics

수학은 머신러닝/딥러닝 알고리즘을 이해하기 위해 가장 기초적인 지식입니다.


### Calculus
책
* [미적분학1+(김홍종,서울대학교출판문화원)](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9788952117878) : 서울대학교 미적분학 기본 교재
* [미적분학2+(김홍종,서울대학교출판문화원)](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788952117885&orderClick=LEa&Kc=) : 서울대학교 미적분학 기본 교재

강의
* [미적분학1+(서울대 김영득, SNUON)](http://etl.snu.ac.kr/local/ubonline/course_view.php?id=206524&returnurl=L2xvY2FsL3Vib25saW5lL2luZGV4LnBocD9zZWFyY2h0eXBlPTEma2V5d29yZD0lRUMlODglOTglRUQlOTUlOTk=)
* [미적분학2+(서울대 김영득, SNUON)](http://etl.snu.ac.kr/local/ubonline/course_view.php?id=206525&returnurl=L2xvY2FsL3Vib25saW5lL2luZGV4LnBocD9zZWFyY2h0eXBlPTEma2V5d29yZD0lRUMlODglOTglRUQlOTUlOTk=)


### Linear Algebra
책
* [프리드버그 선형대수학](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791156644910&orderClick=LEa&Kc=) : 일반적으로 공대에서 사용하는 교재보다 수학적 깊이가 있는 전공서. 
* [딥러닝을 위한 선형대수학](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791156644972&orderClick=LEa&Kc=) : 유명한 길버트 스트랭 교수의 최신작. 선형대수학 기본서 한 권을 마친 학생들을 위한 딥러닝 수학을 다룹니다. 원서 제목은 Linear Algebra and Learning from Data이며, 선형대수학을 빠르게 총정리하는 챕터 1 외에도 응용 선형대수, 최적화 이론, 확률론 등 다양한 수학이 다뤄집니다. 저자 직강이 있습니다. 

강의
* [선형대수학(금오공대 유원석, KOCW)](http://www.kocw.net/home/cview.do?cid=f4e5be3972ba9f35)
* [Khan Academy](https://ko.khanacademy.org/profile/me/courses)
* [선형대수학(한양대 이상화, Youtube)](https://www.youtube.com/watch?v=XHfKCNkLfmg&list=PLSN_PltQeOyjDGSghAf92VhdMBeaLZWR3)
* [딥러닝을 위한 선형대수학(Gilbert Strang, Youtube)](https://www.youtube.com/playlist?list=PLUl4u3cNGP63oMNUHXqIUcrkS2PivhN3k)
* [딥러닝을 위한 선형대수학(부산대)](http://wwwdev.kmoocs.kr/courses/course-v1:PNUk+LD_C01+2020_020/about) 
* [선형대수학 이상엽Math(Youtube)](https://www.youtube.com/watch?v=525w2Zqh13M&list=PL127T2Zu76FuVMq1UQnZv9SG-GFIdZfLg)
* [3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)


### Statistics
책
* [수리통계학(송성주,전명식)](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791158082406&orderClick=LEa&Kc=) : Hogg의 수리통계학보다 난이도가 약간 쉽다는 평이 많습니다. 예제 설명이 쉽고 자세하게 나와있습니다.
* [회귀분석(김충락)](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9788981728304&orderClick=LAG&Kc=) : 회귀분석 분야 권위자 김충락 교수님이 직접 쓰신 책입니다. 아래 강의도 있습니다. 
* [30분 통계학](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791160505948&orderClick=LEa&Kc=)

강의
* [회귀분석1(부산대 김충락, KOCW)](http://www.kocw.net/home/cview.do?cid=75c5b6edd7f56811)
* [확률 및 통계(한양대 이상화, Youtube)](https://www.youtube.com/watch?v=2ewO_6msPbA&list=PLSN_PltQeOyjmRIsC7VNirXOBqWoypd4V) : 수리통계학 내용입니다.
* [Statistics 110(한글자막)](https://www.boostcourse.org/ai152)
* [확률과 통계(서울대 류근관, SNUON)](http://etl.snu.ac.kr/local/ubonline/course_view.php?id=206422&returnurl=L2xvY2FsL3Vib25saW5lL2luZGV4LnBocD9zZWFyY2h0eXBlPTEma2V5d29yZD0lRUIlQTUlOTglRUElQjclQkMlRUElQjQlODA=) : 류근관 현 통계청장이 서울대 교수일 때 찍은 강의입니다. 기초 확률과통계 강의


## Machine Learning

### Machine Learning
책
* [파이썬 라이브러리를 활용한 데이터 분석](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791162241905&orderClick=LEa&Kc=)
* [파이썬 라이브러리를 활용한 머신러닝](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791162241646&orderClick=LEa&Kc=)
* [파이썬을 활용한 머신러닝 쿡북](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791162241950&orderClick=LEa&Kc=)

강의
* [SKplanet Tacademy](https://www.youtube.com/c/SKplanetTacademy)


### Deep Learning
책
* [케라스 창시자에게 배우는 딥러닝](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791160505979&orderClick=LEa&Kc=)
* [핸즈온 머신러닝](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791162242964&orderClick=LEa&Kc=)

강의
* [MIT CS231N(한글자막)](https://github.com/visionNoob/CS231N_17_KOR_SUB)
* [모두의 딥러닝 Pytorch](https://www.youtube.com/watch?v=7eldOrjQVi0&list=PLQ28Nx3M4JrhkqBVIXg-i5_CVVoS1UzAv)
* [모두의 딥러닝 TensorFlow2](https://www.youtube.com/watch?v=7eldOrjQVi0&list=PLQ28Nx3M4Jrguyuwg4xe9d9t2XE639e5C)
* [앤드류 응 머신러닝](https://www.coursera.org/learn/machine-learning/home/welcome)
* [Transformer](https://www.youtube.com/watch?v=TQQlZhbC5ps)


## Projects

### 대외 활동
* [Naver AI boostcamp](https://boostcamp.connect.or.kr/)


### 대회
* [Kaggle](https://www.kaggle.com/)
* [Dacon](https://dacon.io/)
* [이유한(Youtube)](https://www.youtube.com/c/YouHanLee) : Kaggle 한국 그랜드마스터이신 이유한님이 캐글 대회 관련 강의를 하는 채널입니다.


### 개인 프로젝트


### 연구 인턴
* [KAIST AI대학원 인턴](https://gsai.kaist.ac.kr/?lang=ko) : 방학마다 카이스트에서 인턴 프로그램을 한다. 대학원 진학에 관심이 있다면 알아 두는게 좋을 것 같습니다.

### 논문 관련 사이트
* [Papers With Code](https://paperswithcode.com/sota) : 발표되는 논문들의 토픽을 성능 순으로 정리 해놓는 사이트입니다. 오픈소스로 코드가 공개된 경우 링크도 같이 올려줍니다.
* [Yannic Kilcher(Youtube)](https://www.youtube.com/c/YannicKilcher/featured) : 최신 AI 관련 논문들을 리뷰해주는 유튜버

## Programming

### Python
* [점프 투 파이썬](https://wikidocs.net/book/1)


### Algorithm
책
* [이것이 취업을 위한 코딩테스트다 with 파이썬](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791162243077&orderClick=LEa&Kc=)
* [파이썬 알고리즘 인터뷰](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791189909178&orderClick=LEa&Kc=)
* [Foundation of Algorithms(번역)](http://www.kyobobook.co.kr/product/detailViewKor.laf?mallGb=KOR&ejkGb=KOR&barcode=9791156005032)

강의
* [이코테 강의(나동빈)](https://www.youtube.com/watch?v=m-9pAwq1o3w&list=PLRx0vPvlEmdAghTr5mXQxGpHjWqSz0dgC&index=1)
* [파이썬으로 배우는 알고리즘 기초](https://www.inflearn.com/course/%ED%8C%8C%EC%9D%B4%EC%8D%AC-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-%EA%B8%B0%EC%B4%88/dashboard)

문제 사이트
* [Baekjoon Online Judge](https://www.acmicpc.net/)
* [Programmers](https://programmers.co.kr/)
* [CodeForces](http://codeforces.com/problemset?order=BY_RATING_ASC)
* [SW Expert Academy](https://swexpertacademy.com/main/main.do)

### Database
책
* [모두의 SQL](http://www.kyobobook.co.kr/product/detailViewKor.laf?ejkGb=KOR&mallGb=KOR&barcode=9791160505771&orderClick=LEa&Kc=)

문제 사이트
* [HackerRank](https://www.hackerrank.com/dashboard)
* [Programmers](https://programmers.co.kr/)

### Operating System
책
* [Operating System Concepts](http://www.kyobobook.co.kr/product/detailViewEng.laf?ejkGb=ENG&mallGb=ENG&barcode=9781119586166&orderClick=LAG&Kc=) : 운영체제의 바이블 공룡책

강의
* [운영체제 공룡책 강의(inflearn)](https://www.inflearn.com/course/%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C-%EA%B3%B5%EB%A3%A1%EC%B1%85-%EC%A0%84%EA%B3%B5%EA%B0%95%EC%9D%98) : 공룡책 10th Edition 국내 강의

## Etc
### 대학원 면접 준비
* [전공 면접 질문 리스트](https://jrc-park.tistory.com/259?category=487571)

