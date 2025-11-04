#
# Makefile for kernel probes
#

ccflags-y += -I$(src)
obj-$(CONFIG_KPROBES)		+= core.o
obj-$(CONFIG_OPTPROBES)		+= opt.o
obj-$(CONFIG_KPROBES_ON_FTRACE)	+= ftrace.o
