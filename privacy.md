---
title: uploader-test 개인정보처리방침
---

# uploader-test 개인정보처리방침

시행일: 2026년 10월 24일
운영자: Michael Jun
연락처: realjblues@gmail.com

## 1. 이 앱은 무엇인가

uploader-test 는 운영자가 직접 만든 영상을 운영자 본인의 YouTube 채널, Instagram
비즈니스 계정, Threads 계정에 올리는 개인용 도구입니다. 운영자 외의 사용자는 없으며,
다른 사람이 로그인하거나 자기 계정을 연결하는 기능은 없습니다.

## 2. 처리하는 정보

### YouTube (YouTube API 서비스)

- 운영자 본인 Google 계정의 OAuth 토큰. 요청하는 권한은 둘입니다.
  - `youtube.upload`: 운영자 채널에 영상을 비공개로 올립니다.
  - `youtube.readonly`: 운영자 채널에 올린 영상의 상태를 확인합니다.
- 운영자가 올리는 영상, 제목, 설명, 태그, 업로드 후 받은 영상 ID

### Instagram · Threads

- 운영자 본인 계정의 Instagram 비즈니스 계정 ID, Threads 사용자 ID
- Meta 가 발급한 운영자 본인 계정의 액세스 토큰
- 운영자가 게시하는 영상, 캡션, 게시 후 받은 게시물 ID와 링크

다른 사용자의 개인정보, 구독자 · 팔로워 정보, 댓글, 메시지는 수집하지 않습니다.

## 3. 보관 위치와 기간

- 토큰과 계정 ID는 운영자 본인 컴퓨터에만 저장합니다.
- Instagram · Threads 에 게시할 영상은 Meta 가 가져갈 수 있도록 Cloudflare R2 비공개
  저장소에 잠시 올립니다. 이때 1시간 동안만 유효한 서명 주소를 씁니다. 게시가 끝나면
  그 파일을 지웁니다.
- 업로드 기록(영상 · 게시물 ID와 링크)은 운영자 본인 컴퓨터에 남깁니다.

## 4. 제3자 제공

처리하는 정보를 판매하거나 제3자에게 제공하지 않습니다. 영상은 업로드를 위해
Google(YouTube), Meta(Instagram, Threads), Cloudflare R2 에만 전달됩니다.

이 앱은 YouTube API 서비스를 사용합니다. 이 앱을 쓰면
[YouTube 서비스 약관](https://www.youtube.com/t/terms)에 동의하는 것이며,
Google 이 처리하는 정보에는
[Google 개인정보처리방침](https://policies.google.com/privacy)이 적용됩니다.

## 5. 데이터 삭제와 접근 권한 취소

- 운영자는 본인 컴퓨터에 저장된 토큰과 기록 파일을 지워 언제든 데이터를 삭제할 수 있습니다.
- Google 계정의 [보안 → 타사 앱 액세스](https://myaccount.google.com/connections)에서
  이 앱의 접근 권한을 취소할 수 있습니다.
- Meta 계정 설정의 「앱 및 웹사이트」에서 uploader-test 연결을 해제하면 Meta 토큰이
  무효가 됩니다.
- 이 앱이 본인 정보를 처리했다고 생각하시는 분은 위 연락처로 요청해 주십시오.
  확인한 뒤 30일 안에 삭제하고 결과를 알려 드립니다.

## 6. 변경

이 방침이 바뀌면 이 페이지를 고치고 시행일을 새로 적습니다.
