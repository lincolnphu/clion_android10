# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libicuuc)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/appendable.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bmpset.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/brkeng.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytesinkutil.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestream.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestriebuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/bytestrieiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/caniter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/characterproperties.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/chariter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/charstr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cmemory.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cstr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cstring.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/cwchar.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/dictbe.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/dictionarydata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/dtintrv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/edits.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/errorcode.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/filteredbrk.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/filterednormalizer2.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/icudataver.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/icuplug.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/loadednormalizer2impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locavailable.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locbased.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locdispnames.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locdspnm.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locid.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/loclikely.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locmap.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locresdata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/locutil.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/messagepattern.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/normalizer2.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/normalizer2impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/normlzr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/parsepos.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/patternprops.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/pluralmap.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/propname.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/propsvec.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/punycode.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/putil.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbi.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbi_cache.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbidata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbinode.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbirb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbiscan.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbisetb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbistbl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/rbbitblb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/resbund.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/resbund_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/resource.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ruleiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/schriter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/serv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servlk.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servlkf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servls.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servnotf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servrbf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/servslkf.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/sharedobject.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/simpleformatter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/static_unicode_sets.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/stringpiece.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/stringtriebuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uarrsort.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidi.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidi_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidiln.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubiditransform.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubidiwrt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ubrk.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucase.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucasemap.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucasemap_titlecase_brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucat.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uchar.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucharstrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucharstriebuilder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucharstrieiterator.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uchriter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucln_cmn.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucmndata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv2022.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_bld.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_cb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_ct.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_err.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_ext.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_io.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_lmb.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_set.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u16.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u32.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u7.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnv_u8.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvbocu.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvdisp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvhz.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvisci.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvlat1.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvmbcs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvscsu.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucnvsel.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucol_swp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucptrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ucurr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/udata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/udatamem.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/udataswp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uenum.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uhash.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uhash_us.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uidna.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uinit.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uinvchar.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ulist.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uloc.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uloc_keytype.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uloc_tag.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/umapfile.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/umath.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/umutablecptrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/umutex.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unames.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unifiedcache.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unifilt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unifunct.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uniset.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uniset_closure.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uniset_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unisetspan.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_case.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_case_locale.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unistr_titlecase_brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unorm.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/unormcmp.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uobject.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uprops.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ures_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uresbund.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uresdata.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/usc_impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uscript.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uscript_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uset.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uset_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/usetiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ushape.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/usprep.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustack.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustr_cnv.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustr_titlecase_brkiter.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustr_wcs.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrcase.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrcase_locale.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrenum.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrfmt.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustring.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/ustrtrns.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utext.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utf_impl.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/util.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/util_props.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrace.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrie.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrie2.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrie2_builder.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utrie_swap.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uts46.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/utypes.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uvector.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uvectr32.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/uvectr64.cpp
    ${ANDROID_ROOT}/external/icu/icu4c/source/common/wintz.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/icu/icu4c/source/common'
# Raw param [2] = '${config.ArmClangThumbCflags}'
# Raw param [3] = '${config.ArmClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [7] = '-Iexternal/icu/icu4c/source/common'
# Raw param [8] = '-Iexternal/icu/android_icu4c/include'
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
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
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
# Raw param [0] = '-D_REENTRANT'
# Raw param [1] = '-DU_COMMON_IMPLEMENTATION'
# Raw param [2] = '-O3'
# Raw param [3] = '-fvisibility=hidden'
# Raw param [4] = '-Wall'
# Raw param [5] = '-Werror'
# Raw param [6] = '-Wno-unused-parameter'
# Raw param [7] = '-Wno-missing-field-initializers'
# Raw param [8] = '-Wno-sign-compare'
# Raw param [9] = '-Wno-deprecated-declarations'
# Raw param [10] = '-DANDROID_LINK_SHARED_ICU4C'
# Raw param [11] = '-DPIC'
# Raw param [12] = '-fPIC'
# Raw param [13] = '-target armv7a-linux-androideabi'
# Raw param [14] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [15] = '-fPIC'
# Raw param [16] = '-D_USING_LIBCXX'
# FLAG '-D_REENTRANT' became -D_REENTRANT
# FLAG '-DU_COMMON_IMPLEMENTATION' became -DU_COMMON_IMPLEMENTATION
# FLAG '-O3' became -O3
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-DANDROID_LINK_SHARED_ICU4C' became -DANDROID_LINK_SHARED_ICU4C
# FLAG '-DPIC' became -DPIC
# FLAG '-fPIC' became -fPIC
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_REENTRANT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DU_COMMON_IMPLEMENTATION")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_LINK_SHARED_ICU4C")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_REENTRANT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DU_COMMON_IMPLEMENTATION")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_LINK_SHARED_ICU4C")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
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
# Raw param [3] = '-std=c++11'
# Raw param [4] = '-frtti'
# Raw param [5] = '${config.ArmClangCppflags}'
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
# FLAG '-std=c++11' became -std=c++11
# FLAG '-frtti' became -frtti
# variable ${config.ArmClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -frtti")

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


add_executable(libicuuc ${SOURCE_FILES})
