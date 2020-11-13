# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libbt-stack)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/system/bt/stack/crypto_toolbox/aes.cc
    ${ANDROID_ROOT}/system/bt/stack/crypto_toolbox/aes_cmac.cc
    ${ANDROID_ROOT}/system/bt/stack/crypto_toolbox/crypto_toolbox.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_aac.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_aac_decoder.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_aac_encoder.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_api.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_codec_config.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_sbc.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_sbc_decoder.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_sbc_encoder.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_sbc_up_sample.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_aptx.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_aptx_hd.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_aptx_encoder.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_aptx_hd_encoder.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_ldac.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_ldac_abr.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_ldac_decoder.cc
    ${ANDROID_ROOT}/system/bt/stack/a2dp/a2dp_vendor_ldac_encoder.cc
    ${ANDROID_ROOT}/system/bt/stack/avct/avct_api.cc
    ${ANDROID_ROOT}/system/bt/stack/avct/avct_bcb_act.cc
    ${ANDROID_ROOT}/system/bt/stack/avct/avct_ccb.cc
    ${ANDROID_ROOT}/system/bt/stack/avct/avct_l2c.cc
    ${ANDROID_ROOT}/system/bt/stack/avct/avct_l2c_br.cc
    ${ANDROID_ROOT}/system/bt/stack/avct/avct_lcb.cc
    ${ANDROID_ROOT}/system/bt/stack/avct/avct_lcb_act.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_ad.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_api.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_ccb.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_ccb_act.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_l2c.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_msg.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_scb.cc
    ${ANDROID_ROOT}/system/bt/stack/avdt/avdt_scb_act.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_api.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_bld_ct.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_bld_tg.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_opt.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_pars_ct.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_pars_tg.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_sdp.cc
    ${ANDROID_ROOT}/system/bt/stack/avrc/avrc_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/bnep/bnep_api.cc
    ${ANDROID_ROOT}/system/bt/stack/bnep/bnep_main.cc
    ${ANDROID_ROOT}/system/bt/stack/bnep/bnep_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/ble_advertiser_hci_interface.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_acl.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_addr.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_adv_filter.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_batchscan.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_bgconn.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_connection_establishment.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_cont_energy.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_gap.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_multi_adv.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_ble_privacy.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_dev.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_devctl.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_inq.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_main.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_pm.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_sco.cc
    ${ANDROID_ROOT}/system/bt/stack/btm/btm_sec.cc
    ${ANDROID_ROOT}/system/bt/stack/btu/btu_hcif.cc
    ${ANDROID_ROOT}/system/bt/stack/btu/btu_init.cc
    ${ANDROID_ROOT}/system/bt/stack/btu/btu_task.cc
    ${ANDROID_ROOT}/system/bt/stack/gap/gap_ble.cc
    ${ANDROID_ROOT}/system/bt/stack/gap/gap_conn.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/att_protocol.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/connection_manager.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_api.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_attr.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_auth.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_cl.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_db.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_main.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_sr.cc
    ${ANDROID_ROOT}/system/bt/stack/gatt/gatt_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/hcic/hciblecmds.cc
    ${ANDROID_ROOT}/system/bt/stack/hcic/hcicmds.cc
    ${ANDROID_ROOT}/system/bt/stack/hid/hidh_api.cc
    ${ANDROID_ROOT}/system/bt/stack/hid/hidh_conn.cc
    ${ANDROID_ROOT}/system/bt/stack/hid/hidd_api.cc
    ${ANDROID_ROOT}/system/bt/stack/hid/hidd_conn.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2c_api.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2c_ble.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2c_csm.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2c_fcr.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2c_link.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2c_main.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2c_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/l2cap/l2cap_client.cc
    ${ANDROID_ROOT}/system/bt/stack/pan/pan_api.cc
    ${ANDROID_ROOT}/system/bt/stack/pan/pan_main.cc
    ${ANDROID_ROOT}/system/bt/stack/pan/pan_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/port_api.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/port_rfc.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/port_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_l2cap_if.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_mx_fsm.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_port_fsm.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_port_if.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_ts_frames.cc
    ${ANDROID_ROOT}/system/bt/stack/rfcomm/rfc_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/sdp/sdp_api.cc
    ${ANDROID_ROOT}/system/bt/stack/sdp/sdp_db.cc
    ${ANDROID_ROOT}/system/bt/stack/sdp/sdp_discovery.cc
    ${ANDROID_ROOT}/system/bt/stack/sdp/sdp_main.cc
    ${ANDROID_ROOT}/system/bt/stack/sdp/sdp_server.cc
    ${ANDROID_ROOT}/system/bt/stack/sdp/sdp_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/p_256_curvepara.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/p_256_ecc_pp.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/p_256_multprecision.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/smp_act.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/smp_api.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/smp_br_main.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/smp_keys.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/smp_l2c.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/smp_main.cc
    ${ANDROID_ROOT}/system/bt/stack/smp/smp_utils.cc
    ${ANDROID_ROOT}/system/bt/stack/srvc/srvc_dis.cc
    ${ANDROID_ROOT}/system/bt/stack/srvc/srvc_eng.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Isystem/bt/stack/include -Isystem/bt/stack/avct -Isystem/bt/stack/btm -Isystem/bt/stack/avrc -Isystem/bt/stack/l2cap -Isystem/bt/stack/avdt -Isystem/bt/stack/gatt -Isystem/bt/stack/gap -Isystem/bt/stack/pan -Isystem/bt/stack/bnep -Isystem/bt/stack/hid -Isystem/bt/stack/sdp -Isystem/bt/stack/smp -Isystem/bt/stack/srvc'
