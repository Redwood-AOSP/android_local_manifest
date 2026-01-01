![Poco X5 Pro 5G/Redmi Note 12 Pro Speed](https://i.blogs.es/98a725/poco-x5-pro/1366_2000.jpeg "Poco X5 Pro 5G/Redmi Note 12 Pro Speed")

# Redwood-AOSP

## Getting Started

To get started get familiar with [Git & Repo](https://source.android.com/setup/build/downloading).

1. Initialize the ROM repo.

2. Clone local manifest:

	```bash
	git clone https://github.com/Redwood-AOSP/android_local_manifest -b sixteen-qpr1 .repo/local_manifests
	```

3. Then sync:

	```bash
	repo sync -c --no-clone-bundle --no-tags --optimized-fetch --prune --force-sync -j$(nproc --all)
	```

---

**Note**: You need to upbring and adapt the device tree as per the ROM.
