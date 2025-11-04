#
# Makefile for SSP sensor drivers and commons.
#

ccflags-y += -I$(src)
sensorhub-objs				:= ssp_dev.o ssp_spi.o
obj-$(CONFIG_IIO_SSP_SENSORHUB)		+= sensorhub.o

obj-$(CONFIG_IIO_SSP_SENSORS_COMMONS) 	+= ssp_iio.o
