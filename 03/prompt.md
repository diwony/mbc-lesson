## 요청
우리는 프레임워크(React, Vue 등)나 빌드 도구(Webpack, Vite)를 전혀 사용하지 않는 레거시 웹 환경을 구축할 거야.
HTML, CSS, JavaScript(Vanilla JS)만을 사용한 전통적인 MPA(Multi-Page Application) 방식으로 다음 피그마 시안을 구현해줘.

[시안 및 링크 정보]

피그마 URL: https://www.figma.com/design/UxKwdzM8NjvKCzLxlmJ7Kj/84p~100p?node-id=28-164&t=ZreDhOWCMAQaerPQ-4
[개발 아키텍처 및 요구 사항]

전통적 MPA(Multi-Page Application) 구조:

각 페이지는 독립된 개별 .html 파일로 존재해야 해 (예: index.html, sub1.html 등).
메인 메뉴나 네비게이션 바의 링크는 <a href="page-name.html"> 구조의 전통적인 하이퍼링크 이동 방식을 사용해줘.
디렉토리 및 파일 구성:

각 페이지별로 마크업을 분리하되, 공통 스타일과 스크립트는 효율적으로 관리할 수 있게 구조화해줘.
예시 구조:
├── index.html (메인 페이지)
├── pages/ (상세 및 서브 페이지 폴더)
│ └── sub.html
├── css/
│ └── style.css (전체 공통 및 페이지별 스타일)
└── js/
└── main.js (순수 바닐라 자바스크립트)
바닐라 웹 기술 준수:

HTML: Semantic 태그를 적극 활용한 표준 마크업.
CSS: Flexbox와 Grid를 활용해 시안(node-id: 28-164)의 레이아웃, 여백, 컬러, 타이포그래피를 픽셀 단위로 정밀하게 구현.
JS: 외부 라이브러리 없이 브라우저 내장 Web API(document.querySelector, addEventListener 등)만 사용하는 순수 Vanilla JS 인터렉션 구현.
UI/UX 디테일:

피그마 시안에 명시된 컴포넌트의 형태와 배치, Hover 상태의 부드러운 CSS Transition 효과를 포함해줘.
페이지 전환 시 어색함이 없도록 전체적인 톤앤매너를 통일해줘.
위 조건에 맞춰 별도의 빌드 과정 없이 Replit 브라우저 화면에서 바로 페이지 이동과 인터렉션이 완벽히 작동하는 코드를 작성해줘.