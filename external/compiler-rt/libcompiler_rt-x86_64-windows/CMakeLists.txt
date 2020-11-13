# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libcompiler_rt)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/absvdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/absvsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/absvti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/adddf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addtf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addvdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addvsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/addvti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashldi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashlti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashrdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ashrti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clear_cache.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clzdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clzsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/clzti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/cmpdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/cmpti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/comparedf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/comparesf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/comparetf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divmoddi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divmodsi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divtf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divxc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/eprintf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extenddftf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extendhfsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extendsfdf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/extendsftf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ffsdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ffsti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixdfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixdfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixdfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixsfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixsfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixsfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixtfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixtfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixtfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsdfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsdfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsdfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunssfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunssfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunssfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunstfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunstfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunstfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsxfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsxfsi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixunsxfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixxfdi.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/fixxfti.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsitf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatunsidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatunsisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatunsitf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatuntidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatuntisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatuntixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/gcc_personality_v0.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/int_util.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/lshrdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/lshrti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/moddi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/modsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/modti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muldc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muldf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muldi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulodi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulosi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/muloti4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulsc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/multf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/multi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulvdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulvsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulvti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/mulxc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negdf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negvdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negvsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/negvti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/paritydi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/paritysi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/parityti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/popcountdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/popcountsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/popcountti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powidf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powisf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powitf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/powixf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subdf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subsf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subtf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subvdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subvsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/subvti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/trampoline_setup.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/truncdfhf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/truncdfsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/truncsfhf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/trunctfdf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/trunctfsf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ucmpdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ucmpti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivmoddi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivmodsi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivmodti4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umoddi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umodsi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umodti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatundixf.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatdisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatdidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatdixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatundisf.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/x86_64/floatundidf.S
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/compiler-rt'
# Raw param [2] = ''
# Raw param [3] = '${config.WindowsClangCflags} ${config.WindowsX8664ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# variable ${config.WindowsClangCflags} ${config.WindowsX8664ClangCflags} = '-DUSE_MINGW -DWIN32_LEAN_AND_MEAN -Wno-unused-parameter -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -D__USE_MINGW_ANSI_STDIO=1 -D_WIN32_WINNT=0x0601 -DWINVER=0x0601 -D_FILE_OFFSET_BITS=64 --sysroot prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32 -m64'
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
# Raw param [11] = '-m64'
# FLAG '-DUSE_MINGW' became -DUSE_MINGW
# FLAG '-DWIN32_LEAN_AND_MEAN' became -DWIN32_LEAN_AND_MEAN
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__USE_MINGW_ANSI_STDIO=1' became -D__USE_MINGW_ANSI_STDIO=1
# FLAG '-D_WIN32_WINNT=0x0601' became -D_WIN32_WINNT=0x0601
# FLAG '-DWINVER=0x0601' became -DWINVER=0x0601
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
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
    "${ANDROID_ROOT}/external/compiler-rt"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/compiler-rt/**/*.h"
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_MINGW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWIN32_LEAN_AND_MEAN")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__USE_MINGW_ANSI_STDIO=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_WIN32_WINNT=0x0601")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DWINVER=0x0601")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
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
include_directories(SYSTEM "${ANDROID_ROOT}/prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32/usr/include")

# CFLAGS:
# Raw param [0] = '-Wno-unused-parameter'
# Raw param [1] = '-Wno-visibility'
# Raw param [2] = '-Wno-incompatible-pointer-types'
# Raw param [3] = '-Werror'
# Raw param [4] = '-target x86_64-pc-windows-gnu'
# Raw param [5] = '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin'
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-visibility' became -Wno-visibility
# FLAG '-Wno-incompatible-pointer-types' became -Wno-incompatible-pointer-types
# FLAG '-Werror' became -Werror
# FLAG '-target x86_64-pc-windows-gnu' became -target x86_64-pc-windows-gnu
# FLAG '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin' became -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-visibility")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-incompatible-pointer-types")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-pc-windows-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-visibility")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-incompatible-pointer-types")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-pc-windows-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin")

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
# Raw param [3] = '${config.WindowsClangCppflags} ${config.WindowsX8664ClangCppflags}'
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
# variable ${config.WindowsClangCppflags} ${config.WindowsX8664ClangCppflags} = ' '
# Raw param [0] = ''
# Raw param [1] = ''
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdinc++")

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


add_executable(libcompiler_rt ${SOURCE_FILES})
