# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libwilhelm)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/wilhelm/src/OpenSLES_IID.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/assert.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/classes.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/data.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/devices.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/entry.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/handler_bodies.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/trace.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/locks.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/sles.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/sl_iid.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/sllog.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/ThreadPool.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/AudioPlayer_to_android.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/AudioRecorder_to_android.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/MediaPlayer_to_android.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/OutputMix_to_android.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/VideoCodec_to_android.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/BufferQueueSource.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/CallbackProtector.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/AacBqToPcmCbRenderer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/android_AudioSfDecoder.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/android_AudioToCbRenderer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/android_GenericMediaPlayer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/android_GenericPlayer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/android_LocAVPlayer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/android_StreamPlayer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/android_Effect.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/util/AacAdtsExtractor.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/android/channels.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/autogen/IID_to_MPH.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/objects/C3DGroup.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/objects/CAudioPlayer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/objects/CAudioRecorder.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/objects/CEngine.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/objects/COutputMix.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/objects/CMediaPlayer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IAndroidBufferQueue.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IAndroidConfiguration.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IAndroidEffect.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IAndroidEffectCapabilities.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IAndroidEffectSend.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IAcousticEchoCancellation.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IAutomaticGainControl.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IBassBoost.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IBufferQueue.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IDynamicInterfaceManagement.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IEffectSend.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IEngine.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IEngineCapabilities.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IEnvironmentalReverb.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IEqualizer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IMetadataExtraction.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/INoiseSuppression.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IMuteSolo.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IObject.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IOutputMix.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IPlay.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IPlaybackRate.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IPrefetchStatus.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IPresetReverb.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IRecord.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/ISeek.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IStreamInformation.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IVideoDecoderCapabilities.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IVirtualizer.cpp
    ${ANDROID_ROOT}/frameworks/wilhelm/src/itf/IVolume.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/av/media/libstagefright/mpeg2ts'
