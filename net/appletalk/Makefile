#
# Makefile for the Linux AppleTalk layer.
#

ccflags-y += -I$(src)
obj-$(CONFIG_ATALK) += appletalk.o

appletalk-y			:= aarp.o ddp.o dev.o
appletalk-$(CONFIG_PROC_FS)	+= atalk_proc.o
appletalk-$(CONFIG_SYSCTL)	+= sysctl_net_atalk.o
