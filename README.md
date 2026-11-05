# Cloudflare DNS

Register and renew domains with Cloudflare

Official domain registrar for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Resellers who sell domains next to hosting and need automated register / renew.

## Features

- Availability / DNS operations via the official **Cloudflare** API
- Register, renew and transfer domains from Pelty orders where supported
- Nameserver and contact updates where the API allows
- Sandboxed WASM registrar — credentials stay in the panel

## How it works

1. Install **Cloudflare DNS** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-cloudflare) inside Pelty Admin → Addons.
2. Open Pelty Admin → Domains, connect Cloudflare, sync TLDs, and sell domains like any other product.
3. Customers hit checkout / login / order flow as usual — Cloudflare runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working Cloudflare credentials
- Outbound HTTPS from your panel

## Get it

**[Cloudflare DNS on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/registrar-cloudflare)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
