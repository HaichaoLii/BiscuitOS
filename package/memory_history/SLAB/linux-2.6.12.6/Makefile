################################################
#
# SLAB linux 2.6.12.6
#
################################################
PK_SLAB_2_6_12_6_NAME        := BiscuitOS_SLAB
PK_SLAB_2_6_12_6_VERSION     := $(CONFIG_PK_SLAB_2_6_12_6_VERSION)
PK_SLAB_2_6_12_6_SITE        := $(CONFIG_PK_SLAB_2_6_12_6_URL)
PK_SLAB_2_6_12_6_GITHUB      := $(CONFIG_PK_SLAB_2_6_12_6_GITHUB)
PK_SLAB_2_6_12_6_SUBNAME     :=
PK_SLAB_2_6_12_6_BUILDARCH   := $(CONFIG_PK_SLAB_2_6_12_6_BUILDARCH)
PK_SLAB_2_6_12_6_DIR         := $(srctree)/package/memory_history/SLAB/linux-2.6.12.6
PK_SLAB_2_6_12_6_PATCH       := $(PK_SLAB_2_6_12_6_DIR)/patch
PK_SLAB_2_6_12_6_BSBIT       := BiscuitOS_SLAB-$(PK_SLAB_2_6_12_6_VERSION).bsbit
PK_SLAB_2_6_12_6_OUT         :=
PK_SLAB_2_6_12_6_SCRIPTS     := $(srctree)/scripts/package/package-memory.sh
PK_SLAB_2_6_12_6_TAR         := $(CONFIG_PK_SLAB_2_6_12_6_TAR)
PK_SLAB_2_6_12_6_PACKAGE     :=
PK_SLAB_2_6_12_6_CONFIG      := $(CONFIG_PK_SLAB_2_6_12_6_CONFIG)
SUB_TARGET                  += $(PK_SLAB_2_6_12_6_DIR)/build

PK_SLAB_2_6_12_6_sh = $(CONFIG_SHELL) $(PK_SLAB_2_6_12_6_SCRIPTS) \
                 $1X \
                 $(PK_SLAB_2_6_12_6_NAME)X \
                 $(PK_SLAB_2_6_12_6_VERSION)X \
                 $(PK_SLAB_2_6_12_6_SITE)X \
                 $(PK_SLAB_2_6_12_6_GITHUB)X \
                 $(PK_SLAB_2_6_12_6_PATCH)X \
                 $(CONFIG_LINUX_KERNEL_VERSION)X \
	         $(CONFIG_MAIN_PROJ_NAME)X \
                 $(PK_SLAB_2_6_12_6_TAR)X \
                 $(CONFIG_LINUX_KERNEL_CROSS_COMPILE)X \
                 $(PK_SLAB_2_6_12_6_SUBNAME)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_CONFIG)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_LIBPATH)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_CPPFLAGS)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_DPKCONFIG)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_CFLAGS)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_LDFLAGS)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_CXXFLAGS)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_ASFLAGS)X \
                 $(PK_SLAB_2_6_12_6_BSBIT)X \
                 $(PK_SLAB_2_6_12_6_BUILDARCH)X \
		 $(PK_SLAB_2_6_12_6_CSRCFILE)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_SRCFILE)X \
                 $(CONFIG_PK_SLAB_2_6_12_6_CSRCFILE)

$(PK_SLAB_2_6_12_6_DIR)/build: FORCE
	$(Q)$(call PK_SLAB_2_6_12_6_sh,$(srctree))
