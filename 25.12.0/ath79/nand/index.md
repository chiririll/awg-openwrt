---
layout: default
title: "OpenWrt 25.12.0 ath79/nand"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.0](https://chiririll.github.io/awg-openwrt/25.12.0/) / [ath79](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/)

- OpenWrt version: `25.12.0`
- Target: `ath79`
- Subtarget: `nand`
- Package architecture: `mips_24kc`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.0/targets/ath79/nand/](https://downloads.openwrt.org/releases/25.12.0/targets/ath79/nand/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260223-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/amneziawg-tools-1.0.20260223-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/index.json)
- [kmod-amneziawg-6.12.71.1.0.20260329-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/kmod-amneziawg-6.12.71.1.0.20260329-r1.apk)
- [luci-i18n-amneziawg-ru-0.260508.62574.apk](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/luci-i18n-amneziawg-ru-0.260508.62574.apk)
- [luci-i18n-amneziawg-ru-0.apk](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/luci-i18n-amneziawg-ru-0.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.0/ath79/nand/packages.adb)
