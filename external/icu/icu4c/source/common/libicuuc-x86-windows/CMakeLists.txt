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
# Raw param [2] = ''
# Raw param [3] = '${config.WindowsClangCflags} ${config.WindowsX86ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/icu/icu4c/source/common'
# Raw param [8] = '-Iexternal/icu/android_icu4c/include'
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
# variable ${config.WindowsClangCflags} ${config.WindowsX86ClangCflags} = '-DUSE_MINGW -DWIN32_LEAN_AND_MEAN -Wno-unused-parameter -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS -D__USE_MINGW_ANSI_STDIO=1 -D_WIN32_WINNT=0x0601 -DWINVER=0x0601 -D_FILE_OFFSET_BITS=64 --sysroot prebuilts/gcc/linux-x86/host/x86_64-w64-mingw32-4.8/x86_64-w64-mingw32 -m32'
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
# Raw param [11] = '-m32'
# FLAG '-DUSE_MINGW' became -DUSE_MINGW
# FLAG '-DWIN32_LEAN_AND_MEAN' became -DWIN32_LEAN_AND_MEAN
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__USE_MINGW_ANSI_STDIO=1' became -D__USE_MINGW_ANSI_STDIO=1
# FLAG '-D_WIN32_WINNT=0x0601' became -D_WIN32_WINNT=0x0601
# FLAG '-DWINVER=0x0601' became -DWINVER=0x0601
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-m32' became -m32
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
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
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
# Raw param [10] = '-target i686-windows-gnu'
# Raw param [11] = '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin'
# Raw param [12] = '-D_USING_LIBCXX'
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
# FLAG '-target i686-windows-gnu' became -target i686-windows-gnu
# FLAG '-B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin' became -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-windows-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-windows-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.WindowsGccRoot}/${config.WindowsGccTriple}/bin")
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
# Raw param [3] = '-std=c++11'
# Raw param [4] = '${config.WindowsClangCppflags} ${config.WindowsX86ClangCppflags}'
# Raw param [5] = '-nostdinc++'
# Raw param [6] = '-fsjlj-exceptions'
# Raw param [7] = '-D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS'
# Raw param [8] = '-D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS'
# Raw param [9] = '-D_LIBCPP_HAS_THREAD_API_WIN32'
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
# FLAG '-std=c++11' became -std=c++11
# variable ${config.WindowsClangCppflags} ${config.WindowsX86ClangCppflags} = ' '
# Raw param [0] = ''
# Raw param [1] = ''
# FLAG '-nostdinc++' became -nostdinc++
# FLAG '-fsjlj-exceptions' became -fsjlj-exceptions
# FLAG '-D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS' became -D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS
# FLAG '-D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS' became -D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS
# FLAG '-D_LIBCPP_HAS_THREAD_API_WIN32' became -D_LIBCPP_HAS_THREAD_API_WIN32
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -nostdinc++")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fsjlj-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_DISABLE_VISIBILITY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCXXABI_DISABLE_VISIBILITY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_HAS_THREAD_API_WIN32")

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


add_executable(libicuuc ${SOURCE_FILES})
