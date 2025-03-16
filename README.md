# Quazar \ Routing

## Overview
This repository contains JSON configuration files for routing settings used in the **Quazar VPN** service. These configurations are designed for use with **Happ** and include deep links for easy setup.

## Contents
- **Routing JSON Files**: Define routing rules for specific regions.
- **Deep Link Files**: Enable quick configuration in Happ.

## Available Configurations
### FA (Iran Routing)
**File:** `FA.JSON`  
**Deep Link:** `FA.DEEPLINK`
- **Global Proxy:** Enabled
- **DNS Configuration:** Google DNS (DoU)
- **Direct Traffic:** Iranian websites, Cloudflare, Apple services
- **Proxy Traffic:** Blocked content like Discord, YouTube, TikTok
- **Blocked Domains:** Ads-related domains (Google Ads, Apple Ads, Spotify Ads)

### RU (Russia Routing)
**File:** `RU.JSON`  
**Deep Link:** `RU.DEEPLINK`
- **Global Proxy:** Enabled
- **DNS Configuration:** AdGuard DNS (DoU)
- **Direct Traffic:** Russian services, Microsoft updates, Google Play, Steam
- **Proxy Traffic:** Blocked services like Discord, YouTube, TikTok
- **Blocked Domains:** Windows spyware domains, torrents

### Disable Routing
**Deep Link:** `OFF.DEEPLINK`
Disables any active routing in Happ.

## Usage
1. Open Happ and import the deep link file.
2. The VPN settings will be applied automatically.
3. Customize routing rules if needed.

## Updates
Routing rules and configurations are updated regularly. Ensure you are using the latest files from this repository.

---
For more details, visit [Quazar VPN](#).
