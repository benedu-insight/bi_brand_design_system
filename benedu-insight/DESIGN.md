---
version: 1.1
name: benedu-insight-design-system
description: 반도체 플라즈마·RF 전력전송 전문 교육·컨설팅 브랜드 Benedu Insight의 디자인 시스템. 따뜻한 크림(`#FAF9F5`)과 잉크 블랙(`#181715`)이 번갈아 나오는 "샌드위치" 구조 위에, 로고 색 그린(`#0F8C50`)·퍼플(`#7030A0`)은 로고와 2-tone 헤드라인에만 쓰고, 코랄(`#CC785C`) 하나를 유일한 액션 색으로 쓴다. 영문·숫자는 Google Sans, 국문은 Gowun Batang, 데이터·라벨은 JetBrains Mono. 로고는 닫힌 그린 링과 퍼플 소문자 두 줄 워드마크(benedu / insight).
parent: null
children: [benedu atelier]

colors:
  cream: "#FAF9F5"
  surface: "#EFE9DE"
  white: "#FFFFFF"
  ink: "#252320"
  steel: "#6C6A64"
  steel-soft: "#A09D96"
  hairline: "#E6DFD8"
  ink-black: "#181715"
  card-dark: "#232120"
  chip-dark: "#2A2724"
  hairline-dark: "#3A3733"
  on-dark: "#FFFFFF"
  on-dark-muted: "#C9C4BC"
  brand-green: "#0F8C50"
  brand-purple: "#7030A0"
  coral: "#CC785C"
  amber: "#E8A55A"
  teal: "#5DB8A6"
  lavender: "#F0E6F6"
  good: "#0F8C50"
  risk: "#C64545"
  print-text: "#1A1A1A"
  print-sub: "#737373"

typography:
  cover-wordmark:
    fontFamily: "'Google Sans', sans-serif"
    fontSize: 52px
    pptSize: 56pt
    fontWeight: 700
    lineHeight: 1.05
    letterSpacing: -0.5px
  dark-headline:
    fontFamily: "'Google Sans', 'Gowun Batang', sans-serif"
    fontSize: 28px
    pptSize: 30pt
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  slide-title:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 26px
    pptSize: 27pt
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: 0
  slide-subtitle:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 14px
    pptSize: 13.5pt
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  eyebrow:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 12px
    pptSize: 11pt
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0.12em
    textTransform: uppercase
  card-title:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 16px
    pptSize: 15pt
    fontWeight: 700
    lineHeight: 1.35
    letterSpacing: 0
  body:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 13px
    pptSize: 12.5pt
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  table:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 12px
    pptSize: 12pt
    fontWeight: 400
    lineHeight: 1.45
    letterSpacing: 0
  table-header:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 12px
    pptSize: 12pt
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  stat-number:
    fontFamily: "'Google Sans', sans-serif"
    fontSize: 34px
    pptSize: 40pt
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: -0.5px
  footer:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 9px
    pptSize: 9pt
    fontWeight: 500
    lineHeight: 1.0
    letterSpacing: 0.08em
    textTransform: uppercase
  page-title:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 42px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: 0
  page-section:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 24px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  page-body:
    fontFamily: "'Gowun Batang', 'Google Sans', serif"
    fontSize: 15px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 0
  logo-wordmark:
    fontFamily: "Gmarket Sans TTF"
    fontWeight: "500 (benedu) / 300 (insight)"
    textTransform: lowercase
  logo-wordmark-ko:
    fontFamily: "코레일 둥근고딕"
    fontWeight: "700 (베네듀) / 300 (인사이트)"

rounded:
  none: 0px
  xs: 4px
  sm: 8px
  md: 10px
  lg: 12px
  xl: 16px
  pill: 999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  margin-x: 72px

