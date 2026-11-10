---
version: 2.1
name: benedu-atelier-design-system
description: Benedu Insight의 AI 실무 교육 브랜드 benedu atelier(베네듀 아틀리에)의 디자인 시스템. 크림 캔버스(`#FFFAF0`) 위에 잉크 블랙(`#0A0A0A`) 글자와 검정 pill 버튼을 두고, 채도 높은 단색 카드 여섯 가지를 부서 색으로 고정해 쓴다. 로고는 부모 브랜드의 링과 픽셀 심볼을 이어받은 하늘색 단색 마크(`#2BB3F0`)와 소문자 두 줄 워드마크(Bricolage Grotesque 640 / 350)로, 페이지 팔레트와 따로 관리한다. 웹·PPT·PDF의 서체는 benedu_ppt_templates.pptx를 따라 헤드라인은 한국기계연구원 Bold, 본문과 소제목은 에이투지체(A2Z), 실습 프롬프트는 JetBrains Mono.
base: https://getdesign.md/clay/design-md
parent: Benedu Insight

colors:
  primary: "#0A0A0A"
  on-primary: "#FFFFFF"
  ink: "#0A0A0A"
  body: "#3A3A3A"
  muted: "#6A6A6A"
  on-dark: "#F5F0E0"
  canvas: "#FFFAF0"
  surface-soft: "#FAF5E8"
  surface-card: "#F5F0E0"
  surface-strong: "#EBE6D6"
  surface-dark: "#0A1A1A"
  hairline: "#E5E5E5"
  brand-pink: "#FF4D8B"
  brand-peach: "#FFB084"
  brand-ochre: "#E8B94A"
  brand-lavender: "#B8A4ED"
  brand-mint: "#A4D4C5"
  brand-teal: "#1A3A3A"
  brand-coral: "#FF6B5A"
  logo-sky: "#2BB3F0"
  logo-sky-light: "#7DD0F7"
  logo-sky-deep: "#1698DE"
  logo-navy: "#0B2A4A"
  logo-slate: "#4F6B86"
  logo-mist: "#B7C8D9"

department-colors:
  sales: "{colors.brand-pink}"
  purchasing: "{colors.brand-ochre}"
  production-planning: "{colors.brand-lavender}"
  production-engineering: "{colors.brand-mint}"
  quality: "{colors.brand-peach}"
  common: "{colors.brand-teal}"

typography:
  display-xl:
    fontFamily: "KIMM_Bold, '한국기계연구원_Bold', 'A2Z', Pretendard, sans-serif"
    fontSize: 64px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -1.2px
  display-lg:
    fontFamily: "KIMM_Bold, '한국기계연구원_Bold', 'A2Z', Pretendard, sans-serif"
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: -0.9px
  display-md:
    fontFamily: "KIMM_Bold, '한국기계연구원_Bold', 'A2Z', Pretendard, sans-serif"
    fontSize: 40px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: -0.75px
  display-sm:
    fontFamily: "KIMM_Bold, '한국기계연구원_Bold', 'A2Z', Pretendard, sans-serif"
    fontSize: 28px
    fontWeight: 700
    lineHeight: 1.25
    letterSpacing: -0.5px
  title:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 20px
    fontWeight: 700
    lineHeight: 1.35
    letterSpacing: 0
  body-lg:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0
  body-md:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: 0
  body-emphasis:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 16px
    fontWeight: 600
    lineHeight: 1.65
    letterSpacing: 0
  caption-md:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 0
  caption-uppercase:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 12px
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 2px
    textTransform: uppercase
  button-md:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 15px
    fontWeight: 600
    lineHeight: 1.0
    letterSpacing: 0
  prompt:
    fontFamily: "'JetBrains Mono', monospace"
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.6
    letterSpacing: 0
  ppt-cover:
    fontFamily: "KIMM_Bold, '한국기계연구원_Bold', 'A2Z', Pretendard, sans-serif"
    fontSize: 40pt
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.5pt
  ppt-headline:
    fontFamily: "KIMM_Bold, '한국기계연구원_Bold', 'A2Z', Pretendard, sans-serif"
    fontSize: 27pt
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: -0.5pt
  ppt-subhead:
    fontFamily: "KIMM_Bold, '한국기계연구원_Bold', 'A2Z', Pretendard, sans-serif"
    fontSize: 24pt
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 0
  ppt-title:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 19pt
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: 0
  ppt-card-title:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 14pt
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: 0
  ppt-body-emphasis:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 14pt
    fontWeight: 600
    lineHeight: 1.0
    letterSpacing: 0
  ppt-body:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 12pt
    fontWeight: 400
    lineHeight: 1.55
    letterSpacing: 0
  ppt-body-sm:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 10pt
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 0
  ppt-eyebrow:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 11pt
    fontWeight: 700
    lineHeight: 1.0
    letterSpacing: 2pt
    textTransform: uppercase
  ppt-caption:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 9pt
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0
  ppt-footer:
    fontFamily: "'A2Z', '에이투지체', Pretendard, sans-serif"
    fontSize: 8pt
    fontWeight: 400
    lineHeight: 1.0
    letterSpacing: 4pt
    textTransform: uppercase
  logo-wordmark:
    fontFamily: "'Bricolage Grotesque'"
    fontWeight: "640 (benedu) / 350 (atelier)"
    letterSpacing: -2%
    textTransform: lowercase
  logo-tagline:
    fontFamily: "KIMM_Bold"
    fontWeight: 700
    letterSpacing: 0

