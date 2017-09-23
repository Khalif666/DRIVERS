ifneq ($(KERNELRELEASE),)
obj-m := hello.o
else
KDIR := /home/username/linux_kernel/linux-4.14-rc1

all:
	$(MAKE) -C $(KDIR) M=$$PWD
endif
