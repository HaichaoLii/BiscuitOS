################################################
#
# rpi-3b-bootloader
#
################################################
PK_RPI_3B_BOOTLOADER_NAME        := rpi-3b-bootloader
PK_RPI_3B_BOOTLOADER_VERSION     := $(CONFIG_PK_RPI_3B_BOOTLOADER_VERSION)
PK_RPI_3B_BOOTLOADER_SITE        := $(CONFIG_PK_RPI_3B_BOOTLOADER_URL)
PK_RPI_3B_BOOTLOADER_GITHUB      := $(CONFIG_PK_RPI_3B_BOOTLOADER_GITHUB)
PK_RPI_3B_BOOTLOADER_SUBNAME     :=
PK_RPI_3B_BOOTLOADER_BUILDARCH   := $(CONFIG_PK_RPI_3B_BOOTLOADER_BUILDARCH)
PK_RPI_3B_BOOTLOADER_DIR         := $(srctree)/package/rpi-3b-bootloader
PK_RPI_3B_BOOTLOADER_PATCH       := $(PK_RPI_3B_BOOTLOADER_DIR)/patch
PK_RPI_3B_BOOTLOADER_BSBIT       := rpi-3b-bootloader-$(PK_RPI_3B_BOOTLOADER_VERSION).bsbit
PK_RPI_3B_BOOTLOADER_OUT         :=
PK_RPI_3B_BOOTLOADER_SCRIPTS     := $(srctree)/scripts/package/package-rpi.sh
PK_RPI_3B_BOOTLOADER_TAR         := $(CONFIG_PK_RPI_3B_BOOTLOADER_TAR)
PK_RPI_3B_BOOTLOADER_PACKAGE     :=
PK_RPI_3B_BOOTLOADER_CONFIG      := $(CONFIG_PK_RPI_3B_BOOTLOADER_CONFIG)
SUB_TARGET              += $(PK_RPI_3B_BOOTLOADER_DIR)/build

PK_RPI_3B_BOOTLOADER_sh = $(CONFIG_SHELL) $(PK_RPI_3B_BOOTLOADER_SCRIPTS) \
                 $1X \
                 $(PK_RPI_3B_BOOTLOADER_NAME)X \
                 $(PK_RPI_3B_BOOTLOADER_VERSION)X \
                 $(PK_RPI_3B_BOOTLOADER_SITE)X \
                 $(PK_RPI_3B_BOOTLOADER_GITHUB)X \
                 $(PK_RPI_3B_BOOTLOADER_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_RPI_3B_BOOTLOADER_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_RPI_3B_BOOTLOADER_SUBNAME)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_CONFIG)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_LIBPATH)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_CPPFLAGS)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_DPKCONFIG)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_CFLAGS)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_LDFLAGS)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_CXXFLAGS)X \
                 $(CONFIG_PK_RPI_3B_BOOTLOADER_ASFLAGS)X \
                 $(PK_RPI_3B_BOOTLOADER_BSBIT)X \
                 $(PK_RPI_3B_BOOTLOADER_BUILDARCH)X

$(PK_RPI_3B_BOOTLOADER_DIR)/build: FORCE
	$(Q)$(call PK_RPI_3B_BOOTLOADER_sh,$(srctree))
