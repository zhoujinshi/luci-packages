#
# Copyright (C) 2020 Michele Primavera
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-ser2net
PKG_VERSION:=1.0
PKG_RELEASE:=1

LUCI_TITLE:=LuCI Support for ser2net
LUCI_DEPENDS:=+ser2net
LUCI_PKGARCH:=all

include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
