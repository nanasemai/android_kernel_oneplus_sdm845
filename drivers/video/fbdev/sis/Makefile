#
# Makefile for the SiS framebuffer device driver
#

ccflags-y += -I$(src)
obj-$(CONFIG_FB_SIS) += sisfb.o

sisfb-objs := sis_main.o sis_accel.o init.o init301.o initextlfb.o
