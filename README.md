# 실시간 이모티콘 보내기

초보자 수업용 실시간 반응 웹앱입니다. 학생은 이모티콘을 보내고, 강사는 누적 수와 방금 도착한 반응을 확인할 수 있습니다.

## 실행 방법

`index.html` 파일을 인터넷에 연결된 상태에서 더블클릭해 브라우저로 엽니다. 학생 모드는 바로 사용할 수 있고, 강사 모드의 비밀번호는 `1004`입니다.

## Firebase 설정

이 앱은 Firebase Realtime Database의 `practice/reactions` 경로를 사용합니다. Firebase 콘솔에서 Realtime Database를 테스트 모드로 설정해야 읽기와 쓰기가 가능합니다.

`index.html`에는 Firebase 설정값이 이미 포함되어 있습니다. Firebase Authentication 로그인이나 회원가입은 사용하지 않습니다.

## 안내

비밀번호 `1004`는 실습용 화면 진입 제한일 뿐 실제 데이터 보안을 보장하지 않습니다. 수업이 끝난 뒤에는 Firebase 보안 규칙을 적절히 변경해 주세요.
