#
# arch/blackfin/mach-bf609/Makefile
#

ccflags-y += -I$(src)
obj-y := dma.o clock.o ints-priority.o
obj-$(CONFIG_PM) += pm.o dpm.o
obj-$(CONFIG_SCB_PRIORITY) += scb.o
