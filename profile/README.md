<p align="center">
  <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/mark.png" width="88" alt="Ript" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/wordmark-on-dark.png" />
    <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/wordmark-on-light.png" width="280" alt="Ript" />
  </picture>
</p>

<p align="center">
  <strong>Inventory and onboarding for physical-card programs.</strong>
</p>

<p align="center">
  <a href="https://ript.fun"><strong>Open the app</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://ript.fun/partners">Partners</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://ript.fun/developers/guide">Inventory API</a>
</p>

<br />

## Surfaces

<table>
  <tr>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/browser.svg" width="40" alt="" /><br />
      <strong>Browser</strong><br />
      <sub><a href="https://ript.fun">ript.fun</a></sub>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/android.svg" width="40" alt="" /><br />
      <strong>Android</strong><br />
      <sub>Google Play</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/seeker.svg" width="40" alt="" /><br />
      <strong>Seeker</strong><br />
      <sub>Solana dApp Store</sub>
    </td>
    <td align="center" width="25%">
      <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/apple.svg" width="40" alt="" /><br />
      <strong>Apple</strong><br />
      <sub>iOS</sub>
    </td>
  </tr>
</table>

<br />

## Stack

| Layer | What it runs on |
| --- | --- |
| Web | TypeScript, React, Vite, Tailwind. Shipped on Cloudflare Pages. |
| API | TypeScript, Fastify, PostgreSQL, Drizzle. Shipped on Railway. |
| Chain | Solana. Purchases settle in USDC. |
| Mobile | Expo. Android, Solana Seeker, and iOS. |
| Media | Card art and studio scans on Cloudflare R2. |

<br />

## Inventory

A catalog of real cards. Each seat is one physical card with a stable identity.

Partners read the catalog, claim the exact cards they need, and can return them. Sandbox and live stay separate. A claim is all-or-nothing: Ript does not substitute a different card when the one you asked for is gone.

[Inventory API guide](https://ript.fun/developers/guide)

## Onboarding

Two paths, both starting at [ript.fun/partners](https://ript.fun/partners).

**Supply.** Bring cards in. Scan or submit them, confirm identity, and pass review. Approved cards become drawable inventory.

**Programs.** Run packs on Ript inventory. Qualify in sandbox, then take a live key and integrate pack claims and buybacks. Keys stay on the server.

<br />

<p align="center">
  <a href="https://github.com/Ript-fun/Ript">Web</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/Ript-fun/Ript-Backend">API</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://ript.fun">ript.fun</a>
</p>
