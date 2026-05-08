# Stream (stream-io)

Stream provides realtime APIs for chat messaging, video and audio (calls/rooms), activity feeds and AI moderation. Hosted on a global edge network with native SDKs for web, mobile (iOS, Android, Flutter, React Native) and game engines (Unity, Unreal). Stream publishes full OpenAPI specs for its server-side APIs.

**APIs.json:** [apis.yml](apis.yml)

## Type
- **x-type:** company

## APIs
- **Chat** — `https://chat.stream-io-api.com` — channels, messages, users, threads, reactions, push, search, import/export. [Docs](https://getstream.io/chat/docs/) · [OpenAPI](openapi/stream-io-chat-openapi.yml)
- **Video & Audio** — `https://video.stream-io-api.com` — calls, audio rooms, livestreams, recordings, transcriptions. [Docs](https://getstream.io/video/docs/) · [OpenAPI](openapi/stream-io-video-openapi.yml)
- **Moderation** — AI moderation across text/image/video, queues, automod policies, harms taxonomy. [OpenAPI](openapi/stream-io-moderation-openapi.yml)
- **Activity Feeds** — flat / aggregated / notification / ranked feeds, follow graph, reactions, personalisation. [Docs](https://getstream.io/activity-feeds/docs/)

## OpenAPI specs (fetched 2026-05-08)
Stored under `openapi/`:
- `stream-io-chat-openapi.yml` (server-side Chat)
- `stream-io-video-openapi.yml` (server-side Video & Audio)
- `stream-io-moderation-openapi.yml` (server-side Moderation)
- `stream-io-serverside-openapi.yml` (combined server-side surface)

Source: <https://github.com/GetStream/protocol/tree/main/openapi>.

## Tags
Realtime, Chat, Messaging, Video, Audio, Activity Feeds, Moderation, SDK

## Common Properties
- [Website](https://getstream.io/)
- [Documentation](https://getstream.io/docs/)
- [Pricing](https://getstream.io/pricing/)
- [GitHub](https://github.com/GetStream)
- [Protocol Portal](https://getstream.github.io/protocol/)
- [Status Page](https://status.getstream.io/)
- [Plans](plans/stream-io-plans-pricing.yml) — reconciled (Chat tiers exact; Video/Feeds/Moderation directional)
- [Rate Limits](rate-limits/stream-io-rate-limits.yml) — partially reconciled (headers + 429 contract; numeric ceilings undocumented)
- [FinOps](finops/stream-io-finops.yml) — reconciled, FOCUS-aligned

## Plans (reconciled — Chat)
- **Build (Free)** — 1,000 MAU, 100 concurrent connections.
- **Start** — 10K MAU $399/mo annual; 25K $1,049/mo; 50K $1,849/mo (annual). Overage $0.07–0.09 / MAU.
- **Elevate** — adds multi-tenancy, advanced search, HIPAA, translations. 10K MAU $599/mo annual.
- **Enterprise** — 1M+ MAU, 99.999% SLA, dedicated, 24/7 support, SAML/SSO.
- **Add-ons** — stored messages $5/M, API calls $7/M, CDN bandwidth $0.17/GB, CDN storage $0.07/GB.

## Timestamps
- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## Maintainers
- **Kin Lane** — kin@apievangelist.com
