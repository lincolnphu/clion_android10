# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libtextclassifier)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/libtextclassifier/actions/actions-suggestions.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/actions_jni.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/feature-processor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/lua-actions.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/lua-ranker.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/lua-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/ngram-model.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/ranker.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/test_utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/actions/zlib-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/annotator.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/annotator_jni.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/annotator_jni_common.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/cached-features.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/feature-processor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/model-executor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/quantization.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/strip-unpaired-brackets.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/types.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/zlib-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/datetime/extractor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/datetime/parser.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/duration/duration.cc
    ${ANDROID_ROOT}/external/libtextclassifier/annotator/number/number.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/custom-tokenizer.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/lang-id.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/lang-id_jni.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/embedding-feature-extractor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/embedding-network-params.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/embedding-network.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/utf8.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/fel/feature-descriptors.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/fel/feature-extractor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/fel/fel-parser.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/fel/task-context.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/fel/workspace.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/file/file-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/file/mmap.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/flatbuffers/embedding-network-params-from-flatbuffer.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/flatbuffers/model-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/lite_base/compact-logging-raw.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/lite_base/compact-logging.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/lite_strings/numbers.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/lite_strings/str-split.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/math/checksum.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/math/fastexp.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/math/hash.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/common/math/softmax.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/fb_model/lang-id-from-fb.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/fb_model/model-provider-from-fb.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/features/char-ngram-feature.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/features/light-sentence-features.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/features/relevant-script-feature.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/script/approx-script-data.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/script/approx-script.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/script/script-detector.cc
    ${ANDROID_ROOT}/external/libtextclassifier/lang_id/script/tiny-script-detector.cc
    ${ANDROID_ROOT}/external/libtextclassifier/util/hash/hash.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/checksum.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/codepoint-range.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/flatbuffers.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/lua-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/regex-match.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/resources.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/tensor-view.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/test-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/tflite-model-executor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/token-feature-extractor.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/tokenizer.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/base/logging.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/base/logging_raw.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/calendar/calendar-javaicu.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/hash/farmhash.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/i18n/locale.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/intents/intent-generator.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/intents/jni.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/intents/zlib-utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/java/jni-base.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/java/jni-cache.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/java/string_utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/math/fastexp.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/math/softmax.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/memory/mmap.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/sentencepiece/double_array_trie.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/sentencepiece/encoder.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/sentencepiece/normalizer.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/sentencepiece/sorted_strings_table.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/sentencepiece/test_utils.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/strings/numbers.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/strings/split.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/strings/substitute.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/strings/utf8.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/tflite/dist_diversification.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/tflite/encoder_common.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/tflite/text_encoder.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/tflite/token_encoder.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/utf8/unicodetext.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/utf8/unilib-javaicu.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/zlib/zlib.cc
    ${ANDROID_ROOT}/external/libtextclassifier/utils/zlib/zlib_regex.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/libtextclassifier'