rounded:
  none: 0px
  xs: 6px
  sm: 8px
  md: 12px
  lg: 16px
  xl: 24px
  pill: 9999px

spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  xxl: 48px
  section: 96px

components:
  button-primary:
    backgroundColor: "{colors.primary}"
    textColor: "{colors.on-primary}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 12px 22px
    height: 44px
  button-primary-disabled:
    backgroundColor: "{colors.surface-strong}"
    textColor: "{colors.muted}"
    rounded: "{rounded.pill}"
  button-secondary:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.button-md}"
    rounded: "{rounded.pill}"
    padding: 12px 22px
    height: 44px
  button-text-link:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.body-emphasis}"
    padding: 4px 0
  department-chip:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.caption-md}"
    rounded: "{rounded.pill}"
    padding: 6px 12px
  feature-card:
    backgroundColor: "{colors.brand-pink}"
    textColor: "{colors.ink}"
    typography: "{typography.title}"
    rounded: "{rounded.xl}"
    padding: 32px
  feature-card-dark:
    backgroundColor: "{colors.brand-teal}"
    textColor: "{colors.on-primary}"
    typography: "{typography.title}"
    rounded: "{rounded.xl}"
    padding: 32px
  case-card:
    backgroundColor: "{colors.surface-card}"
    textColor: "{colors.ink}"
    typography: "{typography.body-md}"
    rounded: "{rounded.lg}"
    padding: 24px
  prompt-box:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-dark}"
    typography: "{typography.prompt}"
    rounded: "{rounded.md}"
    padding: 16px 20px
  lecture-slide:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.ink}"
    typography: "{typography.display-md}"
    rounded: "{rounded.none}"
    padding: 64px
  logo-lockup:
    backgroundColor: "{colors.canvas}"
    textColor: "{colors.logo-navy}"
    typography: "{typography.logo-wordmark}"
  logo-lockup-white:
    backgroundColor: "{colors.surface-dark}"
    textColor: "{colors.on-primary}"
    typography: "{typography.logo-wordmark}"
  logo-symbol:
    backgroundColor: "{colors.logo-sky}"
    rounded: "{rounded.none}"
---

## Overview

benedu atelier는 Benedu Insight의 **AI 실무 교육 브랜드**다. 반도체 플라즈마·RF 교육(Benedu Insight)과 구분해, 중소제조기업 실무자가 자기 업무에 AI를 직접 써 보는 교육을 이 이름으로 운영한다. 아틀리에(공방)라는 이름처럼 강의를 듣는 곳이 아니라 각자 자기 업무를 빚어 보는 곳이고, 디자인의 출발점인 Clay(점토)와도 이어진다.

