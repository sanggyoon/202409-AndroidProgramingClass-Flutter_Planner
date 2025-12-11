# 프로젝트 소개

---

> 주제
> 
> - To Do List 애플리케이션

> 목표
> 
> - SDLS (Software Development Life Cycle)의 이해
> - Dart 언어 학습
> - 요구사항 명세서 작성 실습 - 최대한 구체적으로 작성
> - 스마트폰에 apk를 직접 설치하여 실행

> 개발 기간
> 
> - 2025.09 ~ 2025.11

> 담당한 부분, 역할
> 
> - 싱글 프로젝트

# 요구사항 명세서

---

![image.png](attachment:035f6c55-262f-474b-8f40-cab9790987f5:image.png)

![image.png](attachment:5f51c9da-7d74-41ad-a9f9-224207486143:image.png)

# 화면 설계

---

![image.png](attachment:d072d1cc-a399-4bf4-add6-5f2bde6dc98c:image.png)

![image.png](attachment:005e1586-f66e-43a6-9a9b-656a9b2b7b65:image.png)

![image.png](attachment:2c8803b3-2edc-41a5-a33c-b0494b743e34:image.png)

# 기능 흐름도

---

![image.png](attachment:9e80662e-81e0-4a24-b467-8cd252f2f7bf:image.png)

# 트러블 슈팅 - 증상 및 원인

---

1. 본인은 맥북과 아이폰을 사용하였고 수업은 윈도우와 안드로이드 기반으로 진행되었습니다.
프로젝트 결과물은 apk 파일을 요구하였기에 수업 내용만 가지고 진행할 수 없었습니다.
2. firebase와 플러터의 버전 업데이트가 있었습니다.
기존에 사용하던 방법(강의 자료, 리서치)으론 firebase를 사용할 수 없었습니다.
개발 당시엔 업데이트가 최근 진행되어 AI도 관련 정보를 찾을 수 없었습니다.

# 트러블 슈팅 - 변경 내용 및 해결 과정

---

1. flutter를 설치하고 터미널에 ‘flutter doctor’를 입력하면 환경에 맞는 요소들을 검사할 수 있습니다.
검사 결과 Xcode, CocoaPods, AndroidStudio가 문제가 되었습니다. 
CocoaPods는 단순 설치로 해결되었고 Xcode와 AndroidStudio는 원하는 SDK 설치와 환경 변수 설정이 핵심이었습니다.
2. 구글 firebase 공식 홈페이지에서 업데이트에 대한 내용과 플러터에서 사용하는 방법이 영문으로 작성되어 있던 것을 찾을 수 있었습니다.
아무런 외부 도움 없이 공식 홈페이지만을 번역하여 한 단계씩 따라하였고 성공적으로 연결할 수 있었습니다.

# 회고

---
