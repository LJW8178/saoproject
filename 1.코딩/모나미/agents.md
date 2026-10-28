그리드 1400px
gutter 22px
margin 20px

lang-but 88x30
sns icon 30x30
ㄴ margin 7px

HOMESITE MAPCONTACT US
https://www.youtube.com/channel/UC7lJDw-5bYXnAGNHh1uUG3A
https://www.facebook.com/monami1960

## 모나미 홈페이지 `head_top` 실측 스타일

- 확인 환경: 브라우저 뷰포트 1365px, 스크롤바를 제외한 문서 너비 1350px.
- `.head_top`: 전체 너비 1350px, 높이 59px. 자체 margin/padding은 0.
- `.head_top .conwrap`: 너비 1269px, 높이 44px. 좌우 margin 각 40.5px(가운데 정렬). 화면 너비에 따라 달라지는 값.
- 왼쪽 `.links`: 204 × 30px, 위쪽 margin 14px.
- 언어 선택 `.lang`: 88 × 30px, 위쪽 padding 7px, 1px 테두리. `KOR` 글자는 Montserrat 11px, 두께 400, 왼쪽 padding 15px.
- SNS 아이콘: 각각 30 × 30px(페이스북·인스타그램·유튜브), 각 항목의 왼쪽 margin 7px. 아이콘 사이 간격은 7px.
- 오른쪽 `.topmenu`: 약 226.6 × 20px, 위쪽 margin 20px. `HOME`, `SITE MAP`, `CONTACT US` 글자는 Montserrat 11px, 두께 400. 각 메뉴 항목은 왼쪽 margin 10px과 padding 12px이 적용됨.
- 참고: `.head_top`의 기본 상속 글자 크기는 13.5px, 두께는 400이나 실제 언어·상단 메뉴 링크의 글자 크기는 11px임.


nav-search

## 모나미 홈페이지 상단바 크기

- 확인 환경: Playwright 브라우저 뷰포트 1067 × 925px.
- 상단 헤더 `#header`: 1052 × 149px (`x=0`, `y=0`). 너비는 스크롤바를 제외한 문서 너비.
- 메인 메뉴 `.gnb`: 높이 89px (`y=59`).
- 상단 보조 메뉴 영역: 약 59px 높이.
- 측정 단위: `getBoundingClientRect()`의 CSS 픽셀.

## 모나미 홈페이지 내비게이션 메뉴 글자

`#header .gnb .nav`의 메인 메뉴와 하위 메뉴를 표시 순서대로 기록함.

1. 모나미소개
   - CEO 메시지
   - 회사정보
   - 회사연혁
   - 윤리강령
   - 투자정보
   - CI
   - 찾아오시는 길
   - 안전보건 경영방침
2. 모나미제품
   - 프리미엄 펜
   - 펜·펜슬
   - 마카·컬러링
   - 노트·사무용품
   - 잉크·리필
3. NEWS & VIDEO
   - 보도자료
   - 동영상자료
4. 브랜드스토어
   - 브랜드스토어
5. 모나미 미술대회
   - 미술대회 소개
   - 수상작 발표
6. 고객지원
   - 자주묻는질문
   - 문의하기
7. 기업 구매 / 개발
   - 대량 구매 문의
   - 기업 및 단체 구매
   - 산업용 맞춤 제품개발

## 상단 네비게이션 메인 메뉴 글자 여백

- 확인 환경: Playwright 브라우저 뷰포트 1067 × 925px.
- 각 메뉴 칸(`.gnb .nav > ul > li`)의 너비는 146.5px, 높이는 89px. 글자는 가운데 정렬.
- 메뉴 칸 사이의 간격은 약 3.8px. 네비게이션 영역 안에서 메뉴 전체의 좌우 여백은 각각 약 61.9px.
- 아래 `실제 CSS 패딩`은 링크의 `getComputedStyle()` 값이다. `글자 주변 빈 공간`은 각 메뉴 칸의 경계와 실제 글자 영역 사이를 `Range.getBoundingClientRect()`로 측정한 값이다. 링크 자체의 CSS `margin`도 0.

| 메뉴 글자 | 실제 CSS 패딩 왼쪽 | 실제 CSS 패딩 오른쪽 | 글자 주변 빈 공간 왼쪽 | 글자 주변 빈 공간 오른쪽 |
| --- | ---: | ---: | ---: | ---: |
| 모나미소개 | 0px | 0px | 34.1px | 34.2px |
| 모나미제품 | 0px | 0px | 34.1px | 34.2px |
| NEWS & VIDEO | 0px | 0px | 7.2px | 7.2px |
| 브랜드스토어 | 0px | 0px | 26.3px | 26.3px |
| 모나미 미술대회 | 0px | 0px | 16.1px | 16.1px |
| 고객지원 | 0px | 0px | 42.0px | 42.0px |
| 기업 구매 / 개발 | 0px | 0px | 15.8px | 15.8px |
