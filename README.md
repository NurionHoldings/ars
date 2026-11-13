# 보이는 ARS 화면

주식회사 아르카온 전화 안내 화면 — https://nurionholdings.github.io/ars/

'보이는 ARS' 안드로이드 앱이 걸려 온 전화에 보내는 메뉴 문자의 링크로 열린다.
내용은 `config.json`만 고치면 된다 (회사명, 인사말, 전화번호, 메뉴).

메뉴 항목 필드: `key`, `title`, `text`, 선택 `map`(지도 검색어), `url`/`urlLabel`, `sms`/`smsLabel`,
`imageText`(그림용 문구) — `sms`는 앱이 알아듣는 메뉴 번호, 누르면 그 번호가 든 문자 작성 화면이 열린다.

`?image`를 붙여 열면(https://nurionholdings.github.io/ars/?image) 모든 안내를 펼친 그림용 화면이 된다.
앱이 MMS로 보내는 메뉴 그림은 이 화면을 캡처해 만든다 (`imageGreeting`, `imageText` 사용).
