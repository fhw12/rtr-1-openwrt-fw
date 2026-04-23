
# Copyright 2017-2020 Dirk Brenken (dev@brenken.org)
# This is free software, licensed under the Apache License, Version 2.0

include $(TOPDIR)/rules.mk

LUCI_TITLE:=LuCI Tsmsmsconsole View
LUCI_DESCRIPTION:=Tsmodem helper module is used to provide SMS web console.
LUCI_DEPENDS:=+tsmsmsconsole
LUCI_PKGARCH:=all

PKG_NAME:=luci-app-tsmsmsconsole
PKG_VERSION:=4.0.0
PKG_RELEASE:=20260423
PKG_LICENSE:=GPL-3.0-or-later

include $(TOPDIR)/feeds/luci/luci.mk

$(eval $(call BuildPackage,$(PKG_NAME)))