components:
  button-cta:
    backgroundColor: "{colors.coral}"
    textColor: "{colors.white}"
    typography: "{typography.card-title}"
    rounded: "{rounded.pill}"
    padding: 10px 22px
    height: 40px
  text-link:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.coral}"
    typography: "{typography.body}"
  chip:
    backgroundColor: "{colors.surface}"
    textColor: "{colors.ink}"
    typography: "{typography.table}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  chip-dark:
    backgroundColor: "{colors.chip-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.table}"
    rounded: "{rounded.pill}"
    padding: 4px 12px
  hairline-card:
    backgroundColor: "{colors.white}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 20px
  card-dark:
    backgroundColor: "{colors.card-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.body}"
    rounded: "{rounded.md}"
    padding: 20px
  stat-panel-dark:
    backgroundColor: "{colors.ink-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.stat-number}"
    rounded: "{rounded.xl}"
    padding: 28px
  quote-box:
    backgroundColor: "{colors.lavender}"
    textColor: "{colors.ink}"
    typography: "{typography.slide-subtitle}"
    rounded: "{rounded.lg}"
    padding: 28px
  cta-box:
    backgroundColor: "{colors.brand-purple}"
    textColor: "{colors.on-dark}"
    typography: "{typography.dark-headline}"
    rounded: "{rounded.xl}"
    padding: 40px
  data-table-dark:
    backgroundColor: "{colors.ink-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.table}"
  data-table-dark-header:
    backgroundColor: "{colors.card-dark}"
    textColor: "{colors.amber}"
    typography: "{typography.table-header}"
  terminal-panel:
    backgroundColor: "{colors.card-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.footer}"
    rounded: "{rounded.md}"
    padding: 20px
  slide-light:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.ink}"
    typography: "{typography.slide-title}"
    padding: 0 72px
  slide-dark:
    backgroundColor: "{colors.ink-black}"
    textColor: "{colors.on-dark}"
    typography: "{typography.dark-headline}"
    padding: 0 72px
  slide-footer:
    backgroundColor: "{colors.cream}"
    textColor: "{colors.steel-soft}"
    typography: "{typography.footer}"
  signature-ring:
    backgroundColor: "{colors.ink-black}"
    textColor: "{colors.brand-green}"
    rounded: "{rounded.pill}"
---

## Overview

Benedu Insight는 반도체 플라즈마 공정과 RF 전력전송을 가르치는 **전문 교육·컨설팅 브랜드**다. 현장 엔지니어를 위한 기술 강의, 회사소개·제안서, 기술 강의 덱과 웹 강의 모듈을 이 이름으로 낸다. AI 실무 교육 브랜드 benedu atelier의 부모 브랜드다.

시스템은 **따뜻한 크림**(`{colors.cream}` — `#FAF9F5`) 라이트 슬라이드와 **잉크 블랙**(`{colors.ink-black}` — `#181715`) 다크 슬라이드가 번갈아 나오는 "샌드위치" 구조로 리듬을 만든다. 본문은 잉크(`{colors.ink}` — `#252320`), 보조 글자는 스틸(`{colors.steel}`)로 쓰고, 구획은 그림자 없이 **hairline** 한 줄로만 나눈다.

색은 엄격하게 역할을 나눈다. **그린**(`{colors.brand-green}` — `#0F8C50`)과 **퍼플**(`{colors.brand-purple}` — `#7030A0`)은 로고 색이라 로고와 "Benedu Insight" 2-tone 헤드라인에만 쓴다. 화면에서 행동을 부르는 색은 **코랄**(`{colors.coral}` — `#CC785C`) 하나뿐이고, 한 슬라이드에 1~3곳까지만 쓴다. 앰버·틸은 다크 슬라이드의 번호와 태그에, 라벤더는 라이트 슬라이드의 인용 박스에만 쓴다.

