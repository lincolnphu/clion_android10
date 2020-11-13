# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libtiagent)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/art/test/ti-agent/agent_common.cc
    ${ANDROID_ROOT}/art/test/ti-agent/agent_startup.cc
    ${ANDROID_ROOT}/art/test/ti-agent/jni_binder.cc
    ${ANDROID_ROOT}/art/test/ti-agent/jvmti_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/test_env.cc
    ${ANDROID_ROOT}/art/test/ti-agent/breakpoint_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/common_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/frame_pop_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/locals_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/monitors_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/redefinition_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/suspension_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/stack_trace_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/threads_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/trace_helper.cc
    ${ANDROID_ROOT}/art/test/ti-agent/exceptions_helper.cc
    ${ANDROID_ROOT}/art/test/903-hello-tagging/tagging.cc
    ${ANDROID_ROOT}/art/test/904-object-allocation/tracking.cc
    ${ANDROID_ROOT}/art/test/905-object-free/tracking_free.cc
    ${ANDROID_ROOT}/art/test/906-iterate-heap/iterate_heap.cc
    ${ANDROID_ROOT}/art/test/907-get-loaded-classes/get_loaded_classes.cc
    ${ANDROID_ROOT}/art/test/908-gc-start-finish/gc_callbacks.cc
    ${ANDROID_ROOT}/art/test/910-methods/methods.cc
    ${ANDROID_ROOT}/art/test/911-get-stack-trace/stack_trace.cc
    ${ANDROID_ROOT}/art/test/912-classes/classes.cc
    ${ANDROID_ROOT}/art/test/913-heaps/heaps.cc
    ${ANDROID_ROOT}/art/test/918-fields/fields.cc
    ${ANDROID_ROOT}/art/test/920-objects/objects.cc
    ${ANDROID_ROOT}/art/test/922-properties/properties.cc
    ${ANDROID_ROOT}/art/test/923-monitors/monitors.cc
    ${ANDROID_ROOT}/art/test/924-threads/threads.cc
    ${ANDROID_ROOT}/art/test/925-threadgroups/threadgroups.cc
    ${ANDROID_ROOT}/art/test/927-timers/timers.cc
    ${ANDROID_ROOT}/art/test/928-jni-table/jni_table.cc
    ${ANDROID_ROOT}/art/test/929-search/search.cc
    ${ANDROID_ROOT}/art/test/931-agent-thread/agent_thread.cc
    ${ANDROID_ROOT}/art/test/933-misc-events/misc_events.cc
    ${ANDROID_ROOT}/art/test/945-obsolete-native/obsolete_native.cc
    ${ANDROID_ROOT}/art/test/983-source-transform-verify/source_transform.cc
    ${ANDROID_ROOT}/art/test/984-obsolete-invoke/obsolete_invoke.cc
    ${ANDROID_ROOT}/art/test/986-native-method-bind/native_bind.cc
    ${ANDROID_ROOT}/art/test/987-agent-bind/agent_bind.cc
    ${ANDROID_ROOT}/art/test/988-method-trace/trace_fib.cc
    ${ANDROID_ROOT}/art/test/989-method-trace-throw/method_trace.cc
    ${ANDROID_ROOT}/art/test/991-field-trace-2/field_trace.cc
    ${ANDROID_ROOT}/art/test/992-source-data/source_file.cc
    ${ANDROID_ROOT}/art/test/993-breakpoints/breakpoints.cc
    ${ANDROID_ROOT}/art/test/996-breakpoint-obsolete/obsolete_breakpoints.cc
    ${ANDROID_ROOT}/art/test/1900-track-alloc/alloc.cc
    ${ANDROID_ROOT}/art/test/1901-get-bytecodes/bytecodes.cc
    ${ANDROID_ROOT}/art/test/1905-suspend-native/native_suspend.cc
    ${ANDROID_ROOT}/art/test/1908-suspend-native-resume-self/native_suspend_resume.cc
    ${ANDROID_ROOT}/art/test/1909-per-agent-tls/agent_tls.cc
    ${ANDROID_ROOT}/art/test/1914-get-local-instance/local_instance.cc
    ${ANDROID_ROOT}/art/test/1919-vminit-thread-start-timing/vminit.cc
    ${ANDROID_ROOT}/art/test/1920-suspend-native-monitor/native_suspend_monitor.cc
    ${ANDROID_ROOT}/art/test/1921-suspend-native-recursive-monitor/native_suspend_recursive_monitor.cc
    ${ANDROID_ROOT}/art/test/1922-owned-monitors-info/owned_monitors.cc
    ${ANDROID_ROOT}/art/test/1924-frame-pop-toggle/frame_pop_toggle.cc
    ${ANDROID_ROOT}/art/test/1926-missed-frame-pop/frame_pop_missed.cc
    ${ANDROID_ROOT}/art/test/1927-exception-event/exception_event.cc
    ${ANDROID_ROOT}/art/test/1930-monitor-info/monitor.cc
    ${ANDROID_ROOT}/art/test/1932-monitor-events-misc/monitor_misc.cc
    ${ANDROID_ROOT}/art/test/1934-jvmti-signal-thread/signal_threads.cc
    ${ANDROID_ROOT}/art/test/1939-proxy-frames/local_instance.cc
    ${ANDROID_ROOT}/art/test/1941-dispose-stress/dispose_stress.cc
    ${ANDROID_ROOT}/art/test/1942-suspend-raw-monitor-exit/native_suspend_monitor.cc
    ${ANDROID_ROOT}/art/test/1943-suspend-raw-monitor-wait/native_suspend_monitor.cc
    ${ANDROID_ROOT}/art/test/1946-list-descriptors/descriptors.cc
    ${ANDROID_ROOT}/art/test/1950-unprepared-transform/unprepared_transform.cc
    ${ANDROID_ROOT}/art/test/1951-monitor-enter-no-suspend/raw_monitor.cc
    ${ANDROID_ROOT}/art/test/1953-pop-frame/pop_frame.cc
    ${ANDROID_ROOT}/art/test/1957-error-ext/lasterror.cc
    ${ANDROID_ROOT}/art/test/1962-multi-thread-events/multi_thread_events.cc
    ${ANDROID_ROOT}/art/test/common/stack_inspect.cc
    ${ANDROID_ROOT}/art/test/common/runtime_state.cc
    ${ANDROID_ROOT}/art/test/ti-agent/common_load.cc
    ${ANDROID_ROOT}/art/test/901-hello-ti-agent/basics.cc
    ${ANDROID_ROOT}/art/test/909-attach-agent/attach.cc
    ${ANDROID_ROOT}/art/test/912-classes/classes_art.cc
    ${ANDROID_ROOT}/art/test/936-search-onload/search_onload.cc
    ${ANDROID_ROOT}/art/test/980-redefine-object/redef_object.cc
    ${ANDROID_ROOT}/art/test/983-source-transform-verify/source_transform_art.cc
    ${ANDROID_ROOT}/art/test/1940-ddms-ext/ddm_ext.cc
    ${ANDROID_ROOT}/art/test/1944-sudden-exit/sudden_exit.cc
    ${ANDROID_ROOT}/art/test/1959-redefine-object-instrument/fake_redef_object.cc
    ${ANDROID_ROOT}/art/test/1960-obsolete-jit-multithread-native/native_say_hi.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iexternal/vixl/src -Iart/test/ti-agent'
