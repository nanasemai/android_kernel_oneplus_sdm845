#
# Arch-specific network modules
#
ccflags-y += -I$(src)
OBJECT_FILES_NON_STANDARD_bpf_jit.o += y

obj-$(CONFIG_BPF_JIT) += bpf_jit.o bpf_jit_comp.o
