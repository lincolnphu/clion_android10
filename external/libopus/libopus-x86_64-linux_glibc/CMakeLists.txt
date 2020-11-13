# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libopus)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libopus/celt/bands.c
    ${ANDROID_ROOT}/external/libopus/celt/celt.c
    ${ANDROID_ROOT}/external/libopus/celt/celt_encoder.c
    ${ANDROID_ROOT}/external/libopus/celt/celt_decoder.c
    ${ANDROID_ROOT}/external/libopus/celt/cwrs.c
    ${ANDROID_ROOT}/external/libopus/celt/entcode.c
    ${ANDROID_ROOT}/external/libopus/celt/entdec.c
    ${ANDROID_ROOT}/external/libopus/celt/entenc.c
    ${ANDROID_ROOT}/external/libopus/celt/kiss_fft.c
    ${ANDROID_ROOT}/external/libopus/celt/laplace.c
    ${ANDROID_ROOT}/external/libopus/celt/mathops.c
    ${ANDROID_ROOT}/external/libopus/celt/mdct.c
    ${ANDROID_ROOT}/external/libopus/celt/modes.c
    ${ANDROID_ROOT}/external/libopus/celt/pitch.c
    ${ANDROID_ROOT}/external/libopus/celt/celt_lpc.c
    ${ANDROID_ROOT}/external/libopus/celt/quant_bands.c
    ${ANDROID_ROOT}/external/libopus/celt/rate.c
    ${ANDROID_ROOT}/external/libopus/celt/vq.c
    ${ANDROID_ROOT}/external/libopus/silk/CNG.c
    ${ANDROID_ROOT}/external/libopus/silk/code_signs.c
    ${ANDROID_ROOT}/external/libopus/silk/init_decoder.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_core.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_frame.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_parameters.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_indices.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_pulses.c
    ${ANDROID_ROOT}/external/libopus/silk/decoder_set_fs.c
    ${ANDROID_ROOT}/external/libopus/silk/dec_API.c
    ${ANDROID_ROOT}/external/libopus/silk/enc_API.c
    ${ANDROID_ROOT}/external/libopus/silk/encode_indices.c
    ${ANDROID_ROOT}/external/libopus/silk/encode_pulses.c
    ${ANDROID_ROOT}/external/libopus/silk/gain_quant.c
    ${ANDROID_ROOT}/external/libopus/silk/interpolate.c
    ${ANDROID_ROOT}/external/libopus/silk/LP_variable_cutoff.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_decode.c
    ${ANDROID_ROOT}/external/libopus/silk/NSQ.c
    ${ANDROID_ROOT}/external/libopus/silk/NSQ_del_dec.c
    ${ANDROID_ROOT}/external/libopus/silk/PLC.c
    ${ANDROID_ROOT}/external/libopus/silk/shell_coder.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_gain.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_LTP.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_NLSF_CB_NB_MB.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_NLSF_CB_WB.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_other.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_pitch_lag.c
    ${ANDROID_ROOT}/external/libopus/silk/tables_pulses_per_block.c
    ${ANDROID_ROOT}/external/libopus/silk/VAD.c
    ${ANDROID_ROOT}/external/libopus/silk/control_audio_bandwidth.c
    ${ANDROID_ROOT}/external/libopus/silk/quant_LTP_gains.c
    ${ANDROID_ROOT}/external/libopus/silk/VQ_WMat_EC.c
    ${ANDROID_ROOT}/external/libopus/silk/HP_variable_cutoff.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_encode.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_VQ.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_unpack.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_del_dec_quant.c
    ${ANDROID_ROOT}/external/libopus/silk/process_NLSFs.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_LR_to_MS.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_MS_to_LR.c
    ${ANDROID_ROOT}/external/libopus/silk/check_control_input.c
    ${ANDROID_ROOT}/external/libopus/silk/control_SNR.c
    ${ANDROID_ROOT}/external/libopus/silk/init_encoder.c
    ${ANDROID_ROOT}/external/libopus/silk/control_codec.c
    ${ANDROID_ROOT}/external/libopus/silk/A2NLSF.c
    ${ANDROID_ROOT}/external/libopus/silk/ana_filt_bank_1.c
    ${ANDROID_ROOT}/external/libopus/silk/biquad_alt.c
    ${ANDROID_ROOT}/external/libopus/silk/bwexpander_32.c
    ${ANDROID_ROOT}/external/libopus/silk/bwexpander.c
    ${ANDROID_ROOT}/external/libopus/silk/debug.c
    ${ANDROID_ROOT}/external/libopus/silk/decode_pitch.c
    ${ANDROID_ROOT}/external/libopus/silk/inner_prod_aligned.c
    ${ANDROID_ROOT}/external/libopus/silk/lin2log.c
    ${ANDROID_ROOT}/external/libopus/silk/log2lin.c
    ${ANDROID_ROOT}/external/libopus/silk/LPC_analysis_filter.c
    ${ANDROID_ROOT}/external/libopus/silk/LPC_fit.c
    ${ANDROID_ROOT}/external/libopus/silk/LPC_inv_pred_gain.c
    ${ANDROID_ROOT}/external/libopus/silk/table_LSF_cos.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF2A.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_stabilize.c
    ${ANDROID_ROOT}/external/libopus/silk/NLSF_VQ_weights_laroia.c
    ${ANDROID_ROOT}/external/libopus/silk/pitch_est_tables.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_down2_3.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_down2.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_AR2.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_down_FIR.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_IIR_FIR.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_private_up2_HQ.c
    ${ANDROID_ROOT}/external/libopus/silk/resampler_rom.c
    ${ANDROID_ROOT}/external/libopus/silk/sigm_Q15.c
    ${ANDROID_ROOT}/external/libopus/silk/sort.c
    ${ANDROID_ROOT}/external/libopus/silk/sum_sqr_shift.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_decode_pred.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_encode_pred.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_find_predictor.c
    ${ANDROID_ROOT}/external/libopus/silk/stereo_quant_pred.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/LTP_analysis_filter_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/LTP_scale_ctrl_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/corrMatrix_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/encode_frame_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_LPC_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_LTP_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_pitch_lags_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/find_pred_coefs_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/noise_shape_analysis_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/process_gains_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/regularize_correlations_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/residual_energy16_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/residual_energy_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/warped_autocorrelation_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/apply_sine_window_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/autocorr_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/burg_modified_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/k2a_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/k2a_Q16_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/pitch_analysis_core_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/vector_ops_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/schur64_FIX.c
    ${ANDROID_ROOT}/external/libopus/silk/fixed/schur_FIX.c
    ${ANDROID_ROOT}/external/libopus/src/mapping_matrix.c
    ${ANDROID_ROOT}/external/libopus/src/opus.c
    ${ANDROID_ROOT}/external/libopus/src/opus_decoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_encoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_multistream.c
    ${ANDROID_ROOT}/external/libopus/src/opus_multistream_encoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_multistream_decoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_projection_encoder.c
    ${ANDROID_ROOT}/external/libopus/src/opus_projection_decoder.c
    ${ANDROID_ROOT}/external/libopus/src/repacketizer.c
    ${ANDROID_ROOT}/external/libopus/src/analysis.c
    ${ANDROID_ROOT}/external/libopus/src/mlp.c
    ${ANDROID_ROOT}/external/libopus/src/mlp_data.c
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/libopus/include'
# Raw param [2] = '-Iexternal/libopus/src -Iexternal/libopus/silk -Iexternal/libopus/celt -Iexternal/libopus/silk/fixed'
# Raw param [3] = '-Iexternal/libopus'
# Raw param [4] = ''
# Raw param [5] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [6] = '${config.CommonClangGlobalCflags}'
# Raw param [7] = '${config.HostClangGlobalCflags}'
# Raw param [8] = ''
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
    "${ANDROID_ROOT}/external/libopus/include"
    "${ANDROID_ROOT}/external/libopus/src -Iexternal/libopus/silk -Iexternal/libopus/celt -Iexternal/libopus/silk/fixed"
    "${ANDROID_ROOT}/external/libopus"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libopus/include/**/*.h"
    "${ANDROID_ROOT}/external/libopus/src -Iexternal/libopus/silk -Iexternal/libopus/celt -Iexternal/libopus/silk/fixed/**/*.h"
    "${ANDROID_ROOT}/external/libopus/**/*.h"
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
# Raw param [0] = '-DNULL=0'
# Raw param [1] = '-DSOCKLEN_T=socklen_t'
# Raw param [2] = '-DLOCALE_NOT_USED'
# Raw param [3] = '-D_LARGEFILE_SOURCE=1'
# Raw param [4] = '-D_FILE_OFFSET_BITS=64'
# Raw param [5] = '-Drestrict='
# Raw param [6] = '-D__EMX__'
# Raw param [7] = '-DOPUS_BUILD'
# Raw param [8] = '-DFIXED_POINT'
# Raw param [9] = '-DUSE_ALLOCA'
# Raw param [10] = '-DHAVE_LRINT'
# Raw param [11] = '-DHAVE_LRINTF'
# Raw param [12] = '-DENABLE_HARDENING'
# Raw param [13] = '-O2'
# Raw param [14] = '-fno-math-errno'
# Raw param [15] = '-Wall'
# Raw param [16] = '-Werror'
# Raw param [17] = '-target x86_64-linux-gnu'
# Raw param [18] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [19] = '-fPIC'
# Raw param [20] = '-D_USING_LIBCXX'
# FLAG '-DNULL=0' became -DNULL=0
# FLAG '-DSOCKLEN_T=socklen_t' became -DSOCKLEN_T=socklen_t
# FLAG '-DLOCALE_NOT_USED' became -DLOCALE_NOT_USED
# FLAG '-D_LARGEFILE_SOURCE=1' became -D_LARGEFILE_SOURCE=1
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-Drestrict=' became -Drestrict=
# FLAG '-D__EMX__' became -D__EMX__
# FLAG '-DOPUS_BUILD' became -DOPUS_BUILD
# FLAG '-DFIXED_POINT' became -DFIXED_POINT
# FLAG '-DUSE_ALLOCA' became -DUSE_ALLOCA
# FLAG '-DHAVE_LRINT' became -DHAVE_LRINT
# FLAG '-DHAVE_LRINTF' became -DHAVE_LRINTF
# FLAG '-DENABLE_HARDENING' became -DENABLE_HARDENING
# FLAG '-O2' became -O2
# FLAG '-fno-math-errno' became -fno-math-errno
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNULL=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSOCKLEN_T=socklen_t")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOCALE_NOT_USED")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LARGEFILE_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Drestrict=")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__EMX__")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPUS_BUILD")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DFIXED_POINT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DUSE_ALLOCA")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAVE_LRINT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAVE_LRINTF")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_HARDENING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-math-errno")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNULL=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSOCKLEN_T=socklen_t")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOCALE_NOT_USED")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LARGEFILE_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Drestrict=")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__EMX__")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPUS_BUILD")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DFIXED_POINT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DUSE_ALLOCA")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAVE_LRINT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAVE_LRINTF")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_HARDENING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-math-errno")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
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
# Raw param [3] = '-DBSD=1'
# Raw param [4] = '-ffast-math'
# Raw param [5] = '-O2'
# Raw param [6] = '-funroll-loops'
# Raw param [7] = ''
# Raw param [8] = '-nostdinc++'
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
# FLAG '-DBSD=1' became -DBSD=1
# FLAG '-ffast-math' became -ffast-math
# FLAG '-O2' became -O2
# FLAG '-funroll-loops' became -funroll-loops
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBSD=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffast-math")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funroll-loops")
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


add_executable(libopus ${SOURCE_FILES})
