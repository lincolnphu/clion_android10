# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(hwui_unit_tests)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/BitmapFillrate.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/BitmapShaders.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ClippingAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/GlyphStressAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwBitmap565.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwBitmapInCompositeShader.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwLayerAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/HwLayerSizeAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/JankyScene.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ListOfFadedTextAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ListViewAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/MagnifierAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/OpPropAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/OvalAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/PartialDamageAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ReadbackFromHardwareBitmap.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/RecentsAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/RectGridAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/RoundRectClippingAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SaveLayer2Animation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SaveLayerAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShadowGrid2Animation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShadowGridAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShadowShaderAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/ShapeAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SimpleColorMatrixAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/SimpleGradientAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/TextAnimation.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/scenes/TvApp.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/LeakChecker.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestListViewSceneBase.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestContext.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestScene.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/common/TestUtils.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/main.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/CacheManagerTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/CanvasContextTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/CommonPoolTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/DamageAccumulatorTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/DeferredLayerUpdaterTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/FatVectorTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/GpuMemoryTrackerTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/GraphicsStatsServiceTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/LayerUpdateQueueTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/LinearAllocatorTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/MatrixTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/PathInterpolatorTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/RenderNodeDrawableTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/RenderNodeTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/RenderPropertiesTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/RenderThreadTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/ShaderCacheTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/SkiaBehaviorTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/SkiaDisplayListTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/SkiaPipelineTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/SkiaRenderPropertiesTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/SkiaCanvasTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/StringUtilsTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/TestUtilsTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/ThreadBaseTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/TypefaceTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/VectorDrawableTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/VectorDrawableAtlasTests.cpp
    ${ANDROID_ROOT}/frameworks/base/libs/hwui/tests/unit/WebViewFunctorManagerTests.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/skia/include/private -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/utils -Iexternal/skia/src/gpu -Iexternal/skia/src/shaders'
