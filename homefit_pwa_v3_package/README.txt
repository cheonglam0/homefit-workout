홈핏 PWA v3 설치 안내
====================

이번 버전 추가 기능
- 오늘 운동·운동 추천·주간 계획에서 운동 항목을 누르면 자세 안내 열기
- 운동별 간단한 SVG 자세 그림(시작 자세/동작 예시)
- 시작 자세, 동작 방법, 호흡, 주의사항, 권장량 표시
- 모바일에 맞춘 팝업 화면 및 닫기 버튼/ESC 지원

포함 파일
index.html, manifest.webmanifest, sw.js, icon.svg, icon-192.png, icon-512.png

GitHub Pages 배포
1. ZIP 압축을 풉니다.
2. GitHub 저장소 homefit-workout을 엽니다.
3. Add file > Upload files에서 위 6개 파일을 저장소 루트에 업로드합니다.
4. Commit changes를 누릅니다.
5. Settings > Pages에서 Source를 Deploy from a branch로 두고 Branch main, Folder /(root)를 선택 후 Save합니다.
6. 표시된 HTTPS 주소를 Android Chrome에서 열고 메뉴 > 앱 설치 또는 홈 화면에 추가를 선택합니다.

업데이트 후 화면이 예전 버전이면 Chrome에서 새로고침하거나 사이트 데이터를 지우고 다시 여세요.
운동 기록은 해당 브라우저의 기기에 저장되며 자동 동기화되지 않으므로 JSON 백업을 권장합니다.
