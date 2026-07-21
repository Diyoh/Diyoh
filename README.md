<div align="center">

# Diyoh Shiloh

**Backend engineer. I build systems where correctness matters: ledgers, payments, auth, and rate limiting.**

Based in Buea, Cameroon. I work across Node, Python, Go, and TypeScript, and I reach for the right database primitive rather than one trick.

![Node](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?logo=go&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

</div>

---

## Featured work

Each of these is a focused backend service that demonstrates one hard problem done correctly, with tests and an in-depth README.

| Project | What it shows | Stack |
|---------|---------------|-------|
| [Double-entry-ledger](https://github.com/Diyoh/Double-entry-ledger) | Double entry, derived balances, integer money, and no overdraw under concurrency via serialisable isolation. | TypeScript, Postgres |
| [idempotent-payments](https://github.com/Diyoh/idempotent-payments) | Idempotency keys, signed webhooks with replay rejection, an explicit state machine, reconciliation, and a dead letter queue. | TypeScript |
| [api-rate-limiter](https://github.com/Diyoh/api-rate-limiter) | Sliding window and token bucket rate limiting made atomic with Redis Lua, plus net/http middleware. | Go, Redis |
| [otp-biometric-auth](https://github.com/Diyoh/otp-biometric-auth) | OTP, argon2id, rotating refresh tokens with reuse detection, TOTP 2FA, and the correct biometric unlock pattern. | Python, FastAPI |
| [realtime-chat-service](https://github.com/Diyoh/realtime-chat-service) | Per channel ordering, at least once delivery with dedupe, offline catch up, and per request authorization. | TypeScript, WebSocket |
| [USSD-Booking-system](https://github.com/Diyoh/USSD-Booking-system) | Hybrid Web and USSD hall and event booking with mobile money and SMS, on one shared backend. | Laravel, PHP |

---

## What I care about

Correctness under concurrency, idempotent APIs that are safe to retry, money as integer minor units, and tests that prove the mechanism rather than decorate it. Most of my repositories have a design decisions section that explains why each choice was made, because the reasoning is the point.

---

## Tech

**Languages** TypeScript, JavaScript, Python, Go, PHP

**Backend** Node and Express, NestJS, FastAPI, Laravel

**Data** PostgreSQL, MySQL, Redis, Prisma

**Practice** database transactions and isolation levels, state machines, retries and dead letter queues, webhook security, CI with GitHub Actions

---

## Reach me

- Email: diyohshiloh4@gmail.com
- LinkedIn: add-your-linkedin-url
- Location: Buea, Cameroon

<div align="center">

![Diyoh's GitHub stats](https://github-readme-stats.vercel.app/api?username=Diyoh&show_icons=true&hide_border=true)

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Diyoh&layout=compact&hide_border=true)

</div>
