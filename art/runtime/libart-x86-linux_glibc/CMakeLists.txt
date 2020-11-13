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
    ${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/libart_mterp.x86/gen/mterp_x86.S
    ${ANDROID_ROOT}/art/runtime/arch/x86/context_x86.cc
    ${ANDROID_ROOT}/art/runtime/arch/x86/entrypoints_init_x86.cc
    ${ANDROID_ROOT}/art/runtime/arch/x86/jni_entrypoints_x86.S
    ${ANDROID_ROOT}/art/runtime/arch/x86/memcmp16_x86.S
    ${ANDROID_ROOT}/art/runtime/arch/x86/quick_entrypoints_x86.S
    ${ANDROID_ROOT}/art/runtime/arch/x86/thread_x86.cc
    ${ANDROID_ROOT}/art/runtime/arch/x86/fault_handler_x86.cc
    ${ANDROID_ROOT}/art/runtime/monitor_linux.cc
    ${ANDROID_ROOT}/art/runtime/runtime_linux.cc
    ${ANDROID_ROOT}/art/runtime/thread_linux.cc
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
# Raw param [1] = '-Iexternal/vixl/src -Iart/sigchainlib -Iexternal/zlib'
# Raw param [2] = '-Iart/runtime'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iart/cmdline'
# Raw param [9] = '-Iart/tools/cpp-define-generator'
# Raw param [10] = '-Iexternal/icu/icu4c/source/common'
# Raw param [11] = '-Iexternal/icu/android_icu4c/include'
# Raw param [12] = '-Ilibnativehelper/header_only_include'
# Raw param [13] = '-Ilibnativehelper/platform_include'
# Raw param [14] = '-Iart/libelffile'
# Raw param [15] = '-Iexternal/libcxx/include'
# Raw param [16] = '-Iexternal/libcxxabi/include'
# Raw param [17] = '-Iart/libartpalette/include'
# Raw param [18] = '-Isystem/core/libnativebridge/include'
# Raw param [19] = '-Isystem/core/libnativeloader/include'
# Raw param [20] = '-Isystem/core/libbacktrace/include'
# Raw param [21] = '-Isystem/core/demangle/include'
# Raw param [22] = '-Isystem/core/liblog/include'
# Raw param [23] = '-Isystem/core/base/include'
# Raw param [24] = '-Iart/libartbase'
# Raw param [25] = '-Iexternal/lz4/lib'
# Raw param [26] = '-Iexternal/lzma/C'
# Raw param [27] = '-Iart/libdexfile'
# Raw param [28] = '-Iart/libprofile'
# Raw param [29] = '-Iexternal/zlib'
# Raw param [30] = '-Iout/soong/.intermediates/art/runtime/art_operator_srcs/gen'
# Raw param [31] = '-Iout/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86/gen'
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
    "${ANDROID_ROOT}/art/runtime"
    "${ANDROID_ROOT}/external/vixl/src -Iart/sigchainlib -Iexternal/zlib"
    "${ANDROID_ROOT}/art/runtime"
    "${ANDROID_ROOT}/art/cmdline"
    "${ANDROID_ROOT}/art/tools/cpp-define-generator"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include"
    "${ANDROID_ROOT}/libnativehelper/header_only_include"
    "${ANDROID_ROOT}/libnativehelper/platform_include"
    "${ANDROID_ROOT}/art/libelffile"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/art/libartpalette/include"
    "${ANDROID_ROOT}/system/core/libnativebridge/include"
    "${ANDROID_ROOT}/system/core/libnativeloader/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/demangle/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/art/libartbase"
    "${ANDROID_ROOT}/external/lz4/lib"
    "${ANDROID_ROOT}/external/lzma/C"
    "${ANDROID_ROOT}/art/libdexfile"
    "${ANDROID_ROOT}/art/libprofile"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/art/runtime/**/*.h"
    "${ANDROID_ROOT}/external/vixl/src -Iart/sigchainlib -Iexternal/zlib/**/*.h"
    "${ANDROID_ROOT}/art/runtime/**/*.h"
    "${ANDROID_ROOT}/art/cmdline/**/*.h"
    "${ANDROID_ROOT}/art/tools/cpp-define-generator/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/header_only_include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/platform_include/**/*.h"
    "${ANDROID_ROOT}/art/libelffile/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/art/libartpalette/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativebridge/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativeloader/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/demangle/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/art/libartbase/**/*.h"
    "${ANDROID_ROOT}/external/lz4/lib/**/*.h"
    "${ANDROID_ROOT}/external/lzma/C/**/*.h"
    "${ANDROID_ROOT}/art/libdexfile/**/*.h"
    "${ANDROID_ROOT}/art/libprofile/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/runtime/art_operator_srcs/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/art/tools/cpp-define-generator/cpp-define-generator-asm-support/linux_glibc_x86/gen/**/*.h"
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
# Raw param [54] = '-target i686-linux-gnu'
# Raw param [55] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [56] = '-DANDROID_STRICT'
# Raw param [57] = '-fPIC'
# Raw param [58] = '-D_USING_LIBCXX'
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
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBUILDING_LIBART=1")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBUILDING_LIBART=1")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
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


add_executable(libart ${SOURCE_FILES})
