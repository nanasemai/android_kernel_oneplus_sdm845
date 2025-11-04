#
# Makefile for the overlay filesystem.
#

ccflags-y += -I$(src)
obj-$(CONFIG_OVERLAY_FS) += overlay.o

overlay-objs := super.o inode.o dir.o readdir.o copy_up.o
