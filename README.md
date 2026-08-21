| **Thribhuvan.** I fix bugs in the tools I build with — upstream, when needed. | [Portfolio](https://thribhuvan0.vercel.app) · [LinkedIn](https://www.linkedin.com/in/thribhuvan003/) · [Email](mailto:thribhuvan003@gmail.com) |
|---|---|

I build multi-tenant products that handle real payments and real user data — the kind of work where a broken edge case actually costs someone money.

Outside of code: I read Vedanta and listen to classical music.

- Built **Tray**, a UPI ordering system for street stalls and campus canteens — multi-tenant, idempotent Razorpay capture, Postgres row-level security
- Built **TrustGrade**, an AI-assisted code grading platform — a Postgres trigger blocks any AI answer from publishing without teacher approval, student code runs in disposable network-less containers
- Built **Unhold**, a tool that drafts the letters needed to release a frozen bank or UPI account — OCR intake with PII redaction
- Built **AquaVision**, underwater image restoration that runs on CPU, benchmarked on a fixed test set
- Landed **14 merged pull requests across 11 upstream projects in seven weeks** — **Svelte**, **Prisma**, **SolidJS**, **SvelteKit**, **Supabase**, **Nitro**, **Refined GitHub**, **WXT**, **Music Blocks**, and **react-jsonschema-form** — reviewed and merged by their maintainers, several by the people who created the framework

Currently working on **Tray**, **TrustGrade**, and **Unhold**, and preparing for SDE interviews with DSA practice on LeetCode, CodeForces, and CodeChef.

### Tech Stack

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Svelte](https://img.shields.io/badge/-Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/-Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Prisma](https://img.shields.io/badge/-Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

### Open Source — Merged Upstream

14 pull requests, 11 projects, 4 July – 20 August 2026. Each row links the PR.

| Project | Reach | What I fixed | Merged by |
|---|---|---|---|
| **[Svelte](https://github.com/sveltejs/svelte)** · [#18521](https://github.com/sveltejs/svelte/pull/18521) | 🌟 87.9k · 5.2k forks<br>5.3M installs/wk | Keyed `{#each}` blocks with computed destructuring keys compiled to undefined variables and crashed at runtime | **@dummdidumm**<br>Svelte core team |
| **[Prisma](https://github.com/prisma/prisma)** · [#29701](https://github.com/prisma/prisma/pull/29701) | 🌟 47.6k · 2.5k forks<br>15M installs/wk | `Bytes` fields decoded as views into Node's shared Buffer pool, exposing bytes from other values in the same query | **@aqrln**<br>Prisma core engineer |
| **[SolidJS](https://github.com/solidjs/solid)** · [#2875](https://github.com/solidjs/solid/pull/2875) | 🌟 35.8k · 1.1k forks<br>3.5M installs/wk | `@solidjs/web/storage` shipped types at a path the package never advertised, breaking downstream type-checking | **@ryansolid**<br>creator of SolidJS |
| **[Refined GitHub](https://github.com/refined-github/refined-github)** · [#9777](https://github.com/refined-github/refined-github/pull/9777) | 🌟 31.9k · 1.9k forks<br>100k+ users | Conventional-commit labelling silently failed for capitalized types (`Fix`, `Feature`); made matching case-insensitive | **@fregante**<br>author of Refined GitHub |
| **[SvelteKit](https://github.com/sveltejs/kit)** · [#16329](https://github.com/sveltejs/kit/pull/16329) | 🌟 20.7k · 2.3k forks<br>2.4M installs/wk | Route exports written as destructured declarations were invisible to type generation | **@Rich-Harris**<br>creator of Svelte |
| **[react-jsonschema-form](https://github.com/rjsf-team/react-jsonschema-form)** · [#5150](https://github.com/rjsf-team/react-jsonschema-form/pull/5150) | 🌟 15.9k · 2.3k forks<br>1.2M installs/wk | Empty-string titles in `oneOf`/`anyOf` were discarded, so intentionally blank labels fell back to defaults | **@heath-freenome**<br>rjsf maintainer |
| **[Nitro](https://github.com/nitrojs/nitro)** · [#4422](https://github.com/nitrojs/nitro/pull/4422) · [#4412](https://github.com/nitrojs/nitro/pull/4412) | 🌟 11.1k · 886 forks<br>2M installs/wk | Vercel skew-protection cookies shipped without `SameSite=Lax`, dropping the deployment pin on cross-site navigation; prerendered routes ending in a slash emitted Build Output overrides Vercel silently refuses to match, so they fell through to the serverless function instead of being served statically | **@pi0**<br>Nitro lead maintainer |
| **[WXT](https://github.com/wxt-dev/wxt)** · [#2486](https://github.com/wxt-dev/wxt/pull/2486) · [#2485](https://github.com/wxt-dev/wxt/pull/2485) | 🌟 10.4k · 558 forks<br>550k installs/wk | i18n consumed mustache `{{tokens}}` as substitutions; added a `\{` escape and replaced a lookbehind regex with a single-pass parse that benchmarked **faster than main** | **@aklinker1**<br>creator of WXT |
| **[Supabase JS](https://github.com/supabase/supabase-js)** · [#2537](https://github.com/supabase/supabase-js/pull/2537) | 🌟 4.5k · 715 forks<br>25M installs/wk | `StorageApiError` swallowed the service error `code`, forcing callers to string-match messages; the Storage team shipped the server half alongside it | **@mandarini**<br>Supabase core |
| **[Supabase SSR](https://github.com/supabase/ssr)** · [#258](https://github.com/supabase/ssr/pull/258) | 🌟 205 · 30 forks<br>6.8M installs/wk | Cookie-deletion ordering left `signOut()` unable to clear a domain-scoped session, so users stayed logged in after signing out | **@mandarini**<br>Supabase core |
| **[Music Blocks](https://github.com/sugarlabs/musicblocks)** · [#7727](https://github.com/sugarlabs/musicblocks/pull/7727) · [#7731](https://github.com/sugarlabs/musicblocks/pull/7731) | 🌟 864 · 1.7k forks<br>GSoC org | Importing legacy Turtle Blocks projects crashed the editor; numerically-labelled blocks had names corrupted on import | **@walterbender**<br>Sugar Labs co-founder |

*Install counts are weekly npm downloads for the package each fix ships in.*

**In review:** [Firecrawl](https://github.com/firecrawl/firecrawl/pull/4354) · [Knip](https://github.com/webpro-nl/knip/pull/1962) · [Directus](https://github.com/directus/directus/pull/27880) · [Skyvern](https://github.com/Skyvern-AI/skyvern/pull/7076) *(approved)* · [Svelte](https://github.com/sveltejs/svelte/pull/18526)
