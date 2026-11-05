# Generic HTTP registrar

Register and renew domains with Generic HTTP registrar

Official **domain registrar** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `registrar-generic`.

## Why this addon

Resellers who sell domains next to hosting and need automated register / renew.

## Features

- Availability checks against the official **Generic HTTP registrar** API
- Register, renew and transfer domains from Pelty orders
- Nameserver and contact updates where the API allows
- TLD costs sync into Pelty pricing
- Sandboxed WASM registrar — credentials stay in the panel

## How it works

1. Install **Generic HTTP registrar** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-generic) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Generic HTTP registrar credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Generic HTTP registrar automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Generic HTTP registrar API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Generic HTTP registrar

## Get it

[Generic HTTP registrar on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-generic)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/registrar-generic
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
