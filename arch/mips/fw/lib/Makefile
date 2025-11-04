#
# Makefile for generic prom monitor library routines under Linux.
#

ccflags-y += -I$(src)
lib-y			+= cmdline.o

lib-$(CONFIG_64BIT)	+= call_o32.o
