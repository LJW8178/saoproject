# 10-14 UI/UX · Frontend 학습 기록

**학습 날짜:** 2026-10-14  
**학습 주제:** GitHub 로컬 및 원격 저장소, Commit과 Push  
**학습 키워드:** #GitHub #Repository #Local #Remote #Markdown #Commit #Push

---

## 1. 오늘의 학습 목표

- 로컬(Local) 저장소와 원격(Remote) 저장소의 차이 이해
- GitHub에서 Repository 생성하기
- Visual Studio에서 Markdown(.md) 파일 작성하기
- Commit과 Push를 사용하여 파일을 GitHub에 업로드하기
- 다른 컴퓨터에서도 GitHub를 통해 파일에 접근하는 방법 이해

---

## 2. 핵심 개념 정리

### 개념 1. 로컬(Local) 저장소

- **정의:** 내 컴퓨터에 있는 저장소
- **사용하는 이유:** 컴퓨터에서 파일을 작성하고 관리하기 위해 사용
- **작동 원리:** 내 컴퓨터에 파일을 저장하고 수정
- **실제 사용 사례:** Visual Studio에서 Markdown(.md) 파일 작성 및 저장

### 개념 2. 원격(Remote) 저장소

- **정의:** GitHub에 있는 저장소
- **사용하는 이유:** 다른 컴퓨터에서도 파일에 접근하고 관리하기 위해 사용
- **작동 원리:** 로컬 저장소의 파일을 GitHub에 업로드하고, 다른 컴퓨터에서 로그인하여 파일에 접근
- **실제 사용 사례:** 학교에서 작성한 파일을 GitHub에 업로드한 후 집에서 가져와 사용

### 개념 3. Repository

- **정의:** 파일을 저장하고 관리하는 저장소
- **사용하는 이유:** 프로젝트 파일을 관리하기 위해 사용
- **작동 원리:** GitHub에서 Repository를 생성하고 파일을 업로드하여 관리
- **실제 사용 사례:** GitHub에서 새로운 Repository 생성

### 개념 4. Commit

- **정의:** 파일의 변경 내용을 저장소에 기록하는 작업
- **사용하는 이유:** 작업한 내용을 기록하기 위해 사용
- **작동 원리:** 변경한 파일의 내용을 로컬 저장소에 기록
- **실제 사용 사례:** Markdown 파일을 작성한 후 Commit 진행

### 개념 5. Push

- **정의:** 로컬 저장소의 Commit을 원격 저장소로 업로드하는 작업
- **사용하는 이유:** 로컬에서 작업한 내용을 GitHub에 반영하기 위해 사용
- **작동 원리:** Commit된 내용을 GitHub 원격 저장소에 전송
- **실제 사용 사례:** Commit 후 Push하여 GitHub에서 파일 확인

---

## 3. 개념 도식화

### 3-1. 로컬 저장소와 원격 저장소 비교

| 구분 | 로컬(Local) | 원격(Remote) |
|---|---|---|
| 저장 위치 | 내 컴퓨터 | GitHub |
| 파일 관리 | 컴퓨터에서 직접 관리 | GitHub에서 관리 |
| 접근 방법 | 해당 컴퓨터에서 접근 | GitHub에 로그인하여 접근 |
| 활용 사례 | 파일 작성 및 수정 | 파일 업로드 및 다른 컴퓨터에서 접근 |

### 3-2. 로컬과 원격 저장소의 관계

```mermaid
flowchart TD
    A["학교 컴퓨터"] --> B["로컬 저장소"]
    B -->|"Push"| C["GitHub 원격 저장소"]
    C -->|"파일 가져오기"| D["집 컴퓨터"]
```

### 3-3. GitHub 파일 업로드 과정

```mermaid
flowchart TD
    A["GitHub 접속"] --> B["Repository 생성"]
    B --> C["Visual Studio에서 작업"]
    C --> D["Markdown 파일 생성 및 작성"]
    D --> E["Commit"]
    E --> F["Push"]
    F --> G["GitHub 원격 저장소에 반영"]
```

### 3-4. Commit과 Push의 차이

