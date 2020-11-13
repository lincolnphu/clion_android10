# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libmusicbundle)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_BypassMix.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_Control.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_Equaliser.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_Process.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_ReverbGenerator.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_StereoEnhancer.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/StereoWidening/src/LVCS_Tables.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bass/src/LVDBE_Control.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bass/src/LVDBE_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bass/src/LVDBE_Process.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bass/src/LVDBE_Tables.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bundle/src/LVM_API_Specials.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bundle/src/LVM_Buffers.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bundle/src/LVM_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bundle/src/LVM_Process.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bundle/src/LVM_Tables.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Bundle/src/LVM_Control.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src/LVPSA_Control.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src/LVPSA_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src/LVPSA_Memory.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src/LVPSA_Process.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src/LVPSA_QPD_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src/LVPSA_QPD_Process.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src/LVPSA_Tables.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Eq/src/LVEQNB_CalcCoef.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Eq/src/LVEQNB_Control.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Eq/src/LVEQNB_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Eq/src/LVEQNB_Process.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Eq/src/LVEQNB_Tables.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/InstAlloc.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/DC_2I_D16_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/DC_2I_D16_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/FO_2I_D16F32C15_LShx_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/FO_2I_D16F32Css_LShx_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/FO_1I_D16F16C15_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/FO_1I_D16F16Css_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BP_1I_D16F32C30_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BP_1I_D16F16C14_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BP_1I_D32F32C30_TRC_WRA_02.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BP_1I_D16F16Css_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BP_1I_D16F32Cll_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BP_1I_D32F32Cll_TRC_WRA_02_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D32F32Cll_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D32F32C30_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D16F32C15_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D16F32C14_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D16F32C13_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D16F32Css_TRC_WRA_01_init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D16F16C15_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D16F16C14_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_2I_D16F16Css_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_1I_D16F16C15_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_1I_D16F16Css_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_1I_D16F32C14_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/BQ_1I_D16F32Css_TRC_WRA_01_init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/PK_2I_D32F32C30G11_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/PK_2I_D32F32C14G11_TRC_WRA_01.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/PK_2I_D32F32CssGss_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/PK_2I_D32F32CllGss_TRC_WRA_01_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Int16LShiftToInt32_16x32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/From2iToMono_16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Copy_16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/MonoTo2I_16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/MonoTo2I_32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LoadConst_16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LoadConst_32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/dB_to_Lin32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Shift_Sat_v16xv16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Shift_Sat_v32xv32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Abs_32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Int32RShiftToInt16_Sat_32x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/From2iToMono_32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/mult3s_16x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Mult3s_32x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/NonLinComp_D16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/DelayMix_16x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/MSTo2i_Sat_16x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/From2iToMS_16x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Mac3s_Sat_16x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Mac3s_Sat_32x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Add2_Sat_16x16.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/Add2_Sat_32x32.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_MixSoft_1St_2i_D16C31_SAT.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_MixSoft_1St_D16C31_SAT.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Mixer_VarSlope_SetTimeConstant.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Mixer_SetTimeConstant.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Mixer_SetTarget.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Mixer_GetTarget.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Mixer_Init.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Core_MixHard_1St_2i_D16C31_SAT.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Core_MixSoft_1St_2i_D16C31_WRA.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Core_MixInSoft_D16C31_SAT.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Mixer_GetCurrent.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_MixSoft_2St_D16C31_SAT.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Core_MixSoft_1St_D16C31_WRA.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_Core_MixHard_2St_D16C31_SAT.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVC_MixInSoft_D16C31_SAT.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/AGC_MIX_VOL_2St1Mon_D32_WRA.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVM_Timer.c
    ${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/src/LVM_Timer_Init.c
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/av/media/libeffects/lvm/lib/Common/lib -Iframeworks/av/media/libeffects/lvm/lib/Bundle/lib'
# Raw param [1] = '-Iframeworks/av/media/libeffects/lvm/lib/Eq/lib -Iframeworks/av/media/libeffects/lvm/lib/Eq/src -Iframeworks/av/media/libeffects/lvm/lib/Bass/lib -Iframeworks/av/media/libeffects/lvm/lib/Bass/src -Iframeworks/av/media/libeffects/lvm/lib/Common/src -Iframeworks/av/media/libeffects/lvm/lib/Bundle/src -Iframeworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/lib -Iframeworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src -Iframeworks/av/media/libeffects/lvm/lib/StereoWidening/src -Iframeworks/av/media/libeffects/lvm/lib/StereoWidening/lib'
# Raw param [2] = '-Iframeworks/av/media/libeffects/lvm/lib'
# Raw param [3] = '${config.ArmClangArmCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [8] = '-Ihardware/libhardware/include'
# Raw param [9] = '-Isystem/media/audio/include'
# Raw param [10] = '-Isystem/core/libcutils/include'
# Raw param [11] = '-Isystem/core/libsystem/include'
# Raw param [12] = '-Isystem/bt/types'
# Raw param [13] = '-Iexternal/libcxx/include'
# Raw param [14] = '-Iexternal/libcxxabi/include'
# Raw param [15] = '-Isystem/core/liblog/include'
# Raw param [16] = '-Ibionic/libc/include'
# Raw param [17] = '-D__LIBC_API__=10000'
# Raw param [18] = '-D__LIBM_API__=10000'
# Raw param [19] = '-D__LIBDL_API__=10000'
# variable ${config.ArmClangArmCflags} = '-fstrict-aliasing'
# Raw param [0] = '-fstrict-aliasing'
# FLAG '-fstrict-aliasing' became -fstrict-aliasing
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
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/lib -Iframeworks/av/media/libeffects/lvm/lib/Bundle/lib"
    "${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Eq/lib -Iframeworks/av/media/libeffects/lvm/lib/Eq/src -Iframeworks/av/media/libeffects/lvm/lib/Bass/lib -Iframeworks/av/media/libeffects/lvm/lib/Bass/src -Iframeworks/av/media/libeffects/lvm/lib/Common/src -Iframeworks/av/media/libeffects/lvm/lib/Bundle/src -Iframeworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/lib -Iframeworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src -Iframeworks/av/media/libeffects/lvm/lib/StereoWidening/src -Iframeworks/av/media/libeffects/lvm/lib/StereoWidening/lib"
    "${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Common/lib -Iframeworks/av/media/libeffects/lvm/lib/Bundle/lib/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/Eq/lib -Iframeworks/av/media/libeffects/lvm/lib/Eq/src -Iframeworks/av/media/libeffects/lvm/lib/Bass/lib -Iframeworks/av/media/libeffects/lvm/lib/Bass/src -Iframeworks/av/media/libeffects/lvm/lib/Common/src -Iframeworks/av/media/libeffects/lvm/lib/Bundle/src -Iframeworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/lib -Iframeworks/av/media/libeffects/lvm/lib/SpectrumAnalyzer/src -Iframeworks/av/media/libeffects/lvm/lib/StereoWidening/src -Iframeworks/av/media/libeffects/lvm/lib/StereoWidening/lib/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libeffects/lvm/lib/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstrict-aliasing")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBDL_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstrict-aliasing")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-fvisibility=hidden'
