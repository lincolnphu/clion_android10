# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libperfprofdcored)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/system/extras/perfprofd/perf_data_converter.cc
    ${ANDROID_ROOT}/system/extras/perfprofd/configreader.cc
    ${ANDROID_ROOT}/system/extras/perfprofd/cpuconfig.cc
    ${ANDROID_ROOT}/system/extras/perfprofd/perfprofdcore.cc
    ${ANDROID_ROOT}/system/extras/perfprofd/perfprofd_cmdline.cc
    ${ANDROID_ROOT}/system/extras/perfprofd/perfprofd_perf.cc
    ${ANDROID_ROOT}/system/extras/perfprofd/symbolizer.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Isystem/extras/perfprofd'
# Raw param [1] = '-Isystem/extras/perfprofd'
# Raw param [2] = ''
# Raw param [3] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Isystem/extras/perfprofd/dropbox'
# Raw param [8] = '-Isystem/extras/perfprofd'
# Raw param [9] = '-Iexternal/perf_data_converter/src/quipper'
# Raw param [10] = '-Iexternal/perf_data_converter/src/quipper/androidbase'
# Raw param [11] = '-Iexternal/boringssl/src/include'
# Raw param [12] = '-Iout/soong/.intermediates/external/perf_data_converter/src/quipper/libquipper/linux_glibc_x86_64_static/gen/proto'
# Raw param [13] = '-Iout/soong/.intermediates/system/extras/perfprofd/libperfprofd_record_proto/linux_glibc_x86_64_static/gen/proto/system/extras/perfprofd'
# Raw param [14] = '-Iout/soong/.intermediates/system/extras/perfprofd/libperfprofd_record_proto/linux_glibc_x86_64_static/gen/proto'
# Raw param [15] = '-Iout/soong/.intermediates/system/extras/perfprofd/libperfprofd_proto_config/linux_glibc_x86_64_static/gen/proto/system/extras/perfprofd'
# Raw param [16] = '-Iout/soong/.intermediates/system/extras/perfprofd/libperfprofd_proto_config/linux_glibc_x86_64_static/gen/proto'
# Raw param [17] = '-Iexternal/protobuf/src'
# Raw param [18] = '-Isystem/extras/simpleperf'
# Raw param [19] = '-Iart/libdexfile/external/include'
# Raw param [20] = '-Isystem/core/base/include'
# Raw param [21] = '-Ibuild/soong/cc/libbuildversion/include'
# Raw param [22] = '-Iart/libprofile'
# Raw param [23] = '-Iart/libdexfile'
# Raw param [24] = '-Iart/libartbase'
# Raw param [25] = '-Iexternal/lz4/lib'
# Raw param [26] = '-Iexternal/lzma/C'
# Raw param [27] = '-Isystem/core/libziparchive/include'
# Raw param [28] = '-Iart/libartpalette/include'
# Raw param [29] = '-Isystem/core/libbacktrace/include'
# Raw param [30] = '-Isystem/core/demangle/include'
# Raw param [31] = '-Isystem/core/liblog/include'
# Raw param [32] = '-Isystem/core/libnativebridge/include'
# Raw param [33] = '-Isystem/core/libnativeloader/include'
# Raw param [34] = '-Isystem/core/libunwindstack/include'
# Raw param [35] = '-Iexternal/zlib'
# Raw param [36] = '-Iart/runtime'
# Raw param [37] = '-Iout/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86_64/gen'
# Raw param [38] = '-Iart/libelffile'
# Raw param [39] = '-Iexternal/libcxx/include'
# Raw param [40] = '-Iexternal/libcxxabi/include'
# variable ${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags} = '-Wa,--noexecstack -fPIC -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8/sysroot -fstack-protector-strong -m64'
# Raw param [0] = '-Wa,--noexecstack'
# Raw param [1] = '-fPIC'
# Raw param [2] = '-U_FORTIFY_SOURCE'
# Raw param [3] = '-D_FORTIFY_SOURCE=2'
# Raw param [4] = '-fstack-protector'
# Raw param [5] = '-D__STDC_FORMAT_MACROS'
# Raw param [6] = '-D__STDC_CONSTANT_MACROS'
# Raw param [7] = '--gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8'
# Raw param [8] = '--sysroot'
# Raw param [9] = 'prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8/sysroot'
# Raw param [10] = '-fstack-protector-strong'
# Raw param [11] = '-m64'
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-fPIC' became -fPIC
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '--gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8' became --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-m64' became -m64
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
# variable ${config.HostClangGlobalCflags} = ''
# Raw param [0] = ''
include_directories( 
    "${ANDROID_ROOT}/system/extras/perfprofd"
    "${ANDROID_ROOT}/system/extras/perfprofd"
    "${ANDROID_ROOT}/system/extras/perfprofd/dropbox"
    "${ANDROID_ROOT}/system/extras/perfprofd"
    "${ANDROID_ROOT}/external/perf_data_converter/src/quipper"
    "${ANDROID_ROOT}/external/perf_data_converter/src/quipper/androidbase"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perf_data_converter/src/quipper/libquipper/linux_glibc_x86_64_static/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_record_proto/linux_glibc_x86_64_static/gen/proto/system/extras/perfprofd"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_record_proto/linux_glibc_x86_64_static/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_proto_config/linux_glibc_x86_64_static/gen/proto/system/extras/perfprofd"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_proto_config/linux_glibc_x86_64_static/gen/proto"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/system/extras/simpleperf"
    "${ANDROID_ROOT}/art/libdexfile/external/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/build/soong/cc/libbuildversion/include"
    "${ANDROID_ROOT}/art/libprofile"
    "${ANDROID_ROOT}/art/libdexfile"
    "${ANDROID_ROOT}/art/libartbase"
    "${ANDROID_ROOT}/external/lz4/lib"
    "${ANDROID_ROOT}/external/lzma/C"
    "${ANDROID_ROOT}/system/core/libziparchive/include"
    "${ANDROID_ROOT}/art/libartpalette/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/demangle/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libnativebridge/include"
    "${ANDROID_ROOT}/system/core/libnativeloader/include"
    "${ANDROID_ROOT}/system/core/libunwindstack/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/art/runtime"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86_64/gen"
    "${ANDROID_ROOT}/art/libelffile"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/system/extras/perfprofd/**/*.h"
    "${ANDROID_ROOT}/system/extras/perfprofd/**/*.h"
    "${ANDROID_ROOT}/system/extras/perfprofd/dropbox/**/*.h"
    "${ANDROID_ROOT}/system/extras/perfprofd/**/*.h"
    "${ANDROID_ROOT}/external/perf_data_converter/src/quipper/**/*.h"
    "${ANDROID_ROOT}/external/perf_data_converter/src/quipper/androidbase/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perf_data_converter/src/quipper/libquipper/linux_glibc_x86_64_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_record_proto/linux_glibc_x86_64_static/gen/proto/system/extras/perfprofd/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_record_proto/linux_glibc_x86_64_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_proto_config/linux_glibc_x86_64_static/gen/proto/system/extras/perfprofd/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/extras/perfprofd/libperfprofd_proto_config/linux_glibc_x86_64_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/system/extras/simpleperf/**/*.h"
    "${ANDROID_ROOT}/art/libdexfile/external/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/build/soong/cc/libbuildversion/include/**/*.h"
    "${ANDROID_ROOT}/art/libprofile/**/*.h"
    "${ANDROID_ROOT}/art/libdexfile/**/*.h"
    "${ANDROID_ROOT}/art/libartbase/**/*.h"
    "${ANDROID_ROOT}/external/lz4/lib/**/*.h"
    "${ANDROID_ROOT}/external/lzma/C/**/*.h"
    "${ANDROID_ROOT}/system/core/libziparchive/include/**/*.h"
    "${ANDROID_ROOT}/art/libartpalette/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/demangle/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativebridge/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativeloader/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libunwindstack/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/art/runtime/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86_64/gen/**/*.h"
    "${ANDROID_ROOT}/art/libelffile/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m64")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m64")
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
include_directories(SYSTEM "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8/sysroot/usr/include")

