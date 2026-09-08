# Dan Kim's Personal Portfolio & Homepage

GitHub Pages(`dankim0524.github.io`)를 위한 모던하고 반응형인 개인 포트폴리오 및 프로필 웹사이트입니다.

## ✨ 주요 기능 및 특징
- **반응형 웹 디자인 (Responsive UI)**: 모바일, 태블릿, 데스크톱 등 모든 화면 크기에 최적화된 레이아웃 및 모바일 전용 드로어 네비게이션
- **다크/라이트 테마 (Dark / Light Mode)**: 사용자 OS 테마 자동 감지 및 원클릭 수동 토글, `localStorage` 설정 영구 저장
- **인터랙티브 기능**:
  - 카테고리별 프로젝트 필터링 (전체, 웹 서비스, 모바일/API, 오픈소스)
  - 이메일 원클릭 클립보드 복사 및 토스트(Toast) 알림
  - 타이핑 헤드라인 애니메이션
  - 스크롤 위치에 따른 네비게이션 자동 하이라이트 (ScrollSpy)
- **제로 빌드 (Zero Build / No Dependency)**: 별도의 Node.js나 빌드 과정 없이 정적 파일만으로 브라우저에서 즉시 구동

---

## 📂 폴더 및 파일 구조
```text
dankim0524.github.io/
├── index.html                  # 메인 페이지 (시맨틱 HTML5, SEO/OG 메타 태그)
├── css/
│   └── style.css               # 디자인 시스템, CSS 변수 및 반응형 스타일
├── js/
│   └── main.js                 # 다크모드, 필터링, 토스트 등 상호작용 스크립트
├── assets/
│   └── avatar-placeholder.svg  # 기본 프로필 아바타 이미지
└── README.md                   # 프로젝트 설명 및 수정 가이드
```

---

## 🚀 로컬에서 확인하기
1. 탐색기에서 `index.html` 파일을 더블 클릭하여 크롬, 엣지(Edge) 등 브라우저로 바로 실행할 수 있습니다.
2. 또는 VS Code 확장 프로그램인 **Live Server**를 통해 실행하실 수도 있습니다.

---

## ✏️ 맞춤 수정 가이드 (Customization)
- **이름 및 소개글 변경**: `index.html`을 열고 `Dan Kim`, 직함, 자기소개 텍스트 및 이메일 주소를 본인의 정보로 변경합니다.
- **프로젝트 및 이력 추가**: `index.html`의 `<section id="projects">` 및 `<section id="experience">` 항목을 복사/수정하여 자신의 경험을 기재합니다.
- **프로필 사진 변경**: 원하는 사진 파일을 `assets/` 폴더에 넣고, `index.html`의 `assets/avatar-placeholder.svg` 경로를 해당 파일명으로 교체합니다.
- **테마 색상 변경**: `css/style.css` 상단의 `:root` 및 `[data-theme="dark"]`의 `--accent-primary` 색상 코드를 원하는 색상으로 변경합니다.

---

## 🌐 GitHub Pages 배포하기
이 저장소에 커밋 및 푸시하면 GitHub Pages를 통해 `https://dankim0524.github.io/`에 자동으로 무료 배포됩니다.
```bash
git add .
git commit -m "feat: 모던 포트폴리오 홈페이지 구축"
git push origin main
```
*(GitHub 저장소 설정의 **Settings > Pages**에서 Branch가 `main`으로 설정되어 있는지 확인하세요.)*
