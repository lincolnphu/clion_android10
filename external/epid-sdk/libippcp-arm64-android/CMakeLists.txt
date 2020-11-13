# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libippcp)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_almmontinv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_almmontinv_ct.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_enginegetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_engineinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_getpool.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_inv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_montfactor.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_montinv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_packctx.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmod_unpackctx.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmodmethod.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmodmethod_dlp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmodmethod_gfp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmodmethod_mont.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsmodmethod_rsa.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/gsscramble.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbn_pack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbn_unpack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbn_val1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbn_val2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbn_val3.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithadd.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithcmp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithcmpz.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithdiv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithgcd.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithmac.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithminv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithmod.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithmul.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnarithsub.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbngetext.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbngetlen.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbngetoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbngetref.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbngetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbngetwords.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbninit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnresourceca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnsetoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnsetwords.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_arith_add.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_arith_dec.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_arith_div.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_arith_inc.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_arith_muldigit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_arith_sub.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_arith_submuldigit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_getoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_nlz.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu32_setoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_add.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_addmuldigit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_dec.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_gcd.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_inc.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_minv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_mul_adc.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_sqr_adc.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_sub.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_arith_submuldigit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_getoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_lsr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_msbit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_nlz.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_ntz.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpbnu_setoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpecc_psetdp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpaddpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpbindgxytblstd192r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpbindgxytblstd224r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpbindgxytblstd256r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpbindgxytblstd384r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpbindgxytblstd521r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpcheckpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpcomparepoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgenkeyca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpget.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetorderbitsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsizestd128r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsizestd128r2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsizestd192r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsizestd224r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsizestd256r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsizestd384r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpgetsizestd521r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinitstd128r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinitstd128r2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinitstd192r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinitstd224r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinitstd256r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinitstd384r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpinitstd521r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpmulpointscalar.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpnegativepoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccppointgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccppointinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccppublickeyca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsecretdhca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsecretdhcca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpset.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetkeyca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetpointatinfinity.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd128r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd128r2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd192r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd224r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd256r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd384r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsetstd521r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsigndsaca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpsignnrca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpstdca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpvalidateca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpvalidatekeyca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpverifydsaca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccpverifynrca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpeccresultca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_exp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_get.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_getoctstring.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_gfeqnr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_inv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_rand.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_set.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_setgfp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_setoctstring.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfp_sqrt.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpadd.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpaddpe.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpbufsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpcmpelem.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpconj.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpcpyelem.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_add.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_addaffine.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_baseprod.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_comppont.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_dblpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_getpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_makepoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_mul.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_mul1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_mulbase.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_mulbase1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_negpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_prod.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_selectp192r1w7.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_selectp224r1w7.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_selectp256r1w7.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_selectp384r1w5.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_selectp521r1w5.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_setpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpec_setuptable.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecaddpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecbindstd192r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecbindstd224r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecbindstd256r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecbindstd384r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecbindstd521r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecbufsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpeccmppoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpeccpypoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecdh.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecdhc.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecget.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecgetpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecgetpointoctstring.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecgetpointreg.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecgetsubgroup.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstd128r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstd128r2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstd192r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstd224r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstd256r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstd384r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstd521r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecinitstdbn256.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpeckeys.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecmakepoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecmulpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecnegpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecpointstuff.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecprivatekey.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecpublickey.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecset.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetpointatinf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetpointhash.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetpointhash_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetpointoctstring.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetpointrand.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetpointreg.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsetsubgroup.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsigndsa.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecsignnr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpectstpoint.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpectstpointinsubgroup.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecverify.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecverifydsa.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpecverifynr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpelemgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpeleminit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpexp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpgetelem.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpgetelemoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpinitarbitrary.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpinitfixed.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpinv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpisunityelem.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpiszeroelem.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_192r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_224r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_256.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_256bn.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_256r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_384r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_521r1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmethod_com.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmul.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmulexp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpmulpe.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpneg.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsetelem.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsetelemhash.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsetelemhashrmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsetelemoctstr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsetelemrand.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsetelemreg.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsqr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsqrt.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsub.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpsubpe.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_add_gfe.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_conj.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_exp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_get.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_getpolyterm.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_inv.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_mul_gfe.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_multiexp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_neg.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_rand.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_set.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_setpolyterm.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpx_sub_gfe.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxinitbinomial.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_binom.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_binom2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_binom3.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_binom3_epid2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_binom_epid2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_add.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_decode.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_div2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_encode.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_mul.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_mul2.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_mul3.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_neg.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_sqr.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxmethod_com_sub.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpgfpxstuff.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphash_digest.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphash_init.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphash_reinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashca_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashcnt.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashduplicate.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashduplicate_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashfinal.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashfinal_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashgetsize_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashgettag.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashgettag_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashinit_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmd5px.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmessage.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmessage_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha1.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha1_ni.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha1_tt.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha224.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha224_ni.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha224_tt.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha256.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha256_ni.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha256_tt.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha384.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha512.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha512_224.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashmethod_sha512_256.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashpack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashpack_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashsha1px.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashsha256px.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashsha512px.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashsm3px.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashunpack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashunpack_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashupdate.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcphashupdate_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmgf1ca_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmgf2ca_rmf.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_expbinbnu.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_expsafebinary.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_getsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_init.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_multiexp_fast.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_multiexpinitarray.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_packctx.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_set.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmont_unpackctx.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontexp.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontexp_winsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontform.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontget.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontgetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontinit.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontmul.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontred.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpmontset.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpp192r1precomca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpp224r1precomca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpp256r1precomca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpp384r1precomca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpp521r1precomca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprng_gen.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngen_bn.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngen_pattern.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngen_range.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngenca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngenhw_bn.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngenhwca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprnggetseed.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprnggetsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprnginitca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngsetaugment.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngsetca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngsetmodulus.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpprngsetseed.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224duplicate.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224final.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224getsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224gettag.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224init.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224messagedigest.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224pack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224unpack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha224update.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256_messagedigest.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256ca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256duplicate.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256final.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256getsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256gettag.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256init.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256messagedigest.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256pack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256unpack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha256update.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384duplicate.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384final.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384getsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384gettag.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384init.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384messagedigest.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384pack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384unpack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha384update.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512_init.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512_messagedigest.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512duplicate.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512final.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512getsize.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512gettag.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512init.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512messagedigest.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512pack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512unpack.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpsha512update.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpshsmgfca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcptrngenhwca.c
    ${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp/pcpver.c
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/epid-sdk/ext/ipp/include'
# Raw param [2] = '-Iexternal/epid-sdk/ext/ipp/sources/ippcp -Iexternal/epid-sdk/ext/ipp/sources/include'
# Raw param [3] = '-Iexternal/epid-sdk'
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
    "${ANDROID_ROOT}/external/epid-sdk/ext/ipp/include"
    "${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp -Iexternal/epid-sdk/ext/ipp/sources/include"
    "${ANDROID_ROOT}/external/epid-sdk"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/epid-sdk/ext/ipp/include/**/*.h"
    "${ANDROID_ROOT}/external/epid-sdk/ext/ipp/sources/ippcp -Iexternal/epid-sdk/ext/ipp/sources/include/**/*.h"
    "${ANDROID_ROOT}/external/epid-sdk/**/*.h"
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
# Raw param [2] = '-Wno-missing-braces'
# Raw param [3] = '-Wno-unknown-pragmas'
# Raw param [4] = '-Wno-typedef-redefinition'
# Raw param [5] = '-Wno-missing-field-initializers'
# Raw param [6] = '-Wno-for-loop-analysis'
# Raw param [7] = '-Wno-unused-const-variable'
# Raw param [8] = '-Wno-null-pointer-arithmetic'
# Raw param [9] = '-fexceptions'
# Raw param [10] = '-fPIC'
# Raw param [11] = '-O2'
# Raw param [12] = '-D_IPP_DEBUG'
# Raw param [13] = '-D_IPP_C99'
# Raw param [14] = '-D_IPP_v50_'
# Raw param [15] = '-D_PX'
# Raw param [16] = '-D_DISABLE_ECP_SM2_'
# Raw param [17] = '-D_DISABLE_ALG_SHA224_'
# Raw param [18] = '-D_DISABLE_ALG_SHA512_224_'
# Raw param [19] = '-D_DISABLE_ALG_MD5_'
# Raw param [20] = '-D_DISABLE_ALG_SM3_'
# Raw param [21] = '-Wno-unused-function'
# Raw param [22] = '-Wno-date-time'
# Raw param [23] = ''-Wno-#pragma-messages''
# Raw param [24] = '-target aarch64-linux-android'
# Raw param [25] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [26] = '-fPIC'
# Raw param [27] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-missing-braces' became -Wno-missing-braces
# FLAG '-Wno-unknown-pragmas' became -Wno-unknown-pragmas
# FLAG '-Wno-typedef-redefinition' became -Wno-typedef-redefinition
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-for-loop-analysis' became -Wno-for-loop-analysis
# FLAG '-Wno-unused-const-variable' became -Wno-unused-const-variable
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-fexceptions' became -fexceptions
# FLAG '-fPIC' became -fPIC
# FLAG '-O2' became -O2
# FLAG '-D_IPP_DEBUG' became -D_IPP_DEBUG
# FLAG '-D_IPP_C99' became -D_IPP_C99
# FLAG '-D_IPP_v50_' became -D_IPP_v50_
# FLAG '-D_PX' became -D_PX
# FLAG '-D_DISABLE_ECP_SM2_' became -D_DISABLE_ECP_SM2_
# FLAG '-D_DISABLE_ALG_SHA224_' became -D_DISABLE_ALG_SHA224_
# FLAG '-D_DISABLE_ALG_SHA512_224_' became -D_DISABLE_ALG_SHA512_224_
# FLAG '-D_DISABLE_ALG_MD5_' became -D_DISABLE_ALG_MD5_
# FLAG '-D_DISABLE_ALG_SM3_' became -D_DISABLE_ALG_SM3_
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-date-time' became -Wno-date-time
# FLAG ''-Wno-#pragma-messages'' became -Wno-#pragma-messages
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-braces")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unknown-pragmas")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-typedef-redefinition")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-for-loop-analysis")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-const-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fexceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_IPP_DEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_IPP_C99")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_IPP_v50_")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_PX")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_DISABLE_ECP_SM2_")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_DISABLE_ALG_SHA224_")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_DISABLE_ALG_SHA512_224_")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_DISABLE_ALG_MD5_")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_DISABLE_ALG_SM3_")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-date-time")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-#pragma-messages")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-braces")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unknown-pragmas")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-typedef-redefinition")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-for-loop-analysis")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-const-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_IPP_DEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_IPP_C99")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_IPP_v50_")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_PX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_DISABLE_ECP_SM2_")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_DISABLE_ALG_SHA224_")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_DISABLE_ALG_SHA512_224_")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_DISABLE_ALG_MD5_")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_DISABLE_ALG_SM3_")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-date-time")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-#pragma-messages")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
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


add_executable(libippcp ${SOURCE_FILES})
