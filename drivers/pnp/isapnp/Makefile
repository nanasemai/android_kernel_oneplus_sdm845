#
# Makefile for the kernel ISAPNP driver.
#
ccflags-y += -I$(src)
obj-y			+= pnp.o
pnp-y			:= core.o compat.o

pnp-$(CONFIG_PROC_FS)	+= proc.o
