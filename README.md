# 🐾🐱 어디가냥

> **“어디가냥은 쉼이 필요한 모두를 위한 체험 예약 플랫폼입니다.”**

---

## 👩‍💻 팀 소개

| 강희정                                                                         | 고서영                                                                         | 김승민                                                                         | 김영호                                                                         | 김희성                                                                         |
| ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ |
| [@tansxx](https://github.com/tansxx)                                           | [@K0seoyoung](https://github.com/K0seoyoung)                                   | [@KingsMinn](https://github.com/KingsMinn)                                     | [@numi8462](https://github.com/numi8462)                                       | [@huiseong29](https://github.com/huiseong29)                                   |
| <img src="https://avatars.githubusercontent.com/u/159680008?v=4" width="100"/> | <img src="https://avatars.githubusercontent.com/u/134926158?v=4" width="100"/> | <img src="https://avatars.githubusercontent.com/u/134246428?v=4" width="100"/> | <img src="https://avatars.githubusercontent.com/u/135202559?v=4" width="100"/> | <img src="https://avatars.githubusercontent.com/u/175691313?v=4" width="100"/> |

---

## 🔗 배포 주소

https://meowhere.vercel.app/

---

## ⏰ 프로젝트 기간

2025년 05월 27일 ~ 2025년 06월 26일

---

## 🐾 주요 기능

- 🔍 다양한 체험 탐색, 필터, 좋아요 기능
- 🗺️ 위치 기반 체험 지도 탐색
- 📅 캘린더 뷰를 통한 예약일 선택
- 💬 체험 후기 작성, 카카오 공유 기능
- ✏️ 새로운 체험 등록, 관리 기능
- 📊 나의 체험 통계 및 후기 확인 기능
- ⭐ 체험 완료를 통한 다양한 업적 뱃지
- 💻 간편 카카오 로그인 기능

---

## 🛠️ 기술 스택 (Tech Stack)

| 🧩 구분               | 🚀 기술                                                                                                                                                                                                                   |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **언어 / 프레임워크** | ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)    |
| **스타일링**          | ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)                                                                                                     |
| **상태 관리**         | ![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=react-query&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-000000?style=flat-square&logo=Zustand&logoColor=white) |
| **UI 라이브러리**     | ![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)                                                                                                             |
| **폼/유효성 검증**    | ![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)   |
| **애니메이션**        | ![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)                                                                                                         |
| **차트 시각화**       | ![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square&logo=recharts&logoColor=white)                                                                                                                 |
| **3D 렌더링**         | ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)                                                                                                                 |
| **OAuth 인증**        | ![Kakao](https://img.shields.io/badge/Kakao-FFCD00?style=flat-square&logo=kakao&logoColor=black)                                                                                                                          |

---

## 📁 폴더 구조

```bash
MEOWHERE/
├── public/
├── src/
│ ├── app/
│ |   ├─ layout.tsx
│ |   ├─ page.tsx                   # 메인 페이지
│ |   ├─ not-found.tsx
│ |   ├─ middleware.tsx
│ |   ├─ account/                   # 로그인 페이지
│ |   │   ├─ page.tsx
│ |   │   └─ components/
│ |   ├─ activities/               # 체험 상세 및 예약
│ |   │   ├─ page.tsx
│ |   │   └─ [id]//
│ |   │       ├─ page.tsx
│ |   │       └─ components/
│ |   ├─ profile/                 # 사용자 정보 관리
│ |   │   ├─ page.tsx
│ |   │   ├─ components/
│ |   │   ├─ my-info/
│ |   │   ├─ reservations/
│ |   │   ├─ my-activities/
│ |   │   ├─ favorites/
│ |   │   ├─ notifications/
│ |   │   └─ my-reservations/
│ |   └─ api/
│ |
│ ├─ components/
│ |   ├─ layout/
│ |   │   ├─ navbar/
│ |   │   └─ Footer.tsx
│ |   └─ common/               # 공통 컴포넌트
│ ├─ constants/
│ ├─ providers/
│ ├─ services/
│ ├─ store/
│ ├─ hooks/
│ ├─ lib/
│ ├─ types/
│ ├─ utils/
│ └─ styles/
├── .gitignore
├── .prettierrc
├── eslint.config.mjs
├── next.config.ts
├── package.json
├── postcss.config.js
├── tailwind.config.js
├── tsconfig.json
└── README.md
```

---

## 🌱 브랜치 네이밍 규칙

| 브랜치 종류 | 네이밍 규칙 예시                             |
| ----------- | -------------------------------------------- |
| 기능 개발   | `feature/{기능-설명}` → `feature/map-filter` |
| 버그 수정   | `fix/{버그-설명}` → `fix/reservation-button` |
| 문서 작업   | `docs/{문서-내용}` → `docs/readme-update`    |
| 핫픽스      | `hotfix/{이슈-설명}` → `hotfix/deploy-error` |

---

## 🧾 네이밍 규칙

| 항목      | 방식             | 예시                |
| --------- | ---------------- | ------------------- |
| 폴더명    | kebab-case       | user-profile        |
| 컴포넌트  | PascalCase       | MeowCard.tsx        |
| 이미지    | kebab-case       | logo-icon.png       |
| 변수/함수 | camelCase        | fetchMeowData       |
| 환경변수  | UPPER_SNAKE_CASE | NEXT_PUBLIC_API_URL |

---

---

## 🌿 Git Branch 전략

| 브랜치명    | 목적                  |
| ----------- | --------------------- |
| `main`      | 배포 전용 브랜치      |
| `develop`   | 통합 개발 브랜치      |
| `feature/*` | 기능 개발 단위 브랜치 |
| `fix/*`     | 버그 수정 브랜치      |
| `docs/*`    | 문서 관련 브랜치      |

---

## 💬 커밋 메시지 컨벤션

| 태그     | 의미              |
| -------- | ----------------- |
| Feat     | ✨ 기능 추가      |
| Fix      | 🐛 버그 수정      |
| Style    | 💄 스타일 변경    |
| Docs     | 📝 문서 변경      |
| Refactor | 🔨 리팩토링       |
| Test     | ✅ 테스트 코드    |
| Chore    | 🔧 기타 설정 변경 |

### 예시

```bash
✨ Feat: 버튼 컴포넌트 생성
```

---

### 🌈 이모지 가이드

| 이모지 | 의미                |
| ------ | ------------------- |
| 🎨     | 코드 형식/구조 개선 |
| 📰     | 새 파일 추가        |
| ✨     | 새로운 기능         |
| 📝     | 사소한 변경         |
| 💄     | UI / 스타일 수정    |
| 🐎     | 성능 개선           |
| 📚     | 문서 수정           |
| 🐛     | 버그 수정           |
| 🚑     | 핫픽스              |
| 🔥     | 코드 삭제           |
| 🚜     | 구조 변경           |
| 🔨     | 리팩토링            |
| 💎     | 새 릴리즈           |
| 🔖     | 버전 태그           |
| 🚀     | 배포                |