# Raw param [1] = '-Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Iexternal/aac/libAACenc/include -Iexternal/aac/libAACdec/include -Iexternal/aac/libSYS/include -Iexternal/libldac/inc -Iexternal/libldac/abr/inc -Isystem/bt -Isystem/bt/btcore/include -Isystem/bt/vnd/include -Isystem/bt/vnd/ble -Isystem/bt/btif/include -Isystem/bt/hci/include -Isystem/bt/internal_include -Isystem/bt/udrv/include -Isystem/bt/bta/include -Isystem/bt/bta/sys -Isystem/bt/utils/include'
# Raw param [2] = '-Isystem/bt/stack'
# Raw param [3] = ''
# Raw param [4] = '${config.Arm64ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [8] = '-Isystem/bt/include'
# Raw param [9] = '-Isystem/bt/include/hardware/avrcp'
# Raw param [10] = '-Isystem/bt/internal_include'
# Raw param [11] = '-Iexternal/googletest/googletest/include'
# Raw param [12] = '-Isystem/core/base/include'
# Raw param [13] = '-Iout/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome'
# Raw param [14] = '-Isystem/bt/types'
# Raw param [15] = '-Iexternal/protobuf/src'
# Raw param [16] = '-Iout/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/core/proto'
# Raw param [17] = '-Iout/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/android_arm64_armv8-a_kryo_core_static/gen/proto'
# Raw param [18] = '-Iexternal/aac/libAACdec/include'
# Raw param [19] = '-Iexternal/aac/libAACenc/include'
# Raw param [20] = '-Iexternal/aac/libPCMutils/include'
# Raw param [21] = '-Iexternal/aac/libFDK/include'
# Raw param [22] = '-Iexternal/aac/libSYS/include'
# Raw param [23] = '-Iexternal/aac/libMpegTPDec/include'
# Raw param [24] = '-Iexternal/aac/libMpegTPEnc/include'
# Raw param [25] = '-Iexternal/aac/libSBRdec/include'
# Raw param [26] = '-Iexternal/aac/libSBRenc/include'
# Raw param [27] = '-Iexternal/aac/libArithCoding/include'
# Raw param [28] = '-Iexternal/aac/libDRCdec/include'
# Raw param [29] = '-Iexternal/aac/libSACdec/include'
# Raw param [30] = '-Iexternal/aac/libSACenc/include'
# Raw param [31] = '-Iexternal/libcxx/include'
# Raw param [32] = '-Iexternal/libcxxabi/include'
# Raw param [33] = '-Iout/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen'
# Raw param [34] = '-Isystem/core/libcutils/include'
# Raw param [35] = '-Isystem/core/libprocessgroup/include'
# Raw param [36] = '-Isystem/core/liblog/include'
# Raw param [37] = '-Ibionic/libc/include'
# Raw param [38] = '-D__LIBC_API__=10000'
# Raw param [39] = '-D__LIBM_API__=10000'
# Raw param [40] = '-D__LIBDL_API__=10000'
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
    "${ANDROID_ROOT}/system/bt/stack/include -Isystem/bt/stack/avct -Isystem/bt/stack/btm -Isystem/bt/stack/avrc -Isystem/bt/stack/l2cap -Isystem/bt/stack/avdt -Isystem/bt/stack/gatt -Isystem/bt/stack/gap -Isystem/bt/stack/pan -Isystem/bt/stack/bnep -Isystem/bt/stack/hid -Isystem/bt/stack/sdp -Isystem/bt/stack/smp -Isystem/bt/stack/srvc"
    "${ANDROID_ROOT}/device/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Iexternal/aac/libAACenc/include -Iexternal/aac/libAACdec/include -Iexternal/aac/libSYS/include -Iexternal/libldac/inc -Iexternal/libldac/abr/inc -Isystem/bt -Isystem/bt/btcore/include -Isystem/bt/vnd/include -Isystem/bt/vnd/ble -Isystem/bt/btif/include -Isystem/bt/hci/include -Isystem/bt/internal_include -Isystem/bt/udrv/include -Isystem/bt/bta/include -Isystem/bt/bta/sys -Isystem/bt/utils/include"
    "${ANDROID_ROOT}/system/bt/stack"
    "${ANDROID_ROOT}/system/bt/include"
    "${ANDROID_ROOT}/system/bt/include/hardware/avrcp"
    "${ANDROID_ROOT}/system/bt/internal_include"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/core/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/android_arm64_armv8-a_kryo_core_static/gen/proto"
    "${ANDROID_ROOT}/external/aac/libAACdec/include"
    "${ANDROID_ROOT}/external/aac/libAACenc/include"
    "${ANDROID_ROOT}/external/aac/libPCMutils/include"
    "${ANDROID_ROOT}/external/aac/libFDK/include"
    "${ANDROID_ROOT}/external/aac/libSYS/include"
    "${ANDROID_ROOT}/external/aac/libMpegTPDec/include"
    "${ANDROID_ROOT}/external/aac/libMpegTPEnc/include"
    "${ANDROID_ROOT}/external/aac/libSBRdec/include"
    "${ANDROID_ROOT}/external/aac/libSBRenc/include"
    "${ANDROID_ROOT}/external/aac/libArithCoding/include"
    "${ANDROID_ROOT}/external/aac/libDRCdec/include"
    "${ANDROID_ROOT}/external/aac/libSACdec/include"
    "${ANDROID_ROOT}/external/aac/libSACenc/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/system/bt/stack/include -Isystem/bt/stack/avct -Isystem/bt/stack/btm -Isystem/bt/stack/avrc -Isystem/bt/stack/l2cap -Isystem/bt/stack/avdt -Isystem/bt/stack/gatt -Isystem/bt/stack/gap -Isystem/bt/stack/pan -Isystem/bt/stack/bnep -Isystem/bt/stack/hid -Isystem/bt/stack/sdp -Isystem/bt/stack/smp -Isystem/bt/stack/srvc/**/*.h"
    "${ANDROID_ROOT}/device/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Idevice/google/marlin/bluetooth -Iexternal/aac/libAACenc/include -Iexternal/aac/libAACdec/include -Iexternal/aac/libSYS/include -Iexternal/libldac/inc -Iexternal/libldac/abr/inc -Isystem/bt -Isystem/bt/btcore/include -Isystem/bt/vnd/include -Isystem/bt/vnd/ble -Isystem/bt/btif/include -Isystem/bt/hci/include -Isystem/bt/internal_include -Isystem/bt/udrv/include -Isystem/bt/bta/include -Isystem/bt/bta/sys -Isystem/bt/utils/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/stack/**/*.h"
    "${ANDROID_ROOT}/system/bt/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/include/hardware/avrcp/**/*.h"
    "${ANDROID_ROOT}/system/bt/internal_include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libchrome/libchrome-include/gen/external/libchrome/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/core/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/proto/libbt-platform-protos-lite/android_arm64_armv8-a_kryo_core_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/external/aac/libAACdec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libAACenc/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libPCMutils/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libFDK/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSYS/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libMpegTPDec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libMpegTPEnc/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSBRdec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSBRenc/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libArithCoding/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libDRCdec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSACdec/include/**/*.h"
    "${ANDROID_ROOT}/external/aac/libSACenc/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

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
# Raw param [1] = '-Wextra'
# Raw param [2] = '-Werror'
# Raw param [3] = '-DHAS_BDROID_BUILDCFG'
# Raw param [4] = ''-DEXPORT_SYMBOL=__attribute__((visibility("default")))''
# Raw param [5] = '-fvisibility=hidden'
# Raw param [6] = '-Wno-gnu-variable-sized-type-not-at-end'
# Raw param [7] = '-Wno-unused-parameter'
# Raw param [8] = '-DLOG_NDEBUG=1'
# Raw param [9] = '-DHAS_BDROID_BUILDCFG'
# Raw param [10] = '-DHAS_BDROID_BUILDCFG'
# Raw param [11] = '-Wno-implicit-fallthrough'
# Raw param [12] = '-DBLUEDROID_DEBUG'
# Raw param [13] = '-target aarch64-linux-android'
# Raw param [14] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [15] = '-DANDROID_STRICT'
# Raw param [16] = '-fPIC'
# Raw param [17] = '-D_USING_LIBCXX'
# Raw param [18] = '-fsanitize=bounds'
# Raw param [19] = '-fsanitize-trap=all'
# Raw param [20] = '-ftrap-function=abort'
# Raw param [21] = '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined'
# Raw param [22] = '-fno-sanitize=implicit-integer-sign-change'
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Werror' became -Werror
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG ''-DEXPORT_SYMBOL=__attribute__((visibility("default")))'' became -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-gnu-variable-sized-type-not-at-end' became -Wno-gnu-variable-sized-type-not-at-end
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-DLOG_NDEBUG=1' became -DLOG_NDEBUG=1
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG '-DHAS_BDROID_BUILDCFG' became -DHAS_BDROID_BUILDCFG
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-DBLUEDROID_DEBUG' became -DBLUEDROID_DEBUG
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
# FLAG '-fsanitize=bounds' became -fsanitize=bounds
# FLAG '-fsanitize-trap=all' became -fsanitize-trap=all
# FLAG '-ftrap-function=abort' became -ftrap-function=abort
# FLAG '-fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined' became -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined
# FLAG '-fno-sanitize=implicit-integer-sign-change' became -fno-sanitize=implicit-integer-sign-change
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-gnu-variable-sized-type-not-at-end")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOG_NDEBUG=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBLUEDROID_DEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize=bounds")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-trap=all")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ftrap-function=abort")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-sanitize=implicit-integer-sign-change")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DEXPORT_SYMBOL=__attribute__((visibility(\\\"default\\\")))")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-variable-sized-type-not-at-end")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOG_NDEBUG=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAS_BDROID_BUILDCFG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBLUEDROID_DEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize=bounds")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-trap=all")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ftrap-function=abort")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsanitize-minimal-runtime -fno-sanitize-trap=integer,undefined -fno-sanitize-recover=integer,undefined")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-sanitize=implicit-integer-sign-change")

# C ONLY FLAGS:
# Raw param [0] = '-std=gnu99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# Raw param [2] = '-std=c99'
# FLAG '-std=gnu99' became -std=gnu99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
# FLAG '-std=c99' became -std=c99
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu99")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99")

# CPP FLAGS:
# Raw param [0] = '-std=c++17'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.DeviceGlobalCppflags}'
# Raw param [3] = '-fno-rtti'
# Raw param [4] = '${config.Arm64ClangCppflags}'
# FLAG '-std=c++17' became -std=c++17
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++17")
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


add_executable(libbt-stack ${SOURCE_FILES})
