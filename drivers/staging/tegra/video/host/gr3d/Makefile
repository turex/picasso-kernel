GCOV_PROFILE := y
EXTRA_CFLAGS += -Idrivers/staging/tegra/video/host
EXTRA_CFLAGS += -Idrivers/staging/tegra/include

nvhost-gr3d-objs  = \
		gr3d.o \
		gr3d_t20.o \
		gr3d_t30.o \
		scale3d.o

obj-$(CONFIG_TEGRA_GRHOST) += nvhost-gr3d.o