| 구분 | Commit | Push |
|---|---|---|
| 역할 | 변경 내용 기록 | 기록한 내용 업로드 |
| 저장 위치 | 로컬 저장소 | 원격 저장소 |
| 목적 | 작업 내용 저장 및 관리 | GitHub에 작업 내용 반영 |

```mermaid
flowchart LR
    A["파일 작성 및 수정"] --> B["Commit"]
    B --> C["로컬 저장소"]
    C -->|"Push"| D["GitHub 원격 저장소"]
```

### 3-5. 오늘 배운 내용 전체 흐름

```mermaid
flowchart TD
    A["GitHub Repository 생성"]
    B["Visual Studio에서 .md 파일 작성"]
    C["Commit: 변경 내용 기록"]
    D["Push: GitHub에 업로드"]
    E["원격 저장소에 파일 보관"]
    F["다른 컴퓨터에서 로그인 후 접근"]

    A --> B --> C --> D --> E --> F
```

**핵심 정리**

- **Local:** 내 컴퓨터에 있는 저장소
- **Remote:** GitHub에 있는 저장소
- **Repository:** 파일을 관리하는 저장소
- **Commit:** 변경 내용을 기록
- **Push:** Commit한 내용을 GitHub에 업로드

GitHub를 활용하면 파일을 이메일로 따로 옮기지 않아도 다른 컴퓨터에서 접근할 수 있다.

# 10-19 UI/UX · Frontend 학습 기록

**학습 날짜:** 2026-10-19  
**학습 주제:** Codex, MCP, Playwright 및 HTML/CSS 기초  
**학습 키워드:** #Codex #MCP #Playwright #HTML #CSS #Class #Layout

---

## 1. 오늘의 학습 목표

- Codex 설치 및 사용
- MCP 도구 설치 및 연결
- Playwright MCP를 활용한 브라우저 조작
- HTML의 주요 태그 이해
- CSS의 주요 속성 이해
- 적절한 클래스명과 레이아웃 구성 방법 학습

---

## 2. 핵심 개념 정리

### 개념 1. Codex

- **정의:** 코드 작성 및 개발 작업을 지원하는 AI 코딩 도구
- **사용하는 이유:** 코드 작성, 수정 및 개발 작업을 지원받기 위해 사용

### 개념 2. MCP

- **정의:** AI가 외부 도구와 연결되어 기능을 사용할 수 있도록 하는 프로토콜
- **사용하는 이유:** Codex에서 외부 도구의 기능을 활용하기 위해 사용


### 개념 3. Playwright MCP

- **정의:** AI가 브라우저를 조작할 수 있도록 지원하는 도구
- **사용하는 이유:** 브라우저를 열고 웹페이지를 조작하기 위해 사용

### 개념 4. HTML 주요 태그

| 태그 | 역할 |
|---|---|
| `<nav>` | 내비게이션 영역을 정의 |
| `<ul>` | 순서가 없는 목록 생성 |
| `<li>` | 목록의 각 항목 정의 |
| `container` | 콘텐츠를 감싸는 영역에 자주 사용하는 클래스명 |

**HTML 코드 예시**

```html
<div class="container">
  <nav>
    <ul>
      <li>Home</li>
      <li>About</li>
      <li>Contact</li>
    </ul>
  </nav>
</div>
```

### 개념 5. CSS 주요 속성

| 속성 | 역할 |
|---|---|
| `border` | 요소의 테두리 설정 |
| `margin` | 요소 바깥쪽 여백 설정 |
| `gap` | Flexbox 또는 Grid 등에서 요소 사이 간격 설정 |

**CSS 코드 예시**

```css
.container {
  margin: 20px;
  border: 1px solid black;
}

ul {
  display: flex;
  gap: 16px;
}
```

### 개념 6. 레이아웃 높이 최소화

- **학습 내용:** 웹페이지의 요소가 차지하는 높이를 최대한 적게 사용하기
- **관련 요소:** `margin`, `gap` 등의 여백 설정
- **활용:** 불필요한 여백을 줄여 공간을 효율적으로 구성

---

## 3. 개념 도식화

### 3-1. Codex와 MCP의 관계