# Raw param [1] = '-Iframeworks/base/libs/hwui'
# Raw param [2] = ''
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [7] = '-Iexternal/googletest/googletest/include'
# Raw param [8] = '-Iframeworks/native/libs/arect/include'
# Raw param [9] = '-Iexternal/sfntly/cpp/src'
# Raw param [10] = '-Iexternal/webp/include'
# Raw param [11] = '-Iframeworks/native/opengl/libs/EGL'
# Raw param [12] = '-Iframeworks/native/opengl/include'
# Raw param [13] = '-Iexternal/googletest/googlemock/include'
# Raw param [14] = '-Iframeworks/base/libs/hwui'
# Raw param [15] = '-Iexternal/skia/include/android'
# Raw param [16] = '-Iexternal/skia/include/atlastext'
# Raw param [17] = '-Iexternal/skia/include/c'
# Raw param [18] = '-Iexternal/skia/include/codec'
# Raw param [19] = '-Iexternal/skia/include/config'
# Raw param [20] = '-Iexternal/skia/include/core'
# Raw param [21] = '-Iexternal/skia/include/docs'
# Raw param [22] = '-Iexternal/skia/include/effects'
# Raw param [23] = '-Iexternal/skia/include/encode'
# Raw param [24] = '-Iexternal/skia/include/gpu'
# Raw param [25] = '-Iexternal/skia/include/pathops'
# Raw param [26] = '-Iexternal/skia/include/ports'
# Raw param [27] = '-Iexternal/skia/include/svg'
# Raw param [28] = '-Iexternal/skia/include/utils'
# Raw param [29] = '-Iexternal/skia/include/utils/mac'
# Raw param [30] = '-Iexternal/skia/include/config/android'
# Raw param [31] = '-Iexternal/vulkan-headers/include'
# Raw param [32] = '-Iexternal/protobuf/src'
# Raw param [33] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui'
# Raw param [34] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/proto'
# Raw param [35] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include'
# Raw param [36] = '-Iexternal/icu/libandroidicu/include'
# Raw param [37] = '-D__LIBANDROIDICU_API__=1'
# Raw param [38] = '-Iexternal/dng_sdk/source'
# Raw param [39] = '-Iexternal/expat/lib'
# Raw param [40] = '-Iexternal/libjpeg-turbo'
# Raw param [41] = '-Iexternal/piex'
# Raw param [42] = '-Iexternal/libpng'
# Raw param [43] = '-Iexternal/zlib'
# Raw param [44] = '-Isystem/core/liblog/include'
# Raw param [45] = '-Iout/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen'
# Raw param [46] = '-Isystem/core/libutils/include'
# Raw param [47] = '-Isystem/core/libbacktrace/include'
# Raw param [48] = '-Isystem/core/libsystem/include'
# Raw param [49] = '-Isystem/core/libcutils/include'
# Raw param [50] = '-Isystem/core/libprocessgroup/include'
# Raw param [51] = '-Isystem/core/base/include'
# Raw param [52] = '-Iframeworks/native/libs/nativebase/include'
# Raw param [53] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [54] = '-Ihardware/libhardware/include'
# Raw param [55] = '-Isystem/media/audio/include'
# Raw param [56] = '-Isystem/bt/types'
# Raw param [57] = '-Iframeworks/native/libs/ui/include'
# Raw param [58] = '-Iframeworks/native/libs/math/include'
# Raw param [59] = '-Isystem/libhidl/base/include'
# Raw param [60] = '-Isystem/libhidl/transport/include'
# Raw param [61] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [62] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [63] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen'
# Raw param [64] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [65] = '-Isystem/libhwbinder/include'
# Raw param [66] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen'
# Raw param [67] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen'
# Raw param [68] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen'
# Raw param [69] = '-Iframeworks/native/libs/gui/include'
# Raw param [70] = '-Iout/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen'
# Raw param [71] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen'
# Raw param [72] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen'
# Raw param [73] = '-Isystem/libhidl/transport/token/1.0/utils/include'
# Raw param [74] = '-Iframeworks/native/libs/binder/include'
# Raw param [75] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [76] = '-Iframeworks/native/opengl/libs/EGL/include'
# Raw param [77] = '-Iframeworks/native/libs/nativewindow/include-private'
# Raw param [78] = '-Iexternal/harfbuzz_ng/src'
# Raw param [79] = '-Iexternal/freetype/include'
# Raw param [80] = '-Iframeworks/minikin/include'
# Raw param [81] = '-Iframeworks/base/libs/androidfw/include'
# Raw param [82] = '-Iexternal/boringssl/src/include'
# Raw param [83] = '-Isystem/core/libsync/include'
# Raw param [84] = '-Isystem/core/libmemunreachable/include'
# Raw param [85] = '-Iframeworks/av/media/libheif/include'
# Raw param [86] = '-Iexternal/libcxx/include'
# Raw param [87] = '-Iexternal/libcxxabi/include'
# Raw param [88] = '-Ibionic/libc/include'
# Raw param [89] = '-D__LIBC_API__=10000'
# Raw param [90] = '-D__LIBM_API__=10000'
# Raw param [91] = '-D__LIBDL_API__=10000'
# variable ${config.Arm64ClangCflags} = '-Werror=implicit-function-declaration'
# Raw param [0] = '-Werror=implicit-function-declaration'
# FLAG '-Werror=implicit-function-declaration' became -Werror=implicit-function-declaration
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
# variable ${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags} = '-march=armv8-a -mcpu=kryo'
# Raw param [0] = '-march=armv8-a'
# Raw param [1] = '-mcpu=kryo'
# FLAG '-march=armv8-a' became -march=armv8-a
# FLAG '-mcpu=kryo' became -mcpu=kryo
# FLAG '-D__LIBANDROIDICU_API__=1' became -D__LIBANDROIDICU_API__=1
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/external/skia/include/private -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/utils -Iexternal/skia/src/gpu -Iexternal/skia/src/shaders"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/external/sfntly/cpp/src"
    "${ANDROID_ROOT}/external/webp/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/external/googletest/googlemock/include"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui"
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
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include"
    "${ANDROID_ROOT}/external/dng_sdk/source"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
    "${ANDROID_ROOT}/external/piex"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include"
    "${ANDROID_ROOT}/system/libhidl/base/include"
    "${ANDROID_ROOT}/system/libhidl/transport/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhwbinder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private"
    "${ANDROID_ROOT}/external/harfbuzz_ng/src"
    "${ANDROID_ROOT}/external/freetype/include"
    "${ANDROID_ROOT}/frameworks/minikin/include"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/system/core/libsync/include"
    "${ANDROID_ROOT}/system/core/libmemunreachable/include"
    "${ANDROID_ROOT}/frameworks/av/media/libheif/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/skia/include/private -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/utils -Iexternal/skia/src/gpu -Iexternal/skia/src/shaders/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/external/sfntly/cpp/src/**/*.h"
    "${ANDROID_ROOT}/external/webp/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googlemock/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui/**/*.h"
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
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui_static_debug/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include/**/*.h"
    "${ANDROID_ROOT}/external/dng_sdk/source/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
    "${ANDROID_ROOT}/external/piex/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/base/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhwbinder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private/**/*.h"
    "${ANDROID_ROOT}/external/harfbuzz_ng/src/**/*.h"
    "${ANDROID_ROOT}/external/freetype/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/minikin/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsync/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libmemunreachable/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libheif/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=implicit-function-declaration")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=armv8-a")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mcpu=kryo")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBANDROIDICU_API__=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBDL_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=implicit-function-declaration")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=armv8-a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mcpu=kryo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBANDROIDICU_API__=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-DEGL_EGLEXT_PROTOTYPES'
