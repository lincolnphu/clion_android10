# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libinit)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/system/core/init/action.cpp
    ${ANDROID_ROOT}/system/core/init/action_manager.cpp
    ${ANDROID_ROOT}/system/core/init/action_parser.cpp
    ${ANDROID_ROOT}/system/core/init/boringssl_self_test.cpp
    ${ANDROID_ROOT}/system/core/init/bootchart.cpp
    ${ANDROID_ROOT}/system/core/init/builtins.cpp
    ${ANDROID_ROOT}/system/core/init/capabilities.cpp
    ${ANDROID_ROOT}/system/core/init/descriptors.cpp
    ${ANDROID_ROOT}/system/core/init/devices.cpp
    ${ANDROID_ROOT}/system/core/init/epoll.cpp
    ${ANDROID_ROOT}/system/core/init/firmware_handler.cpp
    ${ANDROID_ROOT}/system/core/init/first_stage_init.cpp
    ${ANDROID_ROOT}/system/core/init/first_stage_mount.cpp
    ${ANDROID_ROOT}/system/core/init/import_parser.cpp
    ${ANDROID_ROOT}/system/core/init/init.cpp
    ${ANDROID_ROOT}/system/core/init/keychords.cpp
    ${ANDROID_ROOT}/system/core/init/modalias_handler.cpp
    ${ANDROID_ROOT}/system/core/init/mount_handler.cpp
    ${ANDROID_ROOT}/system/core/init/mount_namespace.cpp
    ${ANDROID_ROOT}/system/core/init/parser.cpp
    ${ANDROID_ROOT}/system/core/init/persistent_properties.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto/system/core/init/persistent_properties.pb.cc
    ${ANDROID_ROOT}/system/core/init/property_service.cpp
    ${ANDROID_ROOT}/system/core/init/property_type.cpp
    ${ANDROID_ROOT}/system/core/init/reboot.cpp
    ${ANDROID_ROOT}/system/core/init/reboot_utils.cpp
    ${ANDROID_ROOT}/system/core/init/security.cpp
    ${ANDROID_ROOT}/system/core/init/selinux.cpp
    ${ANDROID_ROOT}/system/core/init/service.cpp
    ${ANDROID_ROOT}/system/core/init/sigchld_handler.cpp
    ${ANDROID_ROOT}/system/core/init/subcontext.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto/system/core/init/subcontext.pb.cc
    ${ANDROID_ROOT}/system/core/init/switch_root.cpp
    ${ANDROID_ROOT}/system/core/init/rlimit_parser.cpp
    ${ANDROID_ROOT}/system/core/init/tokenizer.cpp
    ${ANDROID_ROOT}/system/core/init/uevent_listener.cpp
    ${ANDROID_ROOT}/system/core/init/ueventd.cpp
    ${ANDROID_ROOT}/system/core/init/ueventd_parser.cpp
    ${ANDROID_ROOT}/system/core/init/util.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Isystem/core/init'