```mermaid
flowchart TD
    A["Codex"]
    B["MCP"]
    C["Playwright MCP"]
    D["브라우저"]
    E["웹페이지 조작"]

    A --> B
    B --> C
    C --> D
    D --> E
```

### 3-2. HTML 구조

```mermaid
flowchart TD
    A["div.container"]
    B["nav"]
    C["ul"]
    D["li: Home"]
    E["li: About"]
    F["li: Contact"]

    A --> B
    B --> C
    C --> D
    C --> E
    C --> F
```

### 3-3. CSS 여백과 테두리 관계

```text
┌──────────── margin ────────────┐
│                                │
│   ┌──────── border ────────┐   │
│   │                        │   │
│   │       콘텐츠           │   │
│   │                        │   │
│   └────────────────────────┘   │
│                                │
└────────────────────────────────┘

margin : 요소 바깥쪽 여백
border : 요소의 테두리
gap    : 요소들 사이의 간격
```

### 3-4. 오늘의 학습 내용 전체 구조

```mermaid
flowchart TD
    A["오늘의 학습"]
    A --> B["개발 도구"]
    A --> C["HTML"]
    A --> D["CSS"]

    B --> E["Codex"]
    E --> F["MCP 설치"]
    F --> G["Playwright 브라우저 조작"]

    C --> H["nav / ul / li"]
    C --> I["container / class"]

    D --> J["border"]
    D --> K["margin"]
    D --> L["gap"]
    D --> M["높이 최소화"]
```

---

## 4. 핵심 요약

- **Codex:** AI 코딩 도구
- **MCP:** AI와 외부 도구를 연결하는 프로토콜
- **Playwright MCP:** 브라우저 조작을 지원하는 도구
- **`nav`:** 내비게이션 영역
- **`ul` / `li`:** 목록(제목)과 목록 항목
- **`container`:** 콘텐츠를 감싸는 영역에 사용하는 클래스명
- **`border`:** 선
- **`margin`:** 바깥쪽 여백
- **`gap`:** 요소 사이 간격
- **클래스명:** 요소의 역할을 알아볼 수 있도록 지정
- **레이아웃:** 불필요한 높이와 여백을 줄여 공간 활용


# 10-20 UI/UX · Frontend 학습 기록

**학습 날짜:** 2026-10-20  
**학습 주제:** 웹페이지 구성요소 및 HTML/CSS 기초  
**학습 키워드:** #HTML #CSS #Component #Grid #Image #Padding #BorderRadius #BoxSizing

---

## 1. 오늘의 학습 목표

- 웹페이지를 구성하는 주요 요소 이해
- 메인 헤더, 웹 그리드, 컴포넌트의 개념 이해
- HTML 이미지 태그 사용 방법 학습
- 상대경로와 절대경로의 차이 이해
- CSS의 `padding`, `border-radius`, `box-sizing` 속성 이해

---

## 2. 핵심 개념 정리

### 개념 1. 구성요소와 컴포넌트(Component)

- **구성요소:** 화면을 구성하는 개별 요소
- **컴포넌트:** 화면을 구성하는 요소들을 하나의 기능이나 역할에 따라 묶은 단위
- **사용하는 이유:** 화면의 구조를 구분하고 관리하기 위해 사용
- **실제 사용 사례:** 헤더, 버튼, 메뉴, 카드 등

### 개념 2. 메인 헤더(Main Header)

- **정의:** 웹페이지 상단에 위치하는 주요 영역
- **역할:** 웹사이트의 로고, 메뉴 등 주요 정보를 배치
- **실제 사용 사례:** 홈페이지 상단의 로고 및 내비게이션 메뉴

### 개념 3. 웹 그리드(Web Grid)

- **정의:** 웹페이지의 콘텐츠를 행과 열을 기준으로 배치하는 구조
- **사용하는 이유:** 요소들을 일정한 규칙에 따라 정렬하기 위해 사용
- **실제 사용 사례:** 상품 목록, 사진 갤러리, 카드 레이아웃

### 개념 4. HTML 이미지 태그

**기본 문법**

```html
<img src="" alt="">
```

| 속성 | 역할 |
|---|---|
| `<img>` | 이미지를 표시하는 HTML 태그 |
| `src` | 이미지 파일의 위치 지정 |
| `alt` | 이미지를 설명하는 대체 텍스트 |

