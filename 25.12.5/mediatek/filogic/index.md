---
layout: default
title: "OpenWrt 25.12.5 mediatek/filogic"
---

# AmneziaWG feed

Index of [(root)](https://chiririll.github.io/awg-openwrt/) / [25.12.5](https://chiririll.github.io/awg-openwrt/25.12.5/) / [mediatek](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/)

- OpenWrt version: `25.12.5`
- Target: `mediatek`
- Subtarget: `filogic`
- Package architecture: `aarch64_cortex-a53`

## Upstream OpenWrt target

[https://downloads.openwrt.org/releases/25.12.5/targets/mediatek/filogic/](https://downloads.openwrt.org/releases/25.12.5/targets/mediatek/filogic/)

## Configure Feed

```sh
mkdir -p /etc/apk/keys
wget -O /etc/apk/keys/awg-openwrt-feed.pem "https://chiririll.github.io/awg-openwrt/keys/awg-openwrt-feed.pem"
echo "https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/packages.adb" >> /etc/apk/repositories.d/customfeeds.list
```

## Install Packages

```sh
apk update
apk add amneziawg-tools kmod-amneziawg luci-proto-amneziawg
```

<script src="https://chiririll.github.io/awg-openwrt/assets/copy-code.js?v=2"></script>

## Feed files

- [amneziawg-tools-1.0.20260618-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/amneziawg-tools-1.0.20260618-r1.apk)
- [amneziawg-tools-3.1.20260812-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/amneziawg-tools-3.1.20260812-r1.apk)
- [feed.json](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/feed.json)
- [index.json](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/index.json)
- [kmod-amneziawg-6.12.94.1.0.20260611-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/kmod-amneziawg-6.12.94.1.0.20260611-r1.apk)
- [kmod-amneziawg-6.12.94.3.1.20260906-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/kmod-amneziawg-6.12.94.3.1.20260906-r1.apk)
- [luci-i18n-amneziawg-ru-0.260630.78878.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260630.78878.apk)
- [luci-i18n-amneziawg-ru-0.260917.54129.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260917.54129.apk)
- [luci-i18n-amneziawg-ru-0.260918.79899.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260918.79899.apk)
- [luci-i18n-amneziawg-ru-0.260918.83173.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260918.83173.apk)
- [luci-i18n-amneziawg-ru-0.260919.12826.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260919.12826.apk)
- [luci-i18n-amneziawg-ru-0.260919.16239.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260919.16239.apk)
- [luci-i18n-amneziawg-ru-0.260919.44341.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260919.44341.apk)
- [luci-i18n-amneziawg-ru-0.260919.66278.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-i18n-amneziawg-ru-0.260919.66278.apk)
- [luci-proto-amneziawg-2.0.4-r1.apk](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/luci-proto-amneziawg-2.0.4-r1.apk)
- [packages.adb](https://chiririll.github.io/awg-openwrt/25.12.5/mediatek/filogic/packages.adb)
