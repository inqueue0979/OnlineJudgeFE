# 칭다오 대학 온라인 저지 FE 한국어 번역판

  

>### OJ 시스템을 위한 기본적인 프론트엔드.

  

## 설치 방법

  

node.js **v14.17.3** 버전을 먼저 설치하세요.

  

### Linux

  

```bash

npm  install

# we use webpack DllReference to decrease the build time,

# this command only needs execute once unless you upgrade the package in build/webpack.dll.conf.js

export  NODE_ENV=development

npm  run  build:dll

  

# the dev-server will set proxy table to your backend

export  TARGET=http://Your-backend

  

# serve with hot reload at localhost:8080

npm  run  dev

```

### Windows

  

```bash

npm  install

# we use webpack DllReference to decrease the build time,

# this command only needs execute once unless you upgrade the package in build/webpack.dll.conf.js

set  NODE_ENV=development

npm  run  build:dll

  

# the dev-server will set proxy table to your backend

set  TARGET=http://Your-backend

  

# serve with hot reload at localhost:8080

npm  run  dev

```