# STRIDE Android 배포

APK 설치 파일과 배포 안내를 제공하는 저장소입니다.

## 다운로드

[STRIDE v0.4.0 APK 다운로드](https://github.com/korcrash-bit/stride-releases/releases/download/v0.4.0/STRIDE-0.4.0.apk)

[릴리스 안내](https://github.com/korcrash-bit/stride-releases/releases/tag/v0.4.0) · [배포 CI](https://github.com/korcrash-bit/stride-releases/actions/runs/40327332885) · [공개 다운로드 검증](https://github.com/korcrash-bit/stride-releases/actions/runs/40327728978)

Android 8.0 이상 · 패키지 `kr.stride.workout` · APK 버전 0.4.0

## 이번 버전

- 중량·횟수의 빈 값, 0, 소수를 구분하고 기존 숫자를 쉽게 바꿀 수 있습니다.
- 운동 화면 하단에서 총 운동 시간과 남은 휴식을 계속 확인합니다.
- 앱 전면에서 화면 켜짐을 유지하고, 휴식 10초 전과 마지막 5초에 소리·진동으로 알립니다. 무음·방해 금지 설정을 따릅니다.
- 연하늘색 내부 테마와 운동 종목·별칭 검색을 적용했습니다.
- 진행 중인 운동 이어하기를 강조했습니다.
- 완료한 헬스·러닝 기록을 수정하고 헬스 기록을 새 루틴으로 저장할 수 있습니다.
- 기존 앱을 삭제하지 말고 업데이트 설치하세요. 기존 패키지와 서명을 유지합니다.

## 자동 업데이트 사용

v0.3.4 이상은 앱 실행·복귀 시와 사용 중 5분 간격으로 최신 APK를 확인하고 자동 다운로드합니다. 크기·SHA-256·패키지·서명·버전을 검증한 뒤 Android 설치를 안내합니다. 앱 설치 허용과 최종 설치 확인은 직접 눌러 주세요. v0.3.3 이하에서는 새 APK를 한 번 직접 내려받아 업데이트해야 합니다.

앱을 완전히 종료한 동안의 자동 업데이트·휴식 알림은 수행하지 않습니다. 데이터 관리에서 실제 APK 버전, 최신 버전, 다운로드 진행과 설치 버튼을 확인할 수 있습니다.

## 검증

- 파일 크기: **3,638,146 bytes**
- SHA-256: `072d2fecfda5de5aa4b742fbdd710f3979b70a18deaa91257ee4de8b50365810`
- 인증 없이 공개 URL에서 다운로드한 APK는 준비한 원본과 바이트 단위로 일치합니다.
- 웹·서버 테스트 52개, 네이티브 정책 검사 51개, 타입 검사, 웹/Android 빌드, Android 린트와 APK 서명 검사를 통과했습니다.
- 실제 휴대폰의 키보드·하단바·소리·진동·최종 설치 동작은 별도 확인이 필요합니다.

웹 앱: https://stride-workout-log.lollorulru.chatgpt.site/
