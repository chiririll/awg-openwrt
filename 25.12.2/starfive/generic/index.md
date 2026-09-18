---
layout: default
title: "OpenWrt 25.12.2 starfive/generic"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.2](https://chiririll.github.io/awg-openwrt/25.12.2/) / [starfive](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/)

- OpenWrt version: `25.12.2`
- Target: `starfive`
- Subtarget: `generic`
- Package architecture: `riscv64_generic`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.2/targets/starfive/generic/](https://downloads.openwrt.org/releases/25.12.2/targets/starfive/generic/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260223-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/amneziawg-tools-1.0.20260223-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/index.json)
- [kmod-amneziawg-6.12.74.1.0.20260329-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/kmod-amneziawg-6.12.74.1.0.20260329-r1.apk)
- [luci-i18n-amneziawg-ru-0.260508.70106.apk](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/luci-i18n-amneziawg-ru-0.260508.70106.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.2/starfive/generic/packages.adb)
