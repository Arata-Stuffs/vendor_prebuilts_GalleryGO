# Prebuilts GalleryGO
How to use or add this to your custom roms source?
Follow this steps

### How to use
1. Clone this repository
```
git clone https://github.com/Arata-Stuffs/vendor_prebuilts_GalleryGO.git vendor/prebuilts/GalleryGO
```

2. Add this to your device.mk
```
# GalleryGo
$(call inherit-product-if-exists, vendor/prebuilts/GalleryGO/config.mk)
```