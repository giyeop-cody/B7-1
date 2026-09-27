# B7-1


<!-- codyssey-links:start -->
## 🔗 Codyssey 연결

| 항목 | 링크 |
|---|---|
| **과제** | **B7-1** — 웹 기반 AI 챗봇 서비스 개발 프로젝트 · 기초(Basic) 「AI/SW 기초」 · Term Project · 120h |
| 미션 원문 (정의서) | [`B7-1/b7-1-description.md`](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/B7-1/b7-1-description.md) · [`B7-1-mission.jpg`](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/B7-1/b7-1-mission.jpg) · [`meta.json`](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/B7-1/meta.json) |
| 이 과제 연결 카드 | [`B7-1/links.md`](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/B7-1/links.md) |
| 전체 연결 대장 | [`LINKS.md`](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/LINKS.md) · 진행 현황 [`PROGRESS.md`](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/PROGRESS.md) · [원문 API URL 41개](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/codyssey-all-urls.md) |
| 과정 허브 | [ai-sw-basic](https://github.com/giyeop-cody/ai-sw-basic) `/B7-1/` 서브모듈 |
| 통합 레포 | [codyssey](https://github.com/giyeop-cody/codyssey) → `ai-sw-basic/B7-1/` |
| 다음 과정 | 심화(A) [codyssey-A-studylog-hub](https://github.com/giyeop-cody/codyssey-A-studylog-hub) · 응용(M) 정의서 [`taskmap/M*/`](https://github.com/giyeop-cody/codyssey-taskmap/tree/main/M1-1) |
| 같은 과제의 다른 레포 | <sub>제출물(미션)</sub> [codyssey-term-mission-B7-1/ai-chatbot-service](https://github.com/codyssey-term-mission-B7-1/ai-chatbot-service) · <sub>개인 fork</sub> [giyeop-cody/ai-chatbot-service](https://github.com/giyeop-cody/ai-chatbot-service) |
| 같은 과목 다른 과제 | [B7-2](https://github.com/giyeop-cody/codyssey-taskmap/blob/main/B7-2/links.md) |

> 🔒 = 비공개 레포. 상태·pin 커밋은 연결 카드와 `PROGRESS.md` 에 있다. 이 표는 2026-09-27 기준이며 미션 원문 3종은 원본 데이터라 진행 상태를 쓰지 않는다.
<!-- codyssey-links:end -->

## 📌 과제 정보

| 항목 | 내용 |
|------|------|
| **과목** | Term Project |
| **난이도** | ★★★ (Lv.3) |
| **학습 시간** | 120분 |
| **필수 여부** | ✅ 필수 |
| **과제 번호** | 185017 |


## 🎯 프로젝트 개요

웹 기반 AI 챗봇 서비스를 개발합니다. Python & FastAPI로 백엔드를, 웹 프론트엔드로 채팅 UI를 구현하고, AI API를 연동하여 대화 기능을 제공합니다.

## 🎓 학습 목표

이 과제를 완료한 뒤, 다음을 설명할 수 있어야 한다:

1. AI API를 연동하여 채팅 기능을 구현할 수 있다
2. 대화 내역을 데이터베이스에 저장하고 불러올 수 있다
3. 인증(로그인) 후 개인별 대화 이력을 관리할 수 있다
4. AI API 호출 시 타임아웃/에러 처리를 구현할 수 있다
5. 민감정보를 환경변수로 관리할 수 있다

## ⚠️ 제약 사항

- API 키, DB 비밀번호 등 민감정보를 코드에 직접 작성하지 않는다
- 모든 민감정보는 환경 변수(.env)로 관리
- .env 파일은 .gitignore 적용
- AI API 호출 타임아웃 설정 및 실패 시 오류 안내
- PR 기반으로 머지, 브랜치/PR 기록 저장

웹 기반 AI 챗봇 서비스 개발 프로젝트 | Term Project | AI/SW 기초