# Raw param [1] = '-DGL_GLEXT_PROTOTYPES'
# Raw param [2] = '-DATRACE_TAG=ATRACE_TAG_VIEW'
# Raw param [3] = ''-DLOG_TAG="OpenGLRenderer"''
# Raw param [4] = '-Wall'
# Raw param [5] = '-Wno-unused-parameter'
# Raw param [6] = '-Wunreachable-code'
# Raw param [7] = '-Werror'
# Raw param [8] = '-fvisibility=hidden'
# Raw param [9] = '-Wno-missing-braces'
# Raw param [10] = '-include debug/wrap_gles.h'
# Raw param [11] = '-DHWUI_NULL_GPU'
# Raw param [12] = '-target aarch64-linux-android'
# Raw param [13] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [14] = '-DANDROID_STRICT'
# Raw param [15] = '-fPIE'
# Raw param [16] = '-DGTEST_HAS_STD_STRING'
# Raw param [17] = '-DGTEST_OS_LINUX_ANDROID'
# Raw param [18] = '-D_USING_LIBCXX'
# Raw param [19] = '-flto=thin -fsplit-lto-unit'
# Raw param [20] = '-fprofile-use=toolchain/pgo-profiles/hwui/hwui.profdata.2019-05-09'
# Raw param [21] = '-Wno-backend-plugin'
# Raw param [22] = '-fexperimental-new-pass-manager'
# FLAG '-DEGL_EGLEXT_PROTOTYPES' became -DEGL_EGLEXT_PROTOTYPES
# FLAG '-DGL_GLEXT_PROTOTYPES' became -DGL_GLEXT_PROTOTYPES
# FLAG '-DATRACE_TAG=ATRACE_TAG_VIEW' became -DATRACE_TAG=ATRACE_TAG_VIEW
# FLAG ''-DLOG_TAG="OpenGLRenderer"'' became -DLOG_TAG=\\\"OpenGLRenderer\\\"
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wunreachable-code' became -Wunreachable-code
# FLAG '-Werror' became -Werror
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-missing-braces' became -Wno-missing-braces
# FLAG '-include debug/wrap_gles.h' became -include debug/wrap_gles.h
# FLAG '-DHWUI_NULL_GPU' became -DHWUI_NULL_GPU
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-DGTEST_OS_LINUX_ANDROID' became -DGTEST_OS_LINUX_ANDROID
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-flto=thin -fsplit-lto-unit' became -flto=thin -fsplit-lto-unit
# FLAG '-fprofile-use=toolchain/pgo-profiles/hwui/hwui.profdata.2019-05-09' became -fprofile-use=toolchain/pgo-profiles/hwui/hwui.profdata.2019-05-09
# FLAG '-Wno-backend-plugin' became -Wno-backend-plugin
# FLAG '-fexperimental-new-pass-manager' became -fexperimental-new-pass-manager
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DEGL_EGLEXT_PROTOTYPES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGL_GLEXT_PROTOTYPES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOG_TAG=\\\"OpenGLRenderer\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunreachable-code")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-braces")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -include debug/wrap_gles.h")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHWUI_NULL_GPU")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -flto=thin -fsplit-lto-unit")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fprofile-use=toolchain/pgo-profiles/hwui/hwui.profdata.2019-05-09")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-backend-plugin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fexperimental-new-pass-manager")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DEGL_EGLEXT_PROTOTYPES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGL_GLEXT_PROTOTYPES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOG_TAG=\\\"OpenGLRenderer\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunreachable-code")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-braces")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -include debug/wrap_gles.h")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHWUI_NULL_GPU")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -flto=thin -fsplit-lto-unit")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fprofile-use=toolchain/pgo-profiles/hwui/hwui.profdata.2019-05-09")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-backend-plugin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexperimental-new-pass-manager")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")

# CPP FLAGS:
# Raw param [0] = '-std=gnu++2a'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.DeviceGlobalCppflags}'
# Raw param [3] = '-fno-rtti'
# Raw param [4] = '${config.Arm64ClangCppflags}'
# FLAG '-std=gnu++2a' became -std=gnu++2a
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
# variable ${config.Arm64ClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++2a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.Arm64IncludeFlags}'
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
# variable ${config.Arm64IncludeFlags} = '-isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm64 -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/kernel/uapi'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi/asm-arm64'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/android/scsi'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_jni'
# Raw param [0] = '-Ilibnativehelper/include_jni'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm64/**/*.h"
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


add_executable(hwui_unit_tests ${SOURCE_FILES})
