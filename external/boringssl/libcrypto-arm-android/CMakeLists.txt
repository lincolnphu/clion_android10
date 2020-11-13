# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libcrypto)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/boringssl/err_data.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_bitstr.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_bool.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_d2i_fp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_dup.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_enum.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_gentm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_i2d_fp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_int.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_mbstr.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_object.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_octet.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_print.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_strnid.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_time.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_type.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_utctm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/a_utf8.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/asn1_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/asn1_par.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/asn_pack.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/f_enum.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/f_int.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/f_string.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_dec.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_enc.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_fre.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_new.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_typ.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/tasn_utl.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/asn1/time_support.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/base64/base64.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/bio.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/bio_mem.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/connect.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/fd.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/file.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/hexdump.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/pair.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/printf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/socket.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bio/socket_helper.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bn_extra/bn_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bn_extra/convert.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/buf/buf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/asn1_compat.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/ber.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/cbb.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/cbs.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/bytestring/unicode.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/chacha/chacha.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/cipher_extra.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/derive_key.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_aesccm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_aesctrhmac.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_aesgcmsiv.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_chacha20poly1305.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_null.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_rc2.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_rc4.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/e_tls.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cipher_extra/tls_cbc.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cmac/cmac.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/conf/conf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-aarch64-fuchsia.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-aarch64-linux.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-arm-linux.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-arm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-intel.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/cpu-ppc64le.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/crypto.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/curve25519/spake25519.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/check.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/dh.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/dh_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dh/params.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/digest_extra/digest_extra.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dsa/dsa.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/dsa/dsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ec_extra/ec_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ecdh_extra/ecdh_extra.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ecdsa_extra/ecdsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/engine/engine.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/err/err.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/digestsign.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/evp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/evp_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/evp_ctx.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_dsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ec.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ec_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ed25519.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_ed25519_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_rsa.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/p_rsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/pbkdf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/print.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/scrypt.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/evp/sign.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/ex_data.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/fipsmodule/bcm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/fipsmodule/is_fips.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/hkdf/hkdf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/hrss/hrss.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/lhash/lhash.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/mem.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/obj/obj.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/obj/obj_xref.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_all.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_info.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_oth.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_pk8.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_pkey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pem/pem_xaux.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs7/pkcs7.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs7/pkcs7_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs8/p5_pbev2.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs8/pkcs8.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pkcs8/pkcs8_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/poly1305/poly1305.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/poly1305/poly1305_arm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/poly1305/poly1305_vec.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/pool/pool.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/deterministic.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/forkunsafe.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/fuchsia.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/rand_extra.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rand_extra/windows.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rc4/rc4.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/refcount_c11.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/refcount_lock.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rsa_extra/rsa_asn1.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/rsa_extra/rsa_print.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/stack/stack.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread_none.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread_pthread.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/thread_win.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_digest.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_sign.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_strex.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/a_verify.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/algorithm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/asn1_gen.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/by_dir.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/by_file.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/i2d_pr.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/rsa_pss.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_crl.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_req.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/t_x509a.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_att.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_cmp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_d2.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_def.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_ext.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_lu.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_obj.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_r2x.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_req.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_set.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_trs.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_txt.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_v3.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_vfy.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509_vpm.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509cset.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509name.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509rset.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x509spki.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_algor.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_all.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_attrib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_crl.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_exten.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_info.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_name.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_pkey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_pubkey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_req.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_sig.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_spki.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_val.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_x509.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509/x_x509a.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_cache.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_data.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_map.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_node.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/pcy_tree.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_akey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_akeya.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_alt.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_bcons.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_bitst.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_conf.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_cpols.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_crld.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_enum.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_extku.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_genn.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_ia5.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_info.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_int.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_lib.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_ncons.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_ocsp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pci.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pcia.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pcons.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pku.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_pmaps.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_prn.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_purp.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_skey.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_sxnet.c
    ${ANDROID_ROOT}/external/boringssl/src/crypto/x509v3/v3_utl.c
    ${ANDROID_ROOT}/external/boringssl/src/third_party/fiat/curve25519.c
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/chacha/chacha-armv4.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/fipsmodule/aesv8-armx32.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/fipsmodule/armv4-mont.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/fipsmodule/ghash-armv4.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/fipsmodule/ghashv8-armx32.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/fipsmodule/sha1-armv4-large.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/fipsmodule/sha256-armv4.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/fipsmodule/sha512-armv4.S
    ${ANDROID_ROOT}/external/boringssl/linux-arm/crypto/test/trampoline-armv4.S
    ${ANDROID_ROOT}/external/boringssl/src/crypto/curve25519/asm/x25519-asm-arm.S
    ${ANDROID_ROOT}/external/boringssl/src/crypto/poly1305/poly1305_arm_asm.S
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/boringssl/src/include'
# Raw param [2] = '-Iexternal/boringssl/src/include -Iexternal/boringssl/src/crypto'
# Raw param [3] = '-Iexternal/boringssl'
# Raw param [4] = '-D__ANDROID_API__=16'
# Raw param [5] = '${config.ArmClangThumbCflags}'
# Raw param [6] = '${config.ArmClangCflags}'
# Raw param [7] = '${config.CommonClangGlobalCflags}'
# Raw param [8] = '${config.DeviceClangGlobalCflags}'
# Raw param [9] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [10] = '-Iexternal/boringssl/src/include'
# Raw param [11] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++/include'
# Raw param [12] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include'
# Raw param [13] = '-isystem prebuilts/ndk/current/sources/android/support/include'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# FLAG '-D__ANDROID_API__=16' became -D__ANDROID_API__=16
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
# Found a header search path marker with no pathinclude_directories(SYSTEM 
    "${ANDROID_ROOT}/-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

