#
# Makefile for the lm36011 drivers.
#

ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_req_mgr
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_smmu/
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_sync
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_utils
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_sensor_module/cam_sensor
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_sensor_module/cam_cci
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_sensor_module/cam_sensor_utils
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_cpas/include
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_sensor_module/cam_sensor_io
ccflags-y += -I $(srctree)/drivers/media/platform/msm/camera_floral/cam_core

obj-$(CONFIG_INPUT_LM36011) += lm36011_module.o
