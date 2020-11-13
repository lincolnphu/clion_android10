# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libxaacdec)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_aacdecoder.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_aacpluscheck.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_aac_imdct.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_aac_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_aac_tns.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_acelp_bitparse.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_acelp_decode.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_acelp_mdct.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_acelp_tools.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_adts_crc_check.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_api.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_arith_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_avq_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_avq_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_basic_ops.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_bitbuffer.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_block.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_channel.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_common_initfuncs.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_common_lpfuncs.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_common_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_create.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_decode_main.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_dsp_fft32x32s.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_env_calc.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_env_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_env_extr.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_esbr_envcal.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_esbr_polyphase.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_esbr_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_esbr_fft.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_ext_ch_ele.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_fft.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_freq_sca.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_fwd_alias_cnx.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_hbe_trans.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_headerdecode.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_hufftables.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_huff_tools.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_hybrid.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_imdct.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_initfuncs.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_init_config.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_longblock.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_lpc.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_lpc_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_lpfuncs.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_lpp_tran.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_lt_predict.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_decorr.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_hybrid_filt.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_parse.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_pre_mix.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_smoothing.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_temp_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_temp_reshape.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_pns_js_thumb.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_pred_vec_block.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_ps_bitdec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_ps_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_pvc_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_sbrdecoder.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_sbrdec_initfuncs.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_sbrdec_lpfuncs.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_sbr_crc.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_sbr_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_sbr_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_spectrum_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_stereo.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_tcx_fwd_alcnx.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_tcx_fwd_mdct.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_thumb_ps_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_tns.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_basic_funcs.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_Windowing.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_latmdemux.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_multichannel.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_drc_freq_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_mps_poly_filt.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_huff_code_reorder.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_rev_vlc.c
    ${ANDROID_ROOT}/external/libxaac/decoder/ixheaacd_qmf_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_api.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_bitbuffer.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_dynamic_payload.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_eq.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_extr_delta_coded_info.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_filter_bank.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_gain_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_gain_decoder.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_host_params.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_init.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_interface_decoder.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_interface_parser.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_loudness_control.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_main_qmf_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_main_stft_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_main_td_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_main_td_qmf_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_multiband.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_parametric_dec.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_peak_limiter.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_rom.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_selection_process.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_selection_process_drcset_selection.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_selection_process_init.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_shape_filter.c
    ${ANDROID_ROOT}/external/libxaac/decoder/drc_src/impd_drc_static_payload.c
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_qmf_dec_armv8.c
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_function_selector_armv8.c
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_calcmaxspectralline.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_sbr_imdct_using_fft.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_imdct_using_fft.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_no_lap1.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_post_twiddle.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_pre_twiddle.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_sbr_qmfsyn64_winadd.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_overlap_add1.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_overlap_add2.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_shiftrountine_with_round_eld.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_fft32x32_ld2_armv8.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_inv_dit_fft_8pt.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_shiftrountine_with_round.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_sbr_qmf_analysis32_neon.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_postradixcompute4.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_apply_scale_factors.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_cos_sin_mod_loop1.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_cos_sin_mod_loop2.s
    ${ANDROID_ROOT}/external/libxaac/decoder/armv8/ixheaacd_post_twiddle_overlap.s
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/libxaac/decoder -Iexternal/libxaac/decoder/drc_src'
# Raw param [2] = '-Iexternal/libxaac/decoder/armv8'
# Raw param [3] = '-Iexternal/libxaac'
# Raw param [4] = ''
# Raw param [5] = '${config.Arm64ClangCflags}'
# Raw param [6] = '${config.CommonClangGlobalCflags}'
# Raw param [7] = '${config.DeviceClangGlobalCflags}'
# Raw param [8] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [9] = '-Iexternal/libcxx/include'
# Raw param [10] = '-Iexternal/libcxxabi/include'
# Raw param [11] = '-Ibionic/libc/include'
# Raw param [12] = '-D__LIBC_API__=10000'
# Raw param [13] = '-D__LIBM_API__=10000'
# Raw param [14] = '-D__LIBDL_API__=10000'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
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
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/external/libxaac/decoder -Iexternal/libxaac/decoder/drc_src"
    "${ANDROID_ROOT}/external/libxaac/decoder/armv8"
    "${ANDROID_ROOT}/external/libxaac"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libxaac/decoder -Iexternal/libxaac/decoder/drc_src/**/*.h"
    "${ANDROID_ROOT}/external/libxaac/decoder/armv8/**/*.h"
    "${ANDROID_ROOT}/external/libxaac/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBDL_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-O3'
# Raw param [3] = '-target aarch64-linux-android'
# Raw param [4] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [5] = '-fPIC'
# Raw param [6] = '-D_USING_LIBCXX'
# Raw param [7] = '-fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds'
# Raw param [8] = '-fsanitize-trap=all'
# Raw param [9] = '-ftrap-function=abort'
# Raw param [10] = '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined'
# Raw param [11] = '-fno-sanitize=implicit-integer-sign-change'
# Raw param [12] = '-fsanitize-blacklist=external/libxaac/libxaac_blacklist.txt'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-O3' became -O3
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds' became -fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds
# FLAG '-fsanitize-trap=all' became -fsanitize-trap=all
# FLAG '-ftrap-function=abort' became -ftrap-function=abort
# FLAG '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined' became -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined
# FLAG '-fno-sanitize=implicit-integer-sign-change' became -fno-sanitize=implicit-integer-sign-change
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-blacklist=${ANDROID_ROOT}/external/libxaac/libxaac_blacklist.txt")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-trap=all")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ftrap-function=abort")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-sanitize=implicit-integer-sign-change")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-blacklist=${ANDROID_ROOT}/external/libxaac/libxaac_blacklist.txt")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-trap=all")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ftrap-function=abort")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-sanitize=implicit-integer-sign-change")

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


add_executable(libxaacdec ${SOURCE_FILES})
