# builds a module that calls various trace_printk routines
# then to use one (as root):  insmod <module_name.ko>

# This module can also be used to test the trace_printk code.

ccflags-y += -I$(src)
obj-$(CONFIG_SAMPLE_TRACE_PRINTK) += trace-printk.o