# Raw param [1] = '-Iframeworks/wilhelm/src'
# Raw param [2] = '${config.ArmClangThumbCflags}'
# Raw param [3] = '${config.ArmClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [7] = '-Iframeworks/wilhelm/include'
# Raw param [8] = '-Iframeworks/native/headers/media_plugin'
# Raw param [9] = '-Iframeworks/native/headers/media_plugin/media/openmax'
# Raw param [10] = '-Iframeworks/av/media/libstagefright/include'
# Raw param [11] = '-Isystem/core/libcutils/include'
# Raw param [12] = '-Isystem/core/libutils/include'
# Raw param [13] = '-Isystem/core/libbacktrace/include'
# Raw param [14] = '-Isystem/core/liblog/include'
# Raw param [15] = '-Isystem/core/libsystem/include'
# Raw param [16] = '-Isystem/core/libprocessgroup/include'
# Raw param [17] = '-Iframeworks/av/media/libstagefright/foundation/include'
# Raw param [18] = '-Iframeworks/wilhelm/src/ut'
# Raw param [19] = '-Iframeworks/av/media/libmedia/include'
# Raw param [20] = '-Iframeworks/av/media/ndk/include'
# Raw param [21] = '-Iframeworks/native/libs/binder/include'
# Raw param [22] = '-Isystem/core/base/include'
# Raw param [23] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [24] = '-Iexternal/sonivox/arm-wt-22k/include'
# Raw param [25] = '-Iexternal/icu/libandroidicu/include'
# Raw param [26] = '-D__LIBANDROIDICU_API__=1'
# Raw param [27] = '-Iframeworks/av/media/libaudioclient/include'
# Raw param [28] = '-Iout/soong/.intermediates/frameworks/av/media/libaudioclient/libaudioclient/android_arm_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [29] = '-Iframeworks/av/media/libmedia/aidl'
# Raw param [30] = '-Isystem/libhidl/transport/token/1.0/utils/include'
# Raw param [31] = '-Isystem/libhidl/base/include'
# Raw param [32] = '-Isystem/libhidl/transport/include'
# Raw param [33] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [34] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [35] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen'
# Raw param [36] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [37] = '-Isystem/libhwbinder/include'
# Raw param [38] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen'
# Raw param [39] = '-Iout/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen'
# Raw param [40] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen'
# Raw param [41] = '-Iout/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen'
# Raw param [42] = '-Iframeworks/native/libs/nativebase/include'
# Raw param [43] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [44] = '-Ihardware/libhardware/include'
# Raw param [45] = '-Isystem/media/audio/include'
# Raw param [46] = '-Isystem/bt/types'
# Raw param [47] = '-Iframeworks/native/libs/ui/include'
# Raw param [48] = '-Iframeworks/native/libs/arect/include'
# Raw param [49] = '-Iframeworks/native/libs/math/include'
# Raw param [50] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen'
# Raw param [51] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen'
# Raw param [52] = '-Iout/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [53] = '-Iframeworks/native/libs/gui/include'
# Raw param [54] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen'
# Raw param [55] = '-Iframeworks/native/opengl/libs/EGL/include'
# Raw param [56] = '-Iframeworks/native/opengl/include'
# Raw param [57] = '-Iframeworks/native/libs/nativewindow/include-private'
# Raw param [58] = '-Isystem/libhidl/libhidlmemory/include'
# Raw param [59] = '-Iout/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen'
# Raw param [60] = '-Iout/soong/.intermediates/system/libhidl/transport/memory/token/1.0/android.hidl.memory.token@1.0_genc++_headers/gen'
# Raw param [61] = '-Iout/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen'
# Raw param [62] = '-Iframeworks/base/core/jni'
# Raw param [63] = '-Iframeworks/base/core/jni/include'
# Raw param [64] = '-Ilibnativehelper/include'
# Raw param [65] = '-Ilibnativehelper/header_only_include'
# Raw param [66] = '-Ilibnativehelper/platform_include'
# Raw param [67] = '-D__LIBNATIVEHELPER_API__=1'
# Raw param [68] = '-Iframeworks/base/libs/hwui'
# Raw param [69] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui'
# Raw param [70] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/proto'
# Raw param [71] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/sysprop/include'
# Raw param [72] = '-Iexternal/skia/include/android'
# Raw param [73] = '-Iexternal/skia/include/atlastext'
# Raw param [74] = '-Iexternal/skia/include/c'
# Raw param [75] = '-Iexternal/skia/include/codec'
# Raw param [76] = '-Iexternal/skia/include/config'
# Raw param [77] = '-Iexternal/skia/include/core'
# Raw param [78] = '-Iexternal/skia/include/docs'
# Raw param [79] = '-Iexternal/skia/include/effects'
# Raw param [80] = '-Iexternal/skia/include/encode'
# Raw param [81] = '-Iexternal/skia/include/gpu'
# Raw param [82] = '-Iexternal/skia/include/pathops'
# Raw param [83] = '-Iexternal/skia/include/ports'
# Raw param [84] = '-Iexternal/skia/include/svg'
# Raw param [85] = '-Iexternal/skia/include/utils'
# Raw param [86] = '-Iexternal/skia/include/utils/mac'
# Raw param [87] = '-Iexternal/skia/include/config/android'
# Raw param [88] = '-Iexternal/vulkan-headers/include'
# Raw param [89] = '-Iexternal/protobuf/src'
# Raw param [90] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/proto/frameworks/base/libs/hwui'
# Raw param [91] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/proto'
# Raw param [92] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/sysprop/include'
# Raw param [93] = '-Iframeworks/av/media/libstagefright/http'
# Raw param [94] = '-Iexternal/libcxx/include'
# Raw param [95] = '-Iexternal/libcxxabi/include'
# Raw param [96] = '-Ibionic/libc/include'
# Raw param [97] = '-D__LIBC_API__=10000'
# Raw param [98] = '-D__LIBM_API__=10000'
# Raw param [99] = '-D__LIBDL_API__=10000'
# variable ${config.ArmClangThumbCflags} = '-mthumb -Os'
# Raw param [0] = '-mthumb'
# Raw param [1] = '-Os'
# FLAG '-mthumb' became -mthumb
# FLAG '-Os' became -Os
# variable ${config.ArmClangCflags} = '-fomit-frame-pointer'
# Raw param [0] = '-fomit-frame-pointer'
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# variable ${config.CommonClangGlobalCflags} = '-DANDROID -fmessage-length=0 -W -Wall -Wno-unused -Winit-self -Wpointer-arith -no-canonical-prefixes -DNDEBUG -UDEBUG -fno-exceptions -Wno-multichar -O2 -g -fno-strict-aliasing -fdebug-prefix-map=/proc/self/cwd= -D__compiler_offsetof=__builtin_offsetof -faddrsig -Wimplicit-fallthrough -Werror=int-conversion -Wno-reserved-id-macro -Wno-format-pedantic -Wno-unused-command-line-argument -fcolor-diagnostics -Wno-zero-as-null-pointer-constant -Wno-sign-compare -Wno-defaulted-function-deleted -Wno-inconsistent-missing-override'
# Raw param [0] = '-DANDROID'
# Raw param [1] = '-fmessage-length=0'
# Raw param [2] = '-W'
# Raw param [3] = '-Wall'
# Raw param [4] = '-Wno-unused'
# Raw param [5] = '-Winit-self'
# Raw param [6] = '-Wpointer-arith'
# Raw param [7] = '-no-canonical-prefixes'
# Raw param [8] = '-DNDEBUG'
# Raw param [9] = '-UDEBUG'
# Raw param [10] = '-fno-exceptions'
# Raw param [11] = '-Wno-multichar'
# Raw param [12] = '-O2'
# Raw param [13] = '-g'
# Raw param [14] = '-fno-strict-aliasing'
# Raw param [15] = '-fdebug-prefix-map=/proc/self/cwd='
# Raw param [16] = '-D__compiler_offsetof=__builtin_offsetof'
# Raw param [17] = '-faddrsig'
# Raw param [18] = '-Wimplicit-fallthrough'
# Raw param [19] = '-Werror=int-conversion'
# Raw param [20] = '-Wno-reserved-id-macro'
# Raw param [21] = '-Wno-format-pedantic'
# Raw param [22] = '-Wno-unused-command-line-argument'
# Raw param [23] = '-fcolor-diagnostics'
# Raw param [24] = '-Wno-zero-as-null-pointer-constant'
# Raw param [25] = '-Wno-sign-compare'
# Raw param [26] = '-Wno-defaulted-function-deleted'
# Raw param [27] = '-Wno-inconsistent-missing-override'
# FLAG '-DANDROID' became -DANDROID
# FLAG '-fmessage-length=0' became -fmessage-length=0
# FLAG '-W' became -W
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused' became -Wno-unused
# FLAG '-Winit-self' became -Winit-self
# FLAG '-Wpointer-arith' became -Wpointer-arith
# FLAG '-no-canonical-prefixes' became -no-canonical-prefixes
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-UDEBUG' became -UDEBUG
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-O2' became -O2
# FLAG '-g' became -g
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-fdebug-prefix-map=/proc/self/cwd=' became -fdebug-prefix-map=/proc/self/cwd=
# FLAG '-D__compiler_offsetof=__builtin_offsetof' became -D__compiler_offsetof=__builtin_offsetof
# FLAG '-faddrsig' became -faddrsig
# FLAG '-Wimplicit-fallthrough' became -Wimplicit-fallthrough
# FLAG '-Werror=int-conversion' became -Werror=int-conversion
# FLAG '-Wno-reserved-id-macro' became -Wno-reserved-id-macro
# FLAG '-Wno-format-pedantic' became -Wno-format-pedantic
# FLAG '-Wno-unused-command-line-argument' became -Wno-unused-command-line-argument
# FLAG '-fcolor-diagnostics' became -fcolor-diagnostics
# FLAG '-Wno-zero-as-null-pointer-constant' became -Wno-zero-as-null-pointer-constant
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-defaulted-function-deleted' became -Wno-defaulted-function-deleted
# FLAG '-Wno-inconsistent-missing-override' became -Wno-inconsistent-missing-override
# variable ${config.DeviceClangGlobalCflags} = '-ffunction-sections -fdata-sections -fno-short-enums -funwind-tables -fstack-protector-strong -Wa,--noexecstack -D_FORTIFY_SOURCE=2 -Wstrict-aliasing=2 -Werror=return-type -Werror=non-virtual-dtor -Werror=address -Werror=sequence-point -Werror=date-time -Werror=format-security -nostdlibinc'
# Raw param [0] = '-ffunction-sections'
# Raw param [1] = '-fdata-sections'
# Raw param [2] = '-fno-short-enums'
# Raw param [3] = '-funwind-tables'
# Raw param [4] = '-fstack-protector-strong'
# Raw param [5] = '-Wa,--noexecstack'
# Raw param [6] = '-D_FORTIFY_SOURCE=2'
# Raw param [7] = '-Wstrict-aliasing=2'
# Raw param [8] = '-Werror=return-type'
# Raw param [9] = '-Werror=non-virtual-dtor'
# Raw param [10] = '-Werror=address'
# Raw param [11] = '-Werror=sequence-point'
# Raw param [12] = '-Werror=date-time'
# Raw param [13] = '-Werror=format-security'
# Raw param [14] = '-nostdlibinc'
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-Wstrict-aliasing=2' became -Wstrict-aliasing=2
# FLAG '-Werror=return-type' became -Werror=return-type
# FLAG '-Werror=non-virtual-dtor' became -Werror=non-virtual-dtor
# FLAG '-Werror=address' became -Werror=address
# FLAG '-Werror=sequence-point' became -Werror=sequence-point
# FLAG '-Werror=date-time' became -Werror=date-time
# FLAG '-Werror=format-security' became -Werror=format-security
# FLAG '-nostdlibinc' became -nostdlibinc
# variable ${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags} = '-msoft-float -march=armv8-a -mfloat-abi=softfp -mfpu=neon-fp-armv8 -mcpu=cortex-a53 -mfpu=neon-fp-armv8 -D__ARM_FEATURE_LPAE=1'
# Raw param [0] = '-msoft-float'
# Raw param [1] = '-march=armv8-a'
# Raw param [2] = '-mfloat-abi=softfp'
# Raw param [3] = '-mfpu=neon-fp-armv8'
# Raw param [4] = '-mcpu=cortex-a53'
# Raw param [5] = '-mfpu=neon-fp-armv8'
# Raw param [6] = '-D__ARM_FEATURE_LPAE=1'
# FLAG '-msoft-float' became -msoft-float
# FLAG '-march=armv8-a' became -march=armv8-a
# FLAG '-mfloat-abi=softfp' became -mfloat-abi=softfp
# FLAG '-mfpu=neon-fp-armv8' became -mfpu=neon-fp-armv8
# FLAG '-mcpu=cortex-a53' became -mcpu=cortex-a53
# FLAG '-mfpu=neon-fp-armv8' became -mfpu=neon-fp-armv8
# FLAG '-D__ARM_FEATURE_LPAE=1' became -D__ARM_FEATURE_LPAE=1
# FLAG '-D__LIBANDROIDICU_API__=1' became -D__LIBANDROIDICU_API__=1
# FLAG '-D__LIBNATIVEHELPER_API__=1' became -D__LIBNATIVEHELPER_API__=1
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/mpeg2ts"
    "${ANDROID_ROOT}/frameworks/wilhelm/src"
    "${ANDROID_ROOT}/frameworks/wilhelm/include"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/media/openmax"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/foundation/include"
    "${ANDROID_ROOT}/frameworks/wilhelm/src/ut"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/include"
    "${ANDROID_ROOT}/frameworks/av/media/ndk/include"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/external/sonivox/arm-wt-22k/include"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libaudioclient/libaudioclient/android_arm_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/aidl"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include"
    "${ANDROID_ROOT}/system/libhidl/base/include"
    "${ANDROID_ROOT}/system/libhidl/transport/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhwbinder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private"
    "${ANDROID_ROOT}/system/libhidl/libhidlmemory/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/token/1.0/android.hidl.memory.token@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/frameworks/base/core/jni"
    "${ANDROID_ROOT}/frameworks/base/core/jni/include"
    "${ANDROID_ROOT}/libnativehelper/include"
    "${ANDROID_ROOT}/libnativehelper/header_only_include"
    "${ANDROID_ROOT}/libnativehelper/platform_include"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/sysprop/include"
    "${ANDROID_ROOT}/external/skia/include/android"
    "${ANDROID_ROOT}/external/skia/include/atlastext"
    "${ANDROID_ROOT}/external/skia/include/c"
    "${ANDROID_ROOT}/external/skia/include/codec"
    "${ANDROID_ROOT}/external/skia/include/config"
    "${ANDROID_ROOT}/external/skia/include/core"
    "${ANDROID_ROOT}/external/skia/include/docs"
    "${ANDROID_ROOT}/external/skia/include/effects"
    "${ANDROID_ROOT}/external/skia/include/encode"
    "${ANDROID_ROOT}/external/skia/include/gpu"
    "${ANDROID_ROOT}/external/skia/include/pathops"
    "${ANDROID_ROOT}/external/skia/include/ports"
    "${ANDROID_ROOT}/external/skia/include/svg"
    "${ANDROID_ROOT}/external/skia/include/utils"
    "${ANDROID_ROOT}/external/skia/include/utils/mac"
    "${ANDROID_ROOT}/external/skia/include/config/android"
    "${ANDROID_ROOT}/external/vulkan-headers/include"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/proto/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/sysprop/include"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/http"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/mpeg2ts/**/*.h"
    "${ANDROID_ROOT}/frameworks/wilhelm/src/**/*.h"
    "${ANDROID_ROOT}/frameworks/wilhelm/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/media/openmax/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/foundation/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/wilhelm/src/ut/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/ndk/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/external/sonivox/arm-wt-22k/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libaudioclient/libaudioclient/android_arm_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/aidl/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/base/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhwbinder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/libhidlmemory/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/token/1.0/android.hidl.memory.token@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/core/jni/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/core/jni/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/header_only_include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/platform_include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_static/gen/sysprop/include/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/android/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/atlastext/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/c/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/codec/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/config/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/core/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/docs/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/effects/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/encode/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/pathops/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/ports/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/svg/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/mac/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/config/android/**/*.h"
    "${ANDROID_ROOT}/external/vulkan-headers/include/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/proto/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm_armv8-a_kryo_core_shared/gen/sysprop/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/http/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mthumb")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fmessage-length=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Winit-self")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wpointer-arith")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -no-canonical-prefixes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdebug-prefix-map=/proc/self/cwd=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__compiler_offsetof=__builtin_offsetof")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -faddrsig")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wimplicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-conversion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format-pedantic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-command-line-argument")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fcolor-diagnostics")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-zero-as-null-pointer-constant")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-defaulted-function-deleted")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wstrict-aliasing=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=return-type")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=non-virtual-dtor")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=address")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=sequence-point")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=date-time")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=format-security")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -nostdlibinc")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msoft-float")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=armv8-a")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfloat-abi=softfp")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mcpu=cortex-a53")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ARM_FEATURE_LPAE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBANDROIDICU_API__=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBNATIVEHELPER_API__=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBDL_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mthumb")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fmessage-length=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Winit-self")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wpointer-arith")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -no-canonical-prefixes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdebug-prefix-map=/proc/self/cwd=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__compiler_offsetof=__builtin_offsetof")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -faddrsig")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wimplicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-conversion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format-pedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-command-line-argument")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fcolor-diagnostics")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-zero-as-null-pointer-constant")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-defaulted-function-deleted")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-inconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wstrict-aliasing=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=return-type")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=address")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=sequence-point")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=date-time")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=format-security")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdlibinc")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msoft-float")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=armv8-a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfloat-abi=softfp")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mcpu=cortex-a53")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ARM_FEATURE_LPAE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBANDROIDICU_API__=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBNATIVEHELPER_API__=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-DUSE_PROFILES=0'
