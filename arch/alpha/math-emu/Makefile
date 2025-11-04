#
# Makefile for the FPU instruction emulation.
#

ccflags-y += -I$(src)
ccflags-y := -w

obj-$(CONFIG_MATHEMU) += math-emu.o

math-emu-objs := math.o qrnnd.o
