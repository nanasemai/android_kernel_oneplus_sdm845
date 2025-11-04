#
# Makefile for the linux kernel debugger
#

ccflags-y += -I$(src)
obj-$(CONFIG_KGDB) += debug_core.o gdbstub.o
obj-$(CONFIG_KGDB_KDB) += kdb/
