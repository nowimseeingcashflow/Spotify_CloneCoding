# Spotify Clone

React, Styled-components, React Router를 사용하여 제작한 Spotify 클론 프로젝트입니다. Spotify의 주요 기능과 UI를 재현하며, 반응형 디자인을 지원합니다.

---

## 주요 기능

- 🎵 **홈 화면**: 인기 플레이리스트, 개인화 믹스, 새로운 음악 추천.
- 🔍 **검색**: 곡, 아티스트, 플레이리스트 검색.
- 📚 **라이브러리**: 저장된 플레이리스트 및 좋아요한 곡 관리.
- 🎧 **플레이어**: 재생, 일시 정지, 다음/이전 곡, 셔플, 반복, 볼륨 조절 기능 포함.
- 📱 **반응형 디자인**: 데스크탑과 모바일 환경에서 원활히 작동.

---

## 기술 스택

- **프론트엔드**: React, React Router, Styled-components
- **아이콘**: React Icons
- **스타일링**: CSS-in-JS 방식 (Styled-components)
- **개발 환경**: TypeScript, VSCode

---

## 프로젝트 구조

```plaintext
spotify-clone/
├── public/
│   ├── index.html        # 기본 HTML 파일
│   └── favicon.ico       # 애플리케이션 아이콘
├── src/
│   ├── components/       # 재사용 가능한 UI 컴포넌트
│   │   ├── Header.tsx    # 헤더 컴포넌트
│   │   ├── Player.tsx    # 플레이어 컴포넌트
│   │   └── Sidebar.tsx   # 사이드바 컴포넌트
│   ├── pages/            # 페이지 구성 요소
│   │   ├── Home.tsx      # 홈 페이지
│   │   ├── Search.tsx    # 검색 페이지
│   │   ├── Library.tsx   # 라이브러리 페이지
│   │   └── Playlist.tsx  # 플레이리스트 상세 페이지
│   ├── styles/           # 전역 스타일
│   │   └── GlobalStyles.ts # 애플리케이션 기본 스타일
│   ├── App.tsx           # 루트 컴포넌트
│   └── index.tsx         # 진입점
├── package.json          # 프로젝트 메타데이터 및 의존성
└── tsconfig.json         # TypeScript 설정
