# EasyDoRead

광고 · 수집 없는 안드로이드 문서 리더. EasyDo 시리즈.

## 다운로드

최신 버전 0.2.0 — [Releases](https://github.com/parkrye/AppProject_EasyDoRead/releases)에서 기기에 맞는 APK 하나를 받아 설치. Android 8.0 이상.

| 파일 | 대상 |
|---|---|
| `EasyDoRead-<버전>-arm64-v8a.apk` | 대부분의 최근 휴대전화 (64비트) |
| `EasyDoRead-<버전>-armeabi-v7a.apk` | 구형 · 저사양 32비트 기기 |
| `EasyDoRead-<버전>-universal.apk` | 기기 종류를 모를 때 (위 두 가지 포함, 용량 큼) |

- 처음 설치 시 "출처를 알 수 없는 앱" 설치 허용 필요. Play 프로텍트가 검사 화면을 띄울 수 있음
- 업데이트는 새 APK를 같은 방식으로 덮어 설치. 읽기 기록 · 설정 유지
- 앱 안 업데이트 알림 없음. `표시 설정 → 앱 정보 → 새 버전 받기`로 Releases 페이지 확인
- 서명 인증서 SHA-256: `4e36159fe4a5ff3c0f21f7ca91cdbd60eeaf6118f6d5ba8346275f9775ed96d1`
- 버그 · 제안은 [Issues](https://github.com/parkrye/AppProject_EasyDoRead/issues)에

## 기능

- 지원 형식: txt · md · html · Claude Artifact · epub · pdf · 이미지 · hwp/hwpx · docx
- 등록한 폴더의 파일 목록, 최근 읽은 문서, 마지막 문서 이어 읽기. 파일 앱의 "다음으로 열기"로도 열기
- 페이지 넘김 방식(세로 연속 · 세로 페이지 · 가로 페이지), 찾기 · 바꾸기, 목차, 페이지 · 퍼센트 이동, 다 읽으면 같은 폴더의 다음 파일 열기
- 표시 설정(목록 · 최근 · 리더 화면의 톱니 아이콘): 글꼴(추가 가능) · 글자 크기 · 줄 간격 · 여백 · 색 테마 · 글자색 · 배경색 · 배경 이미지 · 다음 파일 정렬
- 표시 설정 맨 아래 `앱 정보` 영역: `앱 정보`(버전 표시, 앱 정보 화면) · `새 버전 받기` · `오픈소스 라이선스`
- 앱 정보 화면: 앱 이름 · 버전 · 개인정보 · 저작권 · 새 버전 받기 · 오픈소스 라이선스

## 개인정보

인터넷은 문서 표시에만 사용 · 광고 없음 · 수집 · 전송 없음.

- 수집 · 전송하는 데이터 없음. 계정 · 광고 · 사용 통계 · 오류 보고 없음
- 등록 폴더 권한, 읽기 기록, 표시 설정, 추가한 글꼴 · 배경 이미지는 기기 안에만 저장. 앱 삭제 시 함께 삭제. 구글 클라우드 백업 제외
- 인터넷 권한은 HTML 문서(Claude Artifact 등)가 참조하는 외부 이미지 · 스크립트 로드에만 사용

## EasyDo 시리즈

| 앱 | 용도 | 플랫폼 |
|---|---|---|
| [EasyDoDraw](https://github.com/parkrye/MultiProject_EasyDoDraw) | 그림 · 애니메이션 | Android · Windows |
| [EasyDoWrite](https://github.com/parkrye/AppProject_EasyDoWrite) | 소설 · 글쓰기 | Android |
| [EasyDoRead](https://github.com/parkrye/AppProject_EasyDoRead) | 책 · 문서 읽기 | Android |
| [EasyDoShelve](https://github.com/parkrye/AppProject_EasyDoShelve) | 웹 소설 서재 | Android |
| [EasyDoPhoto](https://github.com/parkrye/AppProject_EasyDoPhoto) | 카메라 · 사진 편집 | Android |
| [EasyDoDiet](https://github.com/parkrye/AppProject_EasyDoDiet) | 식단 · 운동 기록 | Android |
| [EasyDoZip](https://github.com/parkrye/AppProject_EasyDoZip) | 파일 · 압축 관리 | Android |
| [EasyDoGame](https://github.com/parkrye/AppProject_EasyDoGame) | 미니 게임 모음 | Android |
| [EasyDoMix](https://github.com/parkrye/AppProject_EasyDoMix) | 영상 · 오디오 편집 | Android |
| [EasyDoRecord](https://github.com/parkrye/AppProject_EasyDoRecord) | 녹음 | Android |
| [EasyDoStudio](https://github.com/parkrye/DesktopProject_EasyDoStudio) | 화면 녹화 · 영상 편집 | Windows |

## 라이선스

MIT License · © parkrye. 포함된 서드파티 라이브러리 라이선스는 앱 안 `표시 설정 → 앱 정보 → 오픈소스 라이선스`에서 확인.