**Key Characteristics:**
- 크림 라이트 슬라이드와 잉크 블랙 다크 슬라이드가 번갈아 나오는 샌드위치 리듬. 뉴트럴이 화면의 70% 이상
- 코랄(`{colors.coral}`)이 유일한 액션 색. 버튼·링크·통계 단위·모듈 번호에만, 슬라이드당 1~3곳
- 그린·퍼플은 로고와 "Benedu Insight" 2-tone 헤드라인 전용
- 영문·숫자 Google Sans, 국문 Gowun Batang, 데이터·라벨·페이지 정보 JetBrains Mono. 국문 문장 속 영문·숫자는 Google Sans로 바꿔 쓴다
- 카드와 표는 hairline으로만 구획. 그림자·좌측 색 띠·제목 밑줄 없음
- 16:9 슬라이드, 좌우 여백 72px(0.75in) 고정, 우상단 로고, 하단 hairline 푸터
- 로고의 링을 크게 키워 흐리게 깐 **Signature Ring**은 다크·퍼플 패널에서만

## Colors

### Brand & Accent
- **Brand Green** (`{colors.brand-green}` — `#0F8C50`): 로고 링, 2-tone 헤드라인의 "Benedu". 의미는 "보이는 약속"(성장·진정성). 로고 밖에서 남용하지 않는다.
- **Royal Purple** (`{colors.brand-purple}` — `#7030A0`): 로고 워드마크, 2-tone 헤드라인의 "Insight", 클로징 CTA 박스 배경. 의미는 "약속의 내용"(통찰·지혜).
- **Coral** (`{colors.coral}` — `#CC785C`): **유일한 액션 색.** CTA 버튼, 링크, 통계 단위 라벨, 모듈 번호(M1, M2…). 슬라이드당 1~3곳.
- **Amber** (`{colors.amber}` — `#E8A55A`): 다크 슬라이드 전용. eyebrow 섹션 번호, 큰 통계 숫자, 다크 표 머리글.
- **Teal** (`{colors.teal}` — `#5DB8A6`): 다크 슬라이드 전용. 태그 색 변주, 다크 배경의 링크.
- **Lavender** (`{colors.lavender}` — `#F0E6F6`): 라이트 슬라이드 전용. 인용·철학 박스의 옅은 배경.

### Surface
- **Cream** (`{colors.cream}` — `#FAF9F5`): 기본 라이트 슬라이드·페이지 배경.
- **Surface** (`{colors.surface}` — `#EFE9DE`): 라이트 배경 위 칩·태그·보조 카드.
- **White** (`{colors.white}` — `#FFFFFF`): hairline 카드 배경.
- **Hairline** (`{colors.hairline}` — `#E6DFD8`): 라이트 배경 구분선·카드 테두리.
- **Ink Black** (`{colors.ink-black}` — `#181715`): 풀블리드 다크 슬라이드 배경, 표지 통계 패널.
- **Card on Dark** (`{colors.card-dark}` — `#232120`): 다크 배경 위 카드·타일, 다크 표 머리글 행.
- **Chip on Dark** (`{colors.chip-dark}` — `#2A2724`): 다크 배경 위 칩.
- **Hairline on Dark** (`{colors.hairline-dark}` — `#3A3733`): 다크 배경 구분선.

### Text
- **Ink** (`{colors.ink}` — `#252320`): 본문 기본 글자.
- **Steel** (`{colors.steel}` — `#6C6A64`): 보조 설명, 부제.
- **Steel Soft** (`{colors.steel-soft}` — `#A09D96`): 캡션, 비활성, 푸터.
- **On Dark** (`{colors.on-dark}` — `#FFFFFF`): 다크 배경 제목과 본문.
- **On Dark Muted** (`{colors.on-dark-muted}` — `#C9C4BC`): 다크 배경 보조 글자.

### Semantic
- **Good** (`{colors.good}` — `#0F8C50`): 표의 긍정 값 전용(Brand Green 재사용).
- **Risk** (`{colors.risk}` — `#C64545`): 위험·주의 값 전용. 남용 금지.

### Print
명함·인쇄물은 브랜드 명세서 v3.2의 값을 쓴다. 흰 바탕(`{colors.white}`)에 본문 `{colors.print-text}`(`#1A1A1A`), 보조 `{colors.print-sub}`(`#737373`), 이름 밑 액센트 선과 T·E·A 레이블은 퍼플. 대형 시각물(표지·간판·포스터)의 면적 비율은 그린 : 퍼플 : 흑백 = 약 50 : 30 : 20.

