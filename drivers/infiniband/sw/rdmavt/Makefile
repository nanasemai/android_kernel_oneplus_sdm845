#
# rdmavt driver
#
#
#
# Called from the kernel module build system.
#
ccflags-y += -I$(src)
obj-$(CONFIG_INFINIBAND_RDMAVT) += rdmavt.o

rdmavt-y := vt.o ah.o cq.o dma.o mad.o mcast.o mmap.o mr.o pd.o qp.o srq.o \
	trace.o

CFLAGS_trace.o = -I$(src)
