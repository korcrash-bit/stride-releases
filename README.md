# STRIDE Android 배포

APK 설치 파일과 배포 안내를 제공하는 저장소입니다. 앱 원본 소스는 포함하지 않습니다.

## 다운로드

[STRIDE v0.3.4 APK 다운로드](https://github.com/korcrash-bit/stride-releases/releases/download/v0.3.4/STRIDE-0.3.4.apk)

[릴리스 안내](https://github.com/korcrash-bit/stride-releases/releases/tag/v0.3.4) · [배포 CI](https://github.com/korcrash-bit/stride-releases/actions/runs/40264492572) · [공개 다운로드 검증](https://github.com/korcrash-bit/stride-releases/actions/runs/40264747251)

Android 8.0 이상 · 패키지 `kr.stride.workout` · APK 버전 0.3.4

## 이번 버전

- APK 자동 업데이트 확인·다운로드·설치 안내를 추가했습니다.
- STRIDE 모양을 유지하면서 앱 아이콘을 하늘색 배경과 흰색으로 변경했습니다.
- 기존 앱을 삭제하지 말고 APK를 업데이트 설치하세요.
- v0.3.3 이하에서는 이번 v0.3.4 APK를 한 번 직접 설치해야 합니다.

## 자동 업데이트 사용

앱 실행·복귀 시, 사용 중 5분 간격으로 GitHub의 최신 정식 APK를 확인합니다. 새 파일은 자동 다운로드하며 크기·SHA-256·패키지·서명·버전 코드를 검사합니다. 준비되면 설치를 안내합니다. 첫 앱 내 업데이트 때 Android의 STRIDE 앱 설치 허용을 선택하고, 마지막 설치 확인은 직접 눌러 주세요. 앱을 완전히 종료한 동안의 백그라운드 업데이트는 수행하지 않습니다.

데이터 관리에서 실제 설치된 APK 버전, GitHub 최신 버전, 다운로드 진행률과 설치 버튼을 볼 수 있습니다. 웹 화면 버전과 APK 버전을 구분합니다.

## 검증

- 파일 크기: **3,634,486 bytes**
- SHA-256: `f63f445a7fdc15024844699721c33f7a507befcffdead09f49a635617a671041`
- 공개 URL에서 인증 없이 다운로드한 파일은 원본과 바이트 단위로 같습니다.
- 기존 자동 테스트 39개, 업데이트 정책 검사 20개, 타입 검사, 최종 아이콘 반영 후 Android 빌드·린트·동일 서명 검증을 통과했습니다.
- 실제 휴대폰의 설치 허용·최종 설치·취소 및 다음 버전 자동 업그레이드 흐름은 별도 확인이 필요합니다.

웹 앱: https://stride-workout-log.lollorulru.chatgpt.site/
