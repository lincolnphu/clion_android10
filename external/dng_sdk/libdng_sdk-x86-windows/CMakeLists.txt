# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libdng_sdk)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_1d_function.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_1d_table.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_abort_sniffer.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_area_task.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_bad_pixels.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_bottlenecks.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_camera_profile.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_color_space.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_color_spec.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_date_time.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_exceptions.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_exif.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_file_stream.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_filter_task.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_fingerprint.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_gain_map.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_globals.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_host.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_hue_sat_map.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_ifd.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_image.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_image_writer.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_info.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_iptc.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_jpeg_image.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_jpeg_memory_source.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_lens_correction.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_linearization_info.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_lossless_jpeg.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_matrix.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_memory.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_memory_stream.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_misc_opcodes.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_mosaic_info.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_mutex.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_negative.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_opcode_list.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_opcodes.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_orientation.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_parse_utils.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_pixel_buffer.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_point.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_preview.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_pthread.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_rational.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_read_image.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_rect.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_ref_counted_block.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_reference.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_render.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_resample.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_safe_arithmetic.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_shared.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_simple_image.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_spline.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_stream.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_string.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_string_list.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_tag_types.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_temperature.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_tile_iterator.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_tone_curve.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_utils.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_xy_coord.cpp
    ${ANDROID_ROOT}/external/dng_sdk/source/dng_xmp.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/dng_sdk/source'
# Raw param [2] = '-Iexternal/dng_sdk'
# Raw param [3] = ''
# Raw param [4] = '${config.WindowsClangCflags} ${config.WindowsX86ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/libcxx/include'
# Raw param [9] = '-Iexternal/libcxxabi/include'
# Raw param [10] = '-Iexternal/zlib'
# Raw param [11] = '-Iexternal/libjpeg-turbo'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# variable ${config.WindowsClangCflags} ${config.WindowsX86ClangCflags} = '-DUSE_MINGW -DWIN32_LEAN_AND_MEAN -Wno-unused-parameter -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -D__USE_MINGW_ANSI_STDIO=1 -D_WIN32_WINNT=0x0601 -DWINVER=0x0601 -D_FILE_OFFSET_BITS=64 --sysroot prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32 -m32'
# Raw param [0] = '-DUSE_MINGW'
# Raw param [1] = '-DWIN32_LEAN_AND_MEAN'
# Raw param [2] = '-Wno-unused-parameter'
# Raw param [3] = '-D__STDC_FORMAT_MACROS'
# Raw param [4] = '-D__STDC_CONSTANT_MACROS'
# Raw param [5] = '-D__USE_MINGW_ANSI_STDIO=1'
# Raw param [6] = '-D_WIN32_WINNT=0x0601'
# Raw param [7] = '-DWINVER=0x0601'
# Raw param [8] = '-D_FILE_OFFSET_BITS=64'
# Raw param [9] = '--sysroot'
# Raw param [10] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32'
# Raw param [11] = '-m32'
# FLAG '-DUSE_MINGW' became -DUSE_MINGW
# FLAG '-DWIN32_LEAN_AND_MEAN' became -DWIN32_LEAN_AND_MEAN
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__USE_MINGW_ANSI_STDIO=1' became -D__USE_MINGW_ANSI_STDIO=1
# FLAG '-D_WIN32_WINNT=0x0601' became -D_WIN32_WINNT=0x0601
# FLAG '-DWINVER=0x0601' became -DWINVER=0x0601
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-m32' became -m32
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
    "${ANDROID_ROOT}/external/dng_sdk/source"
    "${ANDROID_ROOT}/external/dng_sdk"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/dng_sdk/source/**/*.h"
    "${ANDROID_ROOT}/external/dng_sdk/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_MINGW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DWIN32_LEAN_AND_MEAN")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__USE_MINGW_ANSI_STDIO=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_WIN32_WINNT=0x0601")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DWINVER=0x0601")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_MINGW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWIN32_LEAN_AND_MEAN")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__USE_MINGW_ANSI_STDIO=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_WIN32_WINNT=0x0601")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWINVER=0x0601")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
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
include_directories(SYSTEM "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/usr/include")

