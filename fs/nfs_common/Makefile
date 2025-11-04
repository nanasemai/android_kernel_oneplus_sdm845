#
# Makefile for Linux filesystem routines that are shared by client and server.
#

ccflags-y += -I$(src)
obj-$(CONFIG_NFS_ACL_SUPPORT) += nfs_acl.o
nfs_acl-objs := nfsacl.o

obj-$(CONFIG_GRACE_PERIOD) += grace.o
