이 프로젝트는 [React](https://ko.reactjs.org/)의 기본적인 학습을 위한 것입니다. [Create React App](https://github.com/facebook/create-react-app)으로 Bootstrap이 되었으며, [자습서: React 시작하기](https://ko.reactjs.org/tutorial/tutorial.html)를 참고하였습니다.

## 개발 환경

이 프로젝트를 실행하기에 앞서 `npm`이 설치되어 있어야합니다.

프로젝트의 디렉토리에서 다음을 `npm` 명령어들을 실행할 수 있습니다.

### 'npm install'

먼저 프로젝트를 내려받은 후에 `npm install` 명령어를 shell에서 실행해주세요. **npm**은 의존성 패키지 관리자로써 `package.json`에서 이 프로젝트가 어떤 라이브러리를 의존하는 지 참고하여 이 프로젝트에 필요한 npm 모듈을 설치합니다.

### `npm start`

이 명령어는 개발 모드에서 앱을 실행합니다.

브라우저에서 [http://localhost:3000](http://localhost:3000)을 열어 앱의 실행을 확인할 수 있습니다.

이 페이지를 수정하면 다시 로드되며 오류가 났을 경우 콘솔에서 Lint 오류도 표시됩니다.

### `npm test`

이 명령어는 테스트 모듈을 실행합니다.

테스트 모듈에 대한 더 자세한 내용은 [running tests](https://facebook.github.io/create-react-app/docs/running-tests)에서 참조하세요.

### `npm run build`

이 명령어는 `build` 폴더에 프로덕션용 앱을 빌드합니다. React의 제품용을 올바르게 번들로 묶어 최상의 성능을 위해 빌드를 최적화합니다.

빌드는 축소되고 파일 이름에는 해시가 포함됩니다. 이 앱을 배포할 준비가 되었습니다!

자세한 내용은 [https://facebook.github.io/create-react-app/docs/deployment)](https://facebook.github.io/create-react-app/docs/deployment)에 대한 섹션을 참조하세요.

### `npm run eject`

**참고: 이 명령어는 단 한 번만 실행합니다. 한 번 'eject`할 경우 되돌아 갈 수 없습니다!**

이 명령어는 빌드 도구와 빌드 구성이 만족스럽지 않으면 언제든지 'eject'할 수 있으며 프로젝트에서 빌드 의존성을 제거합니다.

대신 모든 구성 파일과 의존성 도구(웹 팩, Babel, ESLint 등)를 프로젝트에 바로 복사하여 사용자가 해당 파일을 완벽하게 제어할 수 있도록 할 수 있습니다.
`eject`를 제외한 모든 명령은 여전히 작동하지만 복사된 스크립트를 수정하세요. 

절대 `eject`를 사용할 필요가 없을 것입니다. 구조화된 기능들은 소형 및 중형 프로젝트들에 적합하며, 이 기능을 사용할 필요성을 느끼지 말아야합니다. 하지만, 이 도구를 사용할 준비가 되었을 때 반드시 의존성을 관리할 준비가 되어있어야 합니다.

## 더 알아보기

React App에 대해 더 알아보고 싶다면, [Create React App 문서](https://facebook.github.io/create-react-app/docs/getting-started)에서 자세히 알아볼 수 있습니다.

React를 배우려면 [React 문서](https://reactjs.org/)를 확인하세요.

### 코드 분할

이 섹션은 [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)으로 이동했습니다.

### 번들 크기 분석

이 섹션은 [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)로 이동했습니다.

### 진보적인 웹 앱 만들기

이 섹션은 [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app]으로 이동했습니다.

### 고급 설정

이 섹션은 [https://facebook.github.io/create-react-app/docs/advanced-configuration]https://facebook.github.io/create-react-app/docs/advanced-configuration)으로 이동했습니다.

### 배포

이 섹션은 [https://facebook.github.io/create-react-app/docs/deployment]으로 이동했습니다.

### `npm run build` 가 실패했을 시

이 섹션은 [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)으로 이동했습니다.
