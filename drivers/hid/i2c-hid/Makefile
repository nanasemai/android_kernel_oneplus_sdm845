#
# Makefile for the I2C input drivers
#

ccflags-y += -I$(src)
obj-$(CONFIG_I2C_HID)				+= i2c-hid.o

i2c-hid-objs					=  i2c-hid-core.o
i2c-hid-$(CONFIG_DMI)				+= i2c-hid-dmi-quirks.o
