#
# Makefile for the DECstation prom monitor library routines
# under Linux.
#

ccflags-y += -I$(src)
lib-y			+= init.o memory.o cmdline.o identify.o console.o

lib-$(CONFIG_CPU_R3000)	+= locore.o