# Raw param [1] = '-DUSE_TRACE'
# Raw param [2] = '-UNDEBUG'
# Raw param [3] = '-DUSE_LOG=SLAndroidLogLevel_Info'
# Raw param [4] = '-fvisibility=hidden'
# Raw param [5] = ''-DLI_API=__attribute__((visibility("default")))''
# Raw param [6] = '-Wno-multichar'
# Raw param [7] = '-Wno-invalid-offsetof'
# Raw param [8] = '-Wall'
# Raw param [9] = '-Wextra'
# Raw param [10] = '-Wno-unused-parameter'
# Raw param [11] = '-Werror'
# Raw param [12] = '-DPLATFORM_SDK_VERSION=29'
# Raw param [13] = '-target armv7a-linux-androideabi'
# Raw param [14] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [15] = '-DANDROID_STRICT'
# Raw param [16] = '-fPIC'
# Raw param [17] = '-D_USING_LIBCXX'
# FLAG '-DUSE_PROFILES=0' became -DUSE_PROFILES=0
# FLAG '-DUSE_TRACE' became -DUSE_TRACE
# FLAG '-UNDEBUG' became -UNDEBUG
# FLAG '-DUSE_LOG=SLAndroidLogLevel_Info' became -DUSE_LOG=SLAndroidLogLevel_Info
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG ''-DLI_API=__attribute__((visibility("default")))'' became -DLI_API=__attribute__((visibility(\\\"default\\\")))
# FLAG '-Wno-multichar' became -Wno-multichar
# FLAG '-Wno-invalid-offsetof' became -Wno-invalid-offsetof
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Werror' became -Werror
# FLAG '-DPLATFORM_SDK_VERSION=29' became -DPLATFORM_SDK_VERSION=29
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_PROFILES=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_TRACE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_LOG=SLAndroidLogLevel_Info")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLI_API=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-multichar")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-invalid-offsetof")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DPLATFORM_SDK_VERSION=29")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_PROFILES=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_TRACE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_LOG=SLAndroidLogLevel_Info")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLI_API=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-multichar")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-invalid-offsetof")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DPLATFORM_SDK_VERSION=29")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")