# Raw param [1] = '-DBUILD_FLOAT'
# Raw param [2] = '-DHIGHER_FS'
# Raw param [3] = '-DSUPPORT_MC'
# Raw param [4] = '-Wall'
# Raw param [5] = '-Werror'
# Raw param [6] = '-target armv7a-linux-androideabi'
# Raw param [7] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [8] = '-DANDROID_STRICT'
# Raw param [9] = '-fPIC'
# Raw param [10] = '-D_USING_LIBCXX'
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-DBUILD_FLOAT' became -DBUILD_FLOAT
# FLAG '-DHIGHER_FS' became -DHIGHER_FS
# FLAG '-DSUPPORT_MC' became -DSUPPORT_MC
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBUILD_FLOAT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHIGHER_FS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSUPPORT_MC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBUILD_FLOAT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHIGHER_FS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSUPPORT_MC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
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
# Raw param [0] = '${config.CommonGlobalIncludes}'
# Raw param [1] = '${config.ArmIncludeFlags}'
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
# variable ${config.ArmIncludeFlags} = '-isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/kernel/uapi'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi/asm-arm'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/android/scsi'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_jni'
# Raw param [0] = '-Ilibnativehelper/include_jni'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm/**/*.h"
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


add_executable(libmusicbundle ${SOURCE_FILES})
