# Gemini Omni 1.1 Flash Ext — 逆向 route (简体中文)

> **per-call billing** · model ID `Omni-Flash-Ext` · **逆向/逆向工程** route.

**[查看实时价格](https://go.apimart.ai/k-d696d4)** · **[领取 API Key](https://go.apimart.ai/k-9f1262)**

gemini-omni-1.1-flash-ext-reverse-api-cn 是 **逆向** 的 Gemini Omni 1.1 Flash Ext 接入仓库：调用 ID `Omni-Flash-Ext`，与官方转接（`gemini-omni-1.1-flash`）并行存在，单价更低。

## Published unit prices (snapshot 2026-09-28)

| Unit | Price |
| --- | --- |
| `GPT Image 2.5 (1K)` | $0.0085 |
| `Seedance 2.0 Mini (480P/sec)` | $0.01056 |
| `Qwen3.7 Flash (per M input)` | $0.0228568 |

## Quickstart

```bash
curl -X POST https://api.apimart.ai/v1/videos/generations \
  -H 'Authorization: Bearer $APIMART_KEY' \
  -H 'Content-Type: application/json' \
  -d '{"model":"Omni-Flash-Ext","prompt":"a girl dancing in a sunny garden","duration":10,"resolution":"1080p","aspect_ratio":"9:16"}}'
```

Async: the response carries a `task_id`; poll `GET https://api.apimart.ai/v1/tasks/<task_id>` (or register a webhook).

## Reverse vs official route

| Route | Callable ID | Price |
| --- | --- | --- |
| **逆向** | `Omni-Flash-Ext` | per-call billing |
| 官方转接 | `gemini-omni-1.1-flash` | official list price, billed at ×0.8 group ratio |


## Keywords

`gemini-omni-1.1-flash-ext` · `Omni-Flash-Ext` · `逆向` · `逆向工程` · `API 中转站` · `AI API 网关` · `统一接入` · `nano banana 2 api` · `gpt-image-2.5 api` · `ai api pricing` · `pay-as-you-go`

## Platform facts

- USD settlement, pay-as-you-go, **$1 minimum top-up**, no subscription.
- Operating since last year; ~100,000 registered users, mostly enterprise accounts.
- International invoices available on request.
- 307 models online (live `/v1/models`) as of 2026-09-28.

## Disclosure

This repository documents **APIMart**, a third-party API aggregator/gateway. It is **not affiliated with, endorsed by, or sponsored by** OpenAI, Google, Anthropic, xAI, ByteDance or any model vendor. Model names and trademarks belong to their owners. Prices are a point-in-time snapshot and may change; the vendor's console billing is authoritative.

