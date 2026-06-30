# VocaNote

VocaNote는 단어장을 만들고 정리하며 학습할 수 있는 웹 애플리케이션입니다. 나만의 단어 세트를 만들고 단어와 뜻을 추가한 뒤, 플래시카드 · 객관식 퀴즈 · 쓰기 연습으로 학습할 수 있습니다.

[English](README.md)

## 주요 기능

- **인증** — 회원가입 및 로그인 후 나만의 단어 세트 관리
- **단어 세트** — 단어 세트 생성, 검색, 조회
- **단어 추가** — 세트에 단어와 뜻 추가
- **학습 모드**
  - 플래시카드 (`study/card`)
  - 객관식 퀴즈 (`study/multiple`)
  - 쓰기 연습 (`study/write`)
- **검색** — 기존 단어 세트 검색

## 기술 스택

- [React 19](https://react.dev/)
- [React Router 7](https://reactrouter.com/)
- [Vite](https://vite.dev/)
- [Axios](https://axios-http.com/)
- [React Icons](https://react-icons.github.io/react-icons/)

## 시작하기

### 사전 준비

- Node.js
- npm

### 설치

```bash
npm install
```

### 개발 서버 실행

```bash
npm run dev
```

### 빌드

```bash
npm run build
```

### 빌드 결과 미리보기

```bash
npm run preview
```

### 린트

```bash
npm run lint
```

## 배포

이 프로젝트는 [Vercel](https://vercel.com/) 배포를 위한 [vercel.json](vercel.json) 설정을 포함하고 있습니다.
