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
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/enable_execute_stack.c
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
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/comparetf2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzdi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzsi2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/ctzti2.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdf3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divdi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divmoddi4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsc3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/divsf3.c
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
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatdidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatdisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatdixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatsitf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floattixf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatundidf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatundisf.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/floatundixf.c
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
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivmodti4.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/udivti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umoddi3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/umodti3.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_dcmp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_div0.c
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_fcmp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_idivmod.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_ldivmod.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_memcmp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_memcpy.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_memmove.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_memset.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_uidivmod.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/aeabi_uldivmod.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/comparesf2.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/divmodsi4.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/divsi3.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/modsi3.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/udivmodsi4.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/udivsi3.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/umodsi3.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/adddf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/addsf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/divdf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/divsf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/eqdf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/eqsf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/extendsfdf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/fixdfsivfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/fixsfsivfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/fixunsdfsivfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/fixunssfsivfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/floatsidfvfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/floatsisfvfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/floatunssidfvfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/floatunssisfvfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/gedf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/gesf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/gtdf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/gtsf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/ledf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/lesf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/ltdf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/ltsf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/muldf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/mulsf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/nedf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/negdf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/negsf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/nesf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/subdf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/subsf3vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/truncdfsf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/unorddf2vfp.S
    ${ANDROID_ROOT}/external/compiler-rt/lib/builtins/arm/unordsf2vfp.S
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/compiler-rt'
# Raw param [2] = '-D__ANDROID_API__=21'
# Raw param [3] = '${config.ArmClangThumbCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [8] = '-Iexternal/lzma/C'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# FLAG '-D__ANDROID_API__=21' became -D__ANDROID_API__=21
# variable ${config.ArmClangThumbCflags} = '-mthumb -Os'
# Raw param [0] = '-mthumb'
# Raw param [1] = '-Os'
# FLAG '-mthumb' became -mthumb
# FLAG '-Os' became -Os
# variable ${config.ArmClangCflags} = '-fomit-frame-pointer'
# Raw param [0] = '-fomit-frame-pointer'
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
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
# variable ${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags} = '-msoft-float -march=armv8-a -mfloat-abi=softfp -mfpu=neon-fp-armv8 -mcpu=cortex-a53 -mfpu=neon-fp-armv8 -D__ARM_FEATURE_LPAE=1'
# Raw param [0] = '-msoft-float'
# Raw param [1] = '-march=armv8-a'
# Raw param [2] = '-mfloat-abi=softfp'
# Raw param [3] = '-mfpu=neon-fp-armv8'
# Raw param [4] = '-mcpu=cortex-a53'
# Raw param [5] = '-mfpu=neon-fp-armv8'
# Raw param [6] = '-D__ARM_FEATURE_LPAE=1'
# FLAG '-msoft-float' became -msoft-float
# FLAG '-march=armv8-a' became -march=armv8-a
# FLAG '-mfloat-abi=softfp' became -mfloat-abi=softfp
# FLAG '-mfpu=neon-fp-armv8' became -mfpu=neon-fp-armv8
# FLAG '-mcpu=cortex-a53' became -mcpu=cortex-a53
# FLAG '-mfpu=neon-fp-armv8' became -mfpu=neon-fp-armv8
# FLAG '-D__ARM_FEATURE_LPAE=1' became -D__ARM_FEATURE_LPAE=1
include_directories( 
    "${ANDROID_ROOT}/external/compiler-rt"
    "${ANDROID_ROOT}/external/lzma/C"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/compiler-rt/**/*.h"
    "${ANDROID_ROOT}/external/lzma/C/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_API__=21")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mthumb")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msoft-float")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=armv8-a")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfloat-abi=softfp")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mcpu=cortex-a53")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ARM_FEATURE_LPAE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_API__=21")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mthumb")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msoft-float")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=armv8-a")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfloat-abi=softfp")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mcpu=cortex-a53")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mfpu=neon-fp-armv8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ARM_FEATURE_LPAE=1")

# CFLAGS:
# Raw param [0] = '-Wno-unused-parameter'
# Raw param [1] = '-Wno-visibility'
# Raw param [2] = '-Wno-incompatible-pointer-types'
# Raw param [3] = '-Werror'
# Raw param [4] = '-D__ARM_EABI__'
# Raw param [5] = '-target armv7a-linux-androideabi'
# Raw param [6] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [7] = '-fPIC'
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-visibility' became -Wno-visibility
# FLAG '-Wno-incompatible-pointer-types' became -Wno-incompatible-pointer-types
# FLAG '-Werror' became -Werror
# FLAG '-D__ARM_EABI__' became -D__ARM_EABI__
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-visibility")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-incompatible-pointer-types")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ARM_EABI__")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-visibility")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-incompatible-pointer-types")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ARM_EABI__")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")

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
# Raw param [4] = '${config.ArmClangCppflags}'
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
# variable ${config.ArmClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")

# SYSTEM INCLUDE FLAGS:
# Raw param [0] = '-isystem out/soong/ndk/sysroot/usr/include'
# Raw param [1] = '-isystem out/soong/ndk/sysroot/usr/include/arm-linux-androideabi'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/-isystem out/soong/ndk/sysroot/usr/include/arm-linux-androideabi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/-isystem out/soong/ndk/sysroot/usr/include/arm-linux-androideabi/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})


add_executable(libcompiler_rt ${SOURCE_FILES})
