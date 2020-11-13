# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libFraunhoferAAC)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/aac/libAACdec/src/FDK_delay.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aac_ram.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aac_rom.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdec_drc.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdec_hcr.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdec_hcr_bit.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdec_hcrs.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdec_pns.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdec_tns.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdecoder.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/aacdecoder_lib.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/block.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/channel.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/channelinfo.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/conceal.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/ldfiltbank.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/pulsedata.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/rvlc.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/rvlcbit.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/rvlcconceal.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/stereo.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/usacdec_ace_d4t64.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/usacdec_ace_ltp.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/usacdec_acelp.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/usacdec_fac.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/usacdec_lpc.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/usacdec_lpd.cpp
    ${ANDROID_ROOT}/external/aac/libAACdec/src/usacdec_rom.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/aacEnc_ram.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/aacEnc_rom.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/aacenc.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/aacenc_lib.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/aacenc_pns.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/aacenc_tns.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/adj_thr.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/band_nrg.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/bandwidth.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/bit_cnt.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/bitenc.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/block_switch.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/channel_map.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/chaosmeasure.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/dyn_bits.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/grp_data.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/intensity.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/line_pe.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/metadata_compressor.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/metadata_main.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/mps_main.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/ms_stereo.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/noisedet.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/pnsparam.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/pre_echo_control.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/psy_configuration.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/psy_main.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/qc_main.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/quantize.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/sf_estim.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/spreading.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/tonality.cpp
    ${ANDROID_ROOT}/external/aac/libAACenc/src/transform.cpp
    ${ANDROID_ROOT}/external/aac/libPCMutils/src/limiter.cpp
    ${ANDROID_ROOT}/external/aac/libPCMutils/src/pcm_utils.cpp
    ${ANDROID_ROOT}/external/aac/libPCMutils/src/pcmdmx_lib.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_bitbuffer.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_core.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_crc.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_decorrelate.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_hybrid.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_lpc.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_matrixCalloc.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_qmf_domain.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_tools_rom.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/FDK_trigFcts.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/autocorr2nd.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/dct.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/fft.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/fft_rad2.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/fixpoint_math.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/huff_nodes.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/mdct.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/nlc_dec.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/qmf.cpp
    ${ANDROID_ROOT}/external/aac/libFDK/src/scale.cpp
    ${ANDROID_ROOT}/external/aac/libSYS/src/genericStds.cpp
    ${ANDROID_ROOT}/external/aac/libSYS/src/syslib_channelMapDescr.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPDec/src/tpdec_adif.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPDec/src/tpdec_adts.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPDec/src/tpdec_asc.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPDec/src/tpdec_drm.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPDec/src/tpdec_latm.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPDec/src/tpdec_lib.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPEnc/src/tpenc_adif.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPEnc/src/tpenc_adts.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPEnc/src/tpenc_asc.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPEnc/src/tpenc_latm.cpp
    ${ANDROID_ROOT}/external/aac/libMpegTPEnc/src/tpenc_lib.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/HFgen_preFlat.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/env_calc.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/env_dec.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/env_extr.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/hbe.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/huff_dec.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/lpp_tran.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/psbitdec.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/psdec.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/psdec_drm.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/psdecrom_drm.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/pvc_dec.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbr_crc.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbr_deb.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbr_dec.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbr_ram.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbr_rom.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbrdec_drc.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbrdec_freq_sca.cpp
    ${ANDROID_ROOT}/external/aac/libSBRdec/src/sbrdecoder.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/bit_sbr.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/code_env.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/env_bit.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/env_est.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/fram_gen.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/invf_est.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/mh_det.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/nf_est.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/ps_bitenc.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/ps_encode.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/ps_main.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/resampler.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/sbr_encoder.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/sbr_misc.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/sbrenc_freq_sca.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/sbrenc_ram.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/sbrenc_rom.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/ton_corr.cpp
    ${ANDROID_ROOT}/external/aac/libSBRenc/src/tran_det.cpp
    ${ANDROID_ROOT}/external/aac/libArithCoding/src/ac_arith_coder.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/FDK_drcDecLib.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcDec_gainDecoder.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcDec_reader.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcDec_rom.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcDec_selectionProcess.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcDec_tools.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcGainDec_init.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcGainDec_preprocess.cpp
    ${ANDROID_ROOT}/external/aac/libDRCdec/src/drcGainDec_process.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_bitdec.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_calcM1andM2.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_dec.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_dec_conceal.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_dec_lib.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_process.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_qmf.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_reshapeBBEnv.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_rom.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_smoothing.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_stp.cpp
    ${ANDROID_ROOT}/external/aac/libSACdec/src/sac_tsd.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_bitstream.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_delay.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_dmx_tdom_enh.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_filter.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_framewindowing.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_huff_tab.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_lib.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_nlc_enc.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_onsetdetect.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_paramextract.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_staticgain.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_tree.cpp
    ${ANDROID_ROOT}/external/aac/libSACenc/src/sacenc_vectorfunctions.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/aac/libAACdec/include -Iexternal/aac/libAACenc/include -Iexternal/aac/libPCMutils/include -Iexternal/aac/libFDK/include -Iexternal/aac/libSYS/include -Iexternal/aac/libMpegTPDec/include -Iexternal/aac/libMpegTPEnc/include -Iexternal/aac/libSBRdec/include -Iexternal/aac/libSBRenc/include -Iexternal/aac/libArithCoding/include -Iexternal/aac/libDRCdec/include -Iexternal/aac/libSACdec/include -Iexternal/aac/libSACenc/include'
