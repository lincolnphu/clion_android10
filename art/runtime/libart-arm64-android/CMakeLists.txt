# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libart)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/art/runtime/aot_class_linker.cc
    ${ANDROID_ROOT}/art/runtime/art_field.cc
    ${ANDROID_ROOT}/art/runtime/art_method.cc
    ${ANDROID_ROOT}/art/runtime/backtrace_helper.cc
    ${ANDROID_ROOT}/art/runtime/barrier.cc
    ${ANDROID_ROOT}/art/runtime/base/locks.cc
    ${ANDROID_ROOT}/art/runtime/base/mem_map_arena_pool.cc
    ${ANDROID_ROOT}/art/runtime/base/mutex.cc
    ${ANDROID_ROOT}/art/runtime/base/quasi_atomic.cc
    ${ANDROID_ROOT}/art/runtime/base/timing_logger.cc
    ${ANDROID_ROOT}/art/runtime/cha.cc
    ${ANDROID_ROOT}/art/runtime/class_linker.cc
    ${ANDROID_ROOT}/art/runtime/class_loader_context.cc
    ${ANDROID_ROOT}/art/runtime/class_root.cc
    ${ANDROID_ROOT}/art/runtime/class_table.cc
    ${ANDROID_ROOT}/art/runtime/common_throws.cc
    ${ANDROID_ROOT}/art/runtime/compiler_filter.cc
    ${ANDROID_ROOT}/art/runtime/debug_print.cc
    ${ANDROID_ROOT}/art/runtime/debugger.cc
    ${ANDROID_ROOT}/art/runtime/dex/dex_file_annotations.cc
    ${ANDROID_ROOT}/art/runtime/dex_register_location.cc
    ${ANDROID_ROOT}/art/runtime/dex_to_dex_decompiler.cc
    ${ANDROID_ROOT}/art/runtime/elf_file.cc
    ${ANDROID_ROOT}/art/runtime/exec_utils.cc
    ${ANDROID_ROOT}/art/runtime/fault_handler.cc
    ${ANDROID_ROOT}/art/runtime/gc/allocation_record.cc
    ${ANDROID_ROOT}/art/runtime/gc/allocator/dlmalloc.cc
    ${ANDROID_ROOT}/art/runtime/gc/allocator/rosalloc.cc
    ${ANDROID_ROOT}/art/runtime/gc/accounting/bitmap.cc
    ${ANDROID_ROOT}/art/runtime/gc/accounting/card_table.cc
    ${ANDROID_ROOT}/art/runtime/gc/accounting/heap_bitmap.cc
    ${ANDROID_ROOT}/art/runtime/gc/accounting/mod_union_table.cc
    ${ANDROID_ROOT}/art/runtime/gc/accounting/remembered_set.cc
    ${ANDROID_ROOT}/art/runtime/gc/accounting/space_bitmap.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/concurrent_copying.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/garbage_collector.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/immune_region.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/immune_spaces.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/mark_sweep.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/partial_mark_sweep.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/semi_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/collector/sticky_mark_sweep.cc
    ${ANDROID_ROOT}/art/runtime/gc/gc_cause.cc
    ${ANDROID_ROOT}/art/runtime/gc/heap.cc
    ${ANDROID_ROOT}/art/runtime/gc/reference_processor.cc
    ${ANDROID_ROOT}/art/runtime/gc/reference_queue.cc
    ${ANDROID_ROOT}/art/runtime/gc/scoped_gc_critical_section.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/bump_pointer_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/dlmalloc_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/image_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/large_object_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/malloc_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/region_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/rosalloc_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/space.cc
    ${ANDROID_ROOT}/art/runtime/gc/space/zygote_space.cc
    ${ANDROID_ROOT}/art/runtime/gc/task_processor.cc
    ${ANDROID_ROOT}/art/runtime/gc/verification.cc
    ${ANDROID_ROOT}/art/runtime/hidden_api.cc
    ${ANDROID_ROOT}/art/runtime/hprof/hprof.cc
    ${ANDROID_ROOT}/art/runtime/image.cc
    ${ANDROID_ROOT}/art/runtime/index_bss_mapping.cc
    ${ANDROID_ROOT}/art/runtime/indirect_reference_table.cc
    ${ANDROID_ROOT}/art/runtime/instrumentation.cc
    ${ANDROID_ROOT}/art/runtime/intern_table.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter_cache.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter_common.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter_intrinsics.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter_switch_impl0.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter_switch_impl1.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter_switch_impl2.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/interpreter_switch_impl3.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/lock_count_data.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/shadow_frame.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/unstarted_runtime.cc
    ${ANDROID_ROOT}/art/runtime/java_frame_root_info.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/jdwp_event.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/jdwp_expand_buf.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/jdwp_handler.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/jdwp_main.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/jdwp_request.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/jdwp_socket.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/object_registry.cc
    ${ANDROID_ROOT}/art/runtime/jit/debugger_interface.cc
    ${ANDROID_ROOT}/art/runtime/jit/jit.cc
    ${ANDROID_ROOT}/art/runtime/jit/jit_code_cache.cc
    ${ANDROID_ROOT}/art/runtime/jit/profiling_info.cc
    ${ANDROID_ROOT}/art/runtime/jit/profile_saver.cc
    ${ANDROID_ROOT}/art/runtime/jni/check_jni.cc
    ${ANDROID_ROOT}/art/runtime/jni/java_vm_ext.cc
    ${ANDROID_ROOT}/art/runtime/jni/jni_env_ext.cc
    ${ANDROID_ROOT}/art/runtime/jni/jni_internal.cc
    ${ANDROID_ROOT}/art/runtime/linear_alloc.cc
    ${ANDROID_ROOT}/art/runtime/managed_stack.cc
    ${ANDROID_ROOT}/art/runtime/method_handles.cc
    ${ANDROID_ROOT}/art/runtime/mirror/array.cc
    ${ANDROID_ROOT}/art/runtime/mirror/class.cc
    ${ANDROID_ROOT}/art/runtime/mirror/class_ext.cc
    ${ANDROID_ROOT}/art/runtime/mirror/dex_cache.cc
    ${ANDROID_ROOT}/art/runtime/mirror/emulated_stack_frame.cc
    ${ANDROID_ROOT}/art/runtime/mirror/executable.cc
    ${ANDROID_ROOT}/art/runtime/mirror/field.cc
    ${ANDROID_ROOT}/art/runtime/mirror/method.cc
    ${ANDROID_ROOT}/art/runtime/mirror/method_handle_impl.cc
    ${ANDROID_ROOT}/art/runtime/mirror/method_handles_lookup.cc
    ${ANDROID_ROOT}/art/runtime/mirror/method_type.cc
    ${ANDROID_ROOT}/art/runtime/mirror/object.cc
    ${ANDROID_ROOT}/art/runtime/mirror/stack_trace_element.cc
    ${ANDROID_ROOT}/art/runtime/mirror/string.cc
    ${ANDROID_ROOT}/art/runtime/mirror/throwable.cc
    ${ANDROID_ROOT}/art/runtime/mirror/var_handle.cc
    ${ANDROID_ROOT}/art/runtime/monitor.cc
    ${ANDROID_ROOT}/art/runtime/monitor_objects_stack_visitor.cc
    ${ANDROID_ROOT}/art/runtime/native_bridge_art_interface.cc
    ${ANDROID_ROOT}/art/runtime/native_stack_dump.cc
    ${ANDROID_ROOT}/art/runtime/native/dalvik_system_DexFile.cc
    ${ANDROID_ROOT}/art/runtime/native/dalvik_system_VMDebug.cc
    ${ANDROID_ROOT}/art/runtime/native/dalvik_system_VMRuntime.cc
    ${ANDROID_ROOT}/art/runtime/native/dalvik_system_VMStack.cc
    ${ANDROID_ROOT}/art/runtime/native/dalvik_system_ZygoteHooks.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_Class.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_Object.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_String.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_StringFactory.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_System.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_Thread.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_Throwable.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_VMClassLoader.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_invoke_MethodHandleImpl.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_ref_FinalizerReference.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_ref_Reference.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_reflect_Array.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_reflect_Constructor.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_reflect_Executable.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_reflect_Field.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_reflect_Method.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_reflect_Parameter.cc
    ${ANDROID_ROOT}/art/runtime/native/java_lang_reflect_Proxy.cc
    ${ANDROID_ROOT}/art/runtime/native/java_util_concurrent_atomic_AtomicLong.cc
    ${ANDROID_ROOT}/art/runtime/native/libcore_util_CharsetUtils.cc
    ${ANDROID_ROOT}/art/runtime/native/org_apache_harmony_dalvik_ddmc_DdmServer.cc
    ${ANDROID_ROOT}/art/runtime/native/org_apache_harmony_dalvik_ddmc_DdmVmInternal.cc
    ${ANDROID_ROOT}/art/runtime/native/sun_misc_Unsafe.cc
    ${ANDROID_ROOT}/art/runtime/non_debuggable_classes.cc
    ${ANDROID_ROOT}/art/runtime/oat.cc
    ${ANDROID_ROOT}/art/runtime/oat_file.cc
    ${ANDROID_ROOT}/art/runtime/oat_file_assistant.cc
    ${ANDROID_ROOT}/art/runtime/oat_file_manager.cc
    ${ANDROID_ROOT}/art/runtime/oat_quick_method_header.cc
    ${ANDROID_ROOT}/art/runtime/object_lock.cc
    ${ANDROID_ROOT}/art/runtime/offsets.cc
    ${ANDROID_ROOT}/art/runtime/parsed_options.cc
    ${ANDROID_ROOT}/art/runtime/plugin.cc
    ${ANDROID_ROOT}/art/runtime/quick_exception_handler.cc
    ${ANDROID_ROOT}/art/runtime/read_barrier.cc
    ${ANDROID_ROOT}/art/runtime/reference_table.cc
    ${ANDROID_ROOT}/art/runtime/reflection.cc
    ${ANDROID_ROOT}/art/runtime/runtime.cc
    ${ANDROID_ROOT}/art/runtime/runtime_callbacks.cc
    ${ANDROID_ROOT}/art/runtime/runtime_common.cc
    ${ANDROID_ROOT}/art/runtime/runtime_intrinsics.cc
    ${ANDROID_ROOT}/art/runtime/runtime_options.cc
    ${ANDROID_ROOT}/art/runtime/scoped_thread_state_change.cc
    ${ANDROID_ROOT}/art/runtime/signal_catcher.cc
    ${ANDROID_ROOT}/art/runtime/stack.cc
    ${ANDROID_ROOT}/art/runtime/stack_map.cc
    ${ANDROID_ROOT}/art/runtime/thread.cc
    ${ANDROID_ROOT}/art/runtime/thread_list.cc
    ${ANDROID_ROOT}/art/runtime/thread_pool.cc
    ${ANDROID_ROOT}/art/runtime/ti/agent.cc
    ${ANDROID_ROOT}/art/runtime/trace.cc
    ${ANDROID_ROOT}/art/runtime/transaction.cc
    ${ANDROID_ROOT}/art/runtime/var_handles.cc
    ${ANDROID_ROOT}/art/runtime/vdex_file.cc
    ${ANDROID_ROOT}/art/runtime/verifier/class_verifier.cc
    ${ANDROID_ROOT}/art/runtime/verifier/instruction_flags.cc
    ${ANDROID_ROOT}/art/runtime/verifier/method_verifier.cc
    ${ANDROID_ROOT}/art/runtime/verifier/reg_type.cc
    ${ANDROID_ROOT}/art/runtime/verifier/reg_type_cache.cc
    ${ANDROID_ROOT}/art/runtime/verifier/register_line.cc
    ${ANDROID_ROOT}/art/runtime/verifier/verifier_deps.cc
    ${ANDROID_ROOT}/art/runtime/verify_object.cc
    ${ANDROID_ROOT}/art/runtime/well_known_classes.cc
    ${ANDROID_ROOT}/art/runtime/arch/context.cc
    ${ANDROID_ROOT}/art/runtime/arch/instruction_set_features.cc
    ${ANDROID_ROOT}/art/runtime/arch/memcmp16.cc
    ${ANDROID_ROOT}/art/runtime/arch/arm/instruction_set_features_arm.cc
    ${ANDROID_ROOT}/art/runtime/arch/arm/registers_arm.cc
    ${ANDROID_ROOT}/art/runtime/arch/arm64/instruction_set_features_arm64.cc
    ${ANDROID_ROOT}/art/runtime/arch/arm64/registers_arm64.cc
    ${ANDROID_ROOT}/art/runtime/arch/mips/instruction_set_features_mips.cc
    ${ANDROID_ROOT}/art/runtime/arch/mips/registers_mips.cc
    ${ANDROID_ROOT}/art/runtime/arch/mips64/instruction_set_features_mips64.cc
    ${ANDROID_ROOT}/art/runtime/arch/mips64/registers_mips64.cc
    ${ANDROID_ROOT}/art/runtime/arch/x86/instruction_set_features_x86.cc
    ${ANDROID_ROOT}/art/runtime/arch/x86/registers_x86.cc
    ${ANDROID_ROOT}/art/runtime/arch/x86_64/registers_x86_64.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/entrypoint_utils.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/jni/jni_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/math_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_alloc_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_cast_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_deoptimization_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_dexcache_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_entrypoints_enum.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_field_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_fillarray_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_jni_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_lock_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_math_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_thread_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_throw_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/entrypoints/quick/quick_trampoline_entrypoints.cc
    ${ANDROID_ROOT}/art/runtime/interpreter/mterp/mterp.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/libart_mterp.arm64/gen/mterp_arm64.S
    ${ANDROID_ROOT}/art/runtime/arch/arm64/context_arm64.cc
    ${ANDROID_ROOT}/art/runtime/arch/arm64/entrypoints_init_arm64.cc
    ${ANDROID_ROOT}/art/runtime/arch/arm64/jni_entrypoints_arm64.S
    ${ANDROID_ROOT}/art/runtime/arch/arm64/memcmp16_arm64.S
    ${ANDROID_ROOT}/art/runtime/arch/arm64/quick_entrypoints_arm64.S
    ${ANDROID_ROOT}/art/runtime/arch/arm64/thread_arm64.cc
    ${ANDROID_ROOT}/art/runtime/monitor_pool.cc
    ${ANDROID_ROOT}/art/runtime/arch/arm64/fault_handler_arm64.cc
    ${ANDROID_ROOT}/art/runtime/jdwp/jdwp_adb.cc
    ${ANDROID_ROOT}/art/runtime/monitor_android.cc
    ${ANDROID_ROOT}/art/runtime/runtime_android.cc
    ${ANDROID_ROOT}/art/runtime/thread_android.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/base/callee_save_type.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/base/locks.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/class_loader_context.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/class_status.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/debugger.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc_root.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/allocator_type.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/allocator/rosalloc.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/collector_type.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/collector/gc_type.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/heap.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/space/region_space.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/space/space.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/gc/weak_root_state.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/image.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/instrumentation.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/indirect_reference_table.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/jdwp_provider.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/jdwp/jdwp.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/jdwp/jdwp_constants.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/lock_word.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/oat.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/object_callbacks.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/process_state.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/stack.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/suspend_reason.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/thread.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/thread_state.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/ti/agent.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/trace.operator_out.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/art/runtime/verifier/verifier_enums.operator_out.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iart/runtime'
