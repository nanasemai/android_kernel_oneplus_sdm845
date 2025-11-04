#
# Makefile for the Linux Bluetooth RFCOMM layer.
#

ccflags-y += -I$(src)
obj-$(CONFIG_BT_RFCOMM) += rfcomm.o

rfcomm-y			:= core.o sock.o
rfcomm-$(CONFIG_BT_RFCOMM_TTY)	+= tty.o
