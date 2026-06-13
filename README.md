# sjglobal.inclicks.kr

에스제이글로벌 공식 사이트 (회사 소개 · 클린쿨타임 앱 소개 · 개인정보처리방침).
GitHub Pages로 호스팅되는 정적 사이트입니다.

## 구성

- `index.html` : 회사 소개 + 앱 소개 + 개인정보처리방침 요약
- `privacy.html` : 개인정보처리방침 전문 (Google Play 제출용 URL)
- `CNAME` : 커스텀 도메인 설정 (`sjglobal.inclicks.kr`)
- `og-image.png`, `icons/icon-192.png`, `favicon.ico` : 공유 카드 및 아이콘
- `robots.txt`, `sitemap.xml` : 검색엔진 안내

## Google Play 제출용 개인정보처리방침 URL

```
https://sjglobal.inclicks.kr/privacy.html
```

## 도메인 연결 (DNS)

도메인 등록기관에서 CNAME 레코드 1개를 추가합니다.

| 유형 | 호스트 | 값 |
| --- | --- | --- |
| CNAME | `sjglobal` | `SJ-Song83.github.io` |
