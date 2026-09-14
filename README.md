# 상권·상업입지 분석 연구 사이트

이 저장소는 ITS OpenAPI 등 공공데이터 활용신청 시 사용할 수 있는 연구·개발 프로젝트 소개 사이트입니다.

## GitHub Pages 공개 설정

1. GitHub 저장소의 **Settings**로 이동
2. 왼쪽 메뉴에서 **Pages** 선택
3. **Build and deployment** → **Source**를 `Deploy from a branch`로 선택
4. Branch를 `main`, Folder를 `/ (root)`로 선택
5. **Save**
6. 배포가 완료되면 보통 다음 주소에서 사이트가 열립니다.

`https://cminpark.github.io/trade-area-research/`

이 주소를 국가교통정보센터 OpenAPI 신청 화면의 **사용처(사이트)**에 입력하면 됩니다.

## 보안 주의

- ITS, VWorld, SGIS 등 API 인증키는 이 공개 저장소에 커밋하지 않습니다.
- 인증키는 로컬 `.env`, Windows 환경변수 또는 별도 비공개 credential 저장소에서 관리합니다.
