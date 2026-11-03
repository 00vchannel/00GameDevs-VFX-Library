# AI integration guide / AI 整合指南 / AI 集成指南 / AI 組み込みガイド

The live guides are authoritative and stay aligned with the downloadable assets. This repository links to them instead of maintaining a second copy.

正式指南與下載素材同步更新；此處提供入口，不維護另一份可能過時的完整指南。
正式指南与下载素材同步更新；此处提供入口，不维护另一份可能过时的完整指南。
最新の仕様は公式ガイドをご確認ください。このリポジトリでは、古くなりやすい複製ではなくリンクを掲載しています。

| Resource | Link |
|---|---|
| AI discovery | [llms.txt](https://00gamedevs.com/llms.txt) |
| Current machine-readable catalog | [catalog.v2.json](https://00gamedevs.com/ai/catalog.v2.json) |
| Full guide — English | [integration.en.md](https://00gamedevs.com/ai/integration.en.md) |
| 完整指南 — 繁體中文 | [integration.zh-TW.md](https://00gamedevs.com/ai/integration.zh-TW.md) |
| Asset license | [ASSET-LICENSE.md](ASSET-LICENSE.md) |

1. Inspect the user's authorized project and Three.js version.
2. Select an asset from catalog v2. Follow `integration.type`: `scene-object` and `postprocess` have different integration paths.
3. Resolve download paths against `https://00gamedevs.com`, verify SHA-256, and keep the catalog version and license notices. Fixed URLs follow the latest build, not immutable releases.
4. Preserve gameplay rules and test playback, stopping/replaying and cleanup in the actual project.
5. Follow the official guide's download-reporting procedure after a successful verified save; reuse the event ID for retries. Reading the catalog or guide does not count as a download.

The AI catalog covers VFX and objects, not Shader examples. Public downloads need no account or API key. These are Three.js modules, not native Unity or Unreal packages. Follow the live guide for the supported Three.js version and dependencies.

[Back to English introduction](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)
