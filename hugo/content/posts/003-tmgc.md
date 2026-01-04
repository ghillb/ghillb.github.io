---
title: "tmgc: Telegram MTProto Go CLI"
date: 2026-01-04T12:00:00Z
draft: false
tags: ["by gh", "go", "cli", "telegram", "mtproto"]
showToc: false
tocOpen: false
showReadingTime: true
showWordCount: true
cover:
  image: "/img/tmgc-cover.webp"
  alt: "friendly assistant at a Telegram CLI"
  hidden: false
---

I built **tmgc**, a Telegram MTProto CLI in Go. It is a thin, practical wrapper around [`gotd/td`](https://github.com/gotd/td), focused on automation and AI agents with predictable commands and machine-friendly output.

Highlights:
- QR login with a PNG fallback
- Chat history and message search
- Send messages (text or file) and schedule messages
- Human, JSON, or TSV output
- Session storage in the OS keychain (or file fallback)

Links:
- GitHub: https://github.com/ghillb/tmgc
- Project page: https://gerohillebrandt.de/tmgc/
