#include $(srctree)/drivers/misc/mediatek/Makefile.custom
#obj-y += s5k4h8mipi_Sensor.o

ifeq ($(TARGET_BUILD_VARIANT),user)
ccflags-y += -D_LOG_USER_
endif

obj-y += s5k4h8_otp.o