시스템 전체는 **크림 캔버스**(`{colors.canvas}` — `#FFFAF0`) 위에 놓인다. 글자와 기본 버튼은 **잉크 블랙**(`{colors.ink}` — `#0A0A0A`) 하나로 처리하고, 색은 **채도 높은 단색 카드**가 맡는다. 카드 색 여섯 가지는 장식이 아니라 **부서 색**이다. 영업은 언제나 핑크, 품질은 언제나 피치로, 모든 교재에서 같은 뜻으로 쓴다.

**로고만은 별도 팔레트**를 쓴다. 부모 브랜드의 굵은 링과 픽셀 심볼을 이어받은 **하늘색 단색 마크**(`{colors.logo-sky}` — `#2BB3F0`)에, 소문자 두 줄 워드마크 `benedu` / `atelier`를 붙인다. 페이지는 크림과 부서 색, 로고는 하늘색이라는 구분을 섞지 않는다.

**Key Characteristics:**
- 크림 캔버스(`{colors.canvas}`)와 잉크 블랙(`{colors.ink}`)이 화면의 대부분을 맡는다. 섹션 리듬은 크림 → 단색 카드 → 크림
- 기본 버튼은 검정 pill(`button-primary`). 색 버튼은 없다
- 브랜드 색 여섯 가지는 부서 색으로 고정(`department-colors`). 한 섹션에 한 색
- 헤드라인은 한국기계연구원 Bold(좁은 자간), 본문·소제목·라벨은 에이투지체(A2Z), 따라 칠 프롬프트는 JetBrains Mono. 웹·PPT·PDF 모두 같은 서체
- 카드는 `{rounded.xl}`(24px)로 둥글게, 버튼과 칩은 `{rounded.pill}`
- 로고는 하늘색 링 + 픽셀 사각형 세 개 + 소문자 두 줄 워드마크. 국문·영문 태그라인 두 가지. 페이지 팔레트와 따로 관리
- 강의 슬라이드는 좌상단 부서 칩, 우하단 작은 링 심볼

## Colors

### Brand & Accent
- **Ink Black** (`{colors.primary}` — `#0A0A0A`): 기본 버튼 배경, 헤드라인, 링크. 이 시스템의 유일한 "행동" 색이다.
- **Pink** (`{colors.brand-pink}` — `#FF4D8B`): 영업·마케팅 부서 색. feature 카드 배경.
- **Ochre** (`{colors.brand-ochre}` — `#E8B94A`): 구매·자재 부서 색.
- **Lavender** (`{colors.brand-lavender}` — `#B8A4ED`): 생산관리 부서 색.
- **Mint** (`{colors.brand-mint}` — `#A4D4C5`): 생산기술 부서 색.
- **Peach** (`{colors.brand-peach}` — `#FFB084`): 품질 부서 색.
- **Deep Teal** (`{colors.brand-teal}` — `#1A3A3A`): 경영지원·공통 부서 색. 이 카드만 흰 글자.
- **Coral** (`{colors.brand-coral}` — `#FF6B5A`): 예비 강조색. 부서 색이 아니므로 부서 표시에는 쓰지 않는다.

### Logo
- **Logo Sky** (`{colors.logo-sky}` — `#2BB3F0`): 링, 첫 번째 픽셀, 흰색 로고의 `atelier`와 가로선.
- **Logo Sky Light** (`{colors.logo-sky-light}` — `#7DD0F7`): 가장 먼 픽셀, 기본 로고의 태그라인 가로선.
- **Logo Sky Deep** (`{colors.logo-sky-deep}` — `#1698DE`): 링에 붙은 픽셀, 기본 로고의 `atelier`.
- **Logo Navy** (`{colors.logo-navy}` — `#0B2A4A`): 기본 로고의 `benedu`.
- **Logo Slate** (`{colors.logo-slate}` — `#4F6B86`): 기본 로고의 태그라인.
- **Logo Mist** (`{colors.logo-mist}` — `#B7C8D9`): 흰색 로고의 태그라인.

로고 색은 로고 파일 안에서만 쓴다. 페이지의 버튼·카드·제목에 하늘색을 끌어오지 않는다.

