# :zap: Chromatic을 이용한 React StoryBook 템플릿
:octocat: 바로가기 : https://www.chromatic.com/build?appId=633051a6a2ff8e8fdbbfd709&number=2/ <br />

![chromatic-build-storybook-link](https://user-images.githubusercontent.com/95972251/192449596-10b64796-f612-412e-a6e8-b2b12dc5eb46.png)

:sparkles: React StoryBook 템플릿입니다. :sparkles:
## 🚅 빠른 설치

- StoryBook 개발 환경에 빌드(build) 프로세스를 설정하려면 다음과 같은 설치과정을 거치면 됩니다.

```shell
# Clone the template
npx degit chromaui/intro-storybook-react-template taskbox
```
```shell
# Navigate to the directory
cd taskbox/

# Install the dependencies
yarn
```
- 이제 다양한 환경에서 애플리케이션이 올바르게 작동하는지 아래 명령어를 통해 빠르게 확인할 수 있습니다:
```shell
# Run the test runner (Jest) in a terminal:
yarn test --watchAll

# Start the component explorer on port 6006:
yarn storybook

# Run the frontend app proper on port 3000:
yarn start
```

![app-three-modalities](https://user-images.githubusercontent.com/95972251/192448098-e216ccac-3931-4dd1-8780-271e82bd5eb6.png)

## 🔎 내부 파일

템플릿을 설치하면 다음과 같은 파일 및 디렉토리가 생성됩니다.

    .
    ├── .storybook
    ├── node_modules
    ├── public
    ├── src
    ├── .gitignore
    ├── LICENSE
    ├── package.json
    ├── yarn.lock
    └── README.md

1. **`.storybook`**: 이 디렉토리에는 Storybook의 [구성](https://storybook.js.org/docs/react/configure/overview) 파일이 들어 있습니다.

2. **`node_modules`**: 이 디렉토리에는 프로젝트가 의존하는 모든 코드 모듈(npm 패키지)이 포함되어 있습니다.

3. **`public`**: 이 디렉토리에는 사이트의 개발 및 프로덕션 빌드가 포함되어 있습니다.

4. **`src`**: 이 디렉토리에는 애플리케이션에서 볼 수 있는 것과 관련된 모든 코드가 포함되어 있습니다.

5. **`.gitignore`**: 이 파일은 프로젝트 개발 과정에서 추적하거나 업로드 되지 말아야 할 파일을 git에 알려줍니다.

6. **`LICENSE`**: 이 템플릿으로 인해 MIT 라이선스에 따라 라이선스가 부여됩니다.

7. **`package.json`**: 일반적으로 프로젝트별 메타데이터(Ex: 프로젝트 이름, 작성자 등)를 포함하는 Node.js 프로젝트용 표준 매니페스트 파일입니다. 이 파일을 기반으로 npm은 프로젝트에 필요한 패키지를 알 수 있습니다.

8. **`yarn.lock`**: 프로젝트에 설치된 npm 종속성의 정확한 버전을 기반으로 자동 생성된 파일입니다. **(수동으로 변경하지 마십시오).**

9. **`README.md`**: 프로젝트에 대한 유용한 참조 정보가 포함된 마크다운 텍스트 파일입니다.

## :tada: Chromatic을 이용한 React StoryBook 템플릿 배포
- 자세한 내용은 StoryBook 템플릿 <a href="https://storybook.js.org/tutorials/intro-to-storybook/react/ko/deploy/">링크</a>를 참조하세요.
