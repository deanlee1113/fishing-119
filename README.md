# 🎣 피싱119

낚시 도우미 서비스를 한 곳에서 만나보는 통합 허브.

**Live**: https://fishing-119.pages.dev (배포 후 업데이트)
**Repo**: https://github.com/deanlee1113/fishing-119

## 서비스

- 🔮 [출조일 운세](https://lucky-fishing.deanlee1113.workers.dev/) — 자미두수로 보는 오늘의 출조 운세
- 📹 [낚시캠](https://fishing-cam.deanlee1113.workers.dev/) — 전국 CCTV · 날씨 · 수위

## 새 서비스 추가하기

`index.html`의 `services` 배열에 객체 한 개만 추가하면 카드가 자동으로 그려집니다.

```js
{
  id: "log-book",
  name: "출조 일지",
  description: "오늘의 조황을 기록하세요",
  icon: "📖",
  url: "https://...",
  status: "live"  // live | beta | coming-soon
}
```

## 기술 스택

- Vanilla HTML / CSS / JavaScript (단일 파일)
- Cloudflare Pages 배포

## 라이선스

취미로 만든 비영리 사이트입니다.
