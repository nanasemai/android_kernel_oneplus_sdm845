# Makefile for lib/ function selftests

# No binaries, but make sure arg-less "make" doesn't trigger "run_tests"
ccflags-y += -I$(src)
all:

TEST_PROGS := printf.sh bitmap.sh

include ../lib.mk
