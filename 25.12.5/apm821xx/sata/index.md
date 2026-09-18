---
layout: default
title: "OpenWrt 25.12.5 apm821xx/sata"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.5](https://chiririll.github.io/awg-openwrt/25.12.5/) / [apm821xx](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/)

- OpenWrt version: `25.12.5`
- Target: `apm821xx`
- Subtarget: `sata`
- Package architecture: `powerpc_464fp`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.5/targets/apm821xx/sata/](https://downloads.openwrt.org/releases/25.12.5/targets/apm821xx/sata/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260618-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/amneziawg-tools-1.0.20260618-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/index.json)
- [kmod-amneziawg-6.12.94.1.0.20260611-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/kmod-amneziawg-6.12.94.1.0.20260611-r1.apk)
- [luci-i18n-amneziawg-ru-0.260701.15941.apk](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/luci-i18n-amneziawg-ru-0.260701.15941.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.5/apm821xx/sata/packages.adb)
