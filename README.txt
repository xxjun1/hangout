THE HANGOUT - 시작 안내

1) 압축을 푼 뒤 폴더 안의 firebase-config.js를 확인하세요.
   현재 대화에서 알려준 Firebase 프로젝트 설정을 넣어 두었습니다.
2) Firebase Console > Authentication > Sign-in method에서 Anonymous를 켭니다.
3) Realtime Database > Rules에서 database.rules.json의 내용을 붙여넣고 게시합니다.
4) index.html은 ES module을 사용하므로 파일을 더블클릭(file://)해서 열면 브라우저가 차단할 수 있습니다.
   VS Code의 Live Server 또는 GitHub Pages 같은 정적 호스팅으로 실행하세요.
5) 친구와 같은 방 코드를 공유하면 채팅과 밸런스 게임 투표가 실시간으로 동기화됩니다.

주의:
- 현재는 친구끼리 기능을 시험하는 초기 프로토타입입니다.
- 규칙은 로그인한 익명 사용자에게 방 데이터 쓰기를 허용하므로, 공개 배포 전에는 방 멤버 검증/데이터 검증/스팸 방지 규칙을 추가해야 합니다.
- 이 ZIP에는 포커 기능이 포함되어 있지 않습니다.
- Firebase 웹 설정의 apiKey는 웹 앱 식별용 설정값이지 서버 비밀키가 아닙니다. 서비스 계정 키나 비밀번호는 공개하지 마세요.
