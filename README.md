# ThatFlag legal pages

스토어용 공개 페이지입니다. Cloudflare Pages에 올리면 HTTPS URL이 생깁니다.

- [`index.html`](./index.html) — 한국어 개인정보 처리방침
- [`en.html`](./en.html) — English Privacy Policy

## Cloudflare Pages 연결

1. [Cloudflare Dashboard](https://dash.cloudflare.com) → **Workers & Pages** → Create → Pages → **Connect to Git**
2. GitHub에서 `Indie-Hackerz/thatflag-legal` 선택
3. Build: Framework **None**, Build command 비움, Output directory 비움 또는 `/`
4. Deploy 후 `https://<프로젝트명>.pages.dev` 확인
5. App Store Connect / Play Console 개인정보 처리방침 URL에 입력

로컬 클론은 필요 없습니다.
