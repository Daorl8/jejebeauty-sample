# STRUCTURE · jejebeauty-sample

```
jejebeauty-sample/
├─ index.html                 단일 파일 (CSS·JS 인라인)
├─ wrangler.toml              name = jejebeauty-sample → jejebeauty-sample.lgt3232.workers.dev
├─ .assetsignore              img/·문서·index_*.html·미사용 webp 배포 제외
├─ jj-gilda.woff2             영문 제목 (Gilda Display · GHEA Ararat 대체)
├─ jj-interop-400/500.woff2   한글·본문 (Interop · 사용 글자만 → 글자 추가 시 재생성)
├─ jj-*.webp                  사진 22장 (hero·spatula·room = 히어로 크로스페이드)
├─ jj-logo.png                로고 (투명 · 푸터)
├─ favicon.png                파비콘
├─ og-jeje.jpg                공유 썸네일 1200×630
├─ img/                       다올 제공 원본 179장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로(`#slides`) → `#about`(회색 면) → `#services`(4줄) → `#menu`(회색 면 · 토글 3) → `#studio`(화보 그리드) → 필름 스트립(`#track`) → `#why`(회색 면) → For Waxers → `#visit`(링크 6칸 `.links` + 지도) → 푸터.

## 가격 수정
`.price` 안 `<div class="row"><dt>영문<small>한글</small></dt><dd>금액<small>원</small></dd></div>` 한 줄 = 한 항목. Best 표시는 dt 안 `<span class="best">Best</span>`(형광 녹색).

## 색
`--neon` #B9F322는 4곳만(키커 점 · Best · 버튼 호버 · 선택색). 늘리지 말 것(다올 요청: 최소 사용).
