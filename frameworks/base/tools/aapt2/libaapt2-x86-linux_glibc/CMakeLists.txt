# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libaapt2)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/IdAssigner.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/InlineXmlFormatParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/NinePatch.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/Png.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/PngChunkFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/PngCrunch.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/PseudolocaleGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/Pseudolocalizer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/compile/XmlIdCollector.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/configuration/ConfigurationParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/dump/DumpManifest.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/filter/AbiFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/filter/ConfigFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/Archive.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/Container.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/binary/BinaryResourceParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/binary/ResChunkPullParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/binary/TableFlattener.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/binary/XmlFlattener.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/proto/ProtoDeserialize.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/format/proto/ProtoSerialize.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/BigBufferStream.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/File.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/FileStream.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/FileSystem.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/StringStream.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/Util.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/io/ZipArchive.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/AutoVersioner.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ManifestFixer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/NoDefaultResourceRemover.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ProductFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/PrivateAttributeMover.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ReferenceLinker.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/ResourceExcluder.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/TableMerger.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlCompatVersioner.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlNamespaceRemover.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/link/XmlReferenceLinker.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/MultiApkGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/ResourceDeduper.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/ResourceFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/ResourcePathShortener.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/optimize/VersionCollapser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/process/SymbolTable.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/split/TableSplitter.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/text/Printer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/text/Unicode.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/text/Utf8Iterator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/BigBuffer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/Files.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/util/Util.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Debug.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/DominatorTree.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/AnnotationProcessor.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ClassDefinition.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/JavaClassGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ManifestClassGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/java/ProguardRules.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/LoadedApk.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/Resource.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceTable.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceUtils.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/ResourceValues.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/SdkConstants.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/StringPool.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/trace/TraceBuffer.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlActionExecutor.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlDom.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlPullParser.cpp
    ${ANDROID_ROOT}/frameworks/base/tools/aapt2/xml/XmlUtil.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto/frameworks/base/tools/aapt2/Configuration.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto/frameworks/base/tools/aapt2/Resources.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto/frameworks/base/tools/aapt2/ResourcesInternal.pb.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/base/tools/aapt2'
# Raw param [1] = ''
# Raw param [2] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [3] = '${config.CommonClangGlobalCflags}'
# Raw param [4] = '${config.HostClangGlobalCflags}'
# Raw param [5] = ''
# Raw param [6] = '-Iout/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto/frameworks/base/tools/aapt2'
# Raw param [7] = '-Iout/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto'
# Raw param [8] = '-Iframeworks/base/libs/androidfw/include'
# Raw param [9] = '-Iexternal/zlib'
# Raw param [10] = '-Isystem/core/libutils/include'
# Raw param [11] = '-Isystem/core/liblog/include'
# Raw param [12] = '-Isystem/core/libsystem/include'
# Raw param [13] = '-Isystem/core/libcutils/include'
# Raw param [14] = '-Isystem/core/libprocessgroup/include'
# Raw param [15] = '-Iexternal/expat/lib'
# Raw param [16] = '-Isystem/core/libziparchive/include'
# Raw param [17] = '-Isystem/core/base/include'
# Raw param [18] = '-Iexternal/libpng'
# Raw param [19] = '-Iexternal/protobuf/src'
# Raw param [20] = '-Ibuild/soong/cc/libbuildversion/include'
# Raw param [21] = '-Iexternal/libcxx/include'
# Raw param [22] = '-Iexternal/libcxxabi/include'
# variable ${config.LinuxClangCflags} ${config.LinuxX86ClangCflags} = '-Wa,--noexecstack -fPIC -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8/sysroot -fstack-protector-strong -msse3 -m32 -march=prescott -D_FILE_OFFSET_BITS=64 -D_LARGEFILE_SOURCE=1'
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
# Raw param [11] = '-msse3'
# Raw param [12] = '-m32'
# Raw param [13] = '-march=prescott'
# Raw param [14] = '-D_FILE_OFFSET_BITS=64'
# Raw param [15] = '-D_LARGEFILE_SOURCE=1'
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-fPIC' became -fPIC
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '--gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8' became --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-msse3' became -msse3
# FLAG '-m32' became -m32
# FLAG '-march=prescott' became -march=prescott
# FLAG '-D_FILE_OFFSET_BITS=64' became -D_FILE_OFFSET_BITS=64
# FLAG '-D_LARGEFILE_SOURCE=1' became -D_LARGEFILE_SOURCE=1
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
    "${ANDROID_ROOT}/frameworks/base/tools/aapt2"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto/frameworks/base/tools/aapt2"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/system/core/libziparchive/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/build/soong/cc/libbuildversion/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/base/tools/aapt2/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto/frameworks/base/tools/aapt2/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/aapt2/libaapt2/linux_glibc_x86_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/system/core/libziparchive/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/build/soong/cc/libbuildversion/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wa,--noexecstack")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fstack-protector-strong")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msse3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m32")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -march=prescott")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_LARGEFILE_SOURCE=1")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wa,--noexecstack")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fstack-protector-strong")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msse3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m32")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -march=prescott")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FILE_OFFSET_BITS=64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LARGEFILE_SOURCE=1")
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-unused-parameter'
# Raw param [3] = '-target i686-linux-gnu'
# Raw param [4] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [5] = '-DANDROID_STRICT'
# Raw param [6] = '-DGOOGLE_PROTOBUF_NO_RTTI'
# Raw param [7] = '-fPIC'
# Raw param [8] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-DGOOGLE_PROTOBUF_NO_RTTI' became -DGOOGLE_PROTOBUF_NO_RTTI
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
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
# Raw param [3] = '-Wno-missing-field-initializers'
# Raw param [4] = '-fno-exceptions'
# Raw param [5] = '-fno-rtti'
# Raw param [6] = ''
# Raw param [7] = '-nostdinc++'
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
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-fno-rtti' became -fno-rtti
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
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


add_executable(libaapt2 ${SOURCE_FILES})
