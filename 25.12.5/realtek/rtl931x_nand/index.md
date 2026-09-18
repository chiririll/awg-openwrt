---
layout: default
title: "OpenWrt 25.12.5 realtek/rtl931x_nand"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.5](https://chiririll.github.io/awg-openwrt/25.12.5/) / [realtek](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/)

- OpenWrt version: `25.12.5`
- Target: `realtek`
- Subtarget: `rtl931x_nand`
- Package architecture: `mips_24kc`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.5/targets/realtek/rtl931x_nand/](https://downloads.openwrt.org/releases/25.12.5/targets/realtek/rtl931x_nand/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260618-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/amneziawg-tools-1.0.20260618-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/index.json)
- [kmod-amneziawg-6.12.94.1.0.20260611-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/kmod-amneziawg-6.12.94.1.0.20260611-r1.apk)
- [luci-i18n-amneziawg-ru-0.260630.82418.apk](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/luci-i18n-amneziawg-ru-0.260630.82418.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.5/realtek/rtl931x_nand/packages.adb)
