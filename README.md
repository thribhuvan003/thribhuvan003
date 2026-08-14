<div align="center">
  <img src="https://raw.githubusercontent.com/thribhuvan003/thribhuvan003/main/header.svg" alt="Building, breaking, learning." width="100%" />
</div>

<br/>

<div align="center">
  <a href="https://thribhuvan0.vercel.app"><b>Portfolio</b></a> &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/thribhuvan003/"><b>LinkedIn</b></a> &nbsp;·&nbsp;
  <a href="mailto:thribhuvan003@gmail.com"><b>Email</b></a>
</div>

<br/>

> **"If it's running in production, I want to know how it works under the hood. When it breaks, I fix it where it lives."**

---

### ⚡ Core Philosophy & Upstream Fixes

I build web systems, break them down to their primitives, and contribute upstream fixes when frameworks fail at the edge.

<table>
  <thead>
    <tr>
      <th align="left">Ecosystem</th>
      <th align="left">Issue Solved</th>
      <th align="center">Impact & Maintainer</th>
      <th align="right">Pull Request</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><b>Svelte</b></td>
      <td>Resolved compiler crash in keyed <code>{#each}</code> destructuring</td>
      <td>⭐ 88k · Merged by <a href="https://github.com/dummdidumm">@dummdidumm</a></td>
      <td align="right"><a href="https://github.com/sveltejs/svelte/pull/18521"><code>#18521</code></a></td>
    </tr>
    <tr>
      <td><b>SvelteKit</b></td>
      <td>Corrected route type generation for destructured exports</td>
      <td>⭐ 21k · Merged by <a href="https://github.com/Rich-Harris">Rich Harris</a></td>
      <td align="right"><a href="https://github.com/sveltejs/kit/pull/16329"><code>#16329</code></a></td>
    </tr>
    <tr>
      <td><b>Prisma ORM</b></td>
      <td>Patched critical isolation leak where queries cross-returned state</td>
      <td>~16M/wk · Merged by <a href="https://github.com/aqrln">@aqrln</a></td>
      <td align="right"><a href="https://github.com/prisma/prisma/pull/29701"><code>#29701</code></a></td>
    </tr>
    <tr>
      <td><b>Supabase SSR</b></td>
      <td>Fixed dangling server session persistence on explicit sign-out</td>
      <td>~7M/wk · Merged by <a href="https://github.com/mandarini">@mandarini</a></td>
      <td align="right"><a href="https://github.com/supabase/ssr/pull/258"><code>#258</code></a></td>
    </tr>
    <tr>
      <td><b>SolidJS</b></td>
      <td>Restored missing type definitions at core exported paths</td>
      <td>⭐ 36k · Merged by <a href="https://github.com/ryansolid">Ryan Carniato</a></td>
      <td align="right"><a href="https://github.com/solidjs/solid/pull/2875"><code>#2875</code></a></td>
    </tr>
    <tr>
      <td><b>Nitro Engine</b></td>
      <td>Adjusted overly aggressive skew-protection cookie policies</td>
      <td>⭐ 11k · Merged by <a href="https://github.com/pi0">@pi0</a></td>
      <td align="right"><a href="https://github.com/nitrojs/nitro/pull/4422"><code>#4422</code></a></td>
    </tr>
    <tr>
      <td><b>Supabase JS</b></td>
      <td>Exposed obfuscated error <code>code</code> properties to top-level callers</td>
      <td>⭐ 4.5k · Merged by <a href="https://github.com/mandarini">@mandarini</a></td>
      <td align="right"><a href="https://github.com/supabase/supabase-js/pull/2537"><code>#2537</code></a></td>
    </tr>
  </tbody>
</table>

---

### 🛠️ Shipped Products (Zero-Fluff Systems)

* 🔒 **[Unhold](https://unhold.live)** — Deterministic evidence & case generator for frozen bank/UPI disputes. Completely client-side generation; zero data retained or sent to third parties.
* 🍱 **[Tray](https://trayy.vercel.app)** — Real-time multi-tenant order distribution for street merchants, isolating ledger views while settling peer-to-peer over local UPI routes.

---

### 💻 Stack & Low-Level Tooling

```typescript
const engineer = {
  core: ["TypeScript", "Rust / Python", "Node.js runtime internals"],
  uiArchitecture: ["Svelte / SvelteKit", "React", "Next.js", "SolidJS"],
  dataAndInfra: ["PostgreSQL", "Supabase", "Prisma", "Docker", "Redis"],
  focus: "Concurrency, compiler internals, type safety, low-latency APIs"
};
