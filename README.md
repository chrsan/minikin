# minikin

[minikin][1] clone with a couple of minor changes.

Cloned as:

```console
git clone -b android-10.0.0_r32 --depth 1 https://android.googlesource.com/platform/frameworks/minikin
```

The `utils` directory was created as follows:

```console
git clone -b android-10.0.0_r32 --depth 1 https://android.googlesource.com/platform/system/core /tmp/core
mkdir utils
cp /tmp/core/libutils/include/utils/{LruCache.h,TypeHelpers.h} utils
```

[1]: https://android.googlesource.com/platform/frameworks/minikin
