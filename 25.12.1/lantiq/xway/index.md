---
layout: default
title: "OpenWrt 25.12.1 lantiq/xway"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.1](https://chiririll.github.io/awg-openwrt/25.12.1/) / [lantiq](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/)

- OpenWrt version: `25.12.1`
- Target: `lantiq`
- Subtarget: `xway`
- Package architecture: `mips_24kc`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.1/targets/lantiq/xway/](https://downloads.openwrt.org/releases/25.12.1/targets/lantiq/xway/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260223-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/amneziawg-tools-1.0.20260223-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/index.json)
- [kmod-amneziawg-6.12.74.1.0.20260329-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/kmod-amneziawg-6.12.74.1.0.20260329-r1.apk)
- [luci-i18n-amneziawg-ru-0.260508.65397.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/luci-i18n-amneziawg-ru-0.260508.65397.apk)
- [luci-i18n-amneziawg-ru-0.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/luci-i18n-amneziawg-ru-0.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xway/packages.adb)
