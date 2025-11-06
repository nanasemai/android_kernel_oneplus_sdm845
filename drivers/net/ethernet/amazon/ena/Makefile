#
# Makefile for the Elastic Network Adapter (ENA) device drivers.
#

ccflags-y += -I$(src)
obj-$(CONFIG_ENA_ETHERNET) += ena.o

ena-y := ena_netdev.o ena_com.o ena_eth_com.o ena_ethtool.o
