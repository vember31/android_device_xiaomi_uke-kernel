# Xiaomi Pad 7 (`uke`) Prebuilt Kernel

Prebuilt kernel artifacts extracted from:

```text
uke_global_images_OS3.0.9.0.WOZMIXM_20260323.0000.00_16.0_global
```

Contents:

- `kernel`: raw ARM64 kernel image extracted from `boot.img`
- `dtbo.img`: stock DTBO image
- `dtb.img`: DTB section extracted from `vendor_boot.img`
- `modules/vendor`: stock `vendor_dlkm` modules and module metadata
- `modules/ramdisk`: stock `vendor_boot` ramdisk modules and load lists
- `modules/system`: stock `system_dlkm` module metadata and flattened modules

Kernel version: `6.1.118-android14-11-gca0ef6d17716-ab13624819`
