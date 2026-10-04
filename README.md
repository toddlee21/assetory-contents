# Assetory Brief

Assetory 앱에서 읽는 공개 교육 콘텐츠입니다.

- 주소: https://toddlee21.github.io/assetory-contents/
- 콘텐츠 목록: https://toddlee21.github.io/assetory-contents/manifest.json
- 2026년 10월–2027년 12월, 매월 8일 Learn / 23일 Insight
- Learn 15편 + Insight 15편, 총 30편

## 배포 구조

이 저장소에는 승인된 공개 JSON과 안내 페이지만 있습니다. 앱 소스, 글 DB 원본, 내부 검토 자료, 계좌 데이터, 개인 백업, 인증·서명 키는 포함하지 않습니다.

GitHub Pages의 Source는 Deploy from a branch, Branch는 main / (root)로 설정합니다. manifest.json과 articles/*.json을 정적 HTTPS 파일로 제공합니다. 별도 유료 서버나 로그인 기능은 사용하지 않습니다.

## 발행일

앱은 각 글의 publishDate에 도달하기 전에는 제목·본문을 숨깁니다. 미래 글을 포함한 JSON 파일은 공개 저장소와 웹 주소에서 미리 읽을 수 있습니다. 월별 게시를 위한 별도 예약 작업은 필요하지 않습니다.

새 콘텐츠 다운로드에는 인터넷이 필요합니다. 내려받은 글은 앱의 콘텐츠 캐시에 저장되며 자산 데이터와 분리됩니다. 글을 수정할 때는 같은 ID를 유지하고 revision을 증가시키며 최종 원고에 대한 승인을 다시 받습니다.

교육 콘텐츠이며 투자·법률·세무 자문이나 수익 보장을 제공하지 않습니다.
