#
# Makefile for the netlink driver.
#

ccflags-y += -I$(src)
obj-y  				:= af_netlink.o genetlink.o

obj-$(CONFIG_NETLINK_DIAG)	+= netlink_diag.o
netlink_diag-y			:= diag.o
