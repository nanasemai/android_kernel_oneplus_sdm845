#
# Makefile for embedded secure element devices
#

ccflags-y += -I$(src)
obj-$(CONFIG_NFC_PN80T)		+= p73.o

ccflags-$(CONFIG_NFC_PN80T) := -DDEBUG