| 컬러 | CMYK 근사값 | Pantone 근사값 |
|---|---|---|
| Brand Green `#0F8C50` | C85 M20 Y80 K10 | 356 C / 348 C |
| Brand Purple `#7030A0` | C70 M90 Y0 K10 | 2603 C / 267 C |

### Accessibility Notes

브랜드 색을 글자에 쓸 때의 실측 명도비(WCAG). 토큰 값은 바꾸지 않고, 쓰는 크기로 조절한다.

| 조합 | 명도비 | 쓰는 법 |
|---|---|---|
| `{colors.coral}` 글자 / `{colors.white}`·`{colors.cream}` 바탕 | 3.1~3.3:1 | 본문 크기 링크로는 기준(4.5:1) 미달. 18.7px Bold 이상 라벨·숫자 단위에 쓰고, 본문 링크에는 밑줄이나 화살표를 함께 둔다 |
| `{colors.white}` 글자 / `{colors.coral}` 버튼 | 3.3:1 | 버튼 글자는 18.7px Bold 이상으로 키운다 |
| `{colors.brand-green}` 글자 / `{colors.cream}` | 4.1:1 | eyebrow 번호처럼 짧은 Bold 숫자에만 |
| `{colors.steel-soft}` 글자 / `{colors.cream}` | 2.6:1 | 장식성 캡션·푸터에만. 읽어야 하는 정보는 `{colors.steel}`(5.1:1) |
| `{colors.ink}` 글자 / `{colors.cream}` | 14.9:1 | 본문 기본 |

## Typography

### Font Family

세 서체로 제한한다. **Google Sans**는 영문, 숫자, 표지 워드마크, 큰 통계 숫자를 맡는다. **Gowun Batang**은 국문 제목·본문·카드·표를 맡는다. 붓맛이 남은 바탕체라 기술 강의에 학술적인 무게를 준다. **JetBrains Mono**는 eyebrow 라벨, 페이지 번호, 푸터, 터미널 패널처럼 데이터 성격의 글자에만 쓴다.

**혼합 언어 규칙:** 국문 문장은 Gowun Batang으로 쓰되, 그 안에 섞인 **영문 단어·숫자·기호는 Google Sans로 바꿔 쓴다.** 웹은 `<span class="en">`(또는 자동 감싸기 스크립트), PPT는 텍스트 run을 나눠 영문·숫자 run에 Google Sans를 지정한다.

로고에는 전용 서체가 따로 있다(브랜드 명세서 v3.2). 영문 워드마크는 G마켓 산스 TTF(benedu Medium 500 / insight Light 300), 국문 워드마크는 코레일 둥근고딕(베네듀 Bold / 인사이트 Light). 로고 파일은 아웃라인이므로 이 서체들은 로고 밖에서 쓰지 않는다.

### Hierarchy — Slides (Web 1280×720 / PPT 13.333×7.5in)

| Token | Web | PPT | Weight | Font | Use |
|---|---|---|---|---|---|
| `{typography.cover-wordmark}` | 52px | 56pt | 700 | Google Sans | 표지 2-tone 워드마크 |
| `{typography.dark-headline}` | 28px | 30pt | 700 | Google Sans / Gowun Batang | 다크 섹션 헤드라인 |
| `{typography.slide-title}` | 26px | 27pt | 700 | Gowun Batang(국문) / Google Sans(영문) | 슬라이드 제목 |
| `{typography.slide-subtitle}` | 14px | 13.5pt | 400 | Gowun Batang | 부제 |
| `{typography.eyebrow}` | 12px | 11pt | 700 | JetBrains Mono | 섹션 번호 + 영문 대문자 태그 |
| `{typography.card-title}` | 16px | 15pt | 700 | Gowun Batang | 카드·모듈 제목 |
| `{typography.body}` | 13px | 12.5pt | 400 | Gowun Batang | 본문 |
| `{typography.table-header}` | 12px | 12pt | 700 | Gowun Batang | 표 머리글 |
| `{typography.table}` | 12px | 12pt | 400 | Gowun Batang | 표 본문, 칩 |
| `{typography.stat-number}` | 34px | 40pt | 700 | Google Sans | 큰 통계 숫자 |
| `{typography.footer}` | 9px | 9pt | 500 | JetBrains Mono | 푸터, 페이지 번호 |

**하한선:** 본문 11pt, 제목 26pt 아래로 내리지 않는다. 발표 화면 뒷자리에서도 읽혀야 한다.

### Hierarchy — Long Pages

| Token | Size | Weight | Line Height | Use |
|---|---|---|---|---|
| `{typography.page-title}` | 42px | 700 | 1.2 | 문서·가이드 페이지 제목 |
| `{typography.page-section}` | 24px | 700 | 1.3 | 섹션 제목 |
| `{typography.page-body}` | 15px | 400 | 1.7 | 본문 |

### Principles

제목은 Gowun Batang 700으로 차분하게, 숫자와 영문은 Google Sans로 또렷하게 쓴다. 강조는 굵기와 코랄 한 곳으로 하고, 제목 밑에 색 띠나 밑줄을 긋지 않는다. eyebrow와 푸터처럼 "정보"인 글자는 모노로 구분한다.

### Note on Font Substitutes

- **Google Sans**: 로컬 설치본을 쓴다. 없으면 시스템 sans-serif(맑은 고딕 영문부, Arial)로 대신한다.
- **Gowun Batang / JetBrains Mono**: 오픈 라이선스(Google Fonts).
- **G마켓 산스 / 코레일 둥근고딕**: 로고 전용. 로고는 아웃라인 SVG를 쓰므로 서체가 없어도 된다.

## Voice & Terminology

현장 엔지니어에게 익숙한 대로 **일반 엔지니어링 용어는 국문 문장 안에서도 영어로 쓴다.** 영어 용어는 혼합 언어 규칙에 따라 Google Sans로 렌더한다. 조사는 그대로 붙인다("RF Matcher가", "Chamber의").

| 쓰지 않는다 | 쓴다 |
|---|---|
| 발전기, RF 발전기, 제너레이터 | RF Generator (RFG 병기 가능) |
| 매처, 매쳐, 매칭기, 정합기 | RF Matcher (문맥상 분명하면 Matcher) |
| 챔버 | Chamber |
| 진공 가변 커패시터 | VVC |
| 반사 전력 보호/출력 저감 | Foldback |
| 점화 프리셋 위치 | Strike (preset) 위치 |

이론 개념어는 한국어가 자연스러우면 한국어로 둔다(반사 계수, 정재파, 공액 정합, 무효전력, 표피효과, 임피던스, 리액턴스). 처음 나올 때 괄호로 영어를 병기해도 좋다.

## Layout

### Slide Grid

- **크기**: Web 1280×720px / PPT 13.333×7.5in(pptxgenjs `LAYOUT_WIDE`).
- **좌우 여백**: `{spacing.margin-x}`(72px = 0.75in) 고정.
- **헤더**: eyebrow 0.46in → 슬라이드 제목 0.72in → (선택) 부제 1.33in. 우상단에 로고(높이 0.34in, 라이트=컬러, 다크=화이트).
- **푸터**: 채운 색 바 없이 상단 hairline 한 줄. 왼쪽 "BENEDU INSIGHT", 가운데 문서 태그라인(모노, 흐리게), 오른쪽 페이지 번호.
- 헤더·푸터 높이는 슬라이드 유형과 상관없이 같다.

### Slide Patterns

1. **Cover** — 라이트, 2-tone 워드마크 + 불릿 + 다크 통계 패널
2. **Agenda** — 라이트, 2열 번호 카드 그리드
3. **Dark 3-Feature Section** — 다크, Signature Ring + 3분할 기능 카드
4. **Profile / Timeline** — 라이트, 세로 타임라인 + 통계 카드
5. **Philosophy / Quote** — 라이트, 라벤더 인용 박스 + 3분할 보조 카드
6. **Curriculum Split** — 왼쪽 30% 다크 레일 + 오른쪽 라이트 모듈 리스트(클래스마다 반복)
7. **Module Grid** — 다크, 4열 카테고리 + 점 불릿 리스트
8. **Terminal Dual Panel** — 다크, 신호등 점 창 헤더 + 2단 리스트
9. **Data Table** — 다크, 태그 행 + 머리글 채움 표
10. **CTA Closing** — 라이트 바탕 + 퍼플 CTA 박스 + Signature Ring

