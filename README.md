# proprietary_vendor_xiaomi_camera

Prebuilt MIUI Camera to include in custom ROM builds.

### Supported devices
* SM6115/SM6225 (bengal/khaje) devices

### How to use?

1. Clone this repo to `vendor/xiaomi/spes-miuicamera`

2. Inherit it from `device.mk` in device tree:

```
# Camera
$(call inherit-product-if-exists, vendor/xiaomi/spes-miuicamera/miuicamera.mk)
```
