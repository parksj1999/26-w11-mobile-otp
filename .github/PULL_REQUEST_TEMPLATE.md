## 제출자

이름: 

## 배포 링크

<!-- 아래 예시 형식을 확인하고 실제 접속 가능한 웹 URL을 입력해 주세요 (.git 주소나 localhost 금지!) -->
- Netlify 배포 URL: 
- GitHub Pages 배포 URL: 

## Release 태그

- 태그: 

## 체크리스트

- [ ] `dev` → `main` 방향으로 PR을 보냈다 (main은 원본 보관용이므로 실제 merge는 하지 않습니다 — 리뷰용 제출입니다)
- [ ] 두 배포 사이트(Netlify, GitHub Pages)가 정상 접속되며 모바일 OTP 기능이 동작한다
- [ ] Secret Key 생성 시 `Math.random()`이 아닌 `crypto.getRandomValues()` 등 Web Crypto API를 사용했다
- [ ] QR 코드(`otpauth://totp/...`)를 스마트폰 Authenticator 앱으로 스캔했을 때 PC 화면의 6자리 OTP와 실시간으로 일치함을 확인했다
- [ ] 코드에 불필요한 시크릿 키나 `.env` 파일이 포함되어 있지 않다
- [ ] `dev` 브랜치의 `README.md`를 작성했다 (앱 컨셉 / AI 기획·구현 과정 / TOTP 보안 점검 / 배포 링크)
- [ ] Git 태그(v1.0)를 생성하고 push했다

## 한 줄 소감

<!--
1. 이번 주에는 복붙 프롬프트 없이 처음부터 스스로 기획해 보았습니다. 어떤 AI 활용 방식(Gemini 웹 기획 + Antigravity IDE 구현 / Antigravity Plan / Copilot 병행 등)을 썼고, 직접 설계·디버깅해 보니 무엇을 느꼈나요?
2. 모바일 OTP가 서버와 통신하지 않고도 스마트폰 앱과 6자리 숫자가 일치하는 원리와 Web Crypto API의 보안적 의미를 한 줄로 정리해 주세요.
-->
