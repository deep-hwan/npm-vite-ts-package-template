# <div align="left">

<h1>NPM-Package-Template</h1>

<p>
ReactJs, Vite , Typescript 환경의 NPM 패키지를 쉽게 배포할 수 있도록 셋팅된 템플릿입니다

</p>
</div>

[![GitHub](https://img.shields.io/github/license/beforesemicolon/flatlist-react)](https://github.com/deep-hwan/npm-vite-ts-package-template/blob/main/LICENSE)

# [package-name](https://github.com/deep-hwan/npm-react-typescript-package-template)

</div>

## 배포 후 Install 셋팅

    npm install package-name

    yarn add package-name

---

## 배포 방법

1. package.json >> version 설정
2. padkage.json >> description / repository.url / keywords 수정
3. vite.config.ts >> build > lib > name 수정
4. src > package > index.tsx 내에 배포할 패키지 export로 반환 셋팅
5. npm login >> npm 로그인
6. npm publish >> 패키지 버전 배포

---

## License

MIT © Deepfactory, Inc. See [LICENSE](LICENSE) for details.

<!-- BOTTOM LOGO -->
<a title="DEEP" href="https://www.deepfactory.kr/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./src/assets/deep-white.png">
    <img alt="DEEP" src="./src/assets/deep-dark.png" width="120">
  </picture>
</a>
<!--  -->
