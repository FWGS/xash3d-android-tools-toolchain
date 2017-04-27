# xash3d-android-tools-toolchain
Toolchain from gcc-termux. Removed termux dependency, but may still depend on android-5


### WARNING
Do not use it to build hardfloat binaries without android sysroot (https://github.com/FWGS/xash3d-android-tools-sysroot)

It will link output files with system libraries, so without sysroot it is very depended on your system. BTW, sysroot will disable libgnustl_shared dependency

### NOTE
To enable STL or RTTI support use STLPort (https://github.com/FWGS/xash3d-android-tools-stlport)

### NOTE
This is untested with android 4.x and should not work with 2.x-
