#
# Makefile for the touchscreen drivers.
#

# Each configuration option enables a list of files.
obj-$(CONFIG_TOUCHPANEL_SYNAPTICS_TCM_S3910) += Syna_tcm_S3910/

oplus_bsp_tp_syna_comnon-y += synaptics_touch_panel_remote.o
oplus_bsp_tp_syna_comnon-y += synaptics_common.o
obj-$(CONFIG_TOUCHPANEL_SYNAPTICS) += oplus_bsp_tp_syna_comnon.o
#endif

obj-$(CONFIG_KUNIT_OPLUS_SYNAPTICS) += kunit_synaptics.o