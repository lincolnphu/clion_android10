# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(aprotoc)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/any.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/arena.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/arenastring.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/descriptor.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/descriptor.pb.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/descriptor_database.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/dynamic_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/extension_set.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/extension_set_heavy.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/generated_message_reflection.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/generated_message_util.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/message_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/reflection_ops.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/repeated_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/service.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/text_format.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/unknown_field_set.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/wire_format.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/wire_format_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/code_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/command_line_interface.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_service.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/cpp/cpp_string_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_doc_comment.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_field_base.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_reflection_class.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_repeated_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_repeated_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_repeated_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_source_generator_base.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/csharp/csharp_wrapper_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/importer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_context.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_doc_comment.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_enum_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_extension_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_generator_factory.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_lazy_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_lazy_message_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_map_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_builder.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_builder_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_message_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_name_resolver.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_primitive_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_service.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_shared_code_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_string_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/java/java_string_field_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javamicro/javamicro_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/javanano/javanano_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/js/js_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/main.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_enum.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_enum_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_extension.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_file.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_helpers.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_map_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_message.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_message_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_oneof.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/objectivec/objectivec_primitive_field.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/parser.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/plugin.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/plugin.pb.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/python/python_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/ruby/ruby_generator.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/subprocess.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/compiler/zip_writer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/coded_stream.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/gzip_stream.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/printer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/strtod.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/tokenizer.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/zero_copy_stream.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/zero_copy_stream_impl.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/io/zero_copy_stream_impl_lite.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/atomicops_internals_x86_gcc.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/atomicops_internals_x86_msvc.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/common.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/int128.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/once.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/status.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/stringpiece.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/structurally_valid.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/strutil.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/substitute.cc
    ${ANDROID_ROOT}/external/protobuf/src/google/protobuf/stubs/stringprintf.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/protobuf/android -Iexternal/protobuf/src'
# Raw param [2] = '-Iexternal/protobuf'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/zlib'
# Raw param [9] = '-Iexternal/libcxx/include'
# Raw param [10] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/protobuf/android -Iexternal/protobuf/src"
    "${ANDROID_ROOT}/external/protobuf"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/protobuf/android -Iexternal/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Wno-error=format'
# Raw param [2] = '-Wno-error=format-extra-args'
# Raw param [3] = '-Wno-error=ignored-qualifiers'
# Raw param [4] = '-Wno-error=sign-promo'
# Raw param [5] = '-Wno-unused-function'
# Raw param [6] = '-Wno-sign-compare'
# Raw param [7] = '-Wno-unused-parameter'
# Raw param [8] = '-Wno-sign-promo'
# Raw param [9] = '-Wno-error=return-type'
# Raw param [10] = '-DHAVE_ZLIB=1'
# Raw param [11] = '-Werror'
# Raw param [12] = '-Wno-unused-const-variable'
# Raw param [13] = '-Wno-error=user-defined-warnings'
# Raw param [14] = '-target x86_64-linux-gnu'
# Raw param [15] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [16] = '-fPIE'
# Raw param [17] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Wno-error=format' became -Wno-error=format
# FLAG '-Wno-error=format-extra-args' became -Wno-error=format-extra-args
# FLAG '-Wno-error=ignored-qualifiers' became -Wno-error=ignored-qualifiers
# FLAG '-Wno-error=sign-promo' became -Wno-error=sign-promo
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-Wno-error=return-type' became -Wno-error=return-type
# FLAG '-DHAVE_ZLIB=1' became -DHAVE_ZLIB=1
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-const-variable' became -Wno-unused-const-variable
# FLAG '-Wno-error=user-defined-warnings' became -Wno-error=user-defined-warnings
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIE' became -fPIE
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=format")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=format-extra-args")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=ignored-qualifiers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=sign-promo")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-promo")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=return-type")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAVE_ZLIB=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-const-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=user-defined-warnings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=format")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=format-extra-args")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=ignored-qualifiers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=return-type")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAVE_ZLIB=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-const-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=user-defined-warnings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
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


add_executable(aprotoc ${SOURCE_FILES})
