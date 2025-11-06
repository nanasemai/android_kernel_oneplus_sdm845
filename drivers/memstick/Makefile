#
# Makefile for the kernel MemoryStick device drivers.
#

ccflags-y += -I$(src)
subdir-ccflags-$(CONFIG_MEMSTICK_DEBUG) := -DDEBUG

obj-$(CONFIG_MEMSTICK)		+= core/
obj-$(CONFIG_MEMSTICK)		+= host/

