#
# Makefile for the Kyro framebuffer driver
#

ccflags-y += -I$(src)
obj-$(CONFIG_FB_KYRO)	+= kyrofb.o

kyrofb-objs	:= STG4000Ramdac.o STG4000VTG.o STG4000OverlayDevice.o \
		   STG4000InitDevice.o fbdev.o
