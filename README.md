# 🔮 타로 점괘 - AI 타로 리딩

> AI가 해석하는 신비로운 타로 카드 리딩 웹 서비스

🌐 **https://tarot-card-app-muwu.onrender.com**

---

## 📸 스크린샷

| 메인 페이지 | 카드 뽑기 | AI 해석 결과 |
|:-----------:|:---------:|:------------:|
| ![Landing](docs/landing.png) | ![Card Draw](docs/card-draw.png) | ![Result](docs/result.png) |

---

## ✨ 주요 기능

### 🃏 타로 카드 리딩
- 78장의 완전한 타로 덱 (메이저 아르카나 22장 + 마이너 아르카나 56장)
- 정방향 / 역방향 해석 지원
- 30가지 이상의 스프레드 (원 카드, 쓰리 카드, 켈틱 크로스 등)
- 점핑 카드 — 낮은 확률로 예기치 않은 카드가 자동으로 튀어나옴

### 🤖 AI 해석
- AI가 뽑힌 카드의 의미를 질문 맥락에 맞게 해석
- 카드별 개별 해석 + 전체 종합 해석
- 해석 결과에 대해 AI와 추가 대화 가능
- 추가 카드를 뽑아 더 깊은 통찰 확인

### 🔍 질문 분석
- 사용자의 질문을 AI가 분석하여 명확도 평가
- 질문 주제에 맞는 최적의 스프레드 자동 추천
- 연애, 재정, 진로, 건강, 영성 등 다양한 카테고리

### 📊 리딩 통계
- 나의 리딩 기록 타임라인
- 가장 많이 나온 카드 / 질문 카테고리 분석
- AI가 누적된 리딩에서 패턴 인사이트 제공

### 🔐 개인정보 보호
- 모든 타로 기록은 사용자 비밀번호 기반으로 암호화 후 저장
- 서버는 암호화된 데이터만 보관 — 서버 관리자도 내용 확인 불가
- 계정 삭제 시 모든 데이터 즉시 삭제

### 🌍 다국어 지원
- 한국어 / English / 日本語 / 中文 / Français
- 브라우저 언어 자동 감지 + 수동 전환 가능

### 🔑 로그인
- 이메일 회원가입
- Google / Kakao / Discord 소셜 로그인

### 📱 PWA
- 모바일 홈 화면에 앱처럼 추가 가능
- 오프라인 접근 지원

---

## 🛠️ 사용 기술 요약

| 영역 | 기술 |
|------|------|
| Backend | Python, Flask, Gunicorn |
| Frontend | Vanilla JavaScript, HTML5, CSS3 |
| AI | Groq API (Llama 3.3 70B) |
| Database | Supabase (PostgreSQL) |
| Auth | Supabase Auth + OAuth (Google, Kakao, Discord) |
| Encryption | AES-256-GCM + PBKDF2 (E2E 암호화) |
| Deploy | Render (Singapore) |
| PWA | Service Worker + Web App Manifest |

---
