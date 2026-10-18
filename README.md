<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:fff0f0,100:ffd1fb&height=180&text=Seoyoung%20Kim&animation=fadeIn&fontColor=febef0&fontSize=50" />
</div>

## 👋 About Me

4년차 프론트엔드 개발자 김서영입니다.
바닐라 JS로 흩어져 있던 사내 업무 사이트 8개를 React · TypeScript 단일 플랫폼으로 통합하면서, FSD 아키텍처와 공용 컴포넌트 체계를 설계했습니다.

- 반복되는 화면은 구조로 해결 — 목록 · 권한 · 폼을 공용 데이터 테이블, 권한 모듈, 서버 메타데이터 기반 동적 폼으로 표준화 (29개 페이지 중 24개가 공용 목록 위젯 사용)
- 운영 중인 코드는 단계적으로 개선 — 화면 67곳의 하드코딩 권한 판정을 서버 권한 기반 공용 레이어로 교체하고, 테스트가 없던 저장소에 Vitest · React Testing Library와 MR 자동 검증 도입
- 이 GitHub에는 개인 프로젝트만 공개 — 업무 코드는 보안상 사내 GitLab에서 관리, 상세 내용은 [포트폴리오](https://portfolio.seoyoung.dev)에 정리

## 🚀 Projects

| 프로젝트 | 기간 | 내용 |
| --- | --- | --- |
| **사내 · 고객사 대상 업무 통합 웹 플랫폼** | 2025.01 ~ 현재 | **성과** 레거시 사이트 8개를 단일 React SPA로 통합하고 CI/CD 배포를 1곳으로 일원화, Lighthouse 성능 75 → 95 · LCP 7.6초 → 1.4초<br>**역할** FE 아키텍처(FSD) · 상태 관리 전략 · 공용 데이터 테이블 · 권한 모듈 · 서버 메타데이터 기반 동적 폼 설계 · 구현 (FE 2 · BE 3 · 기획 · 디자인 1) |
| **서버 기반 권한 체계 전환 및 FE 테스트 도입** | 2026.10 | **성과** 하드코딩 권한 판정 67곳을 서버 권한 API 기반 공용 레이어로 교체해 권한 변경을 FE 배포 없이 반영, 컴포넌트 테스트로 기존 운영 버그 발견 · 수정<br>**역할** FE 권한 레이어 설계 · 구현 단독(fail closed, 계정별 권한 캐시 분리), Vitest · RTL과 커밋 · MR 2단계 자동 검증 도입 |
| **레거시 환경 대시보드 구축 및 업무 자동화** | 2023.01 ~ 2024.12 (2년) | **성과** 고객사가 수동으로 정리하던 현황 문서를 대시보드(Chart.js 차트 27개)로 대체, 일일 리포트 자동화<br>**역할** 바닐라 JS · jQuery 환경에서 대시보드 · Excel 추출 구현, 리포트 자동화 리팩토링 · 운영 (FE 1인) |
| **[개인 포트폴리오 사이트](https://github.com/seoyoung-kim-kr/seoyoung-portfolio)** | 2026.01 ~ 현재 | **성과** 코드 배포 없이 글을 작성 · 수정하면 바로 반영되는 포트폴리오 사이트 운영<br>**역할** 설계 · 개발 · 운영 — Next.js 16 (App Router) · Sanity, SSG + 저장 시 on-demand 재검증, 내장 관리자 페이지, HMAC 서명 쿠키 인증 |

프로젝트별 상세 → [portfolio.seoyoung.dev](https://portfolio.seoyoung.dev)

## 🛠️ Tech Stacks

**Language**

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">

**Frontend**

<img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"> <img src="https://img.shields.io/badge/TanStack%20Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white"> <img src="https://img.shields.io/badge/Zustand-443E38?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=for-the-badge&logo=reacthookform&logoColor=white"> <img src="https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white"> <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"> <img src="https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white"> <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">

**Test · CI · Tools**

<img src="https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white"> <img src="https://img.shields.io/badge/Testing%20Library-E33332?style=for-the-badge&logo=testinglibrary&logoColor=white"> <img src="https://img.shields.io/badge/GitLab%20CI-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white"> <img src="https://img.shields.io/badge/Sanity-F03E2F?style=for-the-badge&logo=sanity&logoColor=white"> <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white">

## 📫 Contact

<a href="https://portfolio.seoyoung.dev"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white"></a> <a href="mailto:seoyoung.k.kr@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
