# 🍷 WHYNE
사용자가 다양한 와인에 대한 리뷰를 보고, 구매 여부를 판단해볼 수 있는 플랫폼입니다. 
와인의 종류, 맛, 가격대, 별점을 기반으로 리뷰를 작성할 수 있으며, 다양한 필터를 적용해서 와인을 골라서 볼 수 있습니다.
<div align="center">
  <a href="https://whyne-pink.vercel.app/" target="_blank">
    <img src="https://github.com/user-attachments/assets/7e00dd2f-e20d-4723-b4fc-217b8774c89e" width="100%" alt="whyne" />
  </a>
</div>

<br/>
<br/>

## 🧑‍🤝‍🧑 팀원 소개
| 김송현 | 김백화 | 남빛나 | 박수정 | 양성준 | 정다은 |
|:------:|:------:|:------:|:------:|:------:|:------:|
| <img src="https://avatars.githubusercontent.com/u/24265870?v=4" alt="김송현" width="150"> | <img src="https://avatars.githubusercontent.com/u/184475828?v=4" alt="김백화" width="150"> | <img src="https://avatars.githubusercontent.com/u/129211732?v=4" alt="남빛나" width="150"> | <img src="https://avatars.githubusercontent.com/u/101353635?v=4" alt="박수정" width="150"> | <img src="https://avatars.githubusercontent.com/u/111010564?v=4" alt="양성준" width="150"> | <img src="https://avatars.githubusercontent.com/u/169114311?v=4" alt="정다은" width="150"> |
| [GitHub](https://github.com/ziy1027) | [GitHub](https://github.com/baekhwa) | [GitHub](https://github.com/bitna0a) | [GitHub](https://github.com/sera355) | [GitHub](https://github.com/jakejun98) | [GitHub](https://github.com/da1eun) |

<br/>
<br/>

## 🎬 주요 기능 및 시연
> (각 기능별로 캡처한 GIF나 이미지를 첨부하세요)
1. **공통 컴포넌트 시스템 구축**: 다양한 페이지에서 재사용 가능한 Input, Dropdown 구현
2. **게시물 작성 및 이미지 미리보기**: 사용자가 이미지를 업로드할 때 브라우저 메모리를 활용해 즉각적인 미리보기 제공
3. **API 데이터 연동**: 주어진 명세서에 맞춰 데이터를 불러오고 로딩/에러 UI 처리

<br/>
<br/>

## 🛠️ 기술 스택

### Core
<img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white"/>

### State Management & Routing
<img src="https://img.shields.io/badge/Zustand-764ABC?style=flat&logo=react&logoColor=white"/> <img src="https://img.shields.io/badge/React%20Router-CA4245?style=flat&logo=reactrouter&logoColor=white"/>

### Form & Validation
<img src="https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=flat&logo=reacthookform&logoColor=white"/> <img src="https://img.shields.io/badge/Zod-3E67B1?style=flat&logo=zod&logoColor=white"/>

### UI & Animation
<img src="https://img.shields.io/badge/Swiper-6332F6?style=flat&logo=swiper&logoColor=white"/> <img src="https://img.shields.io/badge/Anime.js-181818?style=flat&logo=anime.js&logoColor=white"/> <img src="https://img.shields.io/badge/AOS-000000?style=flat"/> <img src="https://img.shields.io/badge/classnames-000000?style=flat"/> 

### Tooling & Formatting
<img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat&logo=eslint&logoColor=white"/> <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat&logo=prettier&logoColor=black"/> <img src="https://img.shields.io/badge/Husky-000000?style=flat&logo=git&logoColor=white"/> <img src="https://img.shields.io/badge/commitlint-000000?style=flat&logo=commitlint&logoColor=white"/>

### Collaboration
<img src="https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white"/> <img src="https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white"/> <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white"/>

<br/>
<br/>

## 📁 폴더 구조
```bash
📦 src
 ┣ 📁 apis        # API 요청 함수
 ┣ 📁 assets      # 아이콘, 이미지 등 정적 리소스
 ┣ 📁 components  # 공통 컴포넌트
 ┣ 📁 pages       # 페이지 단위 컴포넌트
 ┣ 📁 routers     # 라우터 설정
 ┣ 📁 storybook   # 샘플 페이지
 ┣ 📁 styles      # 공통 스타일
 ┣ 📁 utils       # 유틸 함수
 ┣ 📁 hooks       # 커스텀 훅
 ┣ 📁 constants   # 상수 관리
 ┣ 📄 App.jsx     # 루트 컴포넌트
 ┗ 📄 main.jsx    # 엔트리 포인트
```

<br/>
<br/>

## 🤝 협업 규칙 (Convention & Strategy)

### 📝 커밋 컨벤션 (Commit Convention)

**1. 커밋 메시지 구조**
```text
[type]: Subject
```

**2. 커밋 타입 (Commit Type)**
| Type | 설명 |
| --- | --- |
| `[feat]` | 새로운 기능 구현 |
| `[fix]` | 버그, 오류 해결 |
| `[design]` | 사용자 UI 변경 (CSS 등) |
| `[style]` | 코드 스타일 변경 (포매팅 등, 비즈니스 로직 변경 없음) |
| `[refactor]` | 기능 변화 없는 코드 구조 개선 |
| `[chore]` | 라이브러리 설치, 설정 파일 변경 등 기타 작업 |
| `[docs]` | README나 WIKI 등의 문서 개정 |

**3. 커밋 제목 규칙 (Subject Rule)**
- 커밋 제목은 **최대 50자**로 제한합니다.
- '어떻게' 구현했는지보다 **'무엇을', '왜' 변경했는지** 한글로 명확하게 작성합니다.
- 제목 끝에 마침표(`.`)를 붙이지 않습니다.

---

### 🌿 브랜치 전략 (Branch Strategy)
프로젝트의 안정성과 효율적인 협업을 위해 목적에 따라 브랜치를 엄격히 분리하여 운영했습니다.

**1. 주요 브랜치 운영**
- **`main`**: 실제 서비스가 배포되는 가장 안정적인 브랜치
- **`develop`**: 각 기능 브랜치에서 작업된 코드가 병합되는 테스트 및 통합 브랜치

**2. 작업 브랜치 명명 규칙 (Naming Convention)**
작업의 종류와 관련 이슈를 한눈에 파악할 수 있도록 아래와 같은 규칙을 사용했습니다.

| 종류 | 브랜치명 형식 | 예시 |
| --- | --- | --- |
| **기능 개발** | `feat/#이슈명/기능이름` | `feat/#login/social-login` |
| **버그 수정** | `fix/#이슈명/버그이름` | `fix/#header/mobile-overlap` |

**3. 협업 워크플로우**
> **`main`** (배포) ◀ **`develop`** (통합) ◀ **`feat`** (개별 작업)
- 개별 작업 브랜치에서 구현 완료 후, **`develop`** 브랜치로 Pull Request를 보냅니다.
- 팀원의 코드 리뷰를 거친 뒤 **`develop`**에 병합하며, 최종 확인된 내용을 **`main`**에 반영합니다.

<br/>
<br/>

## ⚙️ 실행 방법
```bash
# 저장소 클론
$ git clone https://github.com/WHYNE-team-1/WHYNE.git

# 패키지 설치
$ npm install

# 개발 서버 실행
$ npm run dev
```
