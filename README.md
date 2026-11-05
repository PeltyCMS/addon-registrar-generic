# Generic HTTP registrar

Register and renew domains with your registrar API

Official domain registrar for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Resellers who sell domains next to hosting and need automated register / renew.

## Features

- Availability checks against the official **your registrar API** API
- Register, renew and transfer domains from Pelty orders
- Nameserver and contact updates where the API allows
- TLD costs sync into Pelty pricing
- Sandboxed WASM registrar — credentials stay in the panel

## How it works

1. Install **Generic HTTP registrar** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-generic) inside Pelty Admin → Addons.
2. Open Pelty Admin → Domains, connect your registrar API, sync TLDs, and sell domains like any other product.
3. Customers hit checkout / login / order flow as usual — your registrar API runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working your registrar API credentials
- Outbound HTTPS from your panel

## Get it

**[Generic HTTP registrar on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-generic)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
