# 도기 보나-한국어 사전

검색 기능이 있는 간단한 도기 보나-한국어 사전

그때그때 도기 보나 단어를 찾아보기 위한 목적에서 만들었으며, pu word뿐 아니라 ku word까지 망라할 예정이다. (현재 작업 중)

이 사전은 여러 출처의 정보를 취합한 것으로, 자세한 것은 CREDITS.md 파일을 참조하기 바란다.

본 페이지는 [jProgr 님의 TokiPonaDictionary]를 수정 및 변형하여 제작한 것임을 분명하게 밝힌다.

## Development

The project uses NPM and its ecosystem. So to run it you need at least:

- Node 14.

To begin install depencies using NPM:

```
npm i
```

Now you can start up a server for development:

```
npm start
```

This will lint the code and make the page available at `http://localhost:9000/`.

### Build

To build everything for release or deployment use:

```
npm run build
```

### Utilities

The project includes other commands to aid development.

To see the page in any other device in your local netwrok you can use the following command:

```
npm run start:open
```

This will make the page available under `<IP of the device running the dev server>:9000`. Good for testing in mobile devices.

The command `npm run start:prod` does the same but uses production mode (more optimizations).

#### Linting

To project uses ESLint, to run it use:

```
npm run lint
```
