#
# Makefile for the kernel PNPBIOS driver.
#
ccflags-y += -I$(src)
obj-y := pnp.o

pnp-y := core.o bioscalls.o rsparser.o

pnp-$(CONFIG_PNPBIOS_PROC_FS) += proc.o
