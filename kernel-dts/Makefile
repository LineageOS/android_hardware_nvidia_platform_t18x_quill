old-dtb := $(dtb-y)
old-dtbo := $(dtbo-y)
dtb-y :=
dtbo-y :=
makefile-path := platform/t18x/quill/kernel-dts

BUILD_18x_ENABLE=n
ifneq ($(filter y,$(CONFIG_ARCH_TEGRA_18x_SOC) $(CONFIG_ARCH_TEGRA_186_SOC)),)
BUILD_18x_ENABLE=y
endif

dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-base.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-ape-cam.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-edp.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-dsi-hdmi-dp.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-dsi-hdmi-dp.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-dsi-hdmi-dp-imx274-hdmiin.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-dsi-dp.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-hdmi-primary-p3310-1000-c03-00.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-hdmi-primary-p3310-1000-a00-00.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-base-mods-display.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-imx274.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-imx185_v1.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-00-lc898212.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-hdmi-primary-p3310-1000-a00-00-imx274.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-hdmi-primary-p3310-1000-c03-00-imx274.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-ape-cam.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-imx185_v1.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-dsi-dp.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-dsi-hdmi-hdmi.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-dsi-hdmi-hdmi-imx274-hdmiin.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-null_dsi-2hdmi-imx274-hdmiin.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c00-00-auo-1080p-edp.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-e3313-1000-a00-00-e2598.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3489-1000-a00-00-ucm1.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3489-1000-a00-00-ucm2.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3489-1000-a00-00-e2598.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3489-0888-a00-00-base.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3489-0888-a00-00-e2598.dtb
dtb-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-as-0888.dtb
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-a00-overlay.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-hdr40.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-adafruit-sph0645lm4h.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-adafruit-uda1334a.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-fe-pi-audio.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-respeaker-4-mic-array.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-respeaker-4-mic-lin-array.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-m2ke.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-csi.dtbo
dtbo-$(BUILD_18x_ENABLE) += tegra186-quill-p3310-1000-c03-00-base-hdr30.dtbo

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
dts-include += $(makefile-path)
endif
ifneq ($(dtbo-y),)
dtbo-y := $(addprefix $(makefile-path)/,$(dtbo-y))
endif

dtb-y += $(old-dtb)
dtbo-y += $(old-dtbo)
