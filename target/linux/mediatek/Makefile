#
# Copyright (C) 2015 MediaTek
#
include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=mediatek
BOARDNAME:=MTK APSoC (ARM)
SUBTARGETS:=mt7623_emmc mt7623_mtd
FEATURES:=squashfs gpio
LINUX_VERSION:=3.10.20

include $(INCLUDE_DIR)/target.mk
DEFAULT_PACKAGES += 

define Target/Description
	Build firmware images for MTK/Ralink APSoC based boards.
endef

$(eval $(call BuildTarget))
