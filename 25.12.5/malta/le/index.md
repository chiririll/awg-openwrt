---
layout: default
title: "OpenWrt 25.12.5 malta/le"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.5](https://chiririll.github.io/awg-openwrt/25.12.5/) / [malta](https://chiririll.github.io/awg-openwrt/25.12.5/malta/)

- OpenWrt version: `25.12.5`
- Target: `malta`
- Subtarget: `le`
- Package architecture: `mipsel_24kc`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.5/targets/malta/le/](https://downloads.openwrt.org/releases/25.12.5/targets/malta/le/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260618-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/amneziawg-tools-1.0.20260618-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/index.json)
- [kmod-amneziawg-6.12.94.1.0.20260611-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/kmod-amneziawg-6.12.94.1.0.20260611-r1.apk)
- [luci-i18n-amneziawg-ru-0.260630.76064.apk](https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/luci-i18n-amneziawg-ru-0.260630.76064.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.5/malta/le/packages.adb)
