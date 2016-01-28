KERNEL_BUILD := /media/jamie/73a7d497-3f1f-4cfc-98b3-f2d99df94c66/home/jamie/development/android/desire610/1.31.xxx.3_a3qhdul-3.4.0-g29bee57/kernel_a3qhdul-3.4.0-g29bee57/
KERNEL_CROSS_COMPILE := arm-eabi-4.7/bin/arm-eabi-
obj-m += wp_mod.o

all:
	make -C $(KERNEL_BUILD) CROSS_COMPILE=$(KERNEL_CROSS_COMPILE) M=/media/jamie/73a7d497-3f1f-4cfc-98b3-f2d99df94c66/home/jamie/development/android/desire610/1.31.xxx.3_a3qhdul-3.4.0-g29bee57/kernel_a3qhdul-3.4.0-g29bee57/wp_mod-master/ modules

clean:
	make -C $(KERNEL_BUILD) M=$(PWD) clean 2> /dev/null
	rm -f modules.order *~
