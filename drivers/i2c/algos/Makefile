#
# Makefile for the i2c algorithms
#

ccflags-y += -I$(src)
obj-$(CONFIG_I2C_ALGOBIT)	+= i2c-algo-bit.o
obj-$(CONFIG_I2C_ALGOPCF)	+= i2c-algo-pcf.o
obj-$(CONFIG_I2C_ALGOPCA)	+= i2c-algo-pca.o

ccflags-$(CONFIG_I2C_DEBUG_ALGO) := -DDEBUG
