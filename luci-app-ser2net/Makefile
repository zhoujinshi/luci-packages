include $(TOPDIR)/rules.mk

PKG_NAME:=luci-app-ser2net
PKG_VERSION=1.0
PKG_RELEASE:=1

PKG_MAINTAINER:=cnbbx

PKG_BUILD_DIR:=$(BUILD_DIR)/$(PKG_NAME)

include $(INCLUDE_DIR)/package.mk

define Package/luci-app-ser2net
    SECTION:=luci
    CATEGORY:=LuCI
    SUBMENU:=3. Applications
    TITLE:=ser2net for LuCI
    PKGARCH:=all
endef

define Package/luci-app-ser2net/description
    This package contains LuCI configuration pages for ser2net.
endef

include $(TOPDIR)/feeds/luci/luci.mk