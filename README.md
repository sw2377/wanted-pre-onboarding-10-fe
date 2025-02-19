# Updated
🔗 [블로그에 정리한 STUDY NOTE](https://faystory.tistory.com/entry/%EC%9B%90%ED%8B%B0%EB%93%9C-%ED%94%84%EB%A6%AC%EC%98%A8%EB%B3%B4%EB%94%A9-FE-%EC%B1%8C%EB%A6%B0%EC%A7%80-10%EC%9B%94-%EB%A1%9C%EA%B7%B8%EC%9D%B8-%EA%B8%B0%EB%8A%A5-%EA%B5%AC%ED%98%84-%ED%95%98%EB%82%98%EB%B6%80%ED%84%B0-%EC%97%B4%EA%B9%8C%EC%A7%80) <br />
🔗 [과제 Pull Request](https://github.com/blueStragglr/wanted-pre-onboarding-10-FE-quest/pull/105)

### 🚀 client, server 실행
```shell
# client 실행
cd client
npm install
npm run dev

# server 실행
cd server
npm install
npm start
```

```
✅ 테스트 계정 : test / qwer1234
```

### 🚀 로컬 환경에서 CORS 이슈를 방지하기 위해 아래의 방법을 이용해 브라우저를 실행
```shell
# MacOS terminal

$ open -n -a /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --args --user-data-dir="/tmp/chrome_dev_test" --disable-web-security
```


### 🔖 강의가 끝난 후 복습 겸 추가된 부분
- 원티드 프리온보딩 FE 챌린지 10월 - 4일차 강의 server 가져와 세팅
  1. 로그인/로그아웃 추가 (세션 로그인 기반)
  2. 로그인 여부에 따라 보여줄 수 있는 페이지 제어 (```GeneralLayout, AuthLayout``` 사용)

<div style="display: flex; flex-direction: column; gap: 10px; align-items: center; justify-contents: center; width: 100%;">
  <img style="width: 100%; max-width: 500px" src="https://github.com/sw2377/wanted-pre-onboarding-10-fe/assets/85465266/296e143d-aa4c-42f5-afc9-13a8902fda40">
  <img style="width: 100%; max-width: 500px" src="https://github.com/sw2377/wanted-pre-onboarding-10-fe/assets/85465266/642d4eac-4ecc-4dda-9858-c148ea3a1980">
</div>

<br />
<br />

# 10월 원티드 프리온보딩 프론트엔드 사전과제

수강생 여러분 안녕하세요 :)

10월 프론트엔드 프리온보딩 과정 진행을 위해, 아래의 내용을 읽고 사전 과제를 수행해 주세요.

사전 과제는 해당 레포지토리를 포크하여 시작하시면 되며, Pull Request를 생성해 제출해 주세요.

제출을 위해 PR을 머지하실 필요는 없습니다. 

PR을 생성하신 후, 구글 설문지(https://forms.gle/Y4xBHGSgCMdfEA3M6)를 통해 PR 링크를 제출해 주시면 제출이 완료됩니다.


## 만들어야 할 것

이번 프리온보딩에서는 로그인과 API 호출 등에 대해 다룹니다.

과정 진행 전 관련 지식의 워밍업을 위해, 아래의 요구사항을 충족하는 페이지를 만들어 주세요.

### 페이지 1
- 아이디, 비밀번호를 입력할 수 있는 폼이 있는 페이지
- 클릭해서 아이디, 비밀번호를 콘솔에 출력할 수 있는 버튼

### 페이지 2
- Mock API를 이용해 화면에 호출 결과를 출력하는 페이지
  - 아무 API나 호출하여도 상관 없으며, 포매팅도 아무렇게나 해도 괜찮습니다. API 호출 구문을 작성해 보는 경험을 위한 과제입니다.
  - 만약 호출할 API가 마땅치 않으면, `'GET', https://64f732e69d775408495348ae.mockapi.io/api/v1/authmock` 를 호출하세요. 혹시 정상적으로 호출되지 않는다면 mockapi.io 에서 새 API를 생성해 주세요.

페이지의 스타일은 신경쓰지 않아도 괜찮습니다. 생각나는 적절한 로그인 페이지를 모방하여 만들어 주세요.

곧 강의에서 뵙겠습니다 :)