### Spacing System

- **Base unit**: 8px, 반 단계 4px.
- **Tokens**: `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.margin-x}` 72px
- **카드 패딩**: `{spacing.md}`~`{spacing.lg}`(16~24px). 카드 사이 `{spacing.md}`.

### Whitespace Philosophy

구획은 선과 색 띠가 아니라 여백으로 한다. 크림 슬라이드 몇 장 뒤에 다크 슬라이드 한 장을 넣어 숨을 고른다. 섹션 전환·플랫폼 소개·표 슬라이드는 다크로 보낸다.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 — Flat | 테두리·그림자 없음 | 슬라이드 배경, 다크 패널 |
| 1 — Hairline | 1px solid `{colors.hairline}` (다크는 `{colors.hairline-dark}`) | 카드, 표, 칩 |
| 2 — Panel Lift | `0 8px 24px rgba(24, 23, 21, 0.18)` | 표지 다크 통계 패널 한 곳만 |

### Decorative Depth — Signature Ring

로고의 링을 크게 키우고 투명도를 낮춘 원 테두리 1~2겹. 다크(`{colors.ink-black}`)·퍼플(`{colors.brand-purple}`) 풀블리드 패널(표지 통계 패널, 다크 섹션, CTA)의 모서리에만 놓는다. 크림 라이트 배경에는 쓰지 않는다.

## Shapes

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | 슬라이드, 풀블리드 패널 |
| `{rounded.xs}` | 4px | 인라인 코드, 작은 표시 |
| `{rounded.sm}` | 8px | 작은 타일 |
| `{rounded.md}` | 10px | hairline 카드, 다크 카드, 터미널 패널 |
| `{rounded.lg}` | 12px | 인용 박스 |
| `{rounded.xl}` | 16px | 통계 패널, CTA 박스 |
| `{rounded.pill}` | 999px | 칩, CTA 버튼, Signature Ring |

## Components

### Actions

**`button-cta`** — 코랄 pill
- 배경 `{colors.coral}`, 글자 `{colors.white}`, `{rounded.pill}`, 패딩 10px 22px, 높이 40px
- 쓰는 곳: 클로징 슬라이드의 "문의하기", 웹 강의의 "다음 모듈"

**`text-link`**
- 글자 `{colors.coral}`(다크 배경에서는 `{colors.teal}`), 밑줄 없음, 화살표(→) 허용

### Labels

**`chip`** / **`chip-dark`**
- 라이트: 배경 `{colors.surface}`, hairline 테두리, `{rounded.pill}`
- 다크: 배경 `{colors.chip-dark}`, `{colors.hairline-dark}` 테두리. 글자 색으로 앰버·틸 변주 가능

**Eyebrow** — 두 자리 섹션 번호(라이트=그린, 다크=앰버, Bold) + `/` + 영문 대문자 태그(회색), `{typography.eyebrow}`

### Cards & Panels

**`hairline-card`** — 배경 `{colors.white}`(또는 `{colors.surface}`), 1px `{colors.hairline}`, `{rounded.md}`. 좌측 색 띠·그림자 없음.

**`card-dark`** — 배경 `{colors.card-dark}`, 1px `{colors.hairline-dark}`, `{rounded.md}`.

**`stat-panel-dark`** — 표지 전용. 배경 `{colors.ink-black}`, `{rounded.xl}`, Signature Ring 장식. 큰 숫자 `{typography.stat-number}` + 코랄 단위 라벨 + 회색 설명.

**`quote-box`** — 배경 `{colors.lavender}`, `{rounded.lg}`, 인용문 `{typography.slide-subtitle}`. 라이트 슬라이드 전용.

