## Development for Nothing Phone (3a) Lite "`Galaxian`"

<div>
  <img align="right" width="35%" src="https://www.bouyguestelecom.fr/catalogue/image-resize/full/media/catalog/product/b/a/back-.png">
</div>

This organization contains all the important repositories required to build custom ROMs for Nothing Phone (3a) Lite

### Required device specific repositories
* [**manifest**](https://github.com/Nothing-Phone-3a-Lite/local_manifests) (`local_manifests`)
* [**Device tree**](https://github.com/Nothing-Phone-3a-Lite/device_nothing_Galaxian) (`device_nothing_Galaxian`)
* [**Device kernel tree (Compiled outputs from kernel source)**](https://github.com/Nothing-Phone-3a-Lite/device_nothing_Galaxian-kernel) ('device_nothing_Galaxian-kernel`)
* [**Vendor tree**](https://github.com/Nothing-Phone-3a-Lite/proprietary_vendor_nothing_Galaxian) (`proprietary_vendor_nothing_Galaxian`)

### Other required repositories
* [**MediaTek sepolicy**](https://github.com/Nothing-Phone-3a-Lite/device_mediatek_sepolicy_vndr) (`device_mediatek_sepolicy_vndr`)
* [**MediaTek hardware**](https://github.com/Nothing-Phone-3a-Lite/hardware_mediatek) (`hardware_mediatek`)
* [**hardware dolby**](https://github.com/Nothing-Phone-3a-Lite/hardware_dolby) (`hardware_dolby`)

### Required patches
* [**Add 60FPS recording on Aperture**](https://github.com/Nothing-2A/android_packages_apps_Aperture/commit/a4c34aa57ed56de60f29349a1e6d20cf8160ca15) (`android_packages_apps_Aperture`)

### Optional patches (fenrir patched LK support, use at your own risk)
* [**Allow booting with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/8ff6e7a68523c3b870d8dcd5713c71ea15b43dd2) (`android_system_core`)
* [**Allow flashing images from fastbootd with fenrir patched LKs**](https://github.com/Nothing-2A/android_system_core/commit/0d5990a96c5e6a404887f5575c5d00bcbbaaef74) (`android_system_core`)

* [**Standalone repo to apply all patches automatically**](https://github.com/Nothing-Phone-3a-Lite/patches) (`patches`)

### Device kernel repositories
* [**Kernel source**](https://github.com/Nothing-Phone-3a-Lite/android_kernel_nothing_mt6878) (`android_kernel_nothing_mt6878`)
* * [**External kernel modules source**](https://github.com/Nothing-Phone-3a-Lite/android_kernel_modules_nothing_mt6878) (`android_kernel_modules_nothing_mt6878`)
* [**External device modules source**](https://github.com/Nothing-Phone-3a-Lite/android_kernel_device_modules_6.1_nothing_mt6878) (`android_kernel_device_modules_6.1_nothing_mt6878`)
