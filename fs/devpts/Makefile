#
# Makefile for the Linux /dev/pts virtual filesystem.
#

ccflags-y += -I$(src)
obj-$(CONFIG_UNIX98_PTYS)		+= devpts.o

devpts-$(CONFIG_UNIX98_PTYS)		:= inode.o
