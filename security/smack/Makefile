#
# Makefile for the SMACK LSM
#

ccflags-y += -I$(src)
obj-$(CONFIG_SECURITY_SMACK) := smack.o

smack-y := smack_lsm.o smack_access.o smackfs.o
smack-$(CONFIG_SECURITY_SMACK_NETFILTER) += smack_netfilter.o
