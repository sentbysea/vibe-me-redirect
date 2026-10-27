# vibe-me-redirect

옛 주소 바이브.me(`xn--9g3b29an0p.me` · `www.`)를 정식 주소 **ho.바이브.me**(`ho.xn--9g3b29an0p.me`, 저장소 `sentbysea/home-sweet-home`)로 넘긴다.

- GitHub Pages 의 Custom domain = `xn--9g3b29an0p.me`. 어느 경로든 `index.html` · `404.html` 이 같은 경로 · 쿼리 · 해시로 `location.replace`.
- 해시를 그대로 넘기므로 옛 주소로 돌아온 Google 로그인(`#access_token=…`)도 새 주소에서 이어진다.
- DNS(예스닉, 네임서버 dns1~4.yesnic.com): apex A 185.199.108~111.153 · www CNAME `sentbysea.github.io.` 그대로. 새 주소는 `ho` CNAME `sentbysea.github.io.`
