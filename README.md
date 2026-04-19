read me[README.md](https://github.com/user-attachments/files/26871087/README.md)
# y-BE Design System

> 근태관리의 Begin부터 End까지 — 관리자 페이지 공식 디자인 시스템

[![Design System](https://img.shields.io/badge/Design%20System-v2.0-1E52CC?style=flat-square)](https://your-username.github.io/y-be-design-system/)
[![License](https://img.shields.io/badge/License-Internal-gray?style=flat-square)]()

---

## 🔗 바로가기

**[→ 디자인 시스템 문서 보기](https://your-username.github.io/y-be-design-system/)**

---

## 개요

y-BE 관리자 페이지의 모든 UI 컴포넌트, 색상, 타이포그래피, 레이아웃 패턴을 정의하는 단일 소스 오브 트루스(Single Source of Truth)입니다.

신규 화면 설계 및 프로토타입 제작 시 이 문서의 토큰과 컴포넌트 규칙을 기준으로 합니다.

---

## 포함 항목

| 카테고리 | 항목 |
|---|---|
| **Foundation** | 색상 시스템, 타이포그래피, 스페이싱, 레이아웃 치수 |
| **Components** | 버튼, 배지/칩, 폼 요소, 테이블, 카드/통계, 모달 |
| **Patterns** | 레이아웃 구조, 상단바, 사이드바, 근태 현황 행, 휴가 관리 |
| **Tokens** | 전체 CSS 변수 목록 |

---

## 핵심 토큰

```css
--primary:        #1E52CC;   /* 브랜드 메인 컬러 */
--sidebar-bg:     #2D3A8C;   /* 사이드바 / 테이블 헤더 */
--sidebar-active: #1E3A8A;   /* 사이드바 활성 항목 */
--danger:         #DC2626;
--success:        #16A34A;
--warning:        #D97706;

--sidebar-width:  130px;
--topbar-height:  52px;
--input-height:   34px;
--btn-height:     34px;
--btn-height-sm:  28px;
```

---

## 파일 구조

```
y-be-design-system/
├── index.html   ← 디자인 시스템 전체 문서 (단일 파일)
└── README.md
```

---

## 업데이트 이력

| 버전 | 날짜 | 내용 |
|---|---|---|
| v2.0 | 2026-04-19 | 최초 문서화 — 컴포넌트 전체 정의 |

---

> 문의: y-BE 서비스 기획 담당
