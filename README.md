# project-hub

내 웹 프로젝트들을 한눈에 모아 보여주는 원페이지 허브 사이트.

- 라이브: https://hocheolshin.vercel.app
- 정적 HTML 단일 파일(`index.html`), 빌드 과정 없음
- `master`에 푸시하면 Vercel이 자동 배포

## 프로젝트 추가 방법

`index.html`의 `<main class="grid">` 안에 카드(`<a class="card">`) 블록을 하나 복사해서 내용만 바꾸면 된다.
배너 색은 `<style>`의 `.b-*` 그라디언트 클래스를 새로 추가해서 지정한다.
