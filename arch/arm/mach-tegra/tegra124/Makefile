#
# (C) Copyright 2013-2014
# NVIDIA Corporation <www.nvidia.com>
#
# SPDX-License-Identifier:     GPL-2.0+
#

# The AVP is ARMv4T architecture so we must use special compiler
# flags for any startup files it might use.
CFLAGS_warmboot_avp.o += -march=armv4t

obj-$(CONFIG_SPL_BUILD) += cpu.o

obj-y	+= clock.o
obj-y	+= funcmux.o
obj-y	+= pinmux.o
obj-y   += warmboot.o
obj-y   += warmboot_avp.o
obj-y	+= xusb-padctl.o
