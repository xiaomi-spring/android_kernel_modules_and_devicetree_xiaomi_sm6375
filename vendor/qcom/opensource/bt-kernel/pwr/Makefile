ccflags-y += -I$(BT_ROOT)/include

ifeq ($(CONFIG_BT_HW_SECURE_DISABLE), y)
ccflags-y += -I$(BT_ROOT)/../securemsm-kernel/smcinvoke/
ccflags-y += -I$(BT_ROOT)/../securemsm-kernel/linux/
ccflags-y += -I$(BT_ROOT)/../securemsm-kernel/include/
endif

obj-$(CONFIG_MSM_BT_POWER)  += btpower.o
