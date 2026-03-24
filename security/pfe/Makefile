#
# Makefile for the MSM specific security device drivers.
#

ccflags-y += -I $(srctree)/security/selinux -I $(srctree)/security/selinux/include
ccflags-y += -I $(srctree)/fs/crypto
ccflags-y += -I $(srctree)/drivers/misc

obj-$(CONFIG_PFT) += pft.o
obj-$(CONFIG_PFK) += pfk.o pfk_kc.o pfk_ice.o pfk_ext4.o pfk_f2fs.o
