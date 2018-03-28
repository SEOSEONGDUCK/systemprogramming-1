KERNELDIR = /lib/modules/$(shell uname -r)/build

obj-m :=hello.o

PWD :=$(shell pwd)

default :
	$(MAKE) -C $(KERNELDIR) M=$(PWD) modules
