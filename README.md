Nest JS란? 

Node JS를 폏나게 사용할수 있는 프레임 워크.

Nest JS 내부적 구성

내부적으로 Nest는 Node.js 프레임 워크 (Express / Fastify)위에 추상화 수준을 제공하지만 API를 개발자에게 직접 노출합니다. 이를 통해 개라자는 기본 플랫폼에서 사용할 수 있는 수많은 타사 모듈을 자유롭게 사용할 수 있음.

NestJS의 철학

Node를 위한 훌륭한 라이브러리, 도우미 및 도구가 많이 존재.
Nest는 개발자와 팀이 고도로 테스트 가능하고 확장 가능하여, 느슨하게 결합되고 유지 관리가 쉬운 애플리케이션을 만들 수 있고 즉시 사용 가능한 애플리케이션 아키텍처를 제공.
Angular에서 크게 영감을 받음.

Nest JS 공식 문서

https://docs.nestjs.com


폴더 안에서 nest 기본 구조 생성 

npm i -g @nestjs/cli

nest new ./

앱 실행

npm start:dev

Nest JS 기본 구조 설명

eslintrc.js -> 개발자들이 특정한 규칙을 가지고 코드를 깔끔하게 짤 수 있게 도와주는 라이브러리
타입스크립트를 쓰는 가이드 라인제시, 문법에 오류가 나면 알려주는 역할 등등

prettierrc -> 주로 코드 형식을 맞추는데 사용합니다. 작은따옴표(')를 사용할지 큰 따옴표(")를 사용할지, Indent 값을 2로줄지 4로 줄지등등, 에러 찾는 것이 아닌 코드 포맷터 역할

nest-cli.json -> nest 프로젝트를 위해 특정한 설정을 할 수 있는 json 파일

tsconfig.json -> 어떻게 타입스크립트를 컴파일 할지 설정
