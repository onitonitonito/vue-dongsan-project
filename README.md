# 🏠 Vue-Dongsan-Project

<p align="left">
  <img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D" />
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=FFD62E" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
</p>
<p align="left">
  <img src="https://img.shields.io/badge/Give_Me_Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white" />  <img src="https://img.shields.io/badge/Buy_Me_A_Coffee-FFDD00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" />  <img src="https://img.shields.io/badge/Caffeine_Addict-EFDFBB?style=for-the-badge&logo=coffeescript&logoColor=black" />  <img src="https://img.shields.io/badge/No_Brain_No_Problem-FF0000?style=for-the-badge&logo=headspace&logoColor=white" /> <img src="https://img.shields.io/badge/Works_on-my_machine-4bc51d?style=for-the-badge&logo=visual-studio-code&logoColor=white" />   <img src="https://img.shields.io/badge/Powered_by-Ramen-FFD700?style=for-the-badge&logo=nissandotcom&logoColor=red" />   <img src="https://img.shields.io/badge/StackOverflow-Scavenger-FE7A16?style=for-the-badge&logo=stack-overflow&logoColor=white" />   <img src="https://img.shields.io/badge/Sleep_is_for-the_weak-101010?style=for-the-badge&logo=moo&logoColor=white" />
</p>

> **Modern Real Estate Listing Application**  
> 원룸 및 부동산 매물 목록을 효율적으로 관리하고 시각화하는 Vue.js 기반의 웹 애플리케이션입니다.

---

## ✨ Key Features (주요 기능)

- **Dynamic Data Binding**: 부동산 매물 이름, 가격 등을 배열 데이터를 통해 동적으로 렌더링합니다.
- **Interactive Navigation**: 상단 메뉴(v-for)와 제품 목록의 상호작용을 지원합니다.
- **Premium UI/UX**: 
  - 부드러운 Hover 애니메이션과 카드 스타일 레이아웃.
  - 현대적인 색상 팔레트(Deep Purple)와 그림자 효과 적용.
- **Numbered Listing**: 매물 목록에 자동으로 순번을 부여하여 가독성을 높였습니다 (`{{ i + 1 }}.`).
- **Performance Optimized**: Vite를 사용하여 빠른 개발 서버 구동 및 최적화된 프로덕션 빌드를 제공합니다.

---

## 🛠 Tech Stack (기술 스택)

| 분류 | 기술 | 설명 |
| :--- | :--- | :--- |
| **Framework** | [Vue.js 3](https://vuejs.org/) | 사용자 인터페이스 구축을 위한 프로그레시브 프레임워크 |
| **Build Tool** | [Vite](https://vitejs.dev/) | 빠르고 현대적인 프론트엔드 빌드 도구 |
| **Language** | JavaScript (ES6+) | 유연한 비즈니스 로직 작성을 위한 스크립트 언어 |
| **Styling** | Vanilla CSS | 사용자 정의 디자인 시스템 및 변수 기반 스타일링 |
| **Manager** | npm | 패키지 및 의존성 관리 도구 |
| **Deployment** | GitHub Pages | 정적 웹사이트 배포를 위한 호스팅 서비스 |

---

## 🚀 Getting Started (시작하기)

### Prerequisites
`Node.js` 및 `npm`이 설치되어 있어야 합니다.

### Execution Commands
1. **의존성 설치**
   ```bash
   npm install
   ```

2. **개발 서버 실행**
   ```bash
   npm run dev
   ```

3. **프로덕션 빌드**
   ```bash
   npm run build
   ```

4. **GitHub Pages 배포**
   ```bash
   npm run deploy
   ```

---

## 📂 Directory Structure (디렉토리 구조)
```text
src/
├── assets/         # 정적 자원 (CSS, 이미지 등)
│   ├── main.css    # 전역 스타일 및 디자인 시스템
│   └── logo-mario.png 
├── components/     # 재사용 가능한 컴포넌트
└── App.vue         # 메인 어플리케이션 컴포넌트 (데이터 및 로직 집중)
```

---

## 🍎 코딩애플 Vue 강좌 (학습 로드맵)

### Part 1: 부동산 쇼핑몰 만들기 (Vue.js 3 기초)
- [x] 개발 환경 세팅 및 Vue 3 설치
- [x] 데이터바인딩 문법 (`v-bind`, `{{ }}`)
- [x] 리액트보다 쉬운 반복문 (`v-for`)
- [x] 이벤트 핸들러 활용 (`v-on`, `@click`)
- [x] 동적 UI 제작 (`v-if`, `v-else`)
- [x] 실제 데이터를 박아넣어 상품 목록 만들기 (import / export)
- [x] 컴포넌트화 전략 (Component 기초)
- [x] 부모-자식 데이터 전달 (Props)
- [x] 커스텀 이벤트 (Custom Events / `$emit`)
- [x] 사용자 입력 핸들링 (`v-model`)
- [x] 데이터 감시와 애니메이션 (`watcher`, `transition`)
- [x] 라이프사이클 함수 (`onMounted` 등)

### Part 2: Blog 레이아웃과 라우터
- [ ] Vue Router 설치 및 환경 설정
- [ ] 페이지 라우팅 및 URL 파라미터 활용
- [ ] Named Routes & Navigation Guard

### Part 3: 인스타그램 웹앱 (고급 기술)
- [ ] 이미지 업로드 기능 (`FileReader`, `ObjectURL`)
- [ ] Vuex를 이용한 전역 상태 관리
- [ ] 효율적인 슬롯(`Slot`) 활용법
- [ ] Axios를 이용한 Ajax 서버 통신
- [ ] PWA (Progressive Web App) 배포 및 설정
- [ ] Vue 3 Composition API 마스터

---

## 📝 Recent Updates
- [x] **데이터 바인딩 시스템 최적화**: 가격 정보를 하드코딩에서 배열 데이터 바인딩 방식으로 전환.
- [x] **디자인 시스템 개편**: 카드형 레이아웃 및 반응형 내비게이션 바 적용.
- [x] **리스트 넘버링 추가**: `{{ i + 1 }}` 구문을 활용한 매물 순번 자동 생성 기능 추가.

---
© 2026 Vuedongsan Team.

---

## 📸 수료 결과물 (2강)
<img width="450" src="./public/images/애플코딩-강좌-2강-결과물.png"/>
