# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(art_dexoptanalyzer_tests)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/art/dexoptanalyzer/dexoptanalyzer_test.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Ibionic/libc/private -Iexternal/vixl/src'
# Raw param [1] = '-Iart/dexoptanalyzer'
# Raw param [2] = '${config.ArmClangThumbCflags}'
# Raw param [3] = '${config.ArmClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [7] = '-Ibionic/libc/async_safe/include'
# Raw param [8] = '-Isystem/core/liblog/include'
# Raw param [9] = '-Iart/runtime'
# Raw param [10] = '-Isystem/core/base/include'
# Raw param [11] = '-Iart/libdexfile'
# Raw param [12] = '-Iart/libartbase'
# Raw param [13] = '-Iexternal/lz4/lib'
# Raw param [14] = '-Iexternal/lzma/C'
# Raw param [15] = '-Iout/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/android_arm_armv8-a_kryo_core/gen'
# Raw param [16] = '-Iart/disassembler'
# Raw param [17] = '-Iexternal/googletest/googletest/include'
# Raw param [18] = '-Iart/libprofile'
# Raw param [19] = '-Iexternal/icu/icu4c/source/common'
# Raw param [20] = '-Iexternal/icu/android_icu4c/include'
# Raw param [21] = '-Iexternal/icu/icu4c/source/i18n'
# Raw param [22] = '-Ilibnativehelper/include'
# Raw param [23] = '-Ilibnativehelper/header_only_include'
# Raw param [24] = '-Ilibnativehelper/platform_include'
# Raw param [25] = '-D__LIBNATIVEHELPER_API__=1'
# Raw param [26] = '-Iexternal/zlib'
# Raw param [27] = '-Isystem/core/libbacktrace/include'
# Raw param [28] = '-Isystem/core/demangle/include'
# Raw param [29] = '-Iexternal/libcxx/include'
# Raw param [30] = '-Iexternal/libcxxabi/include'
# Raw param [31] = '-Ibionic/libc/include'
# Raw param [32] = '-D__LIBC_API__=10000'
# Raw param [33] = '-D__LIBM_API__=10000'
# Raw param [34] = '-D__LIBDL_API__=10000'
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
# FLAG '-D__LIBNATIVEHELPER_API__=1' became -D__LIBNATIVEHELPER_API__=1
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/bionic/libc/private -Iexternal/vixl/src"
    "${ANDROID_ROOT}/art/dexoptanalyzer"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/art/runtime"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/art/libdexfile"
    "${ANDROID_ROOT}/art/libartbase"
    "${ANDROID_ROOT}/external/lz4/lib"
    "${ANDROID_ROOT}/external/lzma/C"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/android_arm_armv8-a_kryo_core/gen"
    "${ANDROID_ROOT}/art/disassembler"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/art/libprofile"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
    "${ANDROID_ROOT}/libnativehelper/include"
    "${ANDROID_ROOT}/libnativehelper/header_only_include"
    "${ANDROID_ROOT}/libnativehelper/platform_include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/demangle/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/private -Iexternal/vixl/src/**/*.h"
    "${ANDROID_ROOT}/art/dexoptanalyzer/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/art/runtime/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/art/libdexfile/**/*.h"
    "${ANDROID_ROOT}/art/libartbase/**/*.h"
    "${ANDROID_ROOT}/external/lz4/lib/**/*.h"
    "${ANDROID_ROOT}/external/lzma/C/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/android_arm_armv8-a_kryo_core/gen/**/*.h"
    "${ANDROID_ROOT}/art/disassembler/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/art/libprofile/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/header_only_include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/platform_include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/demangle/include/**/*.h"
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBNATIVEHELPER_API__=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-fno-rtti'
# Raw param [1] = '-ggdb3'
# Raw param [2] = '-Wall'
# Raw param [3] = '-Werror'
# Raw param [4] = '-Wextra'
# Raw param [5] = '-Wstrict-aliasing'
# Raw param [6] = '-fstrict-aliasing'
# Raw param [7] = '-Wunreachable-code'
# Raw param [8] = '-Wredundant-decls'
# Raw param [9] = '-Wshadow'
# Raw param [10] = '-Wunused'
# Raw param [11] = '-fvisibility=protected'
# Raw param [12] = '-Wthread-safety'
# Raw param [13] = '-Wthread-safety-negative'
# Raw param [14] = '-Wimplicit-fallthrough'
# Raw param [15] = '-Wfloat-equal'
# Raw param [16] = '-Wint-to-void-pointer-cast'
# Raw param [17] = '-Wused-but-marked-unused'
# Raw param [18] = '-Wdeprecated'
# Raw param [19] = '-Wunreachable-code-break'
# Raw param [20] = '-Wunreachable-code-return'
# Raw param [21] = '-Wno-invalid-offsetof'
# Raw param [22] = '-Winconsistent-missing-override'
# Raw param [23] = '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS'
# Raw param [24] = '-O3'
# Raw param [25] = '-DART_DEFAULT_GC_TYPE_IS_CMS'
# Raw param [26] = '-DIMT_SIZE=43'
# Raw param [27] = '-DART_USE_READ_BARRIER=1'
# Raw param [28] = '-DART_READ_BARRIER_TYPE_IS_BAKER=1'
# Raw param [29] = '-DART_USE_GENERATIONAL_CC=1'
# Raw param [30] = '-DART_DEFAULT_COMPACT_DEX_LEVEL=fast'
# Raw param [31] = '-DART_STACK_OVERFLOW_GAP_arm=8192'
# Raw param [32] = '-DART_STACK_OVERFLOW_GAP_arm64=8192'
# Raw param [33] = '-DART_STACK_OVERFLOW_GAP_mips=16384'
# Raw param [34] = '-DART_STACK_OVERFLOW_GAP_mips64=16384'
# Raw param [35] = '-DART_STACK_OVERFLOW_GAP_x86=8192'
# Raw param [36] = '-DART_STACK_OVERFLOW_GAP_x86_64=8192'
# Raw param [37] = '-DUSE_D8_DESUGAR=1'
# Raw param [38] = '-DDYNAMIC_ANNOTATIONS_ENABLED=1'
# Raw param [39] = '-DVIXL_DEBUG'
# Raw param [40] = '-UNDEBUG'
# Raw param [41] = '-O2'
# Raw param [42] = '-Wno-frame-larger-than='
# Raw param [43] = '-Wmissing-noreturn'
# Raw param [44] = '-Wno-used-but-marked-unused'
# Raw param [45] = '-Wno-deprecated'
# Raw param [46] = '-Wno-missing-noreturn'
# Raw param [47] = '-DART_TARGET'
# Raw param [48] = '-DART_ENABLE_CODEGEN_arm'
# Raw param [49] = '-DART_ENABLE_CODEGEN_arm64'
# Raw param [50] = '-Wframe-larger-than=1736'
# Raw param [51] = '-DART_FRAME_SIZE_LIMIT=1736'
# Raw param [52] = '-DART_BASE_ADDRESS=0x70000000'
# Raw param [53] = '-DART_TARGET_ANDROID'
# Raw param [54] = '-DART_BASE_ADDRESS_MIN_DELTA=-0x1000000'
# Raw param [55] = '-DART_BASE_ADDRESS_MAX_DELTA=0x1000000'
# Raw param [56] = '-Wno-frame-larger-than='
# Raw param [57] = '-target armv7a-linux-androideabi'
# Raw param [58] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [59] = '-DANDROID_STRICT'
# Raw param [60] = '-fPIE'
# Raw param [61] = '-D_USING_LIBCXX'
# FLAG '-fno-rtti' became -fno-rtti
# FLAG '-ggdb3' became -ggdb3
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wextra' became -Wextra
# FLAG '-Wstrict-aliasing' became -Wstrict-aliasing
# FLAG '-fstrict-aliasing' became -fstrict-aliasing
# FLAG '-Wunreachable-code' became -Wunreachable-code
# FLAG '-Wredundant-decls' became -Wredundant-decls
# FLAG '-Wshadow' became -Wshadow
# FLAG '-Wunused' became -Wunused
# FLAG '-fvisibility=protected' became -fvisibility=protected
# FLAG '-Wthread-safety' became -Wthread-safety
# FLAG '-Wthread-safety-negative' became -Wthread-safety-negative
# FLAG '-Wimplicit-fallthrough' became -Wimplicit-fallthrough
# FLAG '-Wfloat-equal' became -Wfloat-equal
# FLAG '-Wint-to-void-pointer-cast' became -Wint-to-void-pointer-cast
# FLAG '-Wused-but-marked-unused' became -Wused-but-marked-unused
# FLAG '-Wdeprecated' became -Wdeprecated
# FLAG '-Wunreachable-code-break' became -Wunreachable-code-break
# FLAG '-Wunreachable-code-return' became -Wunreachable-code-return
# FLAG '-Wno-invalid-offsetof' became -Wno-invalid-offsetof
# FLAG '-Winconsistent-missing-override' became -Winconsistent-missing-override
# FLAG '-D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS' became -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS
# FLAG '-O3' became -O3
# FLAG '-DART_DEFAULT_GC_TYPE_IS_CMS' became -DART_DEFAULT_GC_TYPE_IS_CMS
# FLAG '-DIMT_SIZE=43' became -DIMT_SIZE=43
# FLAG '-DART_USE_READ_BARRIER=1' became -DART_USE_READ_BARRIER=1
# FLAG '-DART_READ_BARRIER_TYPE_IS_BAKER=1' became -DART_READ_BARRIER_TYPE_IS_BAKER=1
# FLAG '-DART_USE_GENERATIONAL_CC=1' became -DART_USE_GENERATIONAL_CC=1
# FLAG '-DART_DEFAULT_COMPACT_DEX_LEVEL=fast' became -DART_DEFAULT_COMPACT_DEX_LEVEL=fast
# FLAG '-DART_STACK_OVERFLOW_GAP_arm=8192' became -DART_STACK_OVERFLOW_GAP_arm=8192
# FLAG '-DART_STACK_OVERFLOW_GAP_arm64=8192' became -DART_STACK_OVERFLOW_GAP_arm64=8192
# FLAG '-DART_STACK_OVERFLOW_GAP_mips=16384' became -DART_STACK_OVERFLOW_GAP_mips=16384
# FLAG '-DART_STACK_OVERFLOW_GAP_mips64=16384' became -DART_STACK_OVERFLOW_GAP_mips64=16384
# FLAG '-DART_STACK_OVERFLOW_GAP_x86=8192' became -DART_STACK_OVERFLOW_GAP_x86=8192
# FLAG '-DART_STACK_OVERFLOW_GAP_x86_64=8192' became -DART_STACK_OVERFLOW_GAP_x86_64=8192
# FLAG '-DUSE_D8_DESUGAR=1' became -DUSE_D8_DESUGAR=1
# FLAG '-DDYNAMIC_ANNOTATIONS_ENABLED=1' became -DDYNAMIC_ANNOTATIONS_ENABLED=1
# FLAG '-DVIXL_DEBUG' became -DVIXL_DEBUG
# FLAG '-UNDEBUG' became -UNDEBUG
# FLAG '-O2' became -O2
# FLAG '-Wno-frame-larger-than=' became -Wno-frame-larger-than=
# FLAG '-Wmissing-noreturn' became -Wmissing-noreturn
# FLAG '-Wno-used-but-marked-unused' became -Wno-used-but-marked-unused
# FLAG '-Wno-deprecated' became -Wno-deprecated
# FLAG '-Wno-missing-noreturn' became -Wno-missing-noreturn
# FLAG '-DART_TARGET' became -DART_TARGET
# FLAG '-DART_ENABLE_CODEGEN_arm' became -DART_ENABLE_CODEGEN_arm
# FLAG '-DART_ENABLE_CODEGEN_arm64' became -DART_ENABLE_CODEGEN_arm64
# FLAG '-Wframe-larger-than=1736' became -Wframe-larger-than=1736
# FLAG '-DART_FRAME_SIZE_LIMIT=1736' became -DART_FRAME_SIZE_LIMIT=1736
# FLAG '-DART_BASE_ADDRESS=0x70000000' became -DART_BASE_ADDRESS=0x70000000
# FLAG '-DART_TARGET_ANDROID' became -DART_TARGET_ANDROID
# FLAG '-DART_BASE_ADDRESS_MIN_DELTA=-0x1000000' became -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000
# FLAG '-DART_BASE_ADDRESS_MAX_DELTA=0x1000000' became -DART_BASE_ADDRESS_MAX_DELTA=0x1000000
# FLAG '-Wno-frame-larger-than=' became -Wno-frame-larger-than=
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIE' became -fPIE
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-rtti")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ggdb3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wstrict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstrict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunreachable-code")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wredundant-decls")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wshadow")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=protected")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wthread-safety")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wthread-safety-negative")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wimplicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wfloat-equal")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wint-to-void-pointer-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wused-but-marked-unused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wdeprecated")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunreachable-code-break")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunreachable-code-return")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-invalid-offsetof")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Winconsistent-missing-override")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_DEFAULT_GC_TYPE_IS_CMS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DIMT_SIZE=43")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_USE_READ_BARRIER=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_READ_BARRIER_TYPE_IS_BAKER=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_USE_GENERATIONAL_CC=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_DEFAULT_COMPACT_DEX_LEVEL=fast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_STACK_OVERFLOW_GAP_arm=8192")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_STACK_OVERFLOW_GAP_arm64=8192")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_STACK_OVERFLOW_GAP_mips=16384")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_STACK_OVERFLOW_GAP_mips64=16384")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_STACK_OVERFLOW_GAP_x86=8192")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_STACK_OVERFLOW_GAP_x86_64=8192")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_D8_DESUGAR=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDYNAMIC_ANNOTATIONS_ENABLED=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DVIXL_DEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-frame-larger-than=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wmissing-noreturn")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-used-but-marked-unused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-noreturn")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_TARGET")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_arm")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_arm64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wframe-larger-than=1736")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_FRAME_SIZE_LIMIT=1736")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS=0x70000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_TARGET_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS_MAX_DELTA=0x1000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-frame-larger-than=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ggdb3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wstrict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstrict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunreachable-code")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wredundant-decls")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wshadow")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=protected")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wthread-safety")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wthread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wimplicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wfloat-equal")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wint-to-void-pointer-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wused-but-marked-unused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wdeprecated")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunreachable-code-break")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunreachable-code-return")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-invalid-offsetof")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Winconsistent-missing-override")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_DEFAULT_GC_TYPE_IS_CMS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DIMT_SIZE=43")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_USE_READ_BARRIER=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_READ_BARRIER_TYPE_IS_BAKER=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_USE_GENERATIONAL_CC=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_DEFAULT_COMPACT_DEX_LEVEL=fast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_STACK_OVERFLOW_GAP_arm=8192")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_STACK_OVERFLOW_GAP_arm64=8192")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_STACK_OVERFLOW_GAP_mips=16384")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_STACK_OVERFLOW_GAP_mips64=16384")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_STACK_OVERFLOW_GAP_x86=8192")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_STACK_OVERFLOW_GAP_x86_64=8192")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_D8_DESUGAR=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDYNAMIC_ANNOTATIONS_ENABLED=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DVIXL_DEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-frame-larger-than=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wmissing-noreturn")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-used-but-marked-unused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-noreturn")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_TARGET")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_arm")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_arm64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wframe-larger-than=1736")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_FRAME_SIZE_LIMIT=1736")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS=0x70000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_TARGET_ANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS_MAX_DELTA=0x1000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-frame-larger-than=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
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


add_executable(art_dexoptanalyzer_tests ${SOURCE_FILES})
