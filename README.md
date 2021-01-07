# 👾 Codewars
자바스크립트 알고리즘 문제를 풀 수 있는 어플리케이션 제작 과제입니다.

![Codewars](/readme-assets/vc_codewars.gif)

---

## Feature
- 등록된 자바스크립트 알고리즘 문제를 풀 수 있습니다.
- 문제를 풀면 정답 여부를 확인할 수 있습니다.

## How to run
- Package installation & Running local server
```sh
npm install
npm run dev
```

## How to Use
- 깃헙 소셜 로그인 후, 메인 페이지에 접속 할 수 있습니다.
- 메인 페이지에서 각 문제의 레벨과 성공한 유저 수를 볼 수 있습니다.
- 등록되어 있는 알고리즘 문제를 선택하면 문제를 풀 수 있습니다.
- 답변이 틀린 경우, [Retry]를 통해서 다시 풀 수 있습니다.
- 정답을 맞추면 메인 페이지로 이동합니다.
- 상단 [Logout] 버튼으로 로그아웃이 가능합니다.

## Tech Stack
- ES2015+
- Express
- MongoDB Atlas (mongoose)
- Passport
