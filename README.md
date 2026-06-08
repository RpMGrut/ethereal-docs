# ethereal-docs

Документация [ethereal](https://ethereal.llc) — OpenAI-совместимый шлюз к Claude
(Opus / Sonnet / Haiku). Сайт на [Mintlify](https://mintlify.com).

## Структура

- `docs.json` — конфиг Mintlify (навигация, тема, бренд).
- `*.mdx` — страницы: introduction, quickstart, authentication, pricing,
  balance-and-topup, streaming, errors, faq, support.
- `api-reference/` — Chat Completions, Модели.
- `integrations/` — Claude Code, Cursor, Cline, Continue, Aider, Zed, SDK.

## Локальный предпросмотр

```bash
npm i -g mint
mint dev
```

## Деплой

Репозиторий подключён к Mintlify (GitHub App) — каждый push в `main`
авто-публикуется.
