#
# Makefile for Unisys visorbus
#

ccflags-y += -I$(src)
obj-$(CONFIG_UNISYS_VISORBUS)	+= visorbus.o

visorbus-y := visorbus_main.o
visorbus-y += visorchannel.o
visorbus-y += visorchipset.o

ccflags-y += -Idrivers/staging/unisys/include
