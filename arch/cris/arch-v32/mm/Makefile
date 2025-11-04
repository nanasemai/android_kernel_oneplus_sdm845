# Makefile for the Linux/cris parts of the memory manager.

ccflags-y += -I$(src)
obj-y	 += mmu.o init.o tlb.o intmem.o
obj-$(CONFIG_ETRAX_L2CACHE)    += l2cache.o
