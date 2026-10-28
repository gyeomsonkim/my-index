# inventory

갱신: 2026-10-28T06:01:23.717Z
대상: user:gyeomsonkim
레포 15개 · 브랜치 30개 · 배포 환경 작성됨 0개

| 레포 | 브랜치 | 기본 | 마지막 push | 배포 환경 |
|---|---|---|---|---|
| front_5th_chapter1-1 | gh-pages |  | 2025-03-28 |  |
| front_5th_chapter1-1 | main | ✓ | 2025-03-28 |  |
| front_5th_chapter1-3 | gh-pages |  | 2025-04-12 |  |
| front_5th_chapter1-3 | main | ✓ | 2025-04-12 |  |
| front_5th_chapter1-2 | gh-pages |  | 2025-04-03 |  |
| front_5th_chapter1-2 | main | ✓ | 2025-04-03 |  |
| front-5th-4-1_ktg | main | ✓ | 2025-05-29 |  |
| front_5th_chapter2-1 | gh-pages |  | 2025-04-18 |  |
| front_5th_chapter2-1 | main | ✓ | 2025-04-18 |  |
| front_5th_chapter2-2 | main | ✓ | 2025-04-24 |  |
| front_5th_chapter2-3 | main | ✓ | 2025-05-02 |  |
| front_5th_chapter3-1 | easy |  | 2025-05-15 |  |
| front_5th_chapter3-1 | hard |  | 2025-05-15 |  |
| front_5th_chapter3-1 | main | ✓ | 2025-05-15 |  |
| front_5th_chapter3-1 | medium |  | 2025-05-15 |  |
| load_generate_AI | main | ✓ | 2025-11-18 |  |
| front_5th_chapter3-2 | main | ✓ | 2025-05-20 |  |
| front_5th_chapter4-2_basic | main | ✓ | 2025-06-05 |  |
| Member_Community_Board | develop |  | 2024-02-05 |  |
| Member_Community_Board | front-back-connect |  | 2024-02-05 |  |
| Member_Community_Board | main | ✓ | 2024-02-05 |  |
| Member_Community_Board | view |  | 2024-02-05 |  |
| milkyway-ExpressServer | develop |  | 2024-06-18 |  |
| milkyway-ExpressServer | feautre/ktg/middleware |  | 2024-06-18 |  |
| milkyway-ExpressServer | main | ✓ | 2024-06-18 |  |
| MilkyWay_RN | develop |  | 2024-12-09 |  |
| MilkyWay_RN | develop-layout |  | 2024-12-09 |  |
| MilkyWay_RN | main | ✓ | 2024-12-09 |  |
| Milky_Way_Front | develop |  | 2024-10-30 |  |
| Milky_Way_Front | main | ✓ | 2024-10-30 |  |

## 파일 구조

`<레포>/<브랜치>.json` 하나에 그 브랜치의 모든 정보가 들어 있다.

- `environment.runtime` — **자동.** package.json·.nvmrc 등에서 읽은 Node·Electron·React Native 버전
- `environment.deployment` — **사람이 작성.** 실제 설치된 서버·OS·Node·Docker·DB 버전, 담당자, 비고. 자동 실행이 이 부분만은 덮어쓰지 않는다
- 그 외(`dependencies`, `lockFiles`, `sha` 등) — **자동.** 매 실행마다 덮어쓴다

브랜치별로 환경이 다르면 각 브랜치 파일의 `environment.deployment` 에 따로 적는다.
