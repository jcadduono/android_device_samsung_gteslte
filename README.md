## TWRP device tree for Galaxy Tab E 8.0 (Exynos)

Add to `.repo/local_manifests/gteslte.xml`:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
	<project path="device/samsung/gteslte" name="android_device_samsung_gteslte" remote="TeamWin" revision="android-6.0" />
</manifest>
```

Then run `repo sync` to check it out.

Kernel sources are available at: https://github.com/jcadduono/twrp_kernel_samsung_gteslte/tree/twrp-6.0