# CFLAGS:
# Raw param [0] = '-O0'
# Raw param [1] = '-g'
# Raw param [2] = '-UNDEBUG'
# Raw param [3] = '-Wall'
# Raw param [4] = '-Wextra'
# Raw param [5] = '-Werror'
# Raw param [6] = '-Wpedantic'
# Raw param [7] = '-Wunreachable-code-aggressive'
# Raw param [8] = '-Wno-zero-length-array'
# Raw param [9] = '-Wno-c99-extensions'
# Raw param [10] = '-Wno-language-extension-token'
# Raw param [11] = '-Wno-gnu-zero-variadic-macro-arguments'
# Raw param [12] = '-Wno-nested-anon-types'
# Raw param [13] = '-Wno-gnu-statement-expression'
# Raw param [14] = '-Wno-vla-extension'
# Raw param [15] = '-Wno-gnu-anonymous-struct'
# Raw param [16] = '-target x86_64-linux-gnu'
# Raw param [17] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [18] = '-DANDROID_STRICT'
# Raw param [19] = '-fPIC'
# Raw param [20] = '-D_USING_LIBCXX'
# FLAG '-O0' became -O0
# FLAG '-g' became -g
# FLAG '-UNDEBUG' became -UNDEBUG
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Werror' became -Werror
# FLAG '-Wpedantic' became -Wpedantic
# FLAG '-Wunreachable-code-aggressive' became -Wunreachable-code-aggressive
# FLAG '-Wno-zero-length-array' became -Wno-zero-length-array
# FLAG '-Wno-c99-extensions' became -Wno-c99-extensions
# FLAG '-Wno-language-extension-token' became -Wno-language-extension-token
# FLAG '-Wno-gnu-zero-variadic-macro-arguments' became -Wno-gnu-zero-variadic-macro-arguments
# FLAG '-Wno-nested-anon-types' became -Wno-nested-anon-types
# FLAG '-Wno-gnu-statement-expression' became -Wno-gnu-statement-expression
# FLAG '-Wno-vla-extension' became -Wno-vla-extension
# FLAG '-Wno-gnu-anonymous-struct' became -Wno-gnu-anonymous-struct
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wpedantic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunreachable-code-aggressive")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-zero-length-array")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-c99-extensions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-language-extension-token")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-gnu-zero-variadic-macro-arguments")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-nested-anon-types")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-gnu-statement-expression")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-vla-extension")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-gnu-anonymous-struct")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wpedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunreachable-code-aggressive")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-zero-length-array")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-c99-extensions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-language-extension-token")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-zero-variadic-macro-arguments")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-nested-anon-types")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-statement-expression")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-vla-extension")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-anonymous-struct")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
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
# Raw param [2] = '${config.HostGlobalCppflags}'
# Raw param [3] = '-Wno-sign-compare'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = ''
# Raw param [6] = '-nostdinc++'
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
# variable ${config.HostGlobalCppflags} = ''
# Raw param [0] = ''
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdinc++")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = ''
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
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_jni'
# Raw param [0] = '-Ilibnativehelper/include_jni'
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


add_executable(libperfprofdcored ${SOURCE_FILES})
