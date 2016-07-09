# AndroidNative-IntelliJ
Compile JNI using android NDK

Keep your .cpp file in jni folder and run, it creates .so file for different type of CPU archetiture 
Archetiture specify in Android.mk file which lie in jni folder
module name define in build.gradle file of particular sub-project.

### xyz.so file which takes native binary file of ###
* libstdc++.so  -> standard c++ library
* libm.so -> math library
* libc.so -> c library
* libdl.so -> provide dynmic linking support

### libgdx.so file which takes native binary file of ###
* libGLESv2.so -> OpenGLES 2.0 graphics library
* liblog.so -> Ndk logging interface
* libstdc++.so  -> standard c++ library
* libm.so -> math library
* libc.so -> c library
* libdl.so -> provide dynmic linking support

### libcocos2dcpp.so file which takes binary file of ###
* liblog.so
* libOpenSLES.so -> audio input and output
* libGLESv2.so
* libz.so -> compression library
* libandroid.so -> for native header like activity, input...
* libGLESv1_CM.so -> openGLES 1.0 library
* libEGL.so -> ablity to allocate and manage openGL surface
* libstdc++.so  -> standard c++ library
* libm.so -> math library
* libc.so -> c library
* libdl.so -> provide dynmic linking support

### libunity.so file which takes binary file of ###
* libmono.so
* libmain.so
* libc.so -> c library
* libm.so -> math library
* libandroid.so -> for native header like activity, input...
* libdl.so -> provide dynmic linking support
* liblog.so
* libGLESv1_CM.so -> openGLES 1.0 library
* libGLESv2.so
* libstdc++.so  -> standard c++ library
* libz.so -> compression library
* libEGL.so -> ablity to allocate and manage openGL surface
