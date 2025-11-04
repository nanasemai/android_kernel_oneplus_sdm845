#
# Makefile for the linux kernel, U300 machine.
#

ccflags-y += -I$(src)
obj-y		:= core.o

obj-$(CONFIG_MACH_U300_SPIDUMMY)  += dummyspichip.o
obj-$(CONFIG_REGULATOR_AB3100)    += regulator.o
