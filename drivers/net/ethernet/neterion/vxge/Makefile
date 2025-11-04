#
# Makefile for Exar Corp's X3100 Series 10 GbE PCIe I/O
# Virtualized Server Adapter linux driver

ccflags-y += -I$(src)
obj-$(CONFIG_VXGE) += vxge.o

vxge-objs := vxge-config.o vxge-traffic.o vxge-ethtool.o vxge-main.o
