#
# Makefile for the efivarfs filesystem
#

ccflags-y += -I$(src)
obj-$(CONFIG_EFIVAR_FS)		+= efivarfs.o

efivarfs-objs			:= inode.o file.o super.o
