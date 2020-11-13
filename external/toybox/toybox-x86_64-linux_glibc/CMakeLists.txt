# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(toybox)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/toybox/lib/args.c
    ${ANDROID_ROOT}/external/toybox/lib/commas.c
    ${ANDROID_ROOT}/external/toybox/lib/dirtree.c
    ${ANDROID_ROOT}/external/toybox/lib/help.c
    ${ANDROID_ROOT}/external/toybox/lib/lib.c
    ${ANDROID_ROOT}/external/toybox/lib/linestack.c
    ${ANDROID_ROOT}/external/toybox/lib/llist.c
    ${ANDROID_ROOT}/external/toybox/lib/net.c
    ${ANDROID_ROOT}/external/toybox/lib/portability.c
    ${ANDROID_ROOT}/external/toybox/lib/tty.c
    ${ANDROID_ROOT}/external/toybox/lib/xwrap.c
    ${ANDROID_ROOT}/external/toybox/main.c
    ${ANDROID_ROOT}/external/toybox/toys/android/getenforce.c
    ${ANDROID_ROOT}/external/toybox/toys/android/load_policy.c
    ${ANDROID_ROOT}/external/toybox/toys/android/log.c
    ${ANDROID_ROOT}/external/toybox/toys/android/restorecon.c
    ${ANDROID_ROOT}/external/toybox/toys/android/runcon.c
    ${ANDROID_ROOT}/external/toybox/toys/android/sendevent.c
    ${ANDROID_ROOT}/external/toybox/toys/android/setenforce.c
    ${ANDROID_ROOT}/external/toybox/toys/android/setprop.c
    ${ANDROID_ROOT}/external/toybox/toys/android/start.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/dmesg.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/hostname.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/killall.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/md5sum.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/mknod.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/mktemp.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/mount.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/pidof.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/seq.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/sync.c
    ${ANDROID_ROOT}/external/toybox/toys/lsb/umount.c
    ${ANDROID_ROOT}/external/toybox/toys/net/ifconfig.c
    ${ANDROID_ROOT}/external/toybox/toys/net/microcom.c
    ${ANDROID_ROOT}/external/toybox/toys/net/netcat.c
    ${ANDROID_ROOT}/external/toybox/toys/net/netstat.c
    ${ANDROID_ROOT}/external/toybox/toys/net/ping.c
    ${ANDROID_ROOT}/external/toybox/toys/net/rfkill.c
    ${ANDROID_ROOT}/external/toybox/toys/net/tunctl.c
    ${ANDROID_ROOT}/external/toybox/toys/other/acpi.c
    ${ANDROID_ROOT}/external/toybox/toys/other/base64.c
    ${ANDROID_ROOT}/external/toybox/toys/other/blkid.c
    ${ANDROID_ROOT}/external/toybox/toys/other/blockdev.c
    ${ANDROID_ROOT}/external/toybox/toys/other/chcon.c
    ${ANDROID_ROOT}/external/toybox/toys/other/chroot.c
    ${ANDROID_ROOT}/external/toybox/toys/other/chrt.c
    ${ANDROID_ROOT}/external/toybox/toys/other/clear.c
    ${ANDROID_ROOT}/external/toybox/toys/other/devmem.c
    ${ANDROID_ROOT}/external/toybox/toys/other/dos2unix.c
    ${ANDROID_ROOT}/external/toybox/toys/other/fallocate.c
    ${ANDROID_ROOT}/external/toybox/toys/other/flock.c
    ${ANDROID_ROOT}/external/toybox/toys/other/fmt.c
    ${ANDROID_ROOT}/external/toybox/toys/other/free.c
    ${ANDROID_ROOT}/external/toybox/toys/other/freeramdisk.c
    ${ANDROID_ROOT}/external/toybox/toys/other/fsfreeze.c
    ${ANDROID_ROOT}/external/toybox/toys/other/fsync.c
    ${ANDROID_ROOT}/external/toybox/toys/other/help.c
    ${ANDROID_ROOT}/external/toybox/toys/other/hwclock.c
    ${ANDROID_ROOT}/external/toybox/toys/other/i2ctools.c
    ${ANDROID_ROOT}/external/toybox/toys/other/inotifyd.c
    ${ANDROID_ROOT}/external/toybox/toys/other/insmod.c
    ${ANDROID_ROOT}/external/toybox/toys/other/ionice.c
    ${ANDROID_ROOT}/external/toybox/toys/other/losetup.c
    ${ANDROID_ROOT}/external/toybox/toys/other/lsattr.c
    ${ANDROID_ROOT}/external/toybox/toys/other/lsmod.c
    ${ANDROID_ROOT}/external/toybox/toys/other/lspci.c
    ${ANDROID_ROOT}/external/toybox/toys/other/lsusb.c
    ${ANDROID_ROOT}/external/toybox/toys/other/makedevs.c
    ${ANDROID_ROOT}/external/toybox/toys/other/mkswap.c
    ${ANDROID_ROOT}/external/toybox/toys/other/modinfo.c
    ${ANDROID_ROOT}/external/toybox/toys/other/mountpoint.c
    ${ANDROID_ROOT}/external/toybox/toys/other/nbd_client.c
    ${ANDROID_ROOT}/external/toybox/toys/other/nsenter.c
    ${ANDROID_ROOT}/external/toybox/toys/other/partprobe.c
    ${ANDROID_ROOT}/external/toybox/toys/other/pivot_root.c
    ${ANDROID_ROOT}/external/toybox/toys/other/pmap.c
    ${ANDROID_ROOT}/external/toybox/toys/other/printenv.c
    ${ANDROID_ROOT}/external/toybox/toys/other/pwdx.c
    ${ANDROID_ROOT}/external/toybox/toys/other/readlink.c
    ${ANDROID_ROOT}/external/toybox/toys/other/realpath.c
    ${ANDROID_ROOT}/external/toybox/toys/other/rev.c
    ${ANDROID_ROOT}/external/toybox/toys/other/rmmod.c
    ${ANDROID_ROOT}/external/toybox/toys/other/setfattr.c
    ${ANDROID_ROOT}/external/toybox/toys/other/setsid.c
    ${ANDROID_ROOT}/external/toybox/toys/other/stat.c
    ${ANDROID_ROOT}/external/toybox/toys/other/swapoff.c
    ${ANDROID_ROOT}/external/toybox/toys/other/swapon.c
    ${ANDROID_ROOT}/external/toybox/toys/other/sysctl.c
    ${ANDROID_ROOT}/external/toybox/toys/other/tac.c
    ${ANDROID_ROOT}/external/toybox/toys/other/taskset.c
    ${ANDROID_ROOT}/external/toybox/toys/other/timeout.c
    ${ANDROID_ROOT}/external/toybox/toys/other/truncate.c
    ${ANDROID_ROOT}/external/toybox/toys/other/uptime.c
    ${ANDROID_ROOT}/external/toybox/toys/other/usleep.c
    ${ANDROID_ROOT}/external/toybox/toys/other/uuidgen.c
    ${ANDROID_ROOT}/external/toybox/toys/other/vconfig.c
    ${ANDROID_ROOT}/external/toybox/toys/other/vmstat.c
    ${ANDROID_ROOT}/external/toybox/toys/other/watch.c
    ${ANDROID_ROOT}/external/toybox/toys/other/which.c
    ${ANDROID_ROOT}/external/toybox/toys/other/xxd.c
    ${ANDROID_ROOT}/external/toybox/toys/other/yes.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/bc.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/dd.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/diff.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/expr.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/getfattr.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/gzip.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/lsof.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/modprobe.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/more.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/stty.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/tar.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/tr.c
    ${ANDROID_ROOT}/external/toybox/toys/pending/traceroute.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/basename.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/cal.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/cat.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/chgrp.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/chmod.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/cksum.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/cmp.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/comm.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/cp.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/cpio.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/cut.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/date.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/df.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/dirname.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/du.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/echo.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/env.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/expand.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/false.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/file.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/find.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/getconf.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/grep.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/head.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/iconv.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/id.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/kill.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/ln.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/ls.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/mkdir.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/mkfifo.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/nice.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/nl.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/nohup.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/od.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/paste.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/patch.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/printf.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/ps.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/pwd.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/renice.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/rm.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/rmdir.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/sed.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/sleep.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/sort.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/split.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/strings.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/tail.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/tee.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/time.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/touch.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/true.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/tty.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/ulimit.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/uname.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/uniq.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/unlink.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/uudecode.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/uuencode.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/wc.c
    ${ANDROID_ROOT}/external/toybox/toys/posix/xargs.c
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/toybox'
# Raw param [2] = ''
# Raw param [3] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Isystem/core/liblog/include'
# Raw param [8] = '-Iexternal/selinux/libselinux/include'
# Raw param [9] = '-Isystem/core/libcutils/include'
# Raw param [10] = '-Isystem/core/libprocessgroup/include'
# Raw param [11] = '-Iexternal/boringssl/src/include'
# Raw param [12] = '-Iexternal/zlib'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
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
    "${ANDROID_ROOT}/external/toybox"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/selinux/libselinux/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/zlib"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/toybox/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/selinux/libselinux/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
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
# Raw param [0] = '-std=gnu11'
# Raw param [1] = '-Os'
# Raw param [2] = '-Wall'
# Raw param [3] = '-Werror'
# Raw param [4] = '-Wno-char-subscripts'
# Raw param [5] = '-Wno-deprecated-declarations'
# Raw param [6] = '-Wno-missing-field-initializers'
# Raw param [7] = '-Wno-pointer-arith'
# Raw param [8] = '-Wno-sign-compare'
# Raw param [9] = '-Wno-string-plus-int'
# Raw param [10] = '-Wno-unused-parameter'
# Raw param [11] = '-funsigned-char'
# Raw param [12] = '-ffunction-sections'
# Raw param [13] = '-fdata-sections'
# Raw param [14] = '-fno-asynchronous-unwind-tables'
# Raw param [15] = ''-DTOYBOX_VENDOR="-android"''
# Raw param [16] = '-target x86_64-linux-gnu'
# Raw param [17] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [18] = '-fPIE'
# FLAG '-std=gnu11' became -std=gnu11
# FLAG '-Os' became -Os
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-char-subscripts' became -Wno-char-subscripts
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-pointer-arith' became -Wno-pointer-arith
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-string-plus-int' became -Wno-string-plus-int
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-funsigned-char' became -funsigned-char
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-fno-asynchronous-unwind-tables' became -fno-asynchronous-unwind-tables
# FLAG ''-DTOYBOX_VENDOR="-android"'' became -DTOYBOX_VENDOR=\\\"-android\\\"
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIE' became -fPIE
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu11")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-char-subscripts")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-pointer-arith")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-string-plus-int")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funsigned-char")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-asynchronous-unwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DTOYBOX_VENDOR=\\\"-android\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-char-subscripts")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-pointer-arith")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-string-plus-int")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funsigned-char")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-asynchronous-unwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTOYBOX_VENDOR=\\\"-android\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")

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
# Raw param [3] = ''
# Raw param [4] = '-nostdinc++'
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
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
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


add_executable(toybox ${SOURCE_FILES})