# Raw param [1] = '-Ibionic/libc/private -Iexternal/vixl/src -Iart/sigchainlib -Iexternal/zlib'
# Raw param [2] = '-Iart/runtime'
# Raw param [3] = ''
# Raw param [4] = '${config.Arm64ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [8] = '-Iart/cmdline'
# Raw param [9] = '-Iart/tools/cpp-define-generator'
# Raw param [10] = '-Iexternal/icu/icu4c/source/common'
# Raw param [11] = '-Iexternal/icu/android_icu4c/include'
# Raw param [12] = '-Ilibnativehelper/header_only_include'
# Raw param [13] = '-Ilibnativehelper/platform_include'
# Raw param [14] = '-Iexternal/zlib'
# Raw param [15] = '-Iart/libelffile'
# Raw param [16] = '-Ibionic/libc/async_safe/include'
# Raw param [17] = '-Isystem/core/liblog/include'
# Raw param [18] = '-Iexternal/libcxx/include'
# Raw param [19] = '-Iexternal/libcxxabi/include'
# Raw param [20] = '-Iart/libartpalette/include'
# Raw param [21] = '-Isystem/core/libnativebridge/include'
# Raw param [22] = '-D__LIBNATIVEBRIDGE_API__=1'
# Raw param [23] = '-Isystem/core/libnativeloader/include'
# Raw param [24] = '-D__LIBNATIVELOADER_API__=1'
# Raw param [25] = '-Isystem/core/libbacktrace/include'
# Raw param [26] = '-Isystem/core/demangle/include'
# Raw param [27] = '-Isystem/core/base/include'
# Raw param [28] = '-Iart/libartbase'
# Raw param [29] = '-Iexternal/lz4/lib'
# Raw param [30] = '-Iexternal/lzma/C'
# Raw param [31] = '-Iart/libdexfile'
# Raw param [32] = '-Iart/libprofile'
# Raw param [33] = '-Ibionic/libc/include'
# Raw param [34] = '-D__LIBC_API__=10000'
# Raw param [35] = '-D__LIBM_API__=10000'
# Raw param [36] = '-D__LIBDL_API__=10000'
# Raw param [37] = '-Iout/soong/.intermediates/art/runtime/art_operator_srcs/gen'
# Raw param [38] = '-Iout/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/android_arm64_armv8-a_kryo_core/gen'
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
# FLAG '-D__LIBNATIVEBRIDGE_API__=1' became -D__LIBNATIVEBRIDGE_API__=1
# FLAG '-D__LIBNATIVELOADER_API__=1' became -D__LIBNATIVELOADER_API__=1
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/art/runtime"
    "${ANDROID_ROOT}/bionic/libc/private -Iexternal/vixl/src -Iart/sigchainlib -Iexternal/zlib"
    "${ANDROID_ROOT}/art/runtime"
    "${ANDROID_ROOT}/art/cmdline"
    "${ANDROID_ROOT}/art/tools/cpp-define-generator"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include"
    "${ANDROID_ROOT}/libnativehelper/header_only_include"
    "${ANDROID_ROOT}/libnativehelper/platform_include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/art/libelffile"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/art/libartpalette/include"
    "${ANDROID_ROOT}/system/core/libnativebridge/include"
    "${ANDROID_ROOT}/system/core/libnativeloader/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/demangle/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/art/libartbase"
    "${ANDROID_ROOT}/external/lz4/lib"
    "${ANDROID_ROOT}/external/lzma/C"
    "${ANDROID_ROOT}/art/libdexfile"
    "${ANDROID_ROOT}/art/libprofile"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/android_arm64_armv8-a_kryo_core/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/art/runtime/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/private -Iexternal/vixl/src -Iart/sigchainlib -Iexternal/zlib/**/*.h"
    "${ANDROID_ROOT}/art/runtime/**/*.h"
    "${ANDROID_ROOT}/art/cmdline/**/*.h"
    "${ANDROID_ROOT}/art/tools/cpp-define-generator/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/header_only_include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/platform_include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/art/libelffile/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/art/libartpalette/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativebridge/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativeloader/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/demangle/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/art/libartbase/**/*.h"
    "${ANDROID_ROOT}/external/lz4/lib/**/*.h"
    "${ANDROID_ROOT}/external/lzma/C/**/*.h"
    "${ANDROID_ROOT}/art/libdexfile/**/*.h"
    "${ANDROID_ROOT}/art/libprofile/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/android_arm64_armv8-a_kryo_core/gen/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBNATIVEBRIDGE_API__=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBNATIVELOADER_API__=1")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBNATIVEBRIDGE_API__=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBNATIVELOADER_API__=1")
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
# Raw param [38] = '-DBUILDING_LIBART=1'
# Raw param [39] = '-Wmissing-noreturn'
# Raw param [40] = '-DART_TARGET'
# Raw param [41] = '-DART_ENABLE_CODEGEN_arm'
# Raw param [42] = '-DART_ENABLE_CODEGEN_arm64'
# Raw param [43] = '-Wframe-larger-than=1736'
# Raw param [44] = '-DART_FRAME_SIZE_LIMIT=1736'
# Raw param [45] = '-DART_BASE_ADDRESS=0x70000000'
# Raw param [46] = '-DART_TARGET_ANDROID'
# Raw param [47] = '-DART_BASE_ADDRESS_MIN_DELTA=-0x1000000'
# Raw param [48] = '-DART_BASE_ADDRESS_MAX_DELTA=0x1000000'
# Raw param [49] = '-DANDROID_LINK_SHARED_ICU4C'
# Raw param [50] = '-target aarch64-linux-android'
# Raw param [51] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [52] = '-DANDROID_STRICT'
# Raw param [53] = '-fPIC'
# Raw param [54] = '-D_USING_LIBCXX'
# Raw param [55] = '-flto=thin -fsplit-lto-unit'
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
# FLAG '-DBUILDING_LIBART=1' became -DBUILDING_LIBART=1
# FLAG '-Wmissing-noreturn' became -Wmissing-noreturn
# FLAG '-DART_TARGET' became -DART_TARGET
# FLAG '-DART_ENABLE_CODEGEN_arm' became -DART_ENABLE_CODEGEN_arm
# FLAG '-DART_ENABLE_CODEGEN_arm64' became -DART_ENABLE_CODEGEN_arm64
# FLAG '-Wframe-larger-than=1736' became -Wframe-larger-than=1736
# FLAG '-DART_FRAME_SIZE_LIMIT=1736' became -DART_FRAME_SIZE_LIMIT=1736
# FLAG '-DART_BASE_ADDRESS=0x70000000' became -DART_BASE_ADDRESS=0x70000000
# FLAG '-DART_TARGET_ANDROID' became -DART_TARGET_ANDROID
# FLAG '-DART_BASE_ADDRESS_MIN_DELTA=-0x1000000' became -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000
# FLAG '-DART_BASE_ADDRESS_MAX_DELTA=0x1000000' became -DART_BASE_ADDRESS_MAX_DELTA=0x1000000
# FLAG '-DANDROID_LINK_SHARED_ICU4C' became -DANDROID_LINK_SHARED_ICU4C
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-flto=thin -fsplit-lto-unit' became -flto=thin -fsplit-lto-unit
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBUILDING_LIBART=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wmissing-noreturn")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_TARGET")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_arm")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_ENABLE_CODEGEN_arm64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wframe-larger-than=1736")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_FRAME_SIZE_LIMIT=1736")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS=0x70000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_TARGET_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DART_BASE_ADDRESS_MAX_DELTA=0x1000000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_LINK_SHARED_ICU4C")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -flto=thin -fsplit-lto-unit")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBUILDING_LIBART=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wmissing-noreturn")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_TARGET")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_arm")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_ENABLE_CODEGEN_arm64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wframe-larger-than=1736")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_FRAME_SIZE_LIMIT=1736")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS=0x70000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_TARGET_ANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS_MIN_DELTA=-0x1000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DART_BASE_ADDRESS_MAX_DELTA=0x1000000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_LINK_SHARED_ICU4C")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -flto=thin -fsplit-lto-unit")

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


add_executable(libart ${SOURCE_FILES})
