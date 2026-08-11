# AIBOX Homepage Renewal — Design Drafts

AIBOX 홈페이지 리뉴얼을 위한 디자인 시안 저장소입니다.

## 시안 목록

- **시안 1** (`/draft-1/`) — 다크 톤 · 산화철 앰버 · 스크롤 스크럽 애니메이션
- **시안 2 Black** (`/draft-2-black/`) — 블랙 베이스 · 네온 그린 · 섹션 스냅 스크롤
- **시안 2 White** (`/draft-2-white/`) — 라이트 반전 버전
- **시안 3** (`/draft-3/`) — 오프화이트 · 딥 포레스트 그린 · 얇은 고딕 · 헤어라인 편집 격자.
  섹션 순서와 흐름(4슬라이드 히어로 → Performance → Products → Contents → CTA)은 시안 2와 동일
- **회사소개** (`/about.html`) — 원페이지 서브 페이지

## 로컬 실행

파일을 열어서 확인하려면 로컬 서버가 필요합니다 (base64 아닌 외부 미디어 참조 방식이라).

```bash
# Python 3
python3 -m http.server 8000

# 그리고 브라우저에서
# http://localhost:8000
```

## GitHub Pages 배포

1. 이 폴더 전체를 새 GitHub 저장소에 업로드
2. `Settings` → `Pages` → `Source: main branch, / (root)` 선택 → `Save`
3. 몇 분 뒤 `https://[사용자명].github.io/[저장소명]/` 에서 접속 가능

## 파일 구조

```
/
├── index.html              시안 선택 페이지
├── about.html              회사소개
├── draft-1/
│   ├── index.html
│   └── assets/             미디어 파일
├── draft-2-black/
│   ├── index.html
│   └── assets/
├── draft-2-white/
│   ├── index.html
│   └── assets/
└── draft-3/
    ├── index.html
    └── assets/
```

---

© 2026 Bytelabs · AIBOX Design Drafts
