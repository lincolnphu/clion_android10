# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libsfntly)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/byte_array.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/font_data.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/font_input_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/font_output_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/growable_memory_byte_array.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/memory_byte_array.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/readable_font_data.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/data/writable_font_data.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/font.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/font_factory.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/file_input_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/lock.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/memory_input_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/port/memory_output_stream.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/big_glyph_metrics.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/bitmap_glyph.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/bitmap_glyph_info.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/bitmap_size_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/composite_bitmap_glyph.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/ebdt_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/eblc_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/ebsc_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/glyph_metrics.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format1.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format2.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format3.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format4.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/index_sub_table_format5.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/simple_bitmap_glyph.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/bitmap/small_glyph_metrics.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/byte_array_table_builder.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/cmap_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/font_header_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/horizontal_device_metrics_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/horizontal_header_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/horizontal_metrics_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/maximum_profile_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/name_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/core/os2_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/font_data_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/generic_table_builder.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/header.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/subtable.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/table_based_table_builder.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/truetype/glyph_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/table/truetype/loca_table.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sfntly/tag.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sample/chromium/font_subsetter.cc
    ${ANDROID_ROOT}/external/sfntly/cpp/src/sample/chromium/subsetter_impl.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/sfntly/cpp/src'
# Raw param [2] = '-Iexternal/sfntly'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/libcxx/include'
# Raw param [9] = '-Iexternal/libcxxabi/include'
# Raw param [10] = '-Iexternal/icu/libandroidicu/include'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
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
    "${ANDROID_ROOT}/external/sfntly/cpp/src"
    "${ANDROID_ROOT}/external/sfntly"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/sfntly/cpp/src/**/*.h"
    "${ANDROID_ROOT}/external/sfntly/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include/**/*.h"
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
# Raw param [0] = '-fstack-protector'
# Raw param [1] = '--param=ssp-buffer-size=4'
# Raw param [2] = '-Werror'
# Raw param [3] = '-fno-exceptions'
# Raw param [4] = '-fno-strict-aliasing'
# Raw param [5] = '-Wall'
# Raw param [6] = '-Wno-unused-parameter'
# Raw param [7] = '-Wno-missing-field-initializers'
# Raw param [8] = '-fvisibility=hidden'
# Raw param [9] = '-ffunction-sections'
# Raw param [10] = '-funwind-tables'
# Raw param [11] = '-g'
# Raw param [12] = '-fno-short-enums'
# Raw param [13] = '-Wa,--noexecstack'
# Raw param [14] = '-U_FORTIFY_SOURCE'
# Raw param [15] = '-Wno-extra'
# Raw param [16] = '-Wno-ignored-qualifiers'
# Raw param [17] = '-Wno-type-limits'
# Raw param [18] = '-Os'
# Raw param [19] = '-fno-ident'
# Raw param [20] = '-fdata-sections'
# Raw param [21] = '-ffunction-sections'
# Raw param [22] = '-fomit-frame-pointer'
# Raw param [23] = '-DANGLE_DX11'
# Raw param [24] = '-D_FILE_OFFSET_BITS=64'
# Raw param [25] = '-DNO_TCMALLOC'
# Raw param [26] = '-DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY'
# Raw param [27] = '-DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE'
# Raw param [28] = '-DDISABLE_NACL'
# Raw param [29] = '-DCHROMIUM_BUILD'
# Raw param [30] = '-DUSE_LIBJPEG_TURBO=1'
# Raw param [31] = '-DUSE_PROPRIETARY_CODECS'
# Raw param [32] = '-DENABLE_CONFIGURATION_POLICY'
# Raw param [33] = '-DENABLE_GPU=1'
# Raw param [34] = '-DUSE_OPENSSL=1'
# Raw param [35] = '-DENABLE_EGLIMAGE=1'
# Raw param [36] = '-DSFNTLY_NO_EXCEPTION'
# Raw param [37] = '-DU_USING_ICU_NAMESPACE=0'
# Raw param [38] = '-D__STDC_CONSTANT_MACROS'
# Raw param [39] = '-D__STDC_FORMAT_MACROS'
# Raw param [40] = '-DANDROID'
# Raw param [41] = '-D__GNU_SOURCE=1'
# Raw param [42] = '-D_STLP_USE_PTR_SPECIALIZATIONS=1'
# Raw param [43] = ''-DCHROME_BUILD_ID='\''""'\''''
# Raw param [44] = '-DNDEBUG'
# Raw param [45] = '-DNVALGRIND'
# Raw param [46] = '-DDYNAMIC_ANNOTATIONS_ENABLED=0'
# Raw param [47] = '-D_FORTIFY_SOURCE=2'
# Raw param [48] = '-fPIC'
# Raw param [49] = '-target i686-linux-gnu'
# Raw param [50] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [51] = '-fPIC'
# Raw param [52] = '-D_USING_LIBCXX'
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '--param=ssp-buffer-size=4' became --param=ssp-buffer-size=4
# FLAG '-Werror' became -Werror
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-fno-strict-aliasing' became -fno-strict-aliasing
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-funwind-tables' became -funwind-tables
# FLAG '-g' became -g
# FLAG '-fno-short-enums' became -fno-short-enums
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-Wno-extra' became -Wno-extra
# FLAG '-Wno-ignored-qualifiers' became -Wno-ignored-qualifiers
# FLAG '-Wno-type-limits' became -Wno-type-limits
# FLAG '-Os' became -Os
# FLAG '-fno-ident' became -fno-ident
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-DANGLE_DX11' became -DANGLE_DX11
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-DNO_TCMALLOC' became -DNO_TCMALLOC
# FLAG '-DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY' became -DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY
# FLAG '-DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE' became -DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE
# FLAG '-DDISABLE_NACL' became -DDISABLE_NACL
# FLAG '-DCHROMIUM_BUILD' became -DCHROMIUM_BUILD
# FLAG '-DUSE_LIBJPEG_TURBO=1' became -DUSE_LIBJPEG_TURBO=1
# FLAG '-DUSE_PROPRIETARY_CODECS' became -DUSE_PROPRIETARY_CODECS
# FLAG '-DENABLE_CONFIGURATION_POLICY' became -DENABLE_CONFIGURATION_POLICY
# FLAG '-DENABLE_GPU=1' became -DENABLE_GPU=1
# FLAG '-DUSE_OPENSSL=1' became -DUSE_OPENSSL=1
# FLAG '-DENABLE_EGLIMAGE=1' became -DENABLE_EGLIMAGE=1
# FLAG '-DSFNTLY_NO_EXCEPTION' became -DSFNTLY_NO_EXCEPTION
# FLAG '-DU_USING_ICU_NAMESPACE=0' became -DU_USING_ICU_NAMESPACE=0
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-DANDROID' became -DANDROID
# FLAG '-D__GNU_SOURCE=1' became -D__GNU_SOURCE=1
# FLAG '-D_STLP_USE_PTR_SPECIALIZATIONS=1' became -D_STLP_USE_PTR_SPECIALIZATIONS=1
# FLAG ''-DCHROME_BUILD_ID='\''""'\'''' became -DCHROME_BUILD_ID='\\\"\\\"'
# FLAG '-DNDEBUG' became -DNDEBUG
# FLAG '-DNVALGRIND' became -DNVALGRIND
# FLAG '-DDYNAMIC_ANNOTATIONS_ENABLED=0' became -DDYNAMIC_ANNOTATIONS_ENABLED=0
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fPIC' became -fPIC
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} --param=ssp-buffer-size=4")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-strict-aliasing")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funwind-tables")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -g")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-short-enums")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-extra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-type-limits")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-ident")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANGLE_DX11")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNO_TCMALLOC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDISABLE_NACL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DCHROMIUM_BUILD")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_LIBJPEG_TURBO=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_PROPRIETARY_CODECS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_CONFIGURATION_POLICY")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_GPU=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_OPENSSL=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_EGLIMAGE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSFNTLY_NO_EXCEPTION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DU_USING_ICU_NAMESPACE=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__GNU_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_STLP_USE_PTR_SPECIALIZATIONS=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DCHROME_BUILD_ID='\\\"\\\"'")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNVALGRIND")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDYNAMIC_ANNOTATIONS_ENABLED=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} --param=ssp-buffer-size=4")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-strict-aliasing")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funwind-tables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -g")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-short-enums")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-extra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-type-limits")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-ident")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANGLE_DX11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNO_TCMALLOC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISCARDABLE_MEMORY_ALWAYS_SUPPORTED_NATIVELY")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSYSTEM_NATIVELY_SIGNALS_MEMORY_PRESSURE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDISABLE_NACL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DCHROMIUM_BUILD")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_LIBJPEG_TURBO=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_PROPRIETARY_CODECS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_CONFIGURATION_POLICY")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_GPU=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_OPENSSL=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_EGLIMAGE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSFNTLY_NO_EXCEPTION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DU_USING_ICU_NAMESPACE=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__GNU_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_STLP_USE_PTR_SPECIALIZATIONS=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DCHROME_BUILD_ID='\\\"\\\"'")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNVALGRIND")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDYNAMIC_ANNOTATIONS_ENABLED=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
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
# Raw param [3] = '-fno-threadsafe-statics'
# Raw param [4] = '-fvisibility-inlines-hidden'
# Raw param [5] = '-Wsign-compare'
# Raw param [6] = '-Wno-abi'
# Raw param [7] = '-Wno-error=c++0x-compat'
# Raw param [8] = '-Wno-non-virtual-dtor'
# Raw param [9] = '-Wno-sign-promo'
# Raw param [10] = ''
# Raw param [11] = '-nostdinc++'
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
# FLAG '-fno-threadsafe-statics' became -fno-threadsafe-statics
# FLAG '-fvisibility-inlines-hidden' became -fvisibility-inlines-hidden
# FLAG '-Wsign-compare' became -Wsign-compare
# FLAG '-Wno-abi' became -Wno-abi
# FLAG '-Wno-error=c++0x-compat' became -Wno-error=c++0x-compat
# FLAG '-Wno-non-virtual-dtor' became -Wno-non-virtual-dtor
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-threadsafe-statics")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-abi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=c++0x-compat")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
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


add_executable(libsfntly ${SOURCE_FILES})
