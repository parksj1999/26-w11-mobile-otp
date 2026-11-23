# 프로젝트 개발 및 커밋 가이드 (GitHub Copilot Instructions)

이 저장소는 한국폴리텍대학 강서캠퍼스 사이버보안과 1학년 11주차 「모바일 OTP (TOTP 2단계 인증)」 실습 프로젝트입니다.

## 보안 코딩 원칙
- 비밀 키(Base32 Secret)나 난수 생성 시 절대 `Math.random()`을 사용하지 말고 `window.crypto.getRandomValues()`를 사용하세요.
- TOTP(HMAC-SHA1) 계산과 검증은 외부 서버로 비밀 키를 전송하지 않고 브라우저 내장 Web Crypto API(`crypto.subtle`)로 처리하세요.

## Git 커밋 규칙
- 커밋 메시지는 한국어로 작성하되 기술 용어와 코드 표현은 영어 원어를 사용합니다.
- 제목은 50자 내외로 요약하고, 본문에는 주요 변경 사항을 `-` 불릿 포인트로 작성합니다.