### Surface
- **Canvas** (`{colors.canvas}` — `#FFFAF0`): 모든 페이지와 슬라이드의 기본 바탕.
- **Surface Soft** (`{colors.surface-soft}` — `#FAF5E8`): 크림보다 한 단계 짙은 섹션 띠.
- **Surface Card** (`{colors.surface-card}` — `#F5F0E0`): 사례 카드, 부서 칩 바탕.
- **Surface Strong** (`{colors.surface-strong}` — `#EBE6D6`): 비활성 버튼, 표 머리글.
- **Surface Dark** (`{colors.surface-dark}` — `#0A1A1A`): 프롬프트 박스, 어두운 슬라이드. 이 바탕 위의 로고는 반드시 `logo-lockup-white`.
- **Hairline** (`{colors.hairline}` — `#E5E5E5`): 1px 구분선, 표 테두리.

### Text
- **Ink** (`{colors.ink}` — `#0A0A0A`): 제목, 본문 강조, 버튼 글자.
- **Body** (`{colors.body}` — `#3A3A3A`): 기본 본문.
- **Muted** (`{colors.muted}` — `#6A6A6A`): 캡션, 출처, 보조 설명.
- **On Primary** (`{colors.on-primary}` — `#FFFFFF`): 검정 버튼과 딥틸 카드 위 글자.
- **On Dark** (`{colors.on-dark}` — `#F5F0E0`): 프롬프트 박스 글자. 순백 대신 크림빛으로 눈부심을 줄인다.

### Semantic

| 부서 | 토큰 | 색 | 카드 글자 |
|---|---|---|---|
| 영업·마케팅 | `{department-colors.sales}` | Pink `#FF4D8B` | ink |
| 구매·자재 | `{department-colors.purchasing}` | Ochre `#E8B94A` | ink |
| 생산관리 | `{department-colors.production-planning}` | Lavender `#B8A4ED` | ink |
| 생산기술 | `{department-colors.production-engineering}` | Mint `#A4D4C5` | ink |
| 품질 | `{department-colors.quality}` | Peach `#FFB084` | ink |
| 경영지원·공통 | `{department-colors.common}` | Deep Teal `#1A3A3A` | white |

## Typography

### Font Family

웹 페이지, PPT, PDF 등 모든 프레젠테이션 서체는 `benedu_ppt_templates.pptx`의 구성을 기본으로 한다.

- **한국기계연구원 Bold**(`KIMM_Bold`, Office 이름 `한국기계연구원_Bold`): 표지와 슬라이드 헤드라인. 자간을 -0.5pt 좁혀 단단하게 쓴다. 한 문장 안에서 핵심 단어만 다른 색으로 강조하는 방식과 잘 맞는다.
- **에이투지체**(`A2Z`, Office 이름 `에이투지체 4 Regular` / `에이투지체 5 Medium` / `A2Z 6 SemiBold` / `에이투지체 7 Bold`): 소제목, 카드 제목, 본문, 라벨 전부. 굵기 번호로 역할을 나눈다. 4 Regular는 본문, 5 Medium·6 SemiBold는 본문 강조, 7 Bold는 소제목과 대문자 라벨.
- **JetBrains Mono**: 수강생이 그대로 따라 칠 프롬프트에만 쓴다.

로고에는 전용 서체가 따로 있다. 워드마크는 Bricolage Grotesque를 소문자로, 윗줄 640·아랫줄 350 굵기로 쓴다. 태그라인은 국문·영문 모두 한국기계연구원 Bold다. Bricolage Grotesque는 로고 밖에서 쓰지 않는다.

### Hierarchy — Web

| Token | Size | Font · Weight | Line Height | Letter Spacing | Use |
|---|---|---|---|---|---|
| `{typography.display-xl}` | 64px | KIMM Bold | 1.15 | -1.2px | 표지, 히어로 헤드라인 |
| `{typography.display-lg}` | 48px | KIMM Bold | 1.15 | -0.9px | 페이지 제목 |
| `{typography.display-md}` | 40px | KIMM Bold | 1.2 | -0.75px | 섹션 헤드라인 |
| `{typography.display-sm}` | 28px | KIMM Bold | 1.25 | -0.5px | 소제목, 수치 강조(`10분 → 0.1분`) |
| `{typography.title}` | 20px | A2Z 700 | 1.35 | 0 | 카드 제목 |
| `{typography.body-lg}` | 18px | A2Z 400 | 1.65 | 0 | 리드 문단 |
| `{typography.body-md}` | 16px | A2Z 400 | 1.65 | 0 | 기본 본문 |
| `{typography.body-emphasis}` | 16px | A2Z 600 | 1.65 | 0 | 본문 속 강조, 텍스트 링크 |
| `{typography.caption-md}` | 14px | A2Z 400 | 1.5 | 0 | 캡션, 부서 칩, 출처 |
| `{typography.caption-uppercase}` | 12px | A2Z 700 | 1.3 | 2px | 영문 아이브로우(대문자) |
| `{typography.button-md}` | 15px | A2Z 600 | 1.0 | 0 | 버튼 글자 |
| `{typography.prompt}` | 14px | JetBrains Mono 400 | 1.6 | 0 | 실습 프롬프트 |

