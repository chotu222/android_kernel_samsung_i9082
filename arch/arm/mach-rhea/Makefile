#*****************************************************************************
# Copyright 2003 - 2008 Broadcom Corporation.  All rights reserved.
#
# Unless you and Broadcom execute a separate written software license
# agreement governing use of this software, this software is licensed to you
# under the terms of the GNU General Public License version 2, available at
# http://www.broadcom.com/licenses/GPLv2.php (the "GPL").
#
# Notwithstanding the above, under no circumstances may you combine this
# software in any way with any other Broadcom software provided under a
# license other than the GPL, without Broadcom's express prior written
# consent.
#*****************************************************************************

obj-y := io_map.o rhea.o common.o rhea_pinmux.o
obj-$(CONFIG_ARCH_RHEA) += clock_rhea.o
obj-$(CONFIG_MACH_HERA_RAY) += hera_ray.o
obj-$(CONFIG_MACH_RHEA_RAY) += rhea_ray.o rhea_ray_pinmux.o
obj-$(CONFIG_KONA_POWER_MGR) += rhea_pwr_mgr.o
obj-$(CONFIG_KONA_PI_MGR) += rhea_pi_mgr.o
obj-$(CONFIG_KONA_CPU_PM_HANDLER) += rhea_pm.o rhea_wfi.o rhea_pm_dbg.o
obj-$(CONFIG_RHEA_DORMANT_MODE) += rhea_dormant.o dm_pwr_policy_top.o
obj-$(CONFIG_MACH_RHEA_RAY_EDN1X) += rhea_ray.o rhea_ray_pinmux.o
obj-$(CONFIG_MACH_RHEA_RAY_EDN2X) += rhea_ray.o rhea_ray_pinmux.o
obj-$(CONFIG_MACH_RHEA_FARADAY_EB10) += rhea_ray.o rhea_faraday_eb10_pinmux.o
obj-$(CONFIG_MACH_RHEA_BERRI) += rhea_berri.o rhea_berri_pinmux.o
obj-$(CONFIG_MACH_RHEA_BERRI_EDN40) += rhea_berri.o rhea_berri_pinmux.o
obj-$(CONFIG_MACH_RHEALC_BERRI) += rhea_berri.o rhea_berri_pinmux.o
obj-y += pm_params.o

obj-$(CONFIG_ROM_SEC_DISPATCHER) += sec_bridge_tz.i