### 개념 5. 이미지 경로

**상대경로(Relative Path)**

- 현재 파일의 위치를 기준으로 이미지 경로를 지정

```html
<img src="./images/photo.jpg" alt="사진">
```

**절대경로(Absolute Path)**

- 파일의 전체 위치를 기준으로 경로를 지정

```html
<img src="https://example.com/images/photo.jpg" alt="사진">
```

| 구분 | 상대경로 | 절대경로 |
|---|---|---|
| 기준 | 현재 파일 위치 | 전체 경로 |
| 예시 | `./images/photo.jpg` | `https://example.com/photo.jpg` |
| 특징 | 파일 위치에 따라 달라짐 | 현재 파일 위치와 관계없이 지정 |

### 개념 6. Padding

- **정의:** 박스 안쪽에 여백을 생성하는 CSS 속성
- **역할:** 콘텐츠와 테두리 사이의 공간 설정

```css
.box {
  padding: 20px;
}
```

### 개념 7. Border Radius

- **정의:** 요소의 모서리를 둥글게 만드는 CSS 속성
- **올바른 속성명:** `border-radius`

```css
.box {
  border-radius: 10px;
}
```

### 개념 8. Box Sizing

- **정의:** 요소의 너비와 높이를 계산하는 기준을 설정하는 CSS 속성
- **`box-sizing: border-box`:** 지정한 너비와 높이 안에 `padding`과 `border` 크기를 포함

```css
.box {
  width: 200px;
  padding: 20px;
  border: 2px solid black;
  box-sizing: border-box;
}
```

---

## 3. 개념 도식화

### 3-1. 웹페이지 구성요소

```mermaid
flowchart TD
    A["웹페이지"]
    A --> B["메인 헤더"]
    A --> C["콘텐츠 영역"]
    C --> D["웹 그리드"]
    D --> E["컴포넌트"]
    E --> F["이미지"]
    E --> G["텍스트"]
    E --> H["버튼"]
```

### 3-2. 웹 그리드 구조

```text
┌───────────────────────────────┐
│           메인 헤더            │
├─────────┬─────────┬───────────┤
│ 카드 1  │ 카드 2  │ 카드 3    │
├─────────┼─────────┼───────────┤
│ 카드 4  │ 카드 5  │ 카드 6    │
└─────────┴─────────┴───────────┘
```

### 3-3. Padding 구조

```text
┌────────────── Border ──────────────┐
│                                    │
│       Padding (안쪽 여백)           │
│                                    │
│       ┌──────────────────┐         │
│       │     Content      │         │
│       └──────────────────┘         │
│                                    │
└────────────────────────────────────┘
```

### 3-4. Border Radius 비교

```text
border-radius: 0;       border-radius: 12px;

┌──────────────┐         ╭──────────────╮
│              │         │              │
│     BOX      │         │     BOX      │
│              │         │              │
└──────────────┘         ╰──────────────╯
```

### 3-5. Box Sizing 비교

| 구분 | `content-box` | `border-box` |
|---|---|---|
| 기본값 여부 | 기본값 | 직접 지정 |
| width 기준 | 콘텐츠 너비 | 테두리까지 포함한 너비 |
| padding | 지정 너비에 추가 | 지정 너비 안에 포함 |
| border | 지정 너비에 추가 | 지정 너비 안에 포함 |

**예시: `width: 200px`, `padding: 20px`, `border: 2px`**

```text
content-box
┌─────────────────────────────┐
│ border + padding + content  │
└─────────────────────────────┘
실제 전체 너비: 244px

border-box
┌────────────────────────┐
│ border + padding +     │
│ content                │
└────────────────────────┘
실제 전체 너비: 200px
```

---

## 4. 핵심 요약

