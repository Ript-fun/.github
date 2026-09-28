<p align="center">
  <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/banner.png" width="100%" alt="Ript. Inventory and onboarding for physical-card programs. Browser, Android, Seeker, and Apple." />
</p>

<p align="center">
  <a href="https://ript.fun"><img alt="Open the app" src="https://img.shields.io/badge/Open_the_app-ript.fun-F15A22?style=for-the-badge" /></a>
  <a href="https://ript.fun/partners"><img alt="Partners" src="https://img.shields.io/badge/Partners-onboarding-1c2230?style=for-the-badge" /></a>
  <a href="https://ript.fun/developers/guide"><img alt="Inventory API" src="https://img.shields.io/badge/Inventory_API-guide-1c2230?style=for-the-badge" /></a>
</p>

<p align="center">
  <a href="#inventory"><strong>Inventory</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#onboarding"><strong>Onboarding</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#stack"><strong>Stack</strong></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#where-it-runs"><strong>Where it runs</strong></a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/divider.svg" width="100%" alt="" />
</p>

<table>
<tr>
<td width="58%" valign="top">

### Inventory

A catalog of real cards. Each seat is one physical card with a stable identity.

Partners read the catalog, claim the exact cards they need, and can return them. Sandbox and live stay separate. A claim is all-or-nothing: Ript does not substitute a different card when the one you asked for is gone.

[Inventory API guide](https://ript.fun/developers/guide)

### Onboarding

Two paths, both starting at [ript.fun/partners](https://ript.fun/partners).

**Supply.** Bring cards in. Scan or submit them, confirm identity, and pass review. Approved cards become drawable inventory.

**Programs.** Run packs on Ript inventory. Qualify in sandbox, then take a live key and integrate pack claims and buybacks. Keys stay on the server.

</td>
<td width="42%" valign="middle" align="center">

<img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/phone.jpg" width="260" alt="Card Scan on a phone" />

</td>
</tr>
</table>

<p align="center">
  <img src="https://raw.githubusercontent.com/Ript-fun/.github/main/assets/divider.svg" width="100%" alt="" />
</p>

## Stack

<p align="center">
  <img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" />
  <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img alt="Solana" src="https://img.shields.io/badge/Solana-9945FF?style=for-the-badge&logo=solana&logoColor=white" />
  <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" />
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white" />
  <img alt="Expo" src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" />
</p>

| Layer | What it runs on |
| --- | --- |
| Web | TypeScript, React, Vite, Tailwind. Shipped on Cloudflare Pages. |
| API | TypeScript, Fastify, PostgreSQL, Drizzle. Shipped on Railway. |
| Chain | Solana. Purchases settle in USDC. |
| Mobile | Expo. Android, Solana Seeker, and iOS. |
| Media | Card art and studio scans on Cloudflare R2. |

## Where it runs

```mermaid
flowchart LR
    classDef surface fill:#1c2230,stroke:#F15A22,color:#f4f6fb,stroke-width:2px
    classDef core fill:#2a160e,stroke:#F15A22,color:#f4f6fb,stroke-width:2px

    Browser[Browser]:::surface
    Android[Android]:::surface
    Seeker[Seeker]:::surface
    Apple[Apple]:::surface
    Ript[Inventory and onboarding]:::core

    Browser --> Ript
    Android --> Ript
    Seeker --> Ript
    Apple --> Ript
```

<p align="center">
  <a href="https://github.com/Ript-fun/Ript">Web</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/Ript-fun/Ript-Backend">API</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://ript.fun">ript.fun</a>
</p>
