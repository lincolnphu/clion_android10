# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(net_test_stack_rfcomm)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/port_api.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/port_rfc.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/port_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_l2cap_if.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_mx_fsm.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_port_fsm.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_port_if.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_ts_frames.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/test/common/mock_btm_layer.cc
    ${ANDROID_ROOT}/system/bt/stack/test/common/mock_btsnoop_module.cc
    ${ANDROID_ROOT}/system/bt/stack/test/common/mock_btu_layer.cc
    ${ANDROID_ROOT}/system/bt/stack/test/common/mock_l2cap_layer.cc
    ${ANDROID_ROOT}/system/bt/stack/test/common/stack_test_packet_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/test/rfcomm/stack_rfcomm_test.cc
    ${ANDROID_ROOT}/system/bt/stack/test/rfcomm/stack_rfcomm_test_main.cc
    ${ANDROID_ROOT}/system/bt/stack/test/rfcomm/stack_rfcomm_test_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/test/rfcomm/stack_rfcomm_test_utils_test.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Isystem/bt/stack/include -Isystem/bt/stack/btm -Isystem/bt/stack/l2cap -Isystem/bt/stack/smp -Isystem/bt/stack/rfcomm -Isystem/bt/stack/test/common'
# Raw param [1] = '-Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Isystem/bt -Isystem/bt/internal_include -Isystem/bt/btcore/include -Isystem/bt/hci/include -Isystem/bt/utils/include'
# Raw param [2] = '-Isystem/bt/stack'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Isystem/bt/include'
# Raw param [9] = '-Isystem/bt/include/hardware/avrcp'
# Raw param [10] = '-Isystem/bt/internal_include'
# Raw param [11] = '-Iexternal/googletest/googletest/include'
# Raw param [12] = '-Isystem/core/base/include'
# Raw param [13] = '-Iout/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome'
# Raw param [14] = '-Isystem/bt/types'
# Raw param [15] = '-Iexternal/protobuf/src'
# Raw param [16] = '-Iout/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/linux_glibc_x86_static/gen/proto/frameworks/base/core/proto'
# Raw param [17] = '-Iout/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/linux_glibc_x86_static/gen/proto'
# Raw param [18] = '-Isystem/core/liblog/include'
# Raw param [19] = '-Iexternal/googletest/googlemock/include'
# Raw param [20] = '-Iout/soong/.intermediates/system/bt/proto/libbt-protos-lite/linux_glibc_x86_static/gen/proto/system/bt/proto'
# Raw param [21] = '-Iout/soong/.intermediates/system/bt/proto/libbt-protos-lite/linux_glibc_x86_static/gen/proto'
# Raw param [22] = '-Iout/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen'
# Raw param [23] = '-Isystem/core/libcutils/include'
# Raw param [24] = '-Isystem/core/libprocessgroup/include'
# Raw param [25] = '-Iexternal/boringssl/src/include'
# Raw param [26] = '-Iexternal/libcxx/include'
# Raw param [27] = '-Iexternal/libcxxabi/include'
# variable ${config.LinuxClangCflags} ${config.LinuxX86ClangCflags} = '-Wa,--noexecstack -fPIC -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8/sysroot -fstack-protector-strong -msse3 -m32 -march=prescott -D_FILE_OFFSET_BITS=64 -D_LARGEFILE_SOURCE=1'
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
# Raw param [11] = '-msse3'
# Raw param [12] = '-m32'
# Raw param [13] = '-march=prescott'
# Raw param [14] = '-D_FILE_OFFSET_BITS=64'
# Raw param [15] = '-D_LARGEFILE_SOURCE=1'
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-fPIC' became -fPIC
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '--gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8' became --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-msse3' became -msse3
# FLAG '-m32' became -m32
# FLAG '-march=prescott' became -march=prescott
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-D_LARGEFILE_SOURCE=1' became -D_LARGEFILE_SOURCE=1
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
    "${ANDROID_ROOT}/system/bt/stack/include -Isystem/bt/stack/btm -Isystem/bt/stack/l2cap -Isystem/bt/stack/smp -Isystem/bt/stack/rfcomm -Isystem/bt/stack/test/common"
    "${ANDROID_ROOT}/device/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Isystem/bt -Isystem/bt/internal_include -Isystem/bt/btcore/include -Isystem/bt/hci/include -Isystem/bt/utils/include"
    "${ANDROID_ROOT}/system/bt/stack"
    "${ANDROID_ROOT}/system/bt/include"
    "${ANDROID_ROOT}/system/bt/include/hardware/avrcp"
    "${ANDROID_ROOT}/system/bt/internal_include"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/linux_glibc_x86_static/gen/proto/frameworks/base/core/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/linux_glibc_x86_static/gen/proto"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/googletest/googlemock/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/proto/libbt-protos-lite/linux_glibc_x86_static/gen/proto/system/bt/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/proto/libbt-protos-lite/linux_glibc_x86_static/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/system/bt/stack/include -Isystem/bt/stack/btm -Isystem/bt/stack/l2cap -Isystem/bt/stack/smp -Isystem/bt/stack/rfcomm -Isystem/bt/stack/test/common/**/*.h"
    "${ANDROID_ROOT}/device/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Isystem/bt -Isystem/bt/internal_include -Isystem/bt/btcore/include -Isystem/bt/hci/include -Isystem/bt/utils/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/stack/**/*.h"
    "${ANDROID_ROOT}/system/bt/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/include/hardware/avrcp/**/*.h"
    "${ANDROID_ROOT}/system/bt/internal_include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/linux_glibc_x86_static/gen/proto/frameworks/base/core/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/linux_glibc_x86_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googlemock/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/proto/libbt-protos-lite/linux_glibc_x86_static/gen/proto/system/bt/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/bt/proto/libbt-protos-lite/linux_glibc_x86_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msse3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=prescott")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LARGEFILE_SOURCE=1")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msse3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=prescott")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LARGEFILE_SOURCE=1")
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Wextra'
# Raw param [2] = '-Werror'
# Raw param [3] = '-DHAS_BDROID_BUILDCFG'
# Raw param [4] = ''-DEXPORT_SYMBOL=__attribute__((visibility("default")))''
# Raw param [5] = '-fvisibility=hidden'
# Raw param [6] = '-Wno-gnu-variable-sized-type-not-at-end'
# Raw param [7] = '-Wno-unused-parameter'
# Raw param [8] = '-DLOG_NDEBUG=1'
# Raw param [9] = '-DHAS_BDROID_BUILDCFG'
# Raw param [10] = '-DHAS_BDROID_BUILDCFG'
# Raw param [11] = '-DBLUEDROID_DEBUG'
# Raw param [12] = '-target i686-linux-gnu'
# Raw param [13] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [14] = '-DANDROID_STRICT'
# Raw param [15] = '-fPIE'
# Raw param [16] = '-DGTEST_HAS_STD_STRING'
# Raw param [17] = '-O0'
# Raw param [18] = '-g'
# Raw param [19] = '-DGTEST_OS_LINUX'
# Raw param [20] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Werror' became -Werror
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG ''-DEXPORT_SYMBOL=__attribute__((visibility("default")))'' became -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-gnu-variable-sized-type-not-at-end' became -Wno-gnu-variable-sized-type-not-at-end
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-DLOG_NDEBUG=1' became -DLOG_NDEBUG=1
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG '-DBLUEDROID_DEBUG' became -DBLUEDROID_DEBUG
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-O0' became -O0
# FLAG '-g' became -g
# FLAG '-DGTEST_OS_LINUX' became -DGTEST_OS_LINUX
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-gnu-variable-sized-type-not-at-end")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOG_NDEBUG=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBLUEDROID_DEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-variable-sized-type-not-at-end")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOG_NDEBUG=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBLUEDROID_DEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# Raw param [2] = '-std=c99'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
# FLAG '-std=c99' became -std=c99
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99")

# CPP FLAGS:
# Raw param [0] = '-std=c++17'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.HostGlobalCppflags}'
# Raw param [3] = ''
# Raw param [4] = '-nostdinc++'
# FLAG '-std=c++17' became -std=c++17
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
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
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


add_executable(net_test_stack_rfcomm ${SOURCE_FILES})
