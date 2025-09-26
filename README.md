# Tourog Creative Agency

Tourog Creative Agency는 디지털 시대를 위한 창의적인 에이전시 웹사이트입니다. 기존 템플릿을 기반으로 로컬에서 실행 가능한 구조로 재구성되었습니다.

## 주요 특징

- **반응형 디자인**: 모든 디바이스에서 최적화된 사용자 경험
- **모던한 UI/UX**: 깔끔하고 세련된 디자인
- **애니메이션 효과**: 부드러운 전환과 인터랙션
- **로컬 실행**: 외부 의존성 없이 로컬에서 실행 가능

## 페이지 구성

### 1. 홈페이지 (index.html)
- 회사 소개 및 주요 서비스
- 히어로 섹션과 서비스 카드
- 그라데이션 배경과 모던한 디자인

### 2. 에이전시 페이지 (agency.html)
- 회사 소개 및 팀 멤버
- 핵심 가치와 철학
- 팀원 프로필과 전문성

### 3. 연락처 페이지 (contact.html)
- 연락처 정보 및 지도
- 문의 양식
- 소셜 미디어 링크

## 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: Flexbox, Grid, 애니메이션
- **JavaScript**: jQuery 기반 인터랙션
- **Bootstrap**: 반응형 그리드 시스템
- **Font Awesome**: 아이콘
- **Swiper.js**: 슬라이더 기능

## 파일 구조

```
템플릿/
├── index.html              # 홈페이지
├── agency.html             # 에이전시 페이지
├── contact.html            # 연락처 페이지
├── assets/                 # 정적 자원
│   ├── css/               # 스타일시트
│   │   ├── style.css      # 메인 스타일
│   │   ├── bootstrap.min.css
│   │   ├── fontawesome.min.css
│   │   └── ...
│   ├── js/                # JavaScript 파일
│   │   ├── scripts.js     # 메인 스크립트
│   │   ├── jquery.min.js
│   │   ├── bootstrap.min.js
│   │   └── ...
│   └── images/            # 이미지 파일
│       ├── logo.png
│       ├── preloader.gif
│       └── ...
└── README.md              # 프로젝트 설명
```

## 실행 방법

1. 프로젝트 폴더를 다운로드합니다.
2. 웹 브라우저에서 `index.html` 파일을 열거나
3. 로컬 웹 서버를 사용하여 실행합니다:

```bash
# Python 3
python -m http.server 8000

# Node.js (http-server 설치 필요)
npx http-server

# PHP
php -S localhost:8000
```

4. 브라우저에서 `http://localhost:8000`으로 접속합니다.

## 주요 수정사항

- **음악 기능 제거**: 오디오 관련 코드 및 파일 제거
- **네비게이션 간소화**: Home, Agency, Contact 3개 메뉴로 축소
- **Studio → Agency**: 메뉴명 변경
- **로컬 최적화**: 외부 의존성 최소화
- **한국어 지원**: 메타데이터 및 콘텐츠 한국어화

## 브라우저 지원

- Chrome (권장)
- Firefox
- Safari
- Edge

## 라이선스

이 프로젝트는 기존 Tourog 템플릿을 기반으로 수정되었습니다.

## 문의

프로젝트에 대한 문의사항이 있으시면 연락처 페이지를 통해 문의해 주세요.