### Hierarchy — PPT / PDF (16:9, 960×540pt)

pptx 템플릿에서 실제로 쓰인 크기를 그대로 옮겼다. 1920×1080px 웹 슬라이드에서는 pt 값을 2배 해 px로 쓴다.

| Token | Size | Office Font | Line Height | Spacing | Use |
|---|---|---|---|---|---|
| `{typography.ppt-cover}` | 40pt | 한국기계연구원_Bold | 1.1 | -0.5pt | 표지 헤드라인 |
| `{typography.ppt-headline}` | 27pt | 한국기계연구원_Bold | 1.2 | -0.5pt | 슬라이드 헤드라인 |
| `{typography.ppt-subhead}` | 24pt | 한국기계연구원_Bold | 1.0 | 0 | 비교 슬라이드 소제목 |
| `{typography.ppt-title}` | 19pt | 에이투지체 7 Bold | 1.3 | 0 | 본문 블록 제목 |
| `{typography.ppt-card-title}` | 14pt | 에이투지체 7 Bold | 1.1 | 0 | 카드·단계 제목 |
| `{typography.ppt-body-emphasis}` | 14pt | A2Z 6 SemiBold | 1.0 | 0 | 체크리스트, 강조 항목 |
| `{typography.ppt-body}` | 12pt | 에이투지체 4 Regular | 1.55 | 0 | 본문 |
| `{typography.ppt-body-sm}` | 10pt | 에이투지체 4 Regular | 1.4 | 0 | 카드 설명 |
| `{typography.ppt-eyebrow}` | 11pt | 에이투지체 7 Bold | 1.0 | 2pt | 섹션 라벨(대문자) |
| `{typography.ppt-caption}` | 9pt | 에이투지체 4 Regular | 1.2 | 0 | 캡션, 페이지 번호 |
| `{typography.ppt-footer}` | 8pt | 에이투지체 4 Regular | 1.0 | 4pt | 푸터 브랜드 표기(대문자) |

### Principles

헤드라인은 한국기계연구원 Bold로 짧고 단단하게, 본문은 에이투지체 4 Regular로 넉넉하게 쓴다. 강조는 에이투지체 굵기 번호(4 → 6 → 7)로 올리고, 기울임체는 쓰지 않는다. 대문자 자간(2pt)은 영문 라벨과 푸터에서만 쓴다. 헤드라인의 핵심 단어 하나는 해당 부서 색 형광펜(글자 아래 40% 높이 띠)으로 강조할 수 있다. 글자 색은 바꾸지 않고, 한 슬라이드에 한 번만 쓴다.

### Note on Font Substitutes

- **한국기계연구원 Bold / 에이투지체**: 무료 배포 서체. PPT를 다른 PC에서 열 때는 서체를 파일에 포함해 저장하거나 PDF로 내보낸다. 웹에서는 서체 파일을 함께 올리거나, 없으면 Pretendard로 대신한다.
- **Pretendard**: 두 서체가 없는 환경의 공통 대체 서체. 헤드라인은 Pretendard 800, 본문은 400.
- **Bricolage Grotesque**: 로고 전용. 로고는 아웃라인 SVG를 쓰므로 서체가 없어도 된다.

## Layout

### Spacing System

