include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-ser2net
PKG_VERSION=1.0
PKG_RELEASE:=1

PKG_MAINTAINER:=cnbbx

PKG_BUILD_DIR:=$(BUILD_DIR)/$(PKG_NAME)

LUCI_TITLE:=LuCI support for ser2net
LUCI_DEPENDS:=+ser2net
LUCI_PKGARCH:=all

define Package/luci-app-ser2net/description
    This package contains LuCI configuration pages for ser2net.
endef

include $(TOPDIR)/feeds/luci/luci.mk