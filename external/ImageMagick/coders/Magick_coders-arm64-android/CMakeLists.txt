# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(Magick_coders)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/ImageMagick/coders/aai.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/art.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/avs.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/bgr.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/bmp.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/braille.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/cals.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/caption.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/cin.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/cip.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/clip.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/clipboard.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/cmyk.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/cube.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/cut.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/dcm.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/dds.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/debug.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/dib.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/djvu.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/dng.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/dot.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/dps.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/dpx.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/emf.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/ept.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/exr.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/fax.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/fits.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/flif.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/fpx.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/gif.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/gradient.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/gray.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/hald.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/hdr.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/heic.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/histogram.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/hrz.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/html.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/icon.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/info.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/inline.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/ipl.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/jbig.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/jnx.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/jp2.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/jpeg.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/json.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/label.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mac.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/magick.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/map.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mask.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mat.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/matte.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/meta.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/miff.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mono.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mpc.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mpeg.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mpr.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/msl.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mtv.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/mvg.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/null.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/otb.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/palm.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pango.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pattern.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pcd.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pcl.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pcx.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pdb.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pdf.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pes.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pgx.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pict.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pix.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/plasma.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/png.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pnm.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/ps.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/ps2.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/ps3.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/psd.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/pwp.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/raw.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/rgb.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/rgf.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/rla.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/rle.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/scr.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/screenshot.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/sct.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/sfw.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/sgi.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/sixel.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/stegano.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/sun.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/svg.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/tga.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/thumbnail.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/tile.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/tim.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/ttf.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/txt.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/uil.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/url.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/uyvy.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/vicar.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/vid.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/viff.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/vips.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/wbmp.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/webp.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/wmf.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/wpg.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/x.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/xbm.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/xc.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/xcf.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/xpm.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/xps.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/xtrn.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/xwd.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/ycbcr.c
    ${ANDROID_ROOT}/external/ImageMagick/coders/yuv.c
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/ImageMagick/coders'
# Raw param [2] = '-D__ANDROID_API__=24'
# Raw param [3] = ''
# Raw param [4] = '${config.Arm64ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [8] = '-Iexternal/ImageMagick'
# Raw param [9] = '-Iexternal/ImageMagick/configs/arm64'
# Raw param [10] = '-Iexternal/libjpeg-turbo'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# FLAG '-D__ANDROID_API__=24' became -D__ANDROID_API__=24
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
include_directories( 
    "${ANDROID_ROOT}/external/ImageMagick/coders"
    "${ANDROID_ROOT}/external/ImageMagick"
    "${ANDROID_ROOT}/external/ImageMagick/configs/arm64"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/ImageMagick/coders/**/*.h"
    "${ANDROID_ROOT}/external/ImageMagick/**/*.h"
    "${ANDROID_ROOT}/external/ImageMagick/configs/arm64/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_API__=24")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_API__=24")
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

# CFLAGS:
# Raw param [0] = '-DHAVE_CONFIG_H'
# Raw param [1] = '-Wall'
# Raw param [2] = '-Werror'
# Raw param [3] = '-Wno-for-loop-analysis'
# Raw param [4] = '-Wno-sign-compare'
# Raw param [5] = '-Wno-unused-function'
# Raw param [6] = '-Wno-unused-parameter'
# Raw param [7] = '-target aarch64-linux-android'
# Raw param [8] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [9] = '-fPIC'
# Raw param [10] = '-isystem prebuilts/ndk/current/sources/cxx-stl/system/include'
# FLAG '-DHAVE_CONFIG_H' became -DHAVE_CONFIG_H
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-for-loop-analysis' became -Wno-for-loop-analysis
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# Found a header search path marker with no pathset(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DHAVE_CONFIG_H")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-for-loop-analysis")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DHAVE_CONFIG_H")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-for-loop-analysis")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")

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
# Raw param [0] = '-isystem out/soong/ndk/sysroot/usr/include'
# Raw param [1] = '-isystem out/soong/ndk/sysroot/usr/include/aarch64-linux-android'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/-isystem out/soong/ndk/sysroot/usr/include/aarch64-linux-android"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/-isystem out/soong/ndk/sysroot/usr/include/aarch64-linux-android/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})


add_executable(Magick_coders ${SOURCE_FILES})
