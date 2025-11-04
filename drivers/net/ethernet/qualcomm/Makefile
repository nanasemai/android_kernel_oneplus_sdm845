#
# Makefile for the Qualcomm network device drivers.
#

ccflags-y += -I$(src)
obj-$(CONFIG_QCA7000) += qcaspi.o
qcaspi-objs := qca_spi.o qca_framing.o qca_7k.o qca_debug.o

obj-y += emac/
