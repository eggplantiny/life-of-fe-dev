---
theme: seriph
background: https://cover.sli.dev
title: About Frontend Developer's Life
info: |
  ## 프론트엔드 개발자의 삶이란...? 🥺
  프론트엔드 개발자가 되고싶은 모든 개발자들에게

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-up
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# About Frontend Developer's Life

## 프론트엔드 개발자의 삶

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    프론트엔드 개발자가 되고싶은 모든 개발자들에게 <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/eggplantiny/life-of-fe-dev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
---


# 목차

<Toc minDepth="1" maxDepth="2"></Toc>

---
transition: slide-up
---

# FE 개발이란?

프론트엔드 개발은 사용자가 직접적으로 상호작용하는 웹사이트나 애플리케이션의 **UX/UI**를 개발하는 역할

![FE and BE](/fe-and-be.webp)

<!--
프론트엔드 개발은 사용자가 직접적으로 상호작용하는 웹사이트나 애플리케이션의 UI(User Interface)를 구축하고 유지보수하는 역할을 합니다.
HTML, CSS, JavaScript를 활용하여 웹 페이지를 구성하고, 사용자 경험을 향상시키기 위해 다양한 기술을 적용합니다.
-->

---
level: 2
layout: image-right
image: /fe2.jpeg
backgroundSize: contain
---

# FE 개발자의 역할

- 🧑‍💻 **기능 개발**
- 🧑‍🎨 **UI/UX 구현**
- 🗣️ **협업과 커뮤니케이션**
- 🐞 **테스트와 디버깅**

<!--
### 기능 개발
- JavaScript와 프레임워크를 사용해 동적인 웹 애플리케이션 기능을 개발.

### UI/UX 구현
- 디자이너와 협업하여 사용자 인터페이스를 구현.

### 테스트와 디버깅
- 버그를 수정하고 코드의 안정성을 확보.

### 협업과 커뮤니케이션
- 백엔드 개발자, 기획자, 디자이너 등과 원활하게 소통하여 프로젝트 목표를 달성.
-->


---
level: 2
layout: image-right
image: /5.jpeg
backgroundSize: contain
---

# FE 개발자의 회사 내 위치

- 🧑‍💻다양한 서비스 개발에 참여하는 멋진 사람 <v-click>(Admin Service, CMS, Vertial App, Mobile Web etc..)</v-click>
<v-click>(기술이 빠르게 바뀌어 공부 할게 많은데 인원은 적어서 맨날 야근하는 노예)</v-click>
- 🕺💃 다양한 직군과 협업 하는 슈퍼 인싸<v-click>(UI/UX 디자이너, 백엔드 개발자, 기획자, 사업부서 등)</v-click>
<v-click>(문제 터지면 FE 개발자부터 줘팸당함. 동네북 🥲)</v-click>

<!--
-->


---
level: 1
layout: image-right
image: /3.png
backgroundSize: contain
---

# FE 개발의 기본 개념

## FE 개발의 3대 요소
- **HTML**
- **CSS**
- **JavaScript**

## FE 의 환경
- **브라우저**
- **DOM** & **CSSOM**
- **FE 프레임워크**

<!--
### HTML, CSS, JavaScript
- **HTML**: 웹 페이지의 구조를 정의.
- **CSS**: 웹 페이지의 스타일을 정의.
- **JavaScript**: 웹 페이지에 동적인 기능을 추가.

### 웹 브라우저와 DOM
- **웹 브라우저**: 사용자가 웹 페이지를 볼 수 있게 해주는 소프트웨어.
- **DOM (Document Object Model)**: 웹 페이지의 구조화된 표현으로 자바스크립트를 통해 조작 가능.
-->

---
level: 2
layout: image-right
image: /4.png
backgroundSize: contain
---

# FE 개발 프레임워크

### React
<span v-mark.highlight.indigo>컴포넌트 기반 구조</span>, 단방향 데이터 흐름, Virtual DOM 사용

### Vue.js
<span v-mark.highlight.indigo>반응형 데이터 흐름</span>, 직관적인 API, 컴포넌트 기반

### Angular
MVC 패턴, 양방향 데이터 바인딩, 의존성 주입

### Svelte
컴파일러 기반, 가볍고 빠른 성능, <span v-mark.highlight.indigo>단순한 상태 관리</span>

---
level: 2
---

# FE 프레임워크의 주요 개념

### 컴포넌트 기반 구조
- UI를 독립적이고 <span v-mark.highlight.indigo>재사용 가능한 컴포넌트로 분리하여 관리</span>
- 복잡한 사용자 인터페이스를 관리하기 위해 컴포넌트 단위의 구조화된 개발 필요.

