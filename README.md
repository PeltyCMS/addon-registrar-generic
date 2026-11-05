# Generic HTTP registrar

Official **PeltyCMS** `registrar` WASM addon (`registrar-generic`).

## Install

1. Open Pelty Admin → Addons → Marketplace
2. Set registry URL to `https://market.mythicalsystems.org/api/pelty/addons/registry.json`
3. Download **Generic HTTP registrar**

Marketplace: https://market.mythicalsystems.org/marketplace/product/registrar-generic  
Product ID (CI): `84`

## Develop

This repository is a git submodule of [MythicalLTD/PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) at `extensions/addons/reg-generic`.

```bash
# from the PeltyCMS monorepo
cargo xtask addons reg-generic
```

## Release (Mythic Marketplace)

Same flow as [featherpanel-com/PterodactylPanelApi](https://github.com/featherpanel-com/PterodactylPanelApi):

1. Repo secrets: `MYTHIC_PRODUCT_ID`, `MYTHIC_RELEASE_TOKEN`
2. Repo variable: `ADDON_DIR=reg-generic`
3. Actions → **Release Addon** → Run workflow

Publishes the packed `registrar-generic.zip` via `MythicalLTD/.github/actions/publish-release@v1` and creates a GitHub Release.
