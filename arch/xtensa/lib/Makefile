#
# Makefile for Xtensa-specific library files.
#

ccflags-y += -I$(src)
lib-y	+= memcopy.o memset.o checksum.o \
	   usercopy.o strncpy_user.o strnlen_user.o
lib-$(CONFIG_PCI) += pci-auto.o
