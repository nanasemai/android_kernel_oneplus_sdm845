#
# Makefile for USB Class drivers
# (one step up from the misc category)
#

ccflags-y += -I$(src)
obj-$(CONFIG_USB_ACM)		+= cdc-acm.o
obj-$(CONFIG_USB_PRINTER)	+= usblp.o
obj-$(CONFIG_USB_WDM)		+= cdc-wdm.o
obj-$(CONFIG_USB_TMC)		+= usbtmc.o
