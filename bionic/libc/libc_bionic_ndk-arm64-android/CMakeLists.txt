# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libc_bionic_ndk)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/bionic/libc/bionic/NetdClientDispatch.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/__bionic_get_shell_path.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/__cmsg_nxthdr.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/__errno.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/__gnu_basename.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/__libc_current_sigrtmax.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/__libc_current_sigrtmin.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/abort.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/accept.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/accept4.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/access.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/arpa_inet.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/assert.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/atof.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/bionic_allocator.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/bionic_arc4random.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/bionic_futex.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/bionic_netlink.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/bionic_systrace.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/bionic_time_conversions.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/brk.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/c16rtomb.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/c32rtomb.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/chmod.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/chown.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/clearenv.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/clock.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/clock_getcpuclockid.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/clock_nanosleep.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/clone.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/connect.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/ctype.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/dirent.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/dup2.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/environ.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/error.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/eventfd_read.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/eventfd_write.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/exec.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/faccessat.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/fchmod.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/fchmodat.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/fdsan.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/ffs.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/fgetxattr.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/flistxattr.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/flockfile.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/fpclassify.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/fsetxattr.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/ftruncate.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/ftw.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/futimens.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getcwd.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getdomainname.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getentropy.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/gethostname.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getloadavg.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getpagesize.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getpgrp.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getpid.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/getpriority.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/gettid.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/get_device_api_level.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/grp_pwd.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/grp_pwd_file.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/iconv.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/icu_wrappers.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/ifaddrs.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/inotify_init.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/ioctl.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/killpg.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/langinfo.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/lchown.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/lfs64_support.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/libc_init_common.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/libgen.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/link.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/locale.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/lockf.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/lstat.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mblen.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mbrtoc16.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mbrtoc32.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/memmem.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mempcpy.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mkdir.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mkfifo.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mknod.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mntent.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/mremap.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/net_if.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/netdb.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/netinet_in.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/nl_types.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/open.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/pathconf.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/pause.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/pipe.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/poll.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/posix_fadvise.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/posix_fallocate.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/posix_madvise.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/posix_timers.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/ptrace.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/pty.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/raise.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/rand.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/readlink.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/reboot.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/recv.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/rename.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/rmdir.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/scandir.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sched_getaffinity.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sched_getcpu.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/semaphore.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/send.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/setegid.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/seteuid.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/setpgrp.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sigaction.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/signal.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sigprocmask.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/socket.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/spawn.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/stat.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/statvfs.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/stdlib_l.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/strchrnul.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/strerror.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/string_l.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/strings_l.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/strsignal.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/strtol.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/strtold.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/swab.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/symlink.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sync_file_range.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sys_epoll.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sys_msg.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sys_sem.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sys_shm.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sys_signalfd.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sys_time.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/sysinfo.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/syslog.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/system.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/system_property_api.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/system_property_set.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/tdestroy.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/termios.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/thread_private.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/timespec_get.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/tmpfile.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/umount.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/unlink.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/wait.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/wchar.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/wchar_l.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/wcstod.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/wctype.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/wcwidth.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/wmempcpy.cpp
    ${ANDROID_ROOT}/bionic/libc/bionic/icu_static.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Ibionic/libc/stdio'
