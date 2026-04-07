## 웹 서버 만들기
- Language: javascript
- 개발환경: Node.js
- 서버 설치 명령어: npm init -y ->package.json

### Expredd 프레임워크 설치
- 설치: npm install express
- import 사용 - ES6 문법
- package.json 에서 변경(import)
  "type": "module",
- 서버 자동 실행 : nodemon 설치
    npm i nodemon
    package.json에 설정
    "start": "nodemon index.js"
    실행 명령어 - npx nodemon index