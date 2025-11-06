#
# Makefile for PPS generators.
#

ccflags-y += -I$(src)
obj-$(CONFIG_PPS_GENERATOR_PARPORT) += pps_gen_parport.o

ifeq ($(CONFIG_PPS_DEBUG),y)
EXTRA_CFLAGS += -DDEBUG
endif