# Raw param [1] = '-Iart/test'
# Raw param [2] = ''
# Raw param [3] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iart/openjdkjvmti/include'
# Raw param [8] = '-Iexternal/googletest/googletest/include'
# Raw param [9] = '-Iexternal/zlib'
# Raw param [10] = '-Itools/dexter/slicer/export'
# Raw param [11] = '-Iexternal/libcxx/include'
# Raw param [12] = '-Iexternal/libcxxabi/include'
# Raw param [13] = '-Isystem/core/libbacktrace/include'
# Raw param [14] = '-Isystem/core/demangle/include'
# Raw param [15] = '-Isystem/core/base/include'
# Raw param [16] = '-Ilibnativehelper/include'
# Raw param [17] = '-Ilibnativehelper/header_only_include'
# Raw param [18] = '-Ilibnativehelper/platform_include'
# Raw param [19] = '-Iart/runtime'
# Raw param [20] = '-Iart/libdexfile'
# Raw param [21] = '-Iart/libartbase'
# Raw param [22] = '-Iexternal/lz4/lib'
# Raw param [23] = '-Iexternal/lzma/C'
# Raw param [24] = '-Iout/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86_64/gen'
# Raw param [25] = '-Iart/libprofile'
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
    "${ANDROID_ROOT}/external/vixl/src -Iart/test/ti-agent"
    "${ANDROID_ROOT}/art/test"
    "${ANDROID_ROOT}/art/openjdkjvmti/include"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/tools/dexter/slicer/export"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/demangle/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/libnativehelper/include"
    "${ANDROID_ROOT}/libnativehelper/header_only_include"
    "${ANDROID_ROOT}/libnativehelper/platform_include"
    "${ANDROID_ROOT}/art/runtime"
    "${ANDROID_ROOT}/art/libdexfile"
    "${ANDROID_ROOT}/art/libartbase"
    "${ANDROID_ROOT}/external/lz4/lib"
    "${ANDROID_ROOT}/external/lzma/C"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86_64/gen"
    "${ANDROID_ROOT}/art/libprofile"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/vixl/src -Iart/test/ti-agent/**/*.h"
    "${ANDROID_ROOT}/art/test/**/*.h"
    "${ANDROID_ROOT}/art/openjdkjvmti/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/tools/dexter/slicer/export/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/demangle/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/header_only_include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/platform_include/**/*.h"
    "${ANDROID_ROOT}/art/runtime/**/*.h"
    "${ANDROID_ROOT}/art/libdexfile/**/*.h"
    "${ANDROID_ROOT}/art/libartbase/**/*.h"
    "${ANDROID_ROOT}/external/lz4/lib/**/*.h"
    "${ANDROID_ROOT}/external/lzma/C/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86_64/gen/**/*.h"
    "${ANDROID_ROOT}/art/libprofile/**/*.h"
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
# Raw param [38] = '-Wno-frame-larger-than='
# Raw param [39] = '-fno-omit-frame-pointer'
# Raw param [40] = '-msse4.2'
# Raw param [41] = '-mpopcnt'
# Raw param [42] = '-DART_ENABLE_CODEGEN_arm'
# Raw param [43] = '-DART_ENABLE_CODEGEN_arm64'
# Raw param [44] = '-DART_ENABLE_CODEGEN_mips'
# Raw param [45] = '-DART_ENABLE_CODEGEN_mips64'
# Raw param [46] = '-DART_ENABLE_CODEGEN_x86'
# Raw param [47] = '-DART_ENABLE_CODEGEN_x86_64'
# Raw param [48] = '-Wframe-larger-than=1736'
# Raw param [49] = '-DART_FRAME_SIZE_LIMIT=1736'
# Raw param [50] = '-DART_BASE_ADDRESS=0x60000000'
# Raw param [51] = '-DART_BASE_ADDRESS_MIN_DELTA=-0x1000000'
# Raw param [52] = '-DART_BASE_ADDRESS_MAX_DELTA=0x1000000'
# Raw param [53] = '-Wmissing-noreturn'
# Raw param [54] = '-target x86_64-linux-gnu'
# Raw param [55] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [56] = '-DANDROID_STRICT'
# Raw param [57] = '-fPIC'
# Raw param [58] = '-DGTEST_HAS_STD_STRING'
# Raw param [59] = '-O0'
# Raw param [60] = '-g'
# Raw param [61] = '-DGTEST_OS_LINUX'
# Raw param [62] = '-D_USING_LIBCXX'
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
# FLAG '-Wno-frame-larger-than=' became -Wno-frame-larger-than=
# FLAG '-fno-omit-frame-pointer' became -fno-omit-frame-pointer
# FLAG '-msse4.2' became -msse4.2
# FLAG '-mpopcnt' became -mpopcnt
# FLAG '-DART_ENABLE_CODEGEN_arm' became -DART_ENABLE_CODEGEN_arm
# FLAG '-DART_ENABLE_CODEGEN_arm64' became -DART_ENABLE_CODEGEN_arm64
# FLAG '-DART_ENABLE_CODEGEN_mips' became -DART_ENABLE_CODEGEN_mips
# FLAG '-DART_ENABLE_CODEGEN_mips64' became -DART_ENABLE_CODEGEN_mips64
# FLAG '-DART_ENABLE_CODEGEN_x86' became -DART_ENABLE_CODEGEN_x86
# FLAG '-DART_ENABLE_CODEGEN_x86_64' became -DART_ENABLE_CODEGEN_x86_64
# FLAG '-Wframe-larger-than=1736' became -Wframe-larger-than=1736
# FLAG '-DART_FRAME_SIZE_LIMIT=1736' became -DART_FRAME_SIZE_LIMIT=1736
# FLAG '-DART_BASE_ADDRESS=0x60000000' became -DART_BASE_ADDRESS=0x60000000
# FLAG '-DART_BASE_ADDRESS_MIN_DELTA=-0x1000000' became -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000
# FLAG '-DART_BASE_ADDRESS_MAX_DELTA=0x1000000' became -DART_BASE_ADDRESS_MAX_DELTA=0x1000000
# FLAG '-Wmissing-noreturn' became -Wmissing-noreturn
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-O0' became -O0
# FLAG '-g' became -g
# FLAG '-DGTEST_OS_LINUX' became -DGTEST_OS_LINUX
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-frame-larger-than=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-omit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msse4.2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mpopcnt")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_arm")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_arm64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_mips")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_mips64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_x86")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_x86_64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wframe-larger-than=1736")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_FRAME_SIZE_LIMIT=1736")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS=0x60000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS_MAX_DELTA=0x1000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wmissing-noreturn")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-frame-larger-than=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-omit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msse4.2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mpopcnt")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_arm")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_arm64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_mips")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_mips64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_x86")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_x86_64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wframe-larger-than=1736")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_FRAME_SIZE_LIMIT=1736")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS=0x60000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS_MAX_DELTA=0x1000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wmissing-noreturn")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX")
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


add_executable(libtiagent ${SOURCE_FILES})
