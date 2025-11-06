#
# Makefile for the Renesas device drivers.
#

ccflags-y += -I$(src)
obj-$(CONFIG_SH_ETH) += sh_eth.o

ravb-objs := ravb_main.o ravb_ptp.o

obj-$(CONFIG_RAVB) += ravb.o
