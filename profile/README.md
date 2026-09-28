# Ript

**Inventory and onboarding for physical-card programs.**

[ript.fun](https://ript.fun) is the app. This organization is the code behind it. Partners land here when they need the catalog, the claim path, or a way onto the platform.

## Inventory

Ript keeps a catalog of real cards. Each seat is one physical card with a stable identity. A partner reads that catalog, claims the exact cards they need, and can return them.

- Catalog, exact-SKU claims, and buybacks live on the [Inventory API](https://ript.fun/developers/guide).
- Sandbox and live are separate. A test key never reads or changes live stock.
- A claim is all-or-nothing. Ript does not substitute a different card when the one you asked for is gone.

## Onboarding

Two paths, both starting at [ript.fun/partners](https://ript.fun/partners).

**Supply.** Bring cards in. Scan or submit them, confirm identity, and pass review. Approved cards become drawable inventory. Payouts follow after real pulls, on the rail agreed at signup.

**Programs.** Run packs on Ript inventory. Qualify in sandbox (catalog, claim, buyback, conflicts, and retries), then take a live key and integrate pack claims and buybacks. Server-side keys only.

## Repositories

| Repo | What it is |
| --- | --- |
| [Ript](https://github.com/Ript-fun/Ript) | Web app |
| [Ript-Backend](https://github.com/Ript-fun/Ript-Backend) | API, inventory, and onboarding |

Product: [ript.fun](https://ript.fun) · Partners: [ript.fun/partners](https://ript.fun/partners) · API guide: [ript.fun/developers/guide](https://ript.fun/developers/guide)
