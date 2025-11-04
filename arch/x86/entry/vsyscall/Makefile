#
# Makefile for the x86 low level vsyscall code
#
ccflags-y += -I$(src)
obj-y					:= vsyscall_gtod.o

obj-$(CONFIG_X86_VSYSCALL_EMULATION)	+= vsyscall_64.o vsyscall_emu_64.o

