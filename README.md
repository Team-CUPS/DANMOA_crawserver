# DANMOA_crawlserver


### 코드 소개

- 단모아 내 특정 기능을 위한 크롤링 API 서버입니다.
- /week : 단국대 홈페이지에서 주간 학사 일정을 크롤링하여 정제합니다.
- /menu1 : 단국대 홈페이지에서 학생식당 메뉴를 크롤링하여 정제합니다.
- /menu2 : 단국대 홈페이지에서 교직원식당 메뉴를 크롤링하여 정제합니다.
- /contest : 사용자가 공모전 검색에 적용한 필터 값으로 콘테스트 코리아에 POST 요청을 보내고 받은 response를 정제합니다.


### 개발 환경

- **IDE** : Visual Studio Code
- **개발언어** : Python
- **프레임워크** : FastAPI
- **라이브러리** : BeautifulSoup, httpx
- **배포** : cloudtype