include_directories( 
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/boringssl/src/include -Iexternal/boringssl/src/crypto"
    "${ANDROID_ROOT}/external/boringssl"
    "${ANDROID_ROOT}/external/boringssl/src/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include -Iexternal/boringssl/src/crypto/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_API__=16")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_API__=16")
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
# Raw param [0] = '-fvisibility=hidden'
# Raw param [1] = '-DBORINGSSL_SHARED_LIBRARY'
# Raw param [2] = '-DBORINGSSL_ANDROID_SYSTEM'
# Raw param [3] = '-DOPENSSL_SMALL'
# Raw param [4] = '-D_XOPEN_SOURCE=700'
# Raw param [5] = '-Werror'
# Raw param [6] = '-Wno-unused-parameter'
# Raw param [7] = '-DBORINGSSL_IMPLEMENTATION'
# Raw param [8] = '-target armv7a-linux-androideabi'
# Raw param [9] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [10] = '-fPIC'
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-DBORINGSSL_SHARED_LIBRARY' became -DBORINGSSL_SHARED_LIBRARY
# FLAG '-DBORINGSSL_ANDROID_SYSTEM' became -DBORINGSSL_ANDROID_SYSTEM
# FLAG '-DOPENSSL_SMALL' became -DOPENSSL_SMALL
# FLAG '-D_XOPEN_SOURCE=700' became -D_XOPEN_SOURCE=700
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-DBORINGSSL_IMPLEMENTATION' became -DBORINGSSL_IMPLEMENTATION
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_SHARED_LIBRARY")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_ANDROID_SYSTEM")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DOPENSSL_SMALL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_XOPEN_SOURCE=700")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DBORINGSSL_IMPLEMENTATION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_SHARED_LIBRARY")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_ANDROID_SYSTEM")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DOPENSSL_SMALL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_XOPEN_SOURCE=700")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DBORINGSSL_IMPLEMENTATION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")

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
# Raw param [0] = '-std=gnu++17'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.DeviceGlobalCppflags}'
# Raw param [3] = '-Wall'
# Raw param [4] = '-Werror'
# Raw param [5] = '-fno-rtti'
# Raw param [6] = '${config.ArmClangCppflags}'
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
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.ArmClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
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


add_executable(libcrypto ${SOURCE_FILES})
