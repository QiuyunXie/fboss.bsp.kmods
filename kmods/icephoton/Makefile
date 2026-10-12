#!/bin/make -f
# SPDX-License-Identifier: GPL-2.0+
# Copyright (c) Meta Platforms, Inc. and affiliates.

obj-m += icephoton_scmcpld.o
icephoton_scmcpld-objs := icephoton/icephoton_scmcpld_i2c.o lib/regbit-sysfs.o fboss_iob_led_trigger.o
obj-m += icephoton_syscpld.o
icephoton_syscpld-objs := icephoton/icephoton_syscpld_i2c.o lib/regbit-sysfs.o 

# MPQ82D00 driver
obj-m += mpq82d00.o
mpq82d00-objs := icephoton/mpq82d00.o
