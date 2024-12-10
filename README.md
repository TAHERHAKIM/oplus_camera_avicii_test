# Breadcrumbsoplus_camera_avicii_test

A experimental OOSCam for OnePlus Nord (avicii) to include in custom ROM builds. This has no guarantee that it would work

### How to use?

1. Clone this repo to `vendor/oplus/camera`

2. Inherit it from `device.mk` in device tree:

```
# Camera
$(call inherit-product-if-exists, vendor/oplus/camera/opluscamera.mk)
```

3. Ensure that the PRODUCT_BRAND is either oneplus or oppo or realme and that it is not overriden by any of the safetynet hacks.