- **구성요소:** 화면을 이루는 개별 요소
- **컴포넌트:** 특정 역할을 수행하는 화면 구성 단위
- **메인 헤더:** 웹페이지 상단의 주요 영역
- **웹 그리드:** 행과 열을 기준으로 요소를 배치하는 구조
- **`img`:** 이미지를 표시하는 태그
- **`src`:** 이미지 파일의 경로
- **`alt`:** 이미지 대체 텍스트
- **상대경로:** 현재 파일 위치를 기준으로 지정
- **절대경로:** 전체 위치를 기준으로 지정
- **`padding`:** 박스 안쪽 여백
- **`border-radius`:** 박스 모서리 둥글기
- **`box-sizing: border-box`:** 지정한 크기 안에 padding과 border 포함


# 10-21 UI/UX · Frontend 학습 기록

**학습 날짜:** 2026-10-21  
**학습 주제:** HTML 시맨틱 구조, CSS 선택자, 레이아웃 및 아이콘 활용  
**학습 키워드:** #HTML #CSS #ID #Class #Hover #Flexbox #ObjectFit #GoogleFonts #SemanticHTML

---

## 1. 오늘의 학습 목표

- HTML의 `id`, `span`, `h`, `p` 태그 이해
- CSS 선택자와 마우스 상호작용 학습
- Flexbox를 활용한 요소 크기 조절
- 이미지 크기 및 잘림 처리 방법 이해
- 웹 표준에 맞는 헤더 구조 설계
- Google Fonts 아이콘 사용 및 크기 조절

---

## 2. 핵심 개념 정리

### 개념 1. HTML 태그

| 태그 | 역할 | 특징 |
|---|---|---|
| `<span>` | 인라인 요소를 묶음 | 텍스트나 아이콘에 스타일 적용 |
| `<h1>`~`<h6>` | 제목 표시 | 숫자가 작을수록 상위 제목 |
| `<p>` | 문단 표시 | 문장이나 문단을 묶을 때 사용 |
| `<a>` | 링크 연결 | `href` 속성으로 이동할 주소 지정 |

**아이콘에 span 사용 예시**

```html
<a href="https://google.com">
  <span class="material-symbols-outlined">
    home
  </span>
</a>
```

- `<span>`으로 아이콘 표시
- `<a>`로 외부 링크 연결

### 개념 2. ID 선택자와 Class 선택자

| 구분 | ID | Class |
|---|---|---|
| HTML 속성 | `id="header"` | `class="header"` |
| CSS 선택자 | `#header` | `.header` |
| 사용 횟수 | 한 문서에서 고유하게 사용 | 여러 요소에 재사용 가능 |
| 우선순위 | Class보다 높음 | ID보다 낮음 |

```html
<div id="header" class="container">
  Header
</div>
```

```css
#header {
  background: gray;
}

.container {
  padding: 20px;
}
```

**핵심:** ID는 한 HTML 문서에서 같은 값을 중복하지 않도록 사용하며, CSS 선택자에서는 `#`으로 불러온다.

### 개념 3. Cursor와 Hover

**`cursor: pointer;`**

- 마우스 커서를 손가락 모양으로 변경
- 클릭 가능한 요소를 표현할 때 사용

**`:hover`**

- 마우스를 요소 위에 올렸을 때 스타일 변경

```css
.button {
  cursor: pointer;
}

.button:hover {
  background-color: gray;
}
```

### 개념 4. Object-fit

**`object-fit: cover;`**

- 이미지 원본 비율을 유지
- 이미지가 박스를 가득 채우도록 확대 또는 축소
- 박스를 벗어나는 부분은 잘림
- 기본적으로 중앙을 기준으로 배치

```css
.image {
  width: 300px;
  height: 200px;
  object-fit: cover;
}
```

### 개념 5. Flex-grow와 Flex-basis

| 속성 | 역할 |
|---|---|
| `flex-grow: 1;` | 남는 공간을 차지하도록 요소를 확장 |
| `flex-basis: 0;` | 요소의 기본 크기를 0으로 설정하여 공간 분배 계산 |

```css
.item {
  flex-grow: 1;
  flex-basis: 0;
}
```

- 부모 요소에 `display: flex;`가 필요
- 두 속성을 함께 사용하면 요소들이 사용 가능한 공간을 비율에 따라 나누기 쉬움

### 개념 6. 버튼 Normalize

- 브라우저마다 다를 수 있는 버튼의 기본 스타일을 초기화하거나 통일하는 작업

```css
