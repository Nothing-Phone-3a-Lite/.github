## Development for Nothing Phone (3a) Lite "`Galaxian`"

<div>
  <img align="right" width="35%" src="https://www.bouyguestelecom.fr/catalogue/image-resize/full/media/catalog/product/b/a/back-.png">
</div>

This organization contains all the important repositories required to build custom ROMs for Nothing Phone (3a) Lite

### Required device specific repositories
* [**Device tree**](https://github.com/Nothing-Phone-3a-Lite/device_nothing_Galaxian) (`device_nothing_Galaxian`)
* [**Device kernel tree (Compiled outputs from kernel source)**](https://github.com/Nothing-Phone-3a-Lite/device_nothing_Galaxian-kernel) ('device_nothing_Galaxian-kernel`)
* [**Vendor tree**](https://github.com/Nothing-Phone-3a-Lite/proprietary_vendor_nothing_Galaxian) (`proprietary_vendor_nothing_Galaxian`)

### Other required repositories
* [**MediaTek sepolicy**](https://github.com/Nothing-Phone-3a-Lite/device_mediatek_sepolicy_vndr) (`device_mediatek_sepolicy_vndr`)
* [**MediaTek hardware**](https://github.com/Nothing-Phone-3a-Lite/hardware_mediatek) (`hardware_mediatek`)
* [**MediaTek hardware**](https://github.com/Nothing-Phone-3a-Lite/hardware_dolby) (`hardware_dolby`)
* [**ParanoidGlyph**](https://github.com/Nothing-Phone-3a-Lite/packages_apps_ParanoidGlyph) (`android_packages_apps_ParanoidGlyph`)
* [**GlyphAdapter**](https://github.com/Nothing-Phone-3a-Lite/packages_apps_GlyphAdapter) (`android_packages_apps_GlyphAdapter`)
* [**NTCamera**](https://github.com/Nothing-Phone-3a-Lite/packages_apps_NTCamera) (`android_packages_apps_NTCamera`)

### Optional repositories
* [**NTGallery**](https://github.com/Nothing-Phone-3a-Lite/packages_apps_NTGallery) (`android_packages_apps_NTGallery`)
* [**NTGallery**](https://github.com/Nothing-Phone-3a-Lite/packages_apps_GalaxianParts) (`android_packages_apps_GalaxianParts`)

### Required patches
* [**Add 60FPS recording on Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)

### Optional patches (fenrir patched LK support, use at your own risk)
* [**Allow booting with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/8ff6e7a68523c3b870d8dcd5713c71ea15b43dd2) (`android_system_core`)
* [**Allow flashing images from fastbootd with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/0d5990a96c5e6a404887f5575c5d00bcbbaaef74) (`android_system_core`)

### Device kernel repositories
* [**Kernel source**](https://github.com/Nothing-Phone-3a-Lite/android_kernel_nothing_mt6878) (`android_kernel_nothing_mt6878`)
* [**External kernel modules source**](https://github.com/Nothing-Phone-3a-Lite/android_kernel_modules_nothing_mt6878) (`android_kernel_modules_nothing_mt6878`)