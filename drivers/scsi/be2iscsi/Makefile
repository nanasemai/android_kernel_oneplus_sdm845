#
# Makefile to build the iSCSI driver for Emulex OneConnect.
#
#

ccflags-y += -I$(src)
obj-$(CONFIG_BE2ISCSI) += be2iscsi.o

be2iscsi-y := be_iscsi.o be_main.o be_mgmt.o be_cmds.o