# Raw param [1] = ''
# Raw param [2] = '${config.Arm64ClangCflags}'
# Raw param [3] = '${config.CommonClangGlobalCflags}'
# Raw param [4] = '${config.DeviceClangGlobalCflags}'
# Raw param [5] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [6] = '-Iout/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto/system/core/init'
# Raw param [7] = '-Iout/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto'
# Raw param [8] = '-Isystem/core/mkbootimg/include/bootimg'
# Raw param [9] = '-Iexternal/libcap/libcap/include'
# Raw param [10] = '-Iout/soong/.intermediates/system/apex/apexd/sysprop/libcom.android.sysprop.apex/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include'
# Raw param [11] = '-Ibionic/libc/seccomp/include'
# Raw param [12] = '-Iexternal/avb'
# Raw param [13] = '-Iexternal/libcxx/include'
# Raw param [14] = '-Isystem/core/libprocessgroup/cgrouprc_format/include'
# Raw param [15] = '-Iexternal/protobuf/src'
# Raw param [16] = '-Isystem/core/property_service/libpropertyinfoserializer/include'
# Raw param [17] = '-Isystem/core/property_service/libpropertyinfoparser/include'
# Raw param [18] = '-Iexternal/libcxxabi/include'
# Raw param [19] = '-Isystem/core/libbacktrace/include'
# Raw param [20] = '-Isystem/core/demangle/include'
# Raw param [21] = '-Isystem/core/base/include'
# Raw param [22] = '-Iframeworks/native/libs/binder/include'
# Raw param [23] = '-Isystem/core/libcutils/include'
# Raw param [24] = '-Isystem/core/libutils/include'
# Raw param [25] = '-Isystem/core/liblog/include'
# Raw param [26] = '-Isystem/core/libsystem/include'
# Raw param [27] = '-Isystem/core/libprocessgroup/include'
# Raw param [28] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [29] = '-Ibootable/recovery/bootloader_message/include'
# Raw param [30] = '-Iexternal/boringssl/src/include'
# Raw param [31] = '-Isystem/extras/ext4_utils/include'
# Raw param [32] = '-Isystem/core/fs_mgr/include'
# Raw param [33] = '-Isystem/core/logwrapper/include'
# Raw param [34] = '-Isystem/core/fs_mgr/libdm/include'
# Raw param [35] = '-Isystem/core/fs_mgr/include_fstab'
# Raw param [36] = '-Isystem/core/fs_mgr/libfs_avb/include'
# Raw param [37] = '-Isystem/core/fs_mgr/liblp/include'
# Raw param [38] = '-Isystem/extras/libfscrypt/include'
# Raw param [39] = '-Isystem/gsid/include'
# Raw param [40] = '-Isystem/tools/hidl/utils/include'
# Raw param [41] = '-Isystem/core/libkeyutils/include'
# Raw param [42] = '-Isystem/core/libprocessgroup/setup/include'
# Raw param [43] = '-Iexternal/selinux/libselinux/include'
# Raw param [44] = '-Ibionic/libc/include'
# Raw param [45] = '-Ibionic/libc/system_properties/include'
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
include_directories( 
    "${ANDROID_ROOT}/system/core/init"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto/system/core/init"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto"
    "${ANDROID_ROOT}/system/core/mkbootimg/include/bootimg"
    "${ANDROID_ROOT}/external/libcap/libcap/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/apex/apexd/sysprop/libcom.android.sysprop.apex/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include"
    "${ANDROID_ROOT}/bionic/libc/seccomp/include"
    "${ANDROID_ROOT}/external/avb"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/cgrouprc_format/include"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/system/core/property_service/libpropertyinfoserializer/include"
    "${ANDROID_ROOT}/system/core/property_service/libpropertyinfoparser/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/demangle/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/bootable/recovery/bootloader_message/include"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/system/extras/ext4_utils/include"
    "${ANDROID_ROOT}/system/core/fs_mgr/include"
    "${ANDROID_ROOT}/system/core/logwrapper/include"
    "${ANDROID_ROOT}/system/core/fs_mgr/libdm/include"
    "${ANDROID_ROOT}/system/core/fs_mgr/include_fstab"
    "${ANDROID_ROOT}/system/core/fs_mgr/libfs_avb/include"
    "${ANDROID_ROOT}/system/core/fs_mgr/liblp/include"
    "${ANDROID_ROOT}/system/extras/libfscrypt/include"
    "${ANDROID_ROOT}/system/gsid/include"
    "${ANDROID_ROOT}/system/tools/hidl/utils/include"
    "${ANDROID_ROOT}/system/core/libkeyutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/setup/include"
    "${ANDROID_ROOT}/external/selinux/libselinux/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/system_properties/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/system/core/init/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto/system/core/init/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/core/init/libinit/android_arm64_armv8-a_kryo_core_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/system/core/mkbootimg/include/bootimg/**/*.h"
    "${ANDROID_ROOT}/external/libcap/libcap/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/apex/apexd/sysprop/libcom.android.sysprop.apex/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/seccomp/include/**/*.h"
    "${ANDROID_ROOT}/external/avb/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/cgrouprc_format/include/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/system/core/property_service/libpropertyinfoserializer/include/**/*.h"
    "${ANDROID_ROOT}/system/core/property_service/libpropertyinfoparser/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/demangle/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/bootable/recovery/bootloader_message/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/system/extras/ext4_utils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/fs_mgr/include/**/*.h"
    "${ANDROID_ROOT}/system/core/logwrapper/include/**/*.h"
    "${ANDROID_ROOT}/system/core/fs_mgr/libdm/include/**/*.h"
    "${ANDROID_ROOT}/system/core/fs_mgr/include_fstab/**/*.h"
    "${ANDROID_ROOT}/system/core/fs_mgr/libfs_avb/include/**/*.h"
    "${ANDROID_ROOT}/system/core/fs_mgr/liblp/include/**/*.h"
    "${ANDROID_ROOT}/system/extras/libfscrypt/include/**/*.h"
    "${ANDROID_ROOT}/system/gsid/include/**/*.h"
    "${ANDROID_ROOT}/system/tools/hidl/utils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libkeyutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/setup/include/**/*.h"
    "${ANDROID_ROOT}/external/selinux/libselinux/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/system_properties/include/**/*.h"
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

# CFLAGS:
# Raw param [0] = '-DSEPOLICY_VERSION=30'
# Raw param [1] = '-DLOG_UEVENTS=0'
# Raw param [2] = '-Wall'
# Raw param [3] = '-Wextra'
# Raw param [4] = '-Wno-unused-parameter'
# Raw param [5] = '-Werror'
# Raw param [6] = '-DALLOW_LOCAL_PROP_OVERRIDE=0'
# Raw param [7] = '-DALLOW_PERMISSIVE_SELINUX=0'
# Raw param [8] = '-DREBOOT_BOOTLOADER_ON_PANIC=0'
# Raw param [9] = '-DWORLD_WRITABLE_KMSG=0'
# Raw param [10] = '-DDUMP_ON_UMOUNT_FAILURE=0'
# Raw param [11] = '-DSHUTDOWN_ZERO_TIMEOUT=0'
# Raw param [12] = '-target aarch64-linux-android'
# Raw param [13] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [14] = '-DANDROID_STRICT'
# Raw param [15] = '-DGOOGLE_PROTOBUF_NO_RTTI'
# Raw param [16] = '-fPIC'
# Raw param [17] = '-D_USING_LIBCXX'
# Raw param [18] = '-fsanitize=signed-integer-overflow'
# Raw param [19] = '-fsanitize-trap=all'
# Raw param [20] = '-ftrap-function=abort'
# Raw param [21] = '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined'
# Raw param [22] = '-fno-sanitize=implicit-integer-sign-change'
# FLAG '-DSEPOLICY_VERSION=30' became -DSEPOLICY_VERSION=30
# FLAG '-DLOG_UEVENTS=0' became -DLOG_UEVENTS=0
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Werror' became -Werror
# FLAG '-DALLOW_LOCAL_PROP_OVERRIDE=0' became -DALLOW_LOCAL_PROP_OVERRIDE=0
# FLAG '-DALLOW_PERMISSIVE_SELINUX=0' became -DALLOW_PERMISSIVE_SELINUX=0
# FLAG '-DREBOOT_BOOTLOADER_ON_PANIC=0' became -DREBOOT_BOOTLOADER_ON_PANIC=0
# FLAG '-DWORLD_WRITABLE_KMSG=0' became -DWORLD_WRITABLE_KMSG=0
# FLAG '-DDUMP_ON_UMOUNT_FAILURE=0' became -DDUMP_ON_UMOUNT_FAILURE=0
# FLAG '-DSHUTDOWN_ZERO_TIMEOUT=0' became -DSHUTDOWN_ZERO_TIMEOUT=0
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-DGOOGLE_PROTOBUF_NO_RTTI' became -DGOOGLE_PROTOBUF_NO_RTTI
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-fsanitize=signed-integer-overflow' became -fsanitize=signed-integer-overflow
# FLAG '-fsanitize-trap=all' became -fsanitize-trap=all
# FLAG '-ftrap-function=abort' became -ftrap-function=abort
# FLAG '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined' became -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined
# FLAG '-fno-sanitize=implicit-integer-sign-change' became -fno-sanitize=implicit-integer-sign-change
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSEPOLICY_VERSION=30")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOG_UEVENTS=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DALLOW_LOCAL_PROP_OVERRIDE=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DALLOW_PERMISSIVE_SELINUX=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DREBOOT_BOOTLOADER_ON_PANIC=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DWORLD_WRITABLE_KMSG=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDUMP_ON_UMOUNT_FAILURE=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSHUTDOWN_ZERO_TIMEOUT=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize=signed-integer-overflow")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-trap=all")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ftrap-function=abort")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-sanitize=implicit-integer-sign-change")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSEPOLICY_VERSION=30")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOG_UEVENTS=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DALLOW_LOCAL_PROP_OVERRIDE=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DALLOW_PERMISSIVE_SELINUX=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DREBOOT_BOOTLOADER_ON_PANIC=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWORLD_WRITABLE_KMSG=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDUMP_ON_UMOUNT_FAILURE=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSHUTDOWN_ZERO_TIMEOUT=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=signed-integer-overflow")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-trap=all")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ftrap-function=abort")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-sanitize=implicit-integer-sign-change")

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
# Raw param [3] = '-UALLOW_LOCAL_PROP_OVERRIDE'
# Raw param [4] = '-DALLOW_LOCAL_PROP_OVERRIDE=1'
# Raw param [5] = '-UALLOW_PERMISSIVE_SELINUX'
# Raw param [6] = '-DALLOW_PERMISSIVE_SELINUX=1'
# Raw param [7] = '-UREBOOT_BOOTLOADER_ON_PANIC'
# Raw param [8] = '-DREBOOT_BOOTLOADER_ON_PANIC=1'
# Raw param [9] = '-UWORLD_WRITABLE_KMSG'
# Raw param [10] = '-DWORLD_WRITABLE_KMSG=1'
# Raw param [11] = '-UDUMP_ON_UMOUNT_FAILURE'
# Raw param [12] = '-DDUMP_ON_UMOUNT_FAILURE=1'
# Raw param [13] = '-fno-rtti'
# Raw param [14] = '${config.Arm64ClangCppflags}'
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
# FLAG '-UALLOW_LOCAL_PROP_OVERRIDE' became -UALLOW_LOCAL_PROP_OVERRIDE
# FLAG '-DALLOW_LOCAL_PROP_OVERRIDE=1' became -DALLOW_LOCAL_PROP_OVERRIDE=1
# FLAG '-UALLOW_PERMISSIVE_SELINUX' became -UALLOW_PERMISSIVE_SELINUX
# FLAG '-DALLOW_PERMISSIVE_SELINUX=1' became -DALLOW_PERMISSIVE_SELINUX=1
# FLAG '-UREBOOT_BOOTLOADER_ON_PANIC' became -UREBOOT_BOOTLOADER_ON_PANIC
# FLAG '-DREBOOT_BOOTLOADER_ON_PANIC=1' became -DREBOOT_BOOTLOADER_ON_PANIC=1
# FLAG '-UWORLD_WRITABLE_KMSG' became -UWORLD_WRITABLE_KMSG
# FLAG '-DWORLD_WRITABLE_KMSG=1' became -DWORLD_WRITABLE_KMSG=1
# FLAG '-UDUMP_ON_UMOUNT_FAILURE' became -UDUMP_ON_UMOUNT_FAILURE
# FLAG '-DDUMP_ON_UMOUNT_FAILURE=1' became -DDUMP_ON_UMOUNT_FAILURE=1
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.Arm64ClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++2a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UALLOW_LOCAL_PROP_OVERRIDE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DALLOW_LOCAL_PROP_OVERRIDE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UALLOW_PERMISSIVE_SELINUX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DALLOW_PERMISSIVE_SELINUX=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UREBOOT_BOOTLOADER_ON_PANIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DREBOOT_BOOTLOADER_ON_PANIC=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UWORLD_WRITABLE_KMSG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWORLD_WRITABLE_KMSG=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UDUMP_ON_UMOUNT_FAILURE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDUMP_ON_UMOUNT_FAILURE=1")
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


add_executable(libinit ${SOURCE_FILES})
