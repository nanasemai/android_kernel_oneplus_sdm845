#
# Makefile for the linux kernel.
#

# Common support
ccflags-y += -I$(src)
obj-y				:= common.o slcr.o pm.o
obj-$(CONFIG_SMP)		+= headsmp.o platsmp.o