**`cta-box`** — 배경 `{colors.brand-purple}`, 흰 글자, `{rounded.xl}`, 모서리에 Signature Ring.

### Data

**`data-table-dark`** — 다크 배경. 머리글 행만 `{colors.card-dark}` 배경 + `{colors.amber}` 글자(`data-table-dark-header`), 본문 행은 `{colors.hairline-dark}` 구분선.

**`terminal-panel`** — 다크. 신호등 점 3개(Risk 빨강 / 앰버 / 틸) + 모노 헤더, 행 리스트, 하단 가운데 앰버 캡션.

**Timeline** — 세로 hairline 축 + 색 점. 기간(모노) → 제목(볼드) → 설명 순.

### Slide Frame

**`slide-light`** / **`slide-dark`** — 배경 `{colors.cream}` / `{colors.ink-black}`, 좌우 여백 72px, 우상단 로고(컬러 / 화이트).

**`slide-footer`** — 상단 hairline, 왼쪽 "BENEDU INSIGHT", 가운데 태그라인(모노), 오른쪽 `06 / 10`.

### Signature

**`signature-ring`** — 로고 링을 확대·저투명도로 깐 원 테두리. 다크·퍼플 패널 모서리 전용.

## Logo

### 구조

- **심볼**: 완전히 닫힌 원형 링, `{colors.brand-green}`. 닫힌 원은 "빈틈없는 약속"(완결·포용·일관·지속)을 뜻하고, 비어 있는 안쪽은 학습자의 가능성의 자리다.
- **링 비율**: 굵은 도넛 링이다. 기준은 `logo/` 폴더의 현재 파일이며, 브랜드 명세서 v3.2(2026-11-10)도 같은 값으로 고쳤다. v3.1의 "두께 = 외경의 10%"는 폐기한다.
- **워드마크**: 소문자 두 줄 `benedu`(굵게) / `insight`(가늘게), `{colors.brand-purple}`. 국문은 `베네듀` / `인사이트`.
- **배치**: 가로형(링 오른쪽에 워드마크)과 세로형(링 아래 워드마크) 두 가지.
- **색 역할 고정**: 링은 그린, 워드마크는 퍼플. 서로 바꾸지 않는다.

### Versions

| 버전 | 링 | 워드마크 | 쓰는 곳 |
|---|---|---|---|
| color | 그린 | 퍼플 | 밝은 바탕 기본 |
| reverse | 그린 | 흰색 | 어두운 바탕, 영상 인트로 |
| white | 흰색 | 흰색 | 사진·컬러 바탕, 다크 슬라이드 우상단 |
| black | 검정 | 검정 | 팩스·도장·음각, 단색 인쇄 |

### Ring Proportions

`logo/` 폴더의 현재 SVG를 기준으로 한다(2026-11-10 확정). 비율은 반지름 기준이다.

| 쓰임 | 안쪽 / 바깥 반지름 | 링 두께 | 파일 실측 |
|---|---|---|---|
| 락업(가로형·세로형) | 0.6 | 바깥 반지름의 40% (지름의 20%) | 가로형 R56 / r34, 세로형 R75 / r45 |
| 심볼 단독 | 0.52 | 바깥 반지름의 48% (지름의 24%) | R46 / r24 |

심볼 단독은 파비콘·SNS 프로필처럼 작게 쓰이므로 락업보다 링을 조금 더 굵게 둔다. 새 크기가 필요하면 이 비율로 확대·축소하고, 링만 따로 다시 그리지 않는다.

### Clear Space & Minimum Size

- **여백**: 링 두께의 4배 이상(가로형 파일 기준 두께 22 → 여백 88). 이 안에 글자·이미지·경계선을 두지 않는다.
- **최소 크기**: 락업 인쇄 25mm / 디지털 120px, 심볼 인쇄 6mm / 디지털 24px, 파비콘 16px.

### Logo Files

`logo/` 폴더, 모두 아웃라인 SVG.

