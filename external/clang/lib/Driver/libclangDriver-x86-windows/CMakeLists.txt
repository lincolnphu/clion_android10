# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libclangDriver)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/clang/lib/Driver/Action.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Compilation.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/CrossWindowsToolChain.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Driver.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/DriverOptions.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Job.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/MSVCToolChain.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/MinGWToolChain.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Multilib.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Phases.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/SanitizerArgs.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Tool.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/ToolChain.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/ToolChains.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Tools.cpp
    ${ANDROID_ROOT}/external/clang/lib/Driver/Types.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/clang/include -Iexternal/clang/lib/CodeGen'
# Raw param [2] = '-Iexternal/clang/lib/Driver'
# Raw param [3] = ''
# Raw param [4] = '${config.WindowsClangCflags} ${config.WindowsX86ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/llvm/include'
# Raw param [9] = '-Iexternal/llvm/host/include'
# Raw param [10] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-attributes/gen'
# Raw param [11] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen'
# Raw param [12] = '-Iexternal/clang/include'
# Raw param [13] = '-Iout/soong/.intermediates/external/clang/clang-gen-options/gen'
# Raw param [14] = '-Iout/soong/.intermediates/external/clang/clang-gen-attributes/gen'
# Raw param [15] = '-Iout/soong/.intermediates/external/clang/clang-gen-checkers/gen'
# Raw param [16] = '-Iout/soong/.intermediates/external/clang/clang-gen-comment-commands/gen'
# Raw param [17] = '-Iout/soong/.intermediates/external/clang/clang-gen-comment-html-named-character-references/gen'
# Raw param [18] = '-Iout/soong/.intermediates/external/clang/clang-gen-html-tags/gen'
# Raw param [19] = '-Iout/soong/.intermediates/external/clang/clang-gen-comment-nodes/gen'
# Raw param [20] = '-Iout/soong/.intermediates/external/clang/clang-gen-diagnostics/gen'
# Raw param [21] = '-Iout/soong/.intermediates/external/clang/clang-gen-declnodes/gen'
# Raw param [22] = '-Iout/soong/.intermediates/external/clang/clang-gen-statnodes/gen'
# Raw param [23] = '-Iout/soong/.intermediates/external/clang/clang-gen-arm-neon/gen'
# Raw param [24] = '-Iout/soong/.intermediates/external/clang/clang-version/gen'
# Raw param [25] = '-Iexternal/libcxx/include'
# Raw param [26] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/clang/include -Iexternal/clang/lib/CodeGen"
    "${ANDROID_ROOT}/external/clang/lib/Driver"
    "${ANDROID_ROOT}/external/llvm/include"
    "${ANDROID_ROOT}/external/llvm/host/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen"
    "${ANDROID_ROOT}/external/clang/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-options/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-attributes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-checkers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-commands/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-html-named-character-references/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-html-tags/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-nodes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-diagnostics/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-declnodes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-statnodes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-arm-neon/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-version/gen"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/clang/include -Iexternal/clang/lib/CodeGen/**/*.h"
    "${ANDROID_ROOT}/external/clang/lib/Driver/**/*.h"
    "${ANDROID_ROOT}/external/llvm/include/**/*.h"
    "${ANDROID_ROOT}/external/llvm/host/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen/**/*.h"
    "${ANDROID_ROOT}/external/clang/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-options/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-attributes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-checkers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-commands/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-html-named-character-references/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-html-tags/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-comment-nodes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-diagnostics/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-declnodes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-statnodes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-gen-arm-neon/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/clang/clang-version/gen/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
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
# Raw param [0] = '-D_GNU_SOURCE'
# Raw param [1] = '-D__STDC_LIMIT_MACROS'
# Raw param [2] = '-D__STDC_CONSTANT_MACROS'
# Raw param [3] = '-D__STDC_FORMAT_MACROS'
# Raw param [4] = '-fomit-frame-pointer'
# Raw param [5] = '-Wall'
# Raw param [6] = '-W'
# Raw param [7] = '-Wno-cast-qual'
# Raw param [8] = '-Wno-sign-compare'
# Raw param [9] = '-Wno-unused-parameter'
# Raw param [10] = '-Wno-missing-field-initializers'
# Raw param [11] = '-Wno-implicit-fallthrough'
# Raw param [12] = '-Wwrite-strings'
# Raw param [13] = '-Werror'
# Raw param [14] = '-Dsprintf=sprintf'
# Raw param [15] = '-pedantic'
# Raw param [16] = '-Wno-cast-qual'
# Raw param [17] = '-Wno-long-long'
# Raw param [18] = '-Wno-unused-private-field'
# Raw param [19] = '-Wno-unused-lambda-capture'
# Raw param [20] = '-Wno-array-bounds'
# Raw param [21] = '-Wno-comment'
# Raw param [22] = '-UWIN32_LEAN_AND_MEAN'
# Raw param [23] = '-Wno-error=uninitialized'
# Raw param [24] = '-target i686-windows-gnu'
# Raw param [25] = '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin'
# Raw param [26] = '-D_USING_LIBCXX'
# FLAG '-D_GNU_SOURCE' became -D_GNU_SOURCE
# FLAG '-D__STDC_LIMIT_MACROS' became -D__STDC_LIMIT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-Wall' became -Wall
# FLAG '-W' became -W
# FLAG '-Wno-cast-qual' became -Wno-cast-qual
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wwrite-strings' became -Wwrite-strings
# FLAG '-Werror' became -Werror
# FLAG '-Dsprintf=sprintf' became -Dsprintf=sprintf
# FLAG '-pedantic' became -pedantic
# FLAG '-Wno-cast-qual' became -Wno-cast-qual
# FLAG '-Wno-long-long' became -Wno-long-long
# FLAG '-Wno-unused-private-field' became -Wno-unused-private-field
# FLAG '-Wno-unused-lambda-capture' became -Wno-unused-lambda-capture
# FLAG '-Wno-array-bounds' became -Wno-array-bounds
# FLAG '-Wno-comment' became -Wno-comment
# FLAG '-UWIN32_LEAN_AND_MEAN' became -UWIN32_LEAN_AND_MEAN
# FLAG '-Wno-error=uninitialized' became -Wno-error=uninitialized
# FLAG '-target i686-windows-gnu' became -target i686-windows-gnu
# FLAG '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin' became -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_GNU_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-cast-qual")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wwrite-strings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Dsprintf=sprintf")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -pedantic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-cast-qual")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-long-long")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-private-field")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-lambda-capture")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-array-bounds")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-comment")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -UWIN32_LEAN_AND_MEAN")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=uninitialized")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-windows-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_GNU_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-cast-qual")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wwrite-strings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Dsprintf=sprintf")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -pedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-cast-qual")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-long-long")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-private-field")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-lambda-capture")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-array-bounds")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-comment")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -UWIN32_LEAN_AND_MEAN")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=uninitialized")
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
# Raw param [3] = '-Wno-sign-promo'
# Raw param [4] = '-std=c++11'
# Raw param [5] = '-fno-rtti'
# Raw param [6] = '-fno-exceptions'
# Raw param [7] = '${config.WindowsClangCppflags} ${config.WindowsX86ClangCppflags}'
# Raw param [8] = '-nostdinc++'
# Raw param [9] = '-fsjlj-exceptions'
# Raw param [10] = '-D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS'
# Raw param [11] = '-D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS'
# Raw param [12] = '-D_LIBCPP_HAS_THREAD_API_WIN32'
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
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-std=c++11' became -std=c++11
# FLAG '-fno-rtti' became -fno-rtti
# FLAG '-fno-exceptions' became -fno-exceptions
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
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


add_executable(libclangDriver ${SOURCE_FILES})
