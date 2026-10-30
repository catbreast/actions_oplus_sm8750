# GT7 (RMX6688) baseline — extracted 2026-10-30

Device: realme GT7 (RMX6688), MT6991, running build RMX6688_16.0.10.500(CN01), Android 16
Running kernel: 6.6.118-android15-8-ge58033dc8ea6-abogki498046332-4k (stock, CONFIG_MODVERSIONS=y)
Vendor modules (369, incl. wlan_drv_gen4m + conninfra) built against: 6.6.118-android15-8-o-gf2d7ae5320a4-4k
GKI/system modules (95) vermagic matches the running kernel string.

Files:
- stock_config.txt — /proc/config.gz from the running stock kernel (7753 lines)
- stock_symvers.txt — merged __versions CRC map from all 465 vendor_dlkm+system_dlkm .ko
  (extracted from E:\realme\16.501 stock images via fsck.erofs; 5706 symbols, 0 conflicts)
  Gate rule: a custom kernel may only be flashed if every symbol it exports that
  appears in this list has an identical CRC.