# CFLAGS:
# Raw param [0] = '-DUNIX_ENV=1'
# Raw param [1] = '-DqDNGBigEndian=0'
# Raw param [2] = '-DqDNGThreadSafe=1'
# Raw param [3] = '-DqDNGUseLibJPEG=1'
# Raw param [4] = '-DqDNGUseXMP=0'
# Raw param [5] = '-DqDNGValidateTarget=1'
# Raw param [6] = '-DqAndroid=1'
# Raw param [7] = '-Werror'
# Raw param [8] = '-Wsign-compare'
# Raw param [9] = '-Wno-reorder'
# Raw param [10] = '-Wframe-larger-than=20000'
# Raw param [11] = '-Wno-unused-parameter'
# Raw param [12] = '-Wno-ignored-qualifiers'
# Raw param [13] = '-DqDNGValidate=0'
# Raw param [14] = '-D_LIBCPP_ENABLE_CXX17_REMOVED_AUTO_PTR'
# Raw param [15] = '-Wno-null-arithmetic'
# Raw param [16] = '-Wno-sign-compare'
# Raw param [17] = '-Wno-tautological-pointer-compare'
# Raw param [18] = '-Wno-unknown-pragmas'
# Raw param [19] = '-target i686-windows-gnu'
# Raw param [20] = '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin'
# Raw param [21] = '-D_USING_LIBCXX'
# FLAG '-DUNIX_ENV=1' became -DUNIX_ENV=1
# FLAG '-DqDNGBigEndian=0' became -DqDNGBigEndian=0
# FLAG '-DqDNGThreadSafe=1' became -DqDNGThreadSafe=1
# FLAG '-DqDNGUseLibJPEG=1' became -DqDNGUseLibJPEG=1
# FLAG '-DqDNGUseXMP=0' became -DqDNGUseXMP=0
# FLAG '-DqDNGValidateTarget=1' became -DqDNGValidateTarget=1
# FLAG '-DqAndroid=1' became -DqAndroid=1
# FLAG '-Werror' became -Werror
# FLAG '-Wsign-compare' became -Wsign-compare
# FLAG '-Wno-reorder' became -Wno-reorder
# FLAG '-Wframe-larger-than=20000' became -Wframe-larger-than=20000
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-ignored-qualifiers' became -Wno-ignored-qualifiers
# FLAG '-DqDNGValidate=0' became -DqDNGValidate=0
# FLAG '-D_LIBCPP_ENABLE_CXX17_REMOVED_AUTO_PTR' became -D_LIBCPP_ENABLE_CXX17_REMOVED_AUTO_PTR
# FLAG '-Wno-null-arithmetic' became -Wno-null-arithmetic
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-tautological-pointer-compare' became -Wno-tautological-pointer-compare
# FLAG '-Wno-unknown-pragmas' became -Wno-unknown-pragmas
# FLAG '-target i686-windows-gnu' became -target i686-windows-gnu
# FLAG '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin' became -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUNIX_ENV=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DqDNGBigEndian=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DqDNGThreadSafe=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DqDNGUseLibJPEG=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DqDNGUseXMP=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DqDNGValidateTarget=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DqAndroid=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wsign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-reorder")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wframe-larger-than=20000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DqDNGValidate=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LIBCPP_ENABLE_CXX17_REMOVED_AUTO_PTR")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-tautological-pointer-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unknown-pragmas")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-windows-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUNIX_ENV=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DqDNGBigEndian=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DqDNGThreadSafe=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DqDNGUseLibJPEG=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DqDNGUseXMP=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DqDNGValidateTarget=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DqAndroid=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-reorder")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wframe-larger-than=20000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DqDNGValidate=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_CXX17_REMOVED_AUTO_PTR")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-tautological-pointer-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unknown-pragmas")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-windows-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin")
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
# Raw param [3] = '-fexceptions'
# Raw param [4] = '${config.WindowsClangCppflags} ${config.WindowsX86ClangCppflags}'
# Raw param [5] = '-nostdinc++'
# Raw param [6] = '-fsjlj-exceptions'
# Raw param [7] = '-D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS'
# Raw param [8] = '-D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS'
# Raw param [9] = '-D_LIBCPP_HAS_THREAD_API_WIN32'
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
# FLAG '-fexceptions' became -fexceptions
# variable ${config.WindowsClangCppflags} ${config.WindowsX86ClangCppflags} = ' '
# Raw param [0] = ''
# Raw param [1] = ''
# FLAG '-nostdinc++' became -nostdinc++
# FLAG '-fsjlj-exceptions' became -fsjlj-exceptions
# FLAG '-D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS' became -D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS
# FLAG '-D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS' became -D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS
# FLAG '-D_LIBCPP_HAS_THREAD_API_WIN32' became -D_LIBCPP_HAS_THREAD_API_WIN32
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdinc++")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsjlj-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_HAS_THREAD_API_WIN32")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.WindowsIncludeFlags}'
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
# variable ${config.WindowsIncludeFlags} = '-isystem prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include'
# Raw param [0] = '-isystem'
# Raw param [1] = 'prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_jni'
# Raw param [0] = '-Ilibnativehelper/include_jni'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/include/**/*.h"
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


add_executable(libdng_sdk ${SOURCE_FILES})
