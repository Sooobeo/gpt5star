# gpt5star
ycc 25-2 project

# Gpt 5성템 장착시키기 

GPT 대화 내용을 자동으로 저장하고, 웹에서 검색/요약/내보내기를 지원하는 프로젝트입니다.  
웹 + 크롬 확장 프로그램을 함께 개발합니다.

---

## 📂 폴더 구조
- `apps/web` : 프론트엔드 (Next.js, React)
- `apps/server` : 백엔드 (FastAPI or Spring Boot)
- `apps/extension` : 크롬 확장 프로그램
- `docs/` : 문서/회의록/설계안
- `.github/workflows/` : CI/CD 자동화 설정

---

## 👥 역할 분담
- **FE1**: `apps/web`, `apps/extension` UI 개발
- **BE1 (PM)**: `apps/server` 기본 API (CRUD/검색/ingest), 일정 관리
- **BE2**: `apps/server` 인증/Export/요약/태그
- **Infra1**: 배포, CI/CD, 시크릿/백업 관리

---

## 🌱 Git 협업 규칙
1. **main에는 직접 푸시하지 않는다.**  
2. 작업할 때는 브랜치 생성:
   ```bash
   git checkout -b feature/이름-작업내용
