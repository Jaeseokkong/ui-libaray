# UI Component Library

## 프로젝트 소개
이 프로젝트는 프론트엔드 개발에서 자주 사용하는 **UI 컴포넌트**들을 직접 구현하고, 이를 라이브러리 형태로 구성하여 다양한 프로젝트에서 **재사용 가능한 컴포넌트** 모음을 제공합니다. `React`와 `styled-components`를 사용해 컴포넌트를 모듈화하고, `Storybook`을 통해 시각적 문서화를 진행하여, 손쉽게 컴포넌트들을 테스트하고 활용할 수 있습니다.

### 배포 주소
[]()  

### 주요 기능
- **재사용성**: 다양한 스타일 옵션을 가진 컴포넌트로, 다른 프로젝트에서도 쉽게 활용할 수 있습니다.
- **문서화**: `Storybook`을 사용하여 각 컴포넌트의 시각적 미리보기 및 문서화를 제공합니다.
- **유연한 스타일링**: `styled-components`를 통해 컴포넌트 스타일을 확장하고 관리하기 편리합니다.

---

## 프로젝트 구조

### 디렉토리 구조

```plaintext
my-ui-library
├── src
│   ├── components
│   │   ├── Button
│   │   │   ├── Button.js
│   │   │   ├── Button.stories.js
│   │   │   └── Button.test.js
│   │   ├── Modal
│   │   ├── Dropdown
│   │   └── index.js
│   ├── utils
│   ├── App.js
│   └── index.js
├── .storybook
│   ├── main.js
│   ├── preview.js
├── package.json
└── README.md