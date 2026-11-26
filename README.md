# 케이소프트 (KEISOFT)

[https://keisoft.kr](https://keisoft.kr) 홈페이지와, 케이소프트가 직접 만든 Windows 프로그램의 소개 페이지·설치 파일을 담은 저장소입니다.

전체 프로그램은 **[keisoft.kr/sw](https://keisoft.kr/sw/)** 에서 화면과 함께 볼 수 있습니다. (한국어 브라우저가 아니면 영어로 표시되고, 상단 `EN` / `한국어` 버튼으로 바꿀 수 있습니다.)

## 프로그램

| 프로그램 | 설명 | 소개 페이지 | 설치 파일 |
|---|---|---|---|
| **ClipPin** | 복사한 텍스트·이미지를 기록하고, 고정 항목을 숫자 키로 붙여넣는 클립보드 관리자 | [소개](https://keisoft.kr/clippin/) | [ClipPin-Setup.msi](https://keisoft.kr/clippin/ClipPin-Setup.msi) |
| **NoeulPlayer** | 코덱 설치 없이 바로 재생되는 가볍고 깔끔한 동영상 플레이어 | [소개](https://keisoft.kr/noeulplayer/) | [일반판](https://keisoft.kr/noeulplayer/NoeulPlayer-1.1.0-x64.msi) · [Lite판](https://keisoft.kr/noeulplayer/NoeulPlayer-Lite-1.1.0-x64.msi) |
| **WorkLog** | 표·그림·할 일·SQL 쿼리를 한곳에 기록하는 업무일지 프로그램 | [소개](https://keisoft.kr/worklog/) | [WorkLog-Setup.msi](https://keisoft.kr/worklog/WorkLog-Setup.msi) |
| **ZipRush** | 모든 CPU 코어로 빠르게 압축하고 푸는 압축 프로그램 | [소개](https://keisoft.kr/ziprush/) | [ZipRush-Setup.msi](https://keisoft.kr/ziprush/ZipRush-Setup.msi) |
| **QuickCapture** | 항상 화면 위에 떠 있다가 필요한 순간 바로 찍고 편집하는 캡처 도구 | [소개](https://keisoft.kr/quickcapture/) | [QuickCapture.msi](https://keisoft.kr/quickcapture/QuickCapture.msi) |
| **PhotoView** | 폴더를 훑어보고, 크게 열어 보고, 바로 고치는 이미지 관리자·뷰어·편집기 | [소개](https://keisoft.kr/photoview/) | [PhotoView.msi](https://keisoft.kr/photoview/PhotoView.msi) |

모두 Windows 10/11용입니다. 설치 파일에 코드 서명이 없어서, 처음 실행할 때 Windows SmartScreen 경고가 나올 수 있습니다.

## 저장소 구성

```
index.html        메인 페이지 (keisoft.kr)
sw/               전체 프로그램 소개 (카드 목록, 한/영 전환)
clippin/          ClipPin 소개 페이지 + 설치 파일
noeulplayer/      NoeulPlayer 소개 페이지 + 설치 파일
worklog/          WorkLog 소개 페이지 + 설치 파일
ziprush/          ZipRush 소개 페이지 + 설치 파일
quickcapture/     QuickCapture 소개 페이지 + 설치 파일
photoview/        PhotoView 소개 페이지 + 설치 파일
CNAME             사용자 지정 도메인 (keisoft.kr)
```

프로그램마다 폴더 하나에 `index.html`(소개 페이지)과 설치 파일(`.msi`)을 함께 둡니다. 폴더 이름이 곧 주소라서 `quickcapture/` 폴더는 `https://keisoft.kr/quickcapture/` 로 열립니다.

## 문의

개발 문의는 [keisoft.kr](https://keisoft.kr/#contact) 의 문의 항목을 이용해 주세요.
