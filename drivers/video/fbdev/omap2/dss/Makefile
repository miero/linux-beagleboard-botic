obj-$(CONFIG_OMAP2_DSS_INIT) += omapdss-boot-init.o

obj-$(CONFIG_OMAP_DSS_BASE) += omapdss-base.o
omapdss-base-y := base.o display.o dss-of.o output.o

obj-$(CONFIG_OMAP2_DSS) += omapdss.o
# Core DSS files
omapdss-y := core.o dss.o dss_features.o dispc.o dispc_coefs.o \
	pll.o video-pll.o
# DSS compat layer files
omapdss-$(CONFIG_OMAP2_DSS_COMPAT_SUPPORT) += manager.o manager-sysfs.o \
	overlay.o overlay-sysfs.o apply.o dispc-compat.o display-sysfs.o
omapdss-$(CONFIG_OMAP2_DSS_DPI) += dpi.o
omapdss-$(CONFIG_OMAP2_DSS_RFBI) += rfbi.o
omapdss-$(CONFIG_OMAP2_DSS_VENC) += venc.o
omapdss-$(CONFIG_OMAP2_DSS_SDI) += sdi.o
omapdss-$(CONFIG_OMAP2_DSS_DSI) += dsi.o
omapdss-$(CONFIG_OMAP2_DSS_HDMI_COMMON) += hdmi_common.o hdmi_wp.o hdmi_pll.o \
	hdmi_phy.o
omapdss-$(CONFIG_OMAP4_DSS_HDMI) += hdmi4.o hdmi4_core.o
omapdss-$(CONFIG_OMAP5_DSS_HDMI) += hdmi5.o hdmi5_core.o
ccflags-$(CONFIG_OMAP2_DSS_DEBUG) += -DDEBUG