# Raw param [1] = '-Ibionic/libc/async_safe/include -Iexternal/jemalloc_new/include -Ibionic/libstdc++/include'
# Raw param [2] = '-Ibionic/libc'
# Raw param [3] = ''
# Raw param [4] = '${config.Arm64ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [8] = '-Ibionic/libc/system_properties/include'
# Raw param [9] = '-Isystem/core/property_service/libpropertyinfoparser/include'
# Raw param [10] = '-Iout/soong/.intermediates/bionic/libc/generated_android_ids/gen'
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
    "${ANDROID_ROOT}/bionic/libc/stdio"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include -Iexternal/jemalloc_new/include -Ibionic/libstdc++/include"
    "${ANDROID_ROOT}/bionic/libc"
    "${ANDROID_ROOT}/bionic/libc/system_properties/include"
    "${ANDROID_ROOT}/system/core/property_service/libpropertyinfoparser/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/bionic/libc/generated_android_ids/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/stdio/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include -Iexternal/jemalloc_new/include -Ibionic/libstdc++/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/system_properties/include/**/*.h"
    "${ANDROID_ROOT}/system/core/property_service/libpropertyinfoparser/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/bionic/libc/generated_android_ids/gen/**/*.h"
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
# Raw param [0] = '-D_LIBC=1'
# Raw param [1] = '-D__BIONIC_LP32_USE_STAT64'
# Raw param [2] = '-Wall'
# Raw param [3] = '-Wextra'
# Raw param [4] = '-Wunused'
# Raw param [5] = '-Wno-char-subscripts'
# Raw param [6] = '-Wno-deprecated-declarations'
# Raw param [7] = '-Wno-gcc-compat'
# Raw param [8] = '-Wframe-larger-than=2048'
# Raw param [9] = '-Wimplicit-fallthrough'
# Raw param [10] = '-Werror=pointer-to-int-cast'
# Raw param [11] = '-Werror=int-to-pointer-cast'
# Raw param [12] = '-Werror=type-limits'
# Raw param [13] = '-Werror'
# Raw param [14] = '-Wexit-time-destructors'
# Raw param [15] = '-DTREBLE_LINKER_NAMESPACES'
# Raw param [16] = '-target aarch64-linux-android'
# Raw param [17] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [18] = '-DANDROID_STRICT'
# Raw param [19] = '-fPIC'
# FLAG '-D_LIBC=1' became -D_LIBC=1
# FLAG '-D__BIONIC_LP32_USE_STAT64' became -D__BIONIC_LP32_USE_STAT64
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Wunused' became -Wunused
# FLAG '-Wno-char-subscripts' became -Wno-char-subscripts
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-Wno-gcc-compat' became -Wno-gcc-compat
# FLAG '-Wframe-larger-than=2048' became -Wframe-larger-than=2048
# FLAG '-Wimplicit-fallthrough' became -Wimplicit-fallthrough
# FLAG '-Werror=pointer-to-int-cast' became -Werror=pointer-to-int-cast
# FLAG '-Werror=int-to-pointer-cast' became -Werror=int-to-pointer-cast
# FLAG '-Werror=type-limits' became -Werror=type-limits
# FLAG '-Werror' became -Werror
# FLAG '-Wexit-time-destructors' became -Wexit-time-destructors
# FLAG '-DTREBLE_LINKER_NAMESPACES' became -DTREBLE_LINKER_NAMESPACES
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LIBC=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__BIONIC_LP32_USE_STAT64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-char-subscripts")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-gcc-compat")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wframe-larger-than=2048")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wimplicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror=type-limits")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wexit-time-destructors")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DTREBLE_LINKER_NAMESPACES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBC=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__BIONIC_LP32_USE_STAT64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-char-subscripts")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gcc-compat")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wframe-larger-than=2048")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wimplicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=pointer-to-int-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=int-to-pointer-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror=type-limits")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wexit-time-destructors")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTREBLE_LINKER_NAMESPACES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# Raw param [2] = '-std=gnu99'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
# FLAG '-std=gnu99' became -std=gnu99
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")

# CPP FLAGS:
# Raw param [0] = '-std=gnu++17'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.DeviceGlobalCppflags}'
# Raw param [3] = '-Wold-style-cast'
# Raw param [4] = '-fno-rtti'
# Raw param [5] = '${config.Arm64ClangCppflags}'
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
# FLAG '-Wold-style-cast' became -Wold-style-cast
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.Arm64ClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wold-style-cast")
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


add_executable(libc_bionic_ndk ${SOURCE_FILES})
