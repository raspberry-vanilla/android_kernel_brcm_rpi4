ccflags-y += \
	-I$(srctree)/$(src)/../ \
	-I$(srctree)/$(src)/../interface/vchiq_arm\
	-I$(srctree)/$(src)/../include

ccflags-y += \
	-D__VCCOREVER__=0 \
	-Wno-single-bit-bitfield-constant-conversion

vc-sm-cma-$(CONFIG_BCM_VC_SM_CMA) := \
	vc_sm.o vc_sm_cma_vchi.o

obj-$(CONFIG_BCM_VC_SM_CMA) += vc-sm-cma.o
