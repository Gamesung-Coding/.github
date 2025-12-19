# Welcome to Gamesung Coding 👋

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&height=200&color=gradient&customColorList=14&text=Gamesung%20Coding&textBg=false&section=header&desc=Accessibility%20First%20Development&descAlign=50&descAlignY=80" alt="Gamesung Coding Header" width="100%"/>
</div>

<br/>

## 🚀 About Us

안녕하세요! 저희는 **Gamesung Coding(감성코딩)** 팀입니다.
저희는 기술이 단순히 기능적인 편의를 넘어, **모든 사람이 동등하게 정보를 누릴 수 있는 세상**을 만드는 도구가 되어야 한다고 믿습니다.

디지털 소외 계층(시각 장애인, 고령자 등)을 위한 웹 접근성(Accessibility, A11y) 기술을 실제 서비스에 적용하여 **사회적 가치(Social Impact)** 를 실현하는 프로젝트를 진행하고 있습니다.

---

## 🏆 Main Project : A11yMarket

<div align="center"><h3>"누구나 제약 없이 이용 가능한 배리어 프리(Barrier-Free) 이커머스"</h3>
  <br/>
  <a href="https://github.com/gamesung-coding/a11y-market-web">
    <img src="https://img.shields.io/badge/Client-React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black" />
  </a>
  <a href="https://github.com/gamesung-coding/a11y-market-server">
    <img src="https://img.shields.io/badge/Server-Spring_Boot_3.5-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" />
  </a>
  <a href="https://github.com/gamesung-coding/a11ymarket-resources">
    <img src="https://img.shields.io/badge/Docs-Project_Resources-FF9900?style=for-the-badge&logo=googledocs&logoColor=white" />
  </a>
  <a href="https://www.youtube.com/watch?v=SUjhHUoBB_Y" target="_blank">
    <img src="https://img.shields.io/badge/YouTube-Watch%20Demo-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
  </a>
  <br/><br/>
  <p>👉 <b>Live Service:</b> <a href="https://a11ymarket.croffledev.kr" target="_blank">https://a11ymarket.croffledev.kr</a></p>
</div>

### 🎯 Target Audience & Solution

저희는 페르소나 분석을 통해 **디지털 정보 격차(Digital Divide)** 를 겪는 실제 사용자들의 문제를 해결했습니다.

| Target | Pain Point | Solution (Key Features) |
| :---: | :--- | :--- |
| **시각 장애인** <br/> (Screen Reader 사용자) | "이미지만 있는 상품 설명은 내용을 알 수 없고, 결제 진행 상황을 파악하기 두려워요." | • **Gemini AI 이미지 분석:** 상품 이미지를 텍스트로 자동 변환<br/>• **TTS & Screen Reader 최적화:** 모든 UI 요소의 음성 안내 및 키보드 네비게이션 지원 |
| **고령자 / 저시력자** <br/> (디지털 소외 계층) | "글씨가 너무 작고, 복잡한 화면과 어려운 용어 때문에 쇼핑을 포기하게 돼요." | • **맞춤형 접근성 프로필:** 고대비 모드, 큰 글씨 모드 등 개인화 UI 제공<br/>• **AI 요약:** 어려운 전문 용어를 쉬운 말로 요약하여 설명 |
| **소상공인 판매자** <br/> (Non-Tech 유저) | "복잡한 상품 등록 절차와 '대체 텍스트' 같은 기술 용어가 너무 어려워요." | • **간편 등록 시스템:** 사업자등록증 이미지 업로드만으로 가입 신청<br/>• **접근성 가이드:** AI가 대체 텍스트를 자동 생성해주어 손쉬운 상품 등록 지원 |

### 🛠 System Architecture & Features

안정적인 서비스 제공을 위해 **Spring Boot**와 **Oracle DB**를 기반으로 견고한 아키텍처를 설계했으며, **Toss Payments**를 연동하여 신뢰할 수 있는 결제 시스템을 구축했습니다.

- **Frontend:** React 18, Vite, TailwindCSS, Redux Toolkit
- **Backend:** Java 21, Spring Boot 3.5, Spring Security, Spring AI, JPA/Hibernate
- **Database:** Oracle Database 21c XE
- **DevOps:** Docker, GitHub Actions (CI/CD)

---

## 👥 Team Members

|    Name    |                Role                | Responsibility                                              |                     GitHub                     |
| :--------: | :--------------------------------: | :---------------------------------------------------------- | :--------------------------------------------: |
| **안규태** | **👑 팀장** <br/> PM & Architect | 프로젝트 총괄, 아키텍처 설계, 결제 시스템(PG) 연동, CI/CD 구축 | [@BlueNyang](https://github.com/BlueNyang) |
| **김수민** | **🛠 팀원** <br/> DE & UI/UX | 데이터 스키마 설계, 접근성 기능(TTS/UI) 구현, UX 디자인 주도 | [@Gravity251](https://github.com/Gravity251) |
| **백여랑** | **🛠 팀원** <br/> API Developer | REST API 설계 및 명세, 회원/주문 프로세스 로직 구현 | [@byrk205](https://github.com/byrk205) |
| **신운용** | **🛠 팀원** <br/> API Developer | 판매자/상품 관리 API 구현, 프론트엔드 연동 최적화 | [@ShinUnYong](https://github.com/ShinUnYong) |
| **장지훈** | **🛠 팀원** <br/> UI/UX Developer | 클라이언트 UI 구조 설계, 반응형 웹 및 인터랙션 구현 | [@dkdltmqna12](https://github.com/dkdltmqna12) |

---

## 🛠 Tech Stack

<div align="center">
  <img src="https://custom-skill-icons.netlify.app/icons?i=java,springboot,hibernate,swagger,oracledb,js,react,vite,redux,tailwindcss,docker,github,githubactions,idea,vscode&perline=5" />
  <br/><br/>
  
  **Infrastructure & Backend**<br/>
  
  <img src="https://img.shields.io/badge/Java-21-orange?logo=java" /> 
  <img src="https://img.shields.io/badge/Spring Boot-3.5.7-green?logo=springboot" /> 
  <img src="https://img.shields.io/badge/Oracle%20DB-21c-F80000?logo=oracle" /> 
  <img src="https://img.shields.io/badge/Spring AI-Gemini-4285F4?logo=google" />
  <img src="https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white" />
  
  <br/>**Frontend**<br/>
  <img src="https://img.shields.io/badge/React-18.3-61DAFB?logo=react&logoColor=black" /> 
  <img src="https://img.shields.io/badge/Vite-5.4-646CFF?logo=vite" /> 
  <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?logo=tailwindcss&logoColor=white" /> 
  <img src="https://img.shields.io/badge/Redux Toolkit-764ABC?logo=redux" />

  <br/>**Collaboration & Tools**<br/>
  <img src="https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub Actions-2088FF?logo=githubactions&logoColor=white" />
  <img src="https://img.shields.io/badge/Notion-000000?logo=notion&logoColor=white" />
  <img src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white" />
  <img src="https://img.shields.io/badge/Swagger-85EA2D?logo=swagger&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL Developer-Oracle-F80000?logo=oracle" />
</div>

---

## 📧 Contact

- **Organization:** [https://github.com/gamesung-coding](https://github.com/gamesung-coding)
- **Email:** contact@bluenyang.kr
