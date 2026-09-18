---
layout: default
title: "OpenWrt 25.12.1 lantiq/xrx200_legacy"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.1](https://chiririll.github.io/awg-openwrt/25.12.1/) / [lantiq](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/)

- OpenWrt version: `25.12.1`
- Target: `lantiq`
- Subtarget: `xrx200_legacy`
- Package architecture: `mips_24kc`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.1/targets/lantiq/xrx200_legacy/](https://downloads.openwrt.org/releases/25.12.1/targets/lantiq/xrx200_legacy/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260223-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/amneziawg-tools-1.0.20260223-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/index.json)
- [kmod-amneziawg-6.12.74.1.0.20260329-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/kmod-amneziawg-6.12.74.1.0.20260329-r1.apk)
- [luci-i18n-amneziawg-ru-0.260508.66629.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/luci-i18n-amneziawg-ru-0.260508.66629.apk)
- [luci-i18n-amneziawg-ru-0.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/luci-i18n-amneziawg-ru-0.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.1/lantiq/xrx200_legacy/packages.adb)