# CPP FLAGS:
# Raw param [0] = '-std=gnu++17'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.DeviceGlobalCppflags}'
# Raw param [3] = '-fno-rtti'
# Raw param [4] = '${config.ArmClangCppflags}'
# FLAG '-std=gnu++17' became -std=gnu++17
# variable ${config.CommonClangGlobalCppflags} = '-Wsign-promo -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS -Wno-thread-safety-negative -Wno-gnu-include-next'
# Raw param [0] = '-Wsign-promo'
# Raw param [1] = '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS'
# Raw param [2] = '-Wno-thread-safety-negative'
# Raw param [3] = '-Wno-gnu-include-next'
# FLAG '-Wsign-promo' became -Wsign-promo
# FLAG '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS' became -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS
# FLAG '-Wno-thread-safety-negative' became -Wno-thread-safety-negative
# FLAG '-Wno-gnu-include-next' became -Wno-gnu-include-next
# variable ${config.DeviceGlobalCppflags} = '-fvisibility-inlines-hidden'
# Raw param [0] = '-fvisibility-inlines-hidden'
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.ArmClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.ArmIncludeFlags}'
# Raw param [2] = '${config.CommonNativehelperInclude}'
# variable ${config.CommonGlobalIncludes} = '-Isystem/core/include -Isystem/media/audio/include -Ihardware/libhardware/include -Ihardware/libhardware_legacy/include -Ihardware/ril/include -Iframeworks/native/include -Iframeworks/native/opengl/include -Iframeworks/av/include'
# Raw param [0] = '-Isystem/core/include'
# Raw param [1] = '-Isystem/media/audio/include'
# Raw param [2] = '-Ihardware/libhardware/include'
# Raw param [3] = '-Ihardware/libhardware_legacy/include'
# Raw param [4] = '-Ihardware/ril/include'
# Raw param [5] = '-Iframeworks/native/include'
# Raw param [6] = '-Iframeworks/native/opengl/include'
# Raw param [7] = '-Iframeworks/av/include'
# variable ${config.ArmIncludeFlags} = '-isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/kernel/uapi'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi/asm-arm'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/android/scsi'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_jni'
# Raw param [0] = '-Ilibnativehelper/include_jni'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

include_directories( 
    "${ANDROID_ROOT}/system/core/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include"
    "${ANDROID_ROOT}/hardware/ril/include"
    "${ANDROID_ROOT}/frameworks/native/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/frameworks/av/include"
    "${ANDROID_ROOT}/libnativehelper/include_jni"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/system/core/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include/**/*.h"
    "${ANDROID_ROOT}/hardware/ril/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include_jni/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})


add_executable(libwilhelm ${SOURCE_FILES})