- **Base unit**: 8px, 반 단계 4px.
- **Tokens**: `{spacing.xxs}` 4px · `{spacing.xs}` 8px · `{spacing.sm}` 12px · `{spacing.md}` 16px · `{spacing.lg}` 24px · `{spacing.xl}` 32px · `{spacing.xxl}` 48px · `{spacing.section}` 96px
- **Section padding**: 데스크톱에서 섹션 사이 `{spacing.section}`(96px), 모바일에서 `{spacing.xxl}`(48px).
- **Card padding**: feature 카드 `{spacing.xl}`(32px), 사례 카드 `{spacing.lg}`(24px), 프롬프트 박스 `{spacing.md}`(16px).
- **Gutter**: 카드 사이 `{spacing.lg}`(24px).

### Grid & Container

- **긴 스크롤 페이지**: 본문 최대 폭 1120px, 섹션 바탕은 화면 끝까지.
- **사례 카드 그리드**: 데스크톱 3열, 태블릿 2열, 모바일 1열.
- **강의 슬라이드(16:9)**: 1920×1080 기준, 바깥 여백 64px. 좌상단 `department-chip`, 우하단 `logo-symbol`(높이 40px).
- **실습 안내서**: 단계 번호(실제 순서일 때만) → `prompt-box` → 결과 예시 이미지.

### Whitespace Philosophy

크림 바탕이 쉬는 자리이고, 단색 카드가 리듬을 만든다. 카드 안은 꽉 채우지 않는다. 사례 이름, 걸린 시간 전후, 쓴 도구 세 가지만 담고, 나머지는 카드 밖 본문으로 뺀다.

## Elevation & Depth

| Level | Treatment | Use |
|---|---|---|
| 0 — Flat | 테두리·그림자 없음 | 섹션 띠, 단색 feature 카드, 슬라이드 |
| 1 — Hairline | 1px solid `{colors.hairline}` | 사례 카드, 표, 보조 버튼 |
| 2 — Soft Lift | `0 2px 8px rgba(10, 10, 10, 0.06)` | 화면 위에 뜨는 메뉴, 팝오버 |

시스템은 거의 평면이다. 깊이는 그림자보다 **바탕색 대비**(크림 위의 단색 카드, 크림 위의 딥 다크 프롬프트 박스)로 만든다.

## Shapes

### Border Radius Scale

| Token | Value | Use |
|---|---|---|
| `{rounded.none}` | 0px | 슬라이드 프레임, 로고 |
| `{rounded.xs}` | 6px | 작은 태그, 인라인 코드 |
| `{rounded.sm}` | 8px | 이미지 썸네일 |
| `{rounded.md}` | 12px | 프롬프트 박스, 입력창 |
| `{rounded.lg}` | 16px | 사례 카드, 결과 예시 이미지 |
| `{rounded.xl}` | 24px | feature 카드 |
| `{rounded.pill}` | 9999px | 버튼, 부서 칩 |

버튼과 칩은 완전히 둥글게(pill), 카드는 크게 둥글게(24px) 쓴다. 각진 버튼은 이 브랜드가 아니다.

## Components

### Buttons

**`button-primary`** — 검정 pill
- 배경 `{colors.primary}`, 글자 `{colors.on-primary}`, `{typography.button-md}`, 패딩 12px 22px, 높이 44px, `{rounded.pill}`
- 비활성 `button-primary-disabled` — 배경 `{colors.surface-strong}`, 글자 `{colors.muted}`
- 쓰는 곳: 수강 신청, 자료 받기, 실습 시작

**`button-secondary`** — 외곽선 pill
- 배경 `{colors.canvas}`, 글자 `{colors.ink}`, 1.5px `{colors.ink}` 테두리, 나머지는 `button-primary`와 같음
- 쓰는 곳: 커리큘럼 보기, 사례 더 보기

**`button-text-link`**
- 글자 `{colors.ink}`, `{typography.body-emphasis}`, 밑줄
- 쓰는 곳: 카드와 본문 안의 "자세히 보기"

### Cards & Containers

**`feature-card`** — 부서 색 단색 카드
- 배경은 부서 색 하나(`department-colors`), 글자 `{colors.ink}`, `{rounded.xl}`, 패딩 32px
- 내용: 사례 이름(`{typography.title}`), 걸린 시간 전후(`{typography.display-sm}`, 예: `10분 → 0.1분`), 쓴 도구(`{typography.caption-md}`)
- 경영지원·공통은 `feature-card-dark` — 배경 `{colors.brand-teal}`, 글자 `{colors.on-primary}`

