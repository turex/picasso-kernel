GCOV_PROFILE := y
EXTRA_CFLAGS += -Idrivers/staging/tegra/include

obj-y += nvmap.o
obj-y += nvmap_dev.o
obj-y += nvmap_handle.o
obj-y += nvmap_heap.o
obj-y += nvmap_ioctl.o
# obj-${CONFIG_IOMMU_API}	+= nvmap_iommu.o
obj-${CONFIG_NVMAP_RECLAIM_UNPINNED_VM} += nvmap_mru.o