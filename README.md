# 🚀 원티드 프리온보딩 프론트엔드 인턴십 WEEK 1-1 과제 (수정중)


## 📚 과제 소개 및 목적  
>1차 과제 : Best Practice


<hr/>

> 🗣️ 과제 진행 방법
- 팀장 정하기, 레포 생성
- 커밋 메시지 규칙 논의
- eslint, prettier 설정
- 공유 노션 페이지 개설
- 과제 진행 스케줄 정하기
- 과제 역할 분담
   - apis - 오신정, 황성택
   - 회원가입/로그인 - 김은정, 박인
   - 투두리스트 - 이민지, 최영수
   - 라우터 및 기타 업무 - 이정우
- organization 생성 후 미션 별 repository 등록
    <br/>

> 🤔 과제 수행 시 고려 사항
- 모든 팀원이 동일한 배경 지식과 코드 수준을 가지고 있는 것이 아니기 때문에, 다같이 협동하며 팀워크를 기르는 것에 집중했다.
    - pr을 이용해 보지 않은 팀원들의 위해 스터디 진행
    - 타입 스크립트 사용
    - 서로 좋은 강의, 문서 자료 공유
- 커밋 메시지, 디스코드 회의 등 문서를 이용한 비동기적 소통을 꾸준히 활용했다.


<hr/>  




## 🖥️ 배포 링크
<hr/>   


## 👨‍👩‍👧‍👦 팀 소개
<hr/>   

## ✨ 프로젝트 실행방법

```
npm install
npm start
```
<hr/>  
## src 폴더 구조

```
📦 src
┣ 📂components
┃ ┣ 📂 register
┃ ┃ ┣ 📄 SignIn.tsx
┃ ┃ ┗ 📄 SignUp.tsx
┃ ┣ 📂 todo
┃ ┃ ┣ 📄 TodoForm.tsx
┃ ┃ ┣ 📄 TodoItem.tsx
┃ ┃ ┗ 📄 TodoList.tsx
┃ ┗ 📄 Navbar.tsx
┣ 📂 lib
┃ ┣ 📂 apis
┃ ┃ ┣ 📄 authApi.ts
┃ ┃ ┣ 📄 axiosInstance.ts
┃ ┃ ┣ 📄 axiosInterceptors.ts
┃ ┃ ┗ 📄 tokenStore.ts
┃ ┣ 📂 types
┃ ┃ ┣ 📄 index.tsx
┃ ┃ ┗ 📄 User.interface.tsx
┃ ┗ 📂 utils
┃   ┣ 📄 AcessTokenStore.tsx
┃   ┣ 📄 Getregex.tsx
┃   ┗ 📄 index.tsx
┣ 📂pages
┃ ┣ 📄 Register.tsx
┃ ┗ 📄 Todo.tsx 
┣ 📄 App.tsx
┗ 📄 index.tsx
```

<hr/>  

### commit msg

> 해당 프로젝트는 comitlint를 활용하여 다음과 같은 commit convention prefix를 가집니다.

| Prefix   | Description                                                                                            |
| -------- | ------------------------------------------------------------------------------------------------------ |
| build    | Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)    |
| ci       | Changes to our CI configuration files and scripts                                                      |
| docs     | Documentation only changes                                                                             |
| feat     | A new feature                                                                                          |
| fix      | A bug fix                                                                                              |
| perf     | A code change that improves performance                                                                |
| refactor | A code change that neither fixes a bug nor adds a feature                                              |
| style    | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc) |
| test     | Adding missing tests or correcting existing tests                                                      |
|          |                                                                                                        |