**`case-card`** — 사례 목록 카드
- 배경 `{colors.surface-card}`, 1px `{colors.hairline}`, `{rounded.lg}`, 패딩 24px
- 내용: `department-chip`, 사례 제목(`{typography.title}`), 패턴 태그

**`prompt-box`** — 실습 프롬프트
- 배경 `{colors.surface-dark}`, 글자 `{colors.on-dark}`, `{typography.prompt}`, `{rounded.md}`, 패딩 16px 20px
- 오른쪽 위에 복사 버튼. 수강생이 그대로 따라 칠 문장만 넣는다

**`lecture-slide`** — 16:9 강의 슬라이드
- 배경 `{colors.canvas}`, 헤드라인 `{typography.ppt-headline}`(1920px 웹 슬라이드에서는 54px), 본문 `{typography.ppt-body}`, 바깥 여백 64px
- 좌상단 `department-chip`, 우하단 `logo-symbol`

### Labels

**`department-chip`** — 색 점 + 부서명
- 배경 `{colors.surface-card}`, 글자 `{colors.ink}`, `{typography.caption-md}`, `{rounded.pill}`, 패딩 6px 12px
- 왼쪽에 8px 원형 점, 색은 해당 부서 색

### Signature Components

**`logo-lockup`** — 기본 로고(밝은 바탕)
- 하늘색 링(`{colors.logo-sky}`) + 픽셀 사각형 세 개(`{colors.logo-sky}`, `{colors.logo-sky-light}`, `{colors.logo-sky-deep}`)
- 워드마크 `benedu`(`{colors.logo-navy}`, 640) / `atelier`(`{colors.logo-sky-deep}`, 350), `{typography.logo-wordmark}`
- 국문 태그라인 "기업실무활용 AI 교육"(`{colors.logo-slate}`, `{typography.logo-tagline}`), 왼쪽 정렬, 오른쪽에 `{colors.logo-sky-light}` 가로선을 워드마크 끝까지
- 영문 태그라인 "Practical AI Training for Business"(같은 색·서체). 워드마크 폭에 꽉 맞추고 가로선은 없다
- 파일: `logo/benedu_atelier_logo_2line.svg`(국문), `logo/benedu_atelier_logo_2line_en.svg`(영문)

**`logo-lockup-white`** — 어두운 바탕용
- `benedu` `{colors.on-primary}`, `atelier` `{colors.logo-sky}`, 태그라인 `{colors.logo-mist}`, 가로선 `{colors.logo-sky}`. 링과 픽셀은 기본과 같다
- 파일: `logo/benedu_atelier_logo_2line_white.svg`(국문), `logo/benedu_atelier_logo_2line_en_white.svg`(영문)

**`logo-symbol`** — 링 + 픽셀만 있는 정사각 심볼
- 512×512, 투명 배경. 밝은 바탕과 어두운 바탕 모두 그대로 쓴다
- 파일: `logo/benedu_atelier_symbol.svg`

## Do's and Don'ts

### Do
- 부서 색 매핑(`department-colors`)을 모든 교재에서 똑같이 지킨다
- 한 섹션의 feature 카드는 한 가지 부서 색만 쓴다. 여러 색을 섞는 것은 부서 목차·지도처럼 부서 전체를 보여 줄 때뿐이다
- 기본 버튼은 `button-primary`(검정 pill) 하나로 통일한다
- 수강생이 따라 칠 문장은 항상 `prompt-box`에 넣는다
- 실습 단계에는 실제 화면이나 결과물 이미지를 함께 넣는다
- 어두운 바탕(`{colors.surface-dark}`, `{colors.brand-teal}`)에는 `logo-lockup-white`를 쓴다
- 국문 자료에는 국문 태그라인 로고, 영문 자료에는 영문 태그라인 로고를 쓴다

### Don't
- 카드마다 다른 색을 무작위로 쓰지 않는다
- 로고 하늘색(`logo-*`)을 버튼, 카드, 제목 같은 페이지 요소에 쓰지 않는다
- 링을 그라디언트나 하늘색 계열이 아닌 색으로 칠하지 않는다
- 픽셀 사각형 세 개의 위치와 링의 파인 자리를 바꾸지 않는다
- 워드마크를 대문자로 쓰거나 두 줄의 굵기 대비를 없애지 않는다
- 이모지를 섹션 표시로 쓰지 않는다
- Bricolage Grotesque를 로고 밖에서 쓰지 않는다
- 한 슬라이드에서 헤드라인 형광펜 강조를 두 번 이상 쓰지 않고, 강조를 위해 글자 색을 바꾸지 않는다

## Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
|---|---|---|
| Mobile | < 768px | 1열. 섹션 간격 48px. `display-xl`은 40px로 |
| Tablet | 768–1023px | 사례 카드 2열. `display-xl`은 52px로 |
| Desktop | ≥ 1024px | 사례 카드 3열. 본문 최대 폭 1120px |

### Touch Targets

버튼과 칩은 모바일에서 높이 44px 이상을 지킨다. `prompt-box`의 복사 버튼도 44×44px 터치 영역을 둔다.

### Logo Sizes

- 두 줄 로고: 태그라인이 읽히려면 높이 150px 이상. 그보다 작은 자리에는 `logo-symbol`을 쓴다
- 심볼: 16px 이상(파비콘)
- 캔버스: 두 줄 로고 1613×684, 심볼 512×512, 모두 투명 배경

## Logo Files

| 파일 | 용도 |
|---|---|
| `logo/benedu_atelier_logo_2line.svg` | 기본(밝은 바탕). 워드마크는 아웃라인, 태그라인은 텍스트(KIMM_Bold 필요) |
| `logo/benedu_atelier_logo_2line_outlined.svg` | 기본, 전부 아웃라인. 웹·인쇄·서체 없는 PC |
| `logo/benedu_atelier_logo_2line_white.svg` | 어두운 바탕용. 태그라인은 텍스트 |
| `logo/benedu_atelier_logo_2line_white_outlined.svg` | 어두운 바탕용, 전부 아웃라인 |
| `logo/benedu_atelier_logo_2line_en.svg` | 영문 태그라인, 밝은 바탕. 태그라인은 텍스트 |
| `logo/benedu_atelier_logo_2line_en_outlined.svg` | 영문 태그라인, 밝은 바탕, 전부 아웃라인 |
| `logo/benedu_atelier_logo_2line_en_white.svg` | 영문 태그라인, 어두운 바탕. 태그라인은 텍스트 |
| `logo/benedu_atelier_logo_2line_en_white_outlined.svg` | 영문 태그라인, 어두운 바탕, 전부 아웃라인 |
| `logo/benedu_atelier_symbol.svg` | 심볼. 파비콘, 슬라이드 구석 마크 |
| `logo/benedu_atelier_logo_2line.figcraft` | FigCraft 원본(국문 기본·흰색, 영문 기본·흰색, 심볼 다섯 프레임) |

아직 없는 파일: 작은 크기용 태그라인 없는 로고.

## Iteration Guide

1. 한 번에 컴포넌트 하나씩 고친다
2. 본문에서는 hex·px 대신 토큰 이름(`{colors.ink}`, `{rounded.xl}`, `feature-card`)으로 말한다
3. 새 상태는 프론트매터에 별도 컴포넌트(`-disabled`, `-dark`)로 추가하고 본문 속에 묻지 않는다
4. 본문 기본은 `{typography.body-md}`, 강조는 `{typography.body-emphasis}`. 디스플레이 크기는 진짜 제목에만 쓴다
5. 새 섹션 바탕은 `{colors.canvas}` / `{colors.surface-soft}` / 부서 색 카드 / `{colors.surface-dark}` 중에서만 고른다
6. 새 부서가 생기면 `department-colors`에 먼저 추가하고, 기존 색을 다른 뜻으로 재사용하지 않는다

> 이 디자인 시스템은 getdesign.md의 Clay 분석을 출발점으로 삼은 독자 해석이며, Clay와 관련이 없다. 문서 형식은 getdesign.md의 DESIGN.md 구조를 따랐다.