# Raw param [2] = ''
# Raw param [3] = '${config.Arm64ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [7] = '-Iexternal/tensorflow'
# Raw param [8] = '-Iexternal/flatbuffers/include'
# Raw param [9] = '-Iexternal/lua/src'
# Raw param [10] = '-Iexternal/libutf'
# Raw param [11] = '-Isystem/core/liblog/include'
# Raw param [12] = '-Iexternal/zlib'
# Raw param [13] = '-Iexternal/libcxx/include'
# Raw param [14] = '-Iexternal/libcxxabi/include'
# Raw param [15] = '-Ibionic/libc/include'
# Raw param [16] = '-D__LIBC_API__=10000'
# Raw param [17] = '-D__LIBM_API__=10000'
# Raw param [18] = '-D__LIBDL_API__=10000'
# Raw param [19] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_flatbuffers/gen'
# Raw param [20] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_tokenizer/gen'
# Raw param [21] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_codepoint_range/gen'
# Raw param [22] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_entity-data/gen'
# Raw param [23] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_zlib_buffer/gen'
# Raw param [24] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_resources_extra/gen'
# Raw param [25] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_intent_config/gen'
# Raw param [26] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_annotator_model/gen'
# Raw param [27] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_actions_model/gen'
# Raw param [28] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_tflite_text_encoder_config/gen'
# Raw param [29] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_lang_id_embedded_network/gen'
# Raw param [30] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_lang_id_model/gen'
# Raw param [31] = '-Iout/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_actions-entity-data/gen'
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
    "${ANDROID_ROOT}/external/libtextclassifier"
    "${ANDROID_ROOT}/external/tensorflow"
    "${ANDROID_ROOT}/external/flatbuffers/include"
    "${ANDROID_ROOT}/external/lua/src"
    "${ANDROID_ROOT}/external/libutf"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_flatbuffers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_tokenizer/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_codepoint_range/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_entity-data/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_zlib_buffer/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_resources_extra/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_intent_config/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_annotator_model/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_actions_model/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_tflite_text_encoder_config/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_lang_id_embedded_network/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_lang_id_model/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_actions-entity-data/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/libtextclassifier/**/*.h"
    "${ANDROID_ROOT}/external/tensorflow/**/*.h"
    "${ANDROID_ROOT}/external/flatbuffers/include/**/*.h"
    "${ANDROID_ROOT}/external/lua/src/**/*.h"
    "${ANDROID_ROOT}/external/libutf/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_flatbuffers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_tokenizer/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_codepoint_range/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_entity-data/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_zlib_buffer/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_resources_extra/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_intent_config/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_annotator_model/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_actions_model/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_tflite_text_encoder_config/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_lang_id_embedded_network/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_lang_id_model/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/libtextclassifier/libtextclassifier_fbgen_actions-entity-data/gen/**/*.h"
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
# Raw param [2] = '-Wno-deprecated-declarations'
# Raw param [3] = '-Wno-ignored-qualifiers'
# Raw param [4] = '-Wno-missing-field-initializers'
# Raw param [5] = '-Wno-sign-compare'
# Raw param [6] = '-Wno-tautological-constant-out-of-range-compare'
# Raw param [7] = '-Wno-undefined-var-template'
# Raw param [8] = '-Wno-unused-function'
# Raw param [9] = '-Wno-unused-parameter'
# Raw param [10] = '-Wno-extern-c-compat'
# Raw param [11] = '-funsigned-char'
# Raw param [12] = '-fvisibility=hidden'
# Raw param [13] = '-DLIBTEXTCLASSIFIER_UNILIB_ICU'
# Raw param [14] = '-DZLIB_CONST'
# Raw param [15] = '-DSAFTM_COMPACT_LOGGING'
# Raw param [16] = '-DTC3_WITH_ACTIONS_OPS'
# Raw param [17] = '-DTC3_UNILIB_JAVAICU'
# Raw param [18] = '-DTC3_CALENDAR_JAVAICU'
# Raw param [19] = '-DTC3_AOSP'
# Raw param [20] = '-DTC_DEBUG_LOGGING=1'
# Raw param [21] = '-target aarch64-linux-android'
# Raw param [22] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [23] = '-fPIC'
# Raw param [24] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-Wno-ignored-qualifiers' became -Wno-ignored-qualifiers
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-tautological-constant-out-of-range-compare' became -Wno-tautological-constant-out-of-range-compare
# FLAG '-Wno-undefined-var-template' became -Wno-undefined-var-template
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-extern-c-compat' became -Wno-extern-c-compat
# FLAG '-funsigned-char' became -funsigned-char
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-DLIBTEXTCLASSIFIER_UNILIB_ICU' became -DLIBTEXTCLASSIFIER_UNILIB_ICU
# FLAG '-DZLIB_CONST' became -DZLIB_CONST
# FLAG '-DSAFTM_COMPACT_LOGGING' became -DSAFTM_COMPACT_LOGGING
# FLAG '-DTC3_WITH_ACTIONS_OPS' became -DTC3_WITH_ACTIONS_OPS
# FLAG '-DTC3_UNILIB_JAVAICU' became -DTC3_UNILIB_JAVAICU
# FLAG '-DTC3_CALENDAR_JAVAICU' became -DTC3_CALENDAR_JAVAICU
# FLAG '-DTC3_AOSP' became -DTC3_AOSP
# FLAG '-DTC_DEBUG_LOGGING=1' became -DTC_DEBUG_LOGGING=1
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-tautological-constant-out-of-range-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-undefined-var-template")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-extern-c-compat")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -funsigned-char")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLIBTEXTCLASSIFIER_UNILIB_ICU")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DZLIB_CONST")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSAFTM_COMPACT_LOGGING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DTC3_WITH_ACTIONS_OPS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DTC3_UNILIB_JAVAICU")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DTC3_CALENDAR_JAVAICU")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DTC3_AOSP")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DTC_DEBUG_LOGGING=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-tautological-constant-out-of-range-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-undefined-var-template")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-extern-c-compat")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -funsigned-char")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLIBTEXTCLASSIFIER_UNILIB_ICU")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DZLIB_CONST")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSAFTM_COMPACT_LOGGING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTC3_WITH_ACTIONS_OPS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTC3_UNILIB_JAVAICU")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTC3_CALENDAR_JAVAICU")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTC3_AOSP")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DTC_DEBUG_LOGGING=1")
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


add_executable(libtextclassifier ${SOURCE_FILES})