### 반응형 데이터 흐름
- <span v-mark.highlight.indigo>데이터가 변경될 때 자동으로 UI가 업데이트되는 방식</span>
- 데이터와 UI 간의 동기화를 자동으로 처리하여 사용자 인터페이스의 일관성을 유지.

### 단순한 상태 관리
- 애플리케이션이나 <span v-mark.highlight.indigo>컴포넌트의 상태를 단순하고 명확하게 관리</span>
- 코드의 가독성을 높이고 디버깅을 용이하게 함.

<!-- 
### 컴포넌트 기반 구조
- UI를 독립적이고 재사용 가능한 컴포넌트로 분리하여 관리. 각 컴포넌트는 고유의 상태와 로직을 가지며, 전체 애플리케이션의 복잡성을 줄이고 유지보수를 용이하게 합니다.
- 프론트엔드 개발에서는 복잡한 사용자 인터페이스를 관리하기 위해 구조화된 접근이 필요합니다. 컴포넌트 기반 구조는 재사용성과 유지보수성을 높여주며, 변경 사항이 특정 컴포넌트에 국한되도록 하여 전체 애플리케이션의 안정성을 유지합니다.

### 반응형 데이터 흐름
- 데이터가 변경될 때 자동으로 UI가 업데이트되는 방식. 데이터와 UI 간의 동기화를 자동으로 처리하여 사용자 인터페이스의 일관성을 유지합니다.
- 프론트엔드 개발에서는 실시간으로 변화하는 데이터를 처리해야 합니다. 반응형 데이터 흐름은 사용자 상호작용에 즉각적으로 반응하여 더 나은 사용자 경험을 제공합니다.

### 단순한 상태 관리
- 애플리케이션의 상태를 단순하고 명확하게 관리하여, 코드의 가독성을 높이고 디버깅을 용이하게 합니다. 작은 규모의 프로젝트나 단순한 상태 변경이 필요한 경우 적합합니다.
- 프론트엔드에서는 여러 사용자 상호작용과 데이터 상태를 관리해야 하므로, 단순한 상태 관리가 필요합니다. 복잡한 상태 관리 시스템은 오히려 개발을 어렵게 만들 수 있기 때문에, 상태 관리를 단순화하면 코드 유지보수와 오류 디버깅이 용이해집니다.
-->

---
level: 2
---

# 취업에는...?

![React...](/6.png)

<v-click>리엑트로 천하통일중</v-click>

---
level: 2
layout: image-right
image: /7.jpg
backgroundSize: contain
---

# 결국에는 닮아가는 FE Framework

<v-clicks>

- React 의 Virtual DOM 과 Angular 의 양방향 데이터 바인딩을 합쳐서 Vue 탄생!

- React 의 JSX 문법과 Vue 의 반응형을 합쳐서 Solid 탄생!

- Vue 의 개발 편의성을 제공하면서 VDOM 을 Compiler 로서 제거한 Svelte 탄생!

- Svelte 의 컴파일러 기반를 차용한 Vue/Vaper 탄생!

- ... 결국엔 다들 특징이 비슷해짐

</v-clicks>


---
level: 2
align: center
---

# 그러니 결국엔 기본기

![기본기](/3.png)

<span v-mark.underline.indigo>브라우저 동작 원리</span>
와
<span v-mark.underline.indigo>웹 표준</span>
에 대한 이해,
<span v-mark.underline.indigo>HTML</span>
,
<span v-mark.underline.indigo>CSS</span>
,
<span v-mark.underline.indigo>JavaScript</span>
의 <span v-mark.circle.indigo>기본기를 탄탄히 다지는 것이 중요</span>

---
transition: slide-left
---

# 마무리

---
level: 3
transition: slide-left
---

### **Q. 프론트엔드 개발자의 삶은 어떤가요?**

<v-click>
A. 재밌어요 하지만 힘들어요...🥹
</v-click>

---
level: 3
transition: slide-left
---

### **Q. 프론트엔드 개발자가 되고 싶은데 어떻게 해야하나요?**

<v-click>
A. 기본기를 탄탄히 다지고, 프로젝트를 진행해보세요! 🚀
</v-click>

<br/>
<v-click>
(한국에서 취업할려면 React 로 🥺)
</v-click>


---
level: 3
transition: slide-left
---

### **Q. 프론트엔드 개발자의 삶을 한 마디로 표현한다면?**

<v-click>
A. "끝없는 도전의 연속" 📚
</v-click>

---

감사합니다 🙏
