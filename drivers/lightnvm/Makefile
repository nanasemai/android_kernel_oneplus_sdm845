#
# Makefile for Open-Channel SSDs.
#

ccflags-y += -I$(src)
obj-$(CONFIG_NVM)		:= core.o sysblk.o sysfs.o
obj-$(CONFIG_NVM_GENNVM) 	+= gennvm.o
obj-$(CONFIG_NVM_RRPC)		+= rrpc.o