| 파일 | 내용 |
|---|---|
| `logo/benedu_insight_logo_EN_horizontal_{color,reverse,white,black}.svg` | 영문 가로형 4색 |
| `logo/benedu_insight_logo_EN_vertical_{color,reverse,white,black}.svg` | 영문 세로형 4색 |
| `logo/benedu_insight_logo_KR_horizontal_{color,reverse,white,black}.svg` | 국문 가로형 4색 |
| `logo/benedu_insight_logo_KR_vertical_{color,reverse,white,black}.svg` | 국문 세로형 4색 |
| `logo/benedu_insight_symbol_{color,white,black}.svg` | 심볼(링) 3색 |

### 금지

- 비율 왜곡, 회전·기울기
- 지정 그린·퍼플 외 색으로 재채색, 그린과 퍼플의 역할 교체
- 링에 틈(개방부) 추가, 링 두께·안쪽 지름 비율 변경
- 그림자·광택·입체 효과
- 명도비 4.5:1 미만 배경 위 사용

## Do's and Don'ts

### Do
- 본문 11pt 이상, 제목 26pt 이상을 지킨다
- 코랄은 슬라이드당 1~3곳(버튼·핵심 라벨)까지만 쓴다
- 섹션 전환·플랫폼·표 슬라이드는 다크로 보내 라이트와 리듬을 교차한다
- 카드와 표는 hairline으로만 구획하고, 그림자는 표지 통계 패널에만 쓴다
- 로고는 라이트 배경에 color, 다크 배경에 white(또는 reverse)
- 국문 문장 속 영문·숫자는 Google Sans로 바꿔 쓴다
- 장비·엔지니어링 용어는 영어로 쓴다(RF Generator, RF Matcher, Chamber)

### Don't
- 그린·퍼플을 로고와 2-tone 헤드라인 밖에서 쓰지 않는다
- 제목 아래 색 띠나 밑줄을 긋지 않는다
- 카드 왼쪽에 색 띠를 넣지 않는다
- 본문에 네 번째 서체를 섞지 않는다(EN / KO / MONO 세 가지)
- Signature Ring을 크림 라이트 배경에 쓰지 않는다
- 옛 회사소개 덱의 파랑(`#1C60EF`)·금색(`#D4A017`) 같은 정리 전 색을 다시 쓰지 않는다
- 앰버·틸을 라이트 슬라이드에, 라벤더를 다크 슬라이드에 쓰지 않는다
- 발전기·매처·챔버처럼 장비 용어를 한국어로 옮기지 않는다

## Responsive Behavior

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | 슬라이드는 16:9 비율을 유지한 채 폭에 맞춰 축소. 긴 페이지는 1열 |
| Tablet | 768–1023px | 카드 그리드 2열 |
| Desktop | ≥ 1024px | 슬라이드 1280×720 원본 크기, 카드 그리드 3~4열 |

웹 슬라이드는 비율을 지키며 통째로 축소하고, 슬라이드 안의 배치를 다시 짜지 않는다. 축소해도 본문이 화면에서 10px 밑으로 떨어지면 긴 페이지 형식(강의 모듈)으로 옮긴다.

## Iteration Guide

1. 한 번에 컴포넌트 하나씩 고친다
2. 본문에서는 hex·px 대신 토큰 이름(`{colors.coral}`, `{rounded.md}`, `hairline-card`)으로 말한다
3. 새 슬라이드는 위 10가지 패턴에서 먼저 고르고, 정말 다른 구조일 때만 새로 만든다
4. 새 액센트가 필요하면 코랄 → (다크라면) 앰버·틸 순으로 고르고, 새 색을 더하지 않는다
5. 로고 파일은 고치지 않는다. 새 버전이 필요하면 브랜드 명세서를 먼저 고친다
6. QA 때 `grep -n "발전기\|매처\|매쳐\|매칭기\|챔버"` 결과가 0건인지 확인한다

> 출처: Benedu Insight 브랜드 디자인 명세서 v3.2(로고·인쇄), benedu-presentation 디자인 가이드(슬라이드·웹). 문서 형식은 getdesign.md의 DESIGN.md 구조를 따랐다.