# Raw param [2] = '-Iexternal/aac'
# Raw param [3] = '${config.ArmClangThumbCflags}'
# Raw param [4] = '${config.ArmClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [8] = '-Iexternal/libcxx/include'
# Raw param [9] = '-Iexternal/libcxxabi/include'
# Raw param [10] = '-Isystem/core/liblog/include'
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
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/external/aac/libAACdec/include -Iexternal/aac/libAACenc/include -Iexternal/aac/libPCMutils/include -Iexternal/aac/libFDK/include -Iexternal/aac/libSYS/include -Iexternal/aac/libMpegTPDec/include -Iexternal/aac/libMpegTPEnc/include -Iexternal/aac/libSBRdec/include -Iexternal/aac/libSBRenc/include -Iexternal/aac/libArithCoding/include -Iexternal/aac/libDRCdec/include -Iexternal/aac/libSACdec/include -Iexternal/aac/libSACenc/include"
    "${ANDROID_ROOT}/external/aac"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/aac/libAACdec/include -Iexternal/aac/libAACenc/include -Iexternal/aac/libPCMutils/include -Iexternal/aac/libFDK/include -Iexternal/aac/libSYS/include -Iexternal/aac/libMpegTPDec/include -Iexternal/aac/libMpegTPEnc/include -Iexternal/aac/libSBRdec/include -Iexternal/aac/libSBRenc/include -Iexternal/aac/libArithCoding/include -Iexternal/aac/libDRCdec/include -Iexternal/aac/libSACdec/include -Iexternal/aac/libSACenc/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBDL_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-Werror'
# Raw param [1] = '-Wno-unused-parameter'
# Raw param [2] = ''-Wno-#warnings''
# Raw param [3] = '-Wuninitialized'
# Raw param [4] = '-Wno-self-assign'
# Raw param [5] = '-Wno-implicit-fallthrough'
# Raw param [6] = '-target armv7a-linux-androideabi'
# Raw param [7] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [8] = '-fPIC'
# Raw param [9] = '-D_USING_LIBCXX'
# Raw param [10] = '-fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds'
# Raw param [11] = '-fsanitize-trap=all'
# Raw param [12] = '-ftrap-function=abort'
# Raw param [13] = '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined'
# Raw param [14] = '-fno-sanitize=implicit-integer-sign-change'
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG ''-Wno-#warnings'' became -Wno-#warnings
# FLAG '-Wuninitialized' became -Wuninitialized
# FLAG '-Wno-self-assign' became -Wno-self-assign
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds' became -fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds
# FLAG '-fsanitize-trap=all' became -fsanitize-trap=all
# FLAG '-ftrap-function=abort' became -ftrap-function=abort
# FLAG '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined' became -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined
# FLAG '-fno-sanitize=implicit-integer-sign-change' became -fno-sanitize=implicit-integer-sign-change
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-#warnings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wuninitialized")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-self-assign")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize=unsigned-integer-overflow,signed-integer-overflow,bounds")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-trap=all")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ftrap-function=abort")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-sanitize=implicit-integer-sign-change")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-#warnings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wuninitialized")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-self-assign")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
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


add_executable(libFraunhoferAAC ${SOURCE_FILES})
