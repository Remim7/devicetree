你可以通过这clone所有依赖文件，

注意放到合适的文件夹，

文件夹位置都在mk.dependencies。

举个例子

"repository": "android_device_sony_rhine-common",
"target_path": "device/sony/rhine-common"

就是把克隆下来的android_device_sony_rhine-common文件放到源码目录下的device/sony里（sony文件夹自己创建），并重命名为rhine-common
以此类推

注意

https://github.com/Remim7/android_prebuilts_snapdragon_llvm-3.8
克隆下来要放在prebuilts/snapdragon-llvm/toolchains/llvm-Snapdragon_LLVM_for_Android_3.8/prebuilt里面（没有的文件夹自己创建），并重命名为linux-x86_64，不然编译到30%绝对报错
