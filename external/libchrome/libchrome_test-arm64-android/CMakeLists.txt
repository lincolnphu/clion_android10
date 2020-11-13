# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libchrome_test)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libchrome/base/at_exit_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/atomicops_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/base64_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/base64url_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/big_endian_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/bind_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/bits_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/build_time_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_helpers_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_list_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/callback_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/cancelable_callback_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/command_line_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/cpu_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/activity_tracker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/debugger_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/debug/leak_tracker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/environment_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/dir_reader_posix_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_descriptor_watcher_posix_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_enumerator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_path_watcher_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/file_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/important_file_writer_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/files/scoped_temp_dir_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/gmock_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/guid_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_parser_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_reader_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_value_converter_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_value_serializer_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/json_writer_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/json/string_escape_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/lazy_instance_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/logging_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/md5_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/aligned_memory_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/linked_ptr_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/ref_counted_memory_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/ref_counted_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/singleton_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/memory/weak_ptr_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_loop_task_runner_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/message_loop/message_loop_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/bucket_ranges_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/field_trial_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_base_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_macros_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_snapshot_manager_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/histogram_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/metrics_hashes_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_histogram_allocator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_memory_allocator_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/persistent_sample_map_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sample_map_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sample_vector_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/sparse_histogram_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/metrics/statistics_recorder_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/observer_list_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/optional_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/pickle_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/posix/file_descriptor_shuffle_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/posix/unix_domain_socket_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_info_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/process/process_metrics_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/rand_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/scoped_clear_errno_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/scoped_generic_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/security_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sequence_checker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sequence_token_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sha1_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/stl_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/pattern_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string16_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_number_conversions_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_piece_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_split_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/string_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/stringprintf_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/sys_string_conversions_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/strings/utf_string_conversions_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sync_socket_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/atomic_flag_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/condition_variable_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/lock_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/synchronization/waitable_event_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/sys_info_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task/cancelable_task_tracker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_runner_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/scheduler_lock_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/scoped_set_task_priority_for_current_thread_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/sequence_sort_key_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/sequence_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/task_scheduler/task_traits.cc
    ${ANDROID_ROOT}/external/libchrome/base/template_util_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/metrics/histogram_tester.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/mock_entropy_provider.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/multiprocess_test.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/scoped_feature_list.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/scoped_locale.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/simple_test_tick_clock.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_file_util.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_file_util_linux.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_file_util_posix.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_io_thread.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_mock_time_task_runner.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_pending_task.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_shared_memory_util.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_simple_task_runner.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_switches.cc
    ${ANDROID_ROOT}/external/libchrome/base/test/test_timeouts.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/platform_thread_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/simple_thread_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_checker_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_collision_warner_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_id_name_manager_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_local_storage_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_local_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/threading/thread_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/pr_time_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/time/time_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/timer/hi_res_timer_manager_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/timer/mock_timer.cc
    ${ANDROID_ROOT}/external/libchrome/base/tuple_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/values_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/version_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/base/vlog_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/testing/multiprocess_func_list.cc
    ${ANDROID_ROOT}/external/libchrome/testrunner.cc
    ${ANDROID_ROOT}/external/libchrome/ui/gfx/range/range_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/crypto/secure_hash_unittest.cc
    ${ANDROID_ROOT}/external/libchrome/crypto/sha2_unittest.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/libchrome'
# Raw param [2] = ''
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [7] = '-Iexternal/googletest/googletest/include'
# Raw param [8] = '-Iexternal/googletest/googlemock/include'
# Raw param [9] = '-Isystem/core/base/include'
# Raw param [10] = '-Iout/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome'
# Raw param [11] = '-Iexternal/libevent/include'
# Raw param [12] = '-Iout/soong/.intermediates/external/libchrome/libchrome-crypto-include/gen/external/libchrome'
# Raw param [13] = '-Iexternal/libcxx/include'
# Raw param [14] = '-Iexternal/libcxxabi/include'
# Raw param [15] = '-Ibionic/libc/include'
# Raw param [16] = '-D__LIBC_API__=10000'
# Raw param [17] = '-D__LIBM_API__=10000'
# Raw param [18] = '-D__LIBDL_API__=10000'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
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
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/external/libchrome"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/googletest/googlemock/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome"
    "${ANDROID_ROOT}/external/libevent/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-crypto-include/gen/external/libchrome"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googlemock/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/external/libevent/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-crypto-include/gen/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBDL_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-deprecated-declarations'
# Raw param [3] = '-Wno-implicit-fallthrough'
# Raw param [4] = '-Wno-missing-field-initializers'
# Raw param [5] = '-Wno-unused-parameter'
# Raw param [6] = '-Wno-unused-function'
# Raw param [7] = '-Wno-unused-variable'
# Raw param [8] = '-DUNIT_TEST'
# Raw param [9] = '-DDONT_EMBED_BUILD_METADATA'
# Raw param [10] = '-Wno-error=unused-lambda-capture'
# Raw param [11] = '-target aarch64-linux-android'
# Raw param [12] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [13] = '-fPIE'
# Raw param [14] = '-DGTEST_HAS_STD_STRING'
# Raw param [15] = '-DGTEST_OS_LINUX_ANDROID'
# Raw param [16] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-DUNIT_TEST' became -DUNIT_TEST
# FLAG '-DDONT_EMBED_BUILD_METADATA' became -DDONT_EMBED_BUILD_METADATA
# FLAG '-Wno-error=unused-lambda-capture' became -Wno-error=unused-lambda-capture
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-DGTEST_OS_LINUX_ANDROID' became -DGTEST_OS_LINUX_ANDROID
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUNIT_TEST")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=unused-lambda-capture")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUNIT_TEST")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDONT_EMBED_BUILD_METADATA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=unused-lambda-capture")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX_ANDROID")
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
# Raw param [4] = '${config.Arm64ClangCppflags}'
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
# variable ${config.Arm64ClangCppflags} = ''
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


add_executable(libchrome_test ${SOURCE_FILES})
