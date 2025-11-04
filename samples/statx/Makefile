# kbuild trick to avoid linker error. Can be omitted if a module is built.
ccflags-y += -I$(src)
obj- := dummy.o

# List of programs to build
hostprogs-$(CONFIG_SAMPLE_STATX) := test-statx

# Tell kbuild to always build the programs
always := $(hostprogs-y)

HOSTCFLAGS_test-statx.o += -I$(objtree)/usr/include
