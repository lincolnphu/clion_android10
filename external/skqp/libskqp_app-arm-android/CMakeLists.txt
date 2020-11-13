# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libskqp_app)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/skqp/third_party/vulkanmemoryallocator/GrVulkanMemoryAllocator.cpp
    ${ANDROID_ROOT}/external/skqp/dm/DMGpuTestProcs.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGAttribute.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGAttributeParser.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGCircle.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGClipPath.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGContainer.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGDOM.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGEllipse.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGGradient.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGLine.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGLinearGradient.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGNode.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGPath.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGPattern.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGPoly.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGRadialGradient.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGRect.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGRenderContext.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGSVG.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGShape.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGStop.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGTransformableNode.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGUse.cpp
    ${ANDROID_ROOT}/external/skqp/experimental/svg/model/SkSVGValue.cpp
    ${ANDROID_ROOT}/external/skqp/gm/3dgm.cpp
    ${ANDROID_ROOT}/external/skqp/gm/OverStroke.cpp
    ${ANDROID_ROOT}/external/skqp/gm/aaa.cpp
    ${ANDROID_ROOT}/external/skqp/gm/aaclip.cpp
    ${ANDROID_ROOT}/external/skqp/gm/aarectmodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/aaxfermodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/addarc.cpp
    ${ANDROID_ROOT}/external/skqp/gm/all_bitmap_configs.cpp
    ${ANDROID_ROOT}/external/skqp/gm/alpha_image.cpp
    ${ANDROID_ROOT}/external/skqp/gm/alphagradients.cpp
    ${ANDROID_ROOT}/external/skqp/gm/analytic_gradients.cpp
    ${ANDROID_ROOT}/external/skqp/gm/androidblendmodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/animatedGif.cpp
    ${ANDROID_ROOT}/external/skqp/gm/animatedimageblurs.cpp
    ${ANDROID_ROOT}/external/skqp/gm/anisotropic.cpp
    ${ANDROID_ROOT}/external/skqp/gm/annotated_text.cpp
    ${ANDROID_ROOT}/external/skqp/gm/arcofzorro.cpp
    ${ANDROID_ROOT}/external/skqp/gm/arcto.cpp
    ${ANDROID_ROOT}/external/skqp/gm/arithmode.cpp
    ${ANDROID_ROOT}/external/skqp/gm/atlastext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/b_119394958.cpp
    ${ANDROID_ROOT}/external/skqp/gm/badpaint.cpp
    ${ANDROID_ROOT}/external/skqp/gm/beziereffects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/beziers.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bigblurs.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bigmatrix.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bigrect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bigrrectaaeffect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bigtext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bigtileimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmapcopy.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmapfilters.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmapimage.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmappremul.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmaprect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmaprecttest.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmapshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bitmaptiled.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bleed.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blend.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurcircles.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurcircles2.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurignorexform.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurimagevmask.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurpositioning.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurquickreject.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurrect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurredclippedcircle.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurroundrect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurs.cpp
    ${ANDROID_ROOT}/external/skqp/gm/blurtextsmallradii.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bmpfilterqualityrepeat.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bug5252.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bug530095.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bug615686.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bug6643.cpp
    ${ANDROID_ROOT}/external/skqp/gm/bug6783.cpp
    ${ANDROID_ROOT}/external/skqp/gm/cgm.c
    ${ANDROID_ROOT}/external/skqp/gm/cgms.cpp
    ${ANDROID_ROOT}/external/skqp/gm/circle_sizes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/circles.cpp
    ${ANDROID_ROOT}/external/skqp/gm/circulararcs.cpp
    ${ANDROID_ROOT}/external/skqp/gm/circularclips.cpp
    ${ANDROID_ROOT}/external/skqp/gm/clip_error.cpp
    ${ANDROID_ROOT}/external/skqp/gm/clip_strokerect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/clipdrawdraw.cpp
    ${ANDROID_ROOT}/external/skqp/gm/clippedbitmapshaders.cpp
    ${ANDROID_ROOT}/external/skqp/gm/clockwise.cpp
    ${ANDROID_ROOT}/external/skqp/gm/color4f.cpp
    ${ANDROID_ROOT}/external/skqp/gm/coloremoji.cpp
    ${ANDROID_ROOT}/external/skqp/gm/coloremoji_blendmodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/colorfilteralpha8.cpp
    ${ANDROID_ROOT}/external/skqp/gm/colorfilterimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/colorfilters.cpp
    ${ANDROID_ROOT}/external/skqp/gm/colormatrix.cpp
    ${ANDROID_ROOT}/external/skqp/gm/colorwheel.cpp
    ${ANDROID_ROOT}/external/skqp/gm/complexclip.cpp
    ${ANDROID_ROOT}/external/skqp/gm/complexclip2.cpp
    ${ANDROID_ROOT}/external/skqp/gm/complexclip3.cpp
    ${ANDROID_ROOT}/external/skqp/gm/complexclip4.cpp
    ${ANDROID_ROOT}/external/skqp/gm/complexclip_blur_tiled.cpp
    ${ANDROID_ROOT}/external/skqp/gm/composeshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/concavepaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/conicpaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/constcolorprocessor.cpp
    ${ANDROID_ROOT}/external/skqp/gm/convex_all_line_paths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/convexpaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/convexpolyclip.cpp
    ${ANDROID_ROOT}/external/skqp/gm/convexpolyeffect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/copyTo4444.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_691386.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_788500.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_847759.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_884166.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_887103.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_892988.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_899512.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_905548.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crbug_918512.cpp
    ${ANDROID_ROOT}/external/skqp/gm/croppedrects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/crosscontextimage.cpp
    ${ANDROID_ROOT}/external/skqp/gm/cubicpaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/daa.cpp
    ${ANDROID_ROOT}/external/skqp/gm/dashcircle.cpp
    ${ANDROID_ROOT}/external/skqp/gm/dashcubics.cpp
    ${ANDROID_ROOT}/external/skqp/gm/dashing.cpp
    ${ANDROID_ROOT}/external/skqp/gm/degeneratesegments.cpp
    ${ANDROID_ROOT}/external/skqp/gm/dftext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/dftext_blob_persp.cpp
    ${ANDROID_ROOT}/external/skqp/gm/discard.cpp
    ${ANDROID_ROOT}/external/skqp/gm/displacement.cpp
    ${ANDROID_ROOT}/external/skqp/gm/distantclip.cpp
    ${ANDROID_ROOT}/external/skqp/gm/downsamplebitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/draw_bitmap_rect_skbug4374.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawable.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawatlas.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawatlascolor.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawbitmaprect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawimageset.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawlooper.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawminibitmaprect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawquadset.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawregion.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drawregionmodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/dropshadowimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drrect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/drrect_small_inner.cpp
    ${ANDROID_ROOT}/external/skqp/gm/dstreadshuffle.cpp
    ${ANDROID_ROOT}/external/skqp/gm/emboss.cpp
    ${ANDROID_ROOT}/external/skqp/gm/emptypath.cpp
    ${ANDROID_ROOT}/external/skqp/gm/encode-alpha-jpeg.cpp
    ${ANDROID_ROOT}/external/skqp/gm/encode-platform.cpp
    ${ANDROID_ROOT}/external/skqp/gm/encode-srgb.cpp
    ${ANDROID_ROOT}/external/skqp/gm/encode.cpp
    ${ANDROID_ROOT}/external/skqp/gm/etc1.cpp
    ${ANDROID_ROOT}/external/skqp/gm/extractbitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fadefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fatpathfill.cpp
    ${ANDROID_ROOT}/external/skqp/gm/filltypes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/filltypespersp.cpp
    ${ANDROID_ROOT}/external/skqp/gm/filterbitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/filterbug.cpp
    ${ANDROID_ROOT}/external/skqp/gm/filterfastbounds.cpp
    ${ANDROID_ROOT}/external/skqp/gm/filterindiabox.cpp
    ${ANDROID_ROOT}/external/skqp/gm/flippity.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fontcache.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fontmgr.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fontregen.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fontscaler.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fontscalerdistortable.cpp
    ${ANDROID_ROOT}/external/skqp/gm/fwidth_squircle.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gamma.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gammatext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/getpostextpath.cpp
    ${ANDROID_ROOT}/external/skqp/gm/giantbitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/glyph_pos.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gm.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gradientDirtyLaundry.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gradient_matrix.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gradients.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gradients_2pt_conical.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gradients_degenerate.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gradients_no_texture.cpp
    ${ANDROID_ROOT}/external/skqp/gm/gradtext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/grayscalejpg.cpp
    ${ANDROID_ROOT}/external/skqp/gm/hairlines.cpp
    ${ANDROID_ROOT}/external/skqp/gm/hairmodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/hardstop_gradients.cpp
    ${ANDROID_ROOT}/external/skqp/gm/highcontrastfilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/hittestpath.cpp
    ${ANDROID_ROOT}/external/skqp/gm/hsl.cpp
    ${ANDROID_ROOT}/external/skqp/gm/hugepath.cpp
    ${ANDROID_ROOT}/external/skqp/gm/image.cpp
    ${ANDROID_ROOT}/external/skqp/gm/image_pict.cpp
    ${ANDROID_ROOT}/external/skqp/gm/image_shader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagealphathreshold.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imageblur.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imageblur2.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imageblurclampmode.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imageblurrepeatmode.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imageblurtiled.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefilters.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefiltersbase.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefiltersclipped.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefilterscropexpand.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefilterscropped.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefiltersgraph.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefiltersscaled.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefiltersstroked.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefilterstransformed.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagefromyuvtextures.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagemagnifier.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagemakewithfilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagemasksubset.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imageresizetiled.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagescalealigned.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagesource.cpp
    ${ANDROID_ROOT}/external/skqp/gm/imagesource2.cpp
    ${ANDROID_ROOT}/external/skqp/gm/internal_links.cpp
    ${ANDROID_ROOT}/external/skqp/gm/inversepaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/jpg_color_cube.cpp
    ${ANDROID_ROOT}/external/skqp/gm/largeglyphblur.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lattice.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lcdblendmodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lcdoverlap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lcdtext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lighting.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lightingshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lightingshader2.cpp
    ${ANDROID_ROOT}/external/skqp/gm/linepaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/localmatriximagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/localmatriximageshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/localmatrixshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/lumafilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/makeRasterImage.cpp
    ${ANDROID_ROOT}/external/skqp/gm/makecolorspace.cpp
    ${ANDROID_ROOT}/external/skqp/gm/mandoline.cpp
    ${ANDROID_ROOT}/external/skqp/gm/manypaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/matrixconvolution.cpp
    ${ANDROID_ROOT}/external/skqp/gm/matriximagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/megalooper.cpp
    ${ANDROID_ROOT}/external/skqp/gm/mipmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/mixedtextblobs.cpp
    ${ANDROID_ROOT}/external/skqp/gm/modecolorfilters.cpp
    ${ANDROID_ROOT}/external/skqp/gm/morphology.cpp
    ${ANDROID_ROOT}/external/skqp/gm/multipicturedraw.cpp
    ${ANDROID_ROOT}/external/skqp/gm/nested.cpp
    ${ANDROID_ROOT}/external/skqp/gm/ninepatchstretch.cpp
    ${ANDROID_ROOT}/external/skqp/gm/nonclosedpaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/offsetimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/orientation.cpp
    ${ANDROID_ROOT}/external/skqp/gm/ovals.cpp
    ${ANDROID_ROOT}/external/skqp/gm/overdrawcolorfilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/p3.cpp
    ${ANDROID_ROOT}/external/skqp/gm/patch.cpp
    ${ANDROID_ROOT}/external/skqp/gm/path_stroke_with_zero_length.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathcontourstart.cpp
    ${ANDROID_ROOT}/external/skqp/gm/patheffects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathfill.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathinterior.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathmaskcache.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathmeasure.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathopsinverse.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathopsskpclip.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pathreverse.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pdf_never_embed.cpp
    ${ANDROID_ROOT}/external/skqp/gm/perlinnoise.cpp
    ${ANDROID_ROOT}/external/skqp/gm/perspimages.cpp
    ${ANDROID_ROOT}/external/skqp/gm/perspshaders.cpp
    ${ANDROID_ROOT}/external/skqp/gm/picture.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pictureimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pictureimagegenerator.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pictureshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pictureshadercache.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pictureshadertile.cpp
    ${ANDROID_ROOT}/external/skqp/gm/pixelsnap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/plus.cpp
    ${ANDROID_ROOT}/external/skqp/gm/points.cpp
    ${ANDROID_ROOT}/external/skqp/gm/poly2poly.cpp
    ${ANDROID_ROOT}/external/skqp/gm/polygonoffset.cpp
    ${ANDROID_ROOT}/external/skqp/gm/polygons.cpp
    ${ANDROID_ROOT}/external/skqp/gm/quadpaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/radial_gradient_precision.cpp
    ${ANDROID_ROOT}/external/skqp/gm/readpixels.cpp
    ${ANDROID_ROOT}/external/skqp/gm/recordopts.cpp
    ${ANDROID_ROOT}/external/skqp/gm/rectangletexture.cpp
    ${ANDROID_ROOT}/external/skqp/gm/rects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/repeated_bitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/resizeimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/roundrects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/rrect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/rrectclipdrawpaint.cpp
    ${ANDROID_ROOT}/external/skqp/gm/rrects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/samplerstress.cpp
    ${ANDROID_ROOT}/external/skqp/gm/savelayer.cpp
    ${ANDROID_ROOT}/external/skqp/gm/scaledemoji.cpp
    ${ANDROID_ROOT}/external/skqp/gm/scaledemoji_rendering.cpp
    ${ANDROID_ROOT}/external/skqp/gm/scaledstrokes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/shadermaskfilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/shadertext3.cpp
    ${ANDROID_ROOT}/external/skqp/gm/shadows.cpp
    ${ANDROID_ROOT}/external/skqp/gm/shadowutils.cpp
    ${ANDROID_ROOT}/external/skqp/gm/shallowgradient.cpp
    ${ANDROID_ROOT}/external/skqp/gm/shapes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/shapes_as_paths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/sharedcorners.cpp
    ${ANDROID_ROOT}/external/skqp/gm/showmiplevels.cpp
    ${ANDROID_ROOT}/external/skqp/gm/simple_magnification.cpp
    ${ANDROID_ROOT}/external/skqp/gm/simpleaaclip.cpp
    ${ANDROID_ROOT}/external/skqp/gm/simplerect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/skbug1719.cpp
    ${ANDROID_ROOT}/external/skqp/gm/skbug_257.cpp
    ${ANDROID_ROOT}/external/skqp/gm/skbug_4868.cpp
    ${ANDROID_ROOT}/external/skqp/gm/skbug_5321.cpp
    ${ANDROID_ROOT}/external/skqp/gm/skbug_8664.cpp
    ${ANDROID_ROOT}/external/skqp/gm/skinning.cpp
    ${ANDROID_ROOT}/external/skqp/gm/smallarc.cpp
    ${ANDROID_ROOT}/external/skqp/gm/smallpaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/spritebitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/srcmode.cpp
    ${ANDROID_ROOT}/external/skqp/gm/srgb.cpp
    ${ANDROID_ROOT}/external/skqp/gm/stlouisarch.cpp
    ${ANDROID_ROOT}/external/skqp/gm/stringart.cpp
    ${ANDROID_ROOT}/external/skqp/gm/stroke_rect_shader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/strokedlines.cpp
    ${ANDROID_ROOT}/external/skqp/gm/strokefill.cpp
    ${ANDROID_ROOT}/external/skqp/gm/strokerect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/strokerects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/strokes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/stroketext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/subsetshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/surface.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tablecolorfilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tallstretchedbitmaps.cpp
    ${ANDROID_ROOT}/external/skqp/gm/testgradient.cpp
    ${ANDROID_ROOT}/external/skqp/gm/text_scale_skew.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblob.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobblockreordering.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobcolortrans.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobgeometrychange.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textbloblooper.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobmixedsizes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobrandomfont.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobshader.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobtransforms.cpp
    ${ANDROID_ROOT}/external/skqp/gm/textblobuseaftergpufree.cpp
    ${ANDROID_ROOT}/external/skqp/gm/texteffects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/texturedomaineffect.cpp
    ${ANDROID_ROOT}/external/skqp/gm/thinconcavepaths.cpp
    ${ANDROID_ROOT}/external/skqp/gm/thinrects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/thinstrokedrects.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tiledscaledbitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tileimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tilemodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tilemodes_scaled.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tinybitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/tosrgb_colorfilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/transparency.cpp
    ${ANDROID_ROOT}/external/skqp/gm/trickycubicstrokes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/typeface.cpp
    ${ANDROID_ROOT}/external/skqp/gm/unpremul.cpp
    ${ANDROID_ROOT}/external/skqp/gm/variedtext.cpp
    ${ANDROID_ROOT}/external/skqp/gm/vertices.cpp
    ${ANDROID_ROOT}/external/skqp/gm/verylargebitmap.cpp
    ${ANDROID_ROOT}/external/skqp/gm/wacky_yuv_formats.cpp
    ${ANDROID_ROOT}/external/skqp/gm/windowrectangles.cpp
    ${ANDROID_ROOT}/external/skqp/gm/xfermodeimagefilter.cpp
    ${ANDROID_ROOT}/external/skqp/gm/xfermodes.cpp
    ${ANDROID_ROOT}/external/skqp/gm/xfermodes2.cpp
    ${ANDROID_ROOT}/external/skqp/gm/xfermodes3.cpp
    ${ANDROID_ROOT}/external/skqp/gm/yuvtorgbeffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/android/SkAndroidFrameworkUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/android/SkAnimatedImage.cpp
    ${ANDROID_ROOT}/external/skqp/src/android/SkBitmapRegionCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/android/SkBitmapRegionDecoder.cpp
    ${ANDROID_ROOT}/external/skqp/src/atlastext/SkAtlasTextContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/atlastext/SkAtlasTextTarget.cpp
    ${ANDROID_ROOT}/external/skqp/src/atlastext/SkInternalAtlasTextContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/c/sk_effects.cpp
    ${ANDROID_ROOT}/external/skqp/src/c/sk_imageinfo.cpp
    ${ANDROID_ROOT}/external/skqp/src/c/sk_paint.cpp
    ${ANDROID_ROOT}/external/skqp/src/c/sk_surface.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkAndroidCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkAndroidCodecAdapter.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkBmpBaseCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkBmpCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkBmpMaskCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkBmpRLECodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkBmpStandardCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkCodecImageGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkColorTable.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkEncodedInfo.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkGifCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkIcoCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkJpegCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkJpegDecoderMgr.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkJpegUtility.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkMaskSwizzler.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkMasks.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkPngCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkSampledCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkSampler.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkStreamBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkSwizzler.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkWbmpCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/codec/SkWebpCodec.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkAAClip.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkATrace.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkAlphaRuns.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkAnalyticEdge.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkAnnotation.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkArenaAlloc.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkAutoPixmapStorage.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBBHFactory.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBigPicture.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBitmap.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBitmapCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBitmapController.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBitmapDevice.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBitmapProcState.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBitmapProcState_matrixProcs.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBitmapProvider.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlendMode.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlitRow_D32.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlitter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlitter_A8.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlitter_ARGB32.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlitter_RGB565.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlitter_Sprite.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlurMF.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBlurMask.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkCachedData.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkCanvasPriv.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkClipStack.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkClipStackDevice.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkColor.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkColorFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkColorMatrixFilterRowMajor255.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkColorSpace.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkColorSpaceXformCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkColorSpaceXformSteps.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkColorSpaceXformer.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkConvertPixels.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkCoverageDelta.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkCpu.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkCubicClipper.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkCubicMap.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkData.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDataTable.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDebug.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDeferredDisplayList.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDeferredDisplayListRecorder.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDeque.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDescriptor.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDevice.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDistanceFieldGen.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDocument.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDraw.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDrawLooper.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDrawShadowInfo.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDraw_text.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDraw_vertices.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkDrawable.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkEdge.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkEdgeBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkEdgeClipper.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkExecutor.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkFlattenable.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkFont.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkFontDescriptor.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkFontLCDConfig.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkFontMgr.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkFontPriv.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkFontStream.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGaussFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGeometry.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGlobalInitialization_core.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGlyph.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGlyphRun.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGlyphRunPainter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGpuBlurUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkGraphics.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkHalf.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkICC.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkImageFilterCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkImageGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkImageInfo.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkLatticeIter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkLineClipper.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkLiteDL.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkLiteRecorder.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkLocalMatrixImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMD5.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMallocPixelRef.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMask.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMaskBlurFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMaskCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMaskFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMaskGamma.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMath.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMatrix.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMatrix44.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMatrixImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMetaData.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMiniRecorder.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMipMap.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkModeColorFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkMultiPictureDraw.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkNormalFlatSource.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkNormalMapSource.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkNormalSource.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkOpts.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkOverdrawCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPaint.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPaintPriv.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPathMeasure.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPathRef.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPath_serial.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPicture.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPictureData.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPictureFlat.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPictureImageGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPicturePlayback.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPictureRecord.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPictureRecorder.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPixelRef.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPixmap.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPoint.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPoint3.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPromiseImageTexture.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkPtrRecorder.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkQuadClipper.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRRect.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRTree.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRWBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRasterClip.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRasterPipeline.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRasterPipelineBlitter.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkReadBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRecord.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRecordDraw.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRecordOpts.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRecordedDrawable.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRecorder.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRecords.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRect.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRegion.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRegion_path.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkRemoteGlyphCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkResourceCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScalar.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScalerContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScan.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScan_AAAPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScan_AntiPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScan_Antihair.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScan_DAAPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScan_Hairline.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkScan_Path.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSemaphore.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSharedMutex.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSpecialImage.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSpecialSurface.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSpinlock.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSpriteBlitter_ARGB32.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSpriteBlitter_RGB565.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkStream.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkStrike.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkStrikeCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkString.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkStringUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkStroke.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkStrokeRec.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkStrokerPriv.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSurfaceCharacterization.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkSwizzle.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTLS.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTSearch.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTaskGroup.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTextBlob.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkThreadID.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTime.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTypeface.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTypefaceCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkTypeface_remote.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkUnPreMultiply.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkVertState.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkVertices.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkWriteBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkWriter32.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkXfermode.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkXfermodeInterpretation.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkYUVASizeInfo.cpp
    ${ANDROID_ROOT}/external/skqp/src/core/SkYUVPlanesCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/Sk1DPathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/Sk2DPathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkColorMatrix.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkColorMatrixFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkCornerPathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkDashPathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkDiscretePathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkEmbossMask.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkEmbossMaskFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkHighContrastFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkLayerDrawLooper.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkLumaColorFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkOpPathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkOverdrawColorFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkPackBits.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkShaderMaskFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkTableColorFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkTableMaskFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkToSRGBColorFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/SkTrimPathEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkAlphaThresholdFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkArithmeticImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkBlurImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkColorFilterImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkComposeImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkDisplacementMapEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkDropShadowImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkImageSource.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkLightingImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkMagnifierImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkMatrixConvolutionImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkMergeImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkMorphologyImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkOffsetImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkPaintImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkPictureImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkTileImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/effects/imagefilters/SkXfermodeImageFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrAHardwareBufferImageGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrAuditTrail.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrBackendSurface.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrBackendTextureImageGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrBitmapTextureMaker.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrBlurUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrBufferAllocPool.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrCaps.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrClipStackClip.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrColorSpaceInfo.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrColorSpaceXform.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrContextThreadSafeProxy.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrContext_Base.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDDLContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDefaultGeoProcFactory.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDeinstantiateProxyTracker.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDirectContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDistanceFieldGenFromVector.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDrawOpAtlas.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDrawOpTest.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDrawingManager.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrDriverBugWorkarounds.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrFixedClip.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrGpu.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrGpuCommandBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrGpuResource.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrImageContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrImageTextureMaker.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrMemoryPool.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrOnFlushResourceProvider.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrOpFlushState.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrOpList.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPaint.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPathProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPathRendererChain.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPathRendering.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPathUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPipeline.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrPrimitiveProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrProcessorAnalysis.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrProcessorSet.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrProcessorUnitTest.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrProgramDesc.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrProxyProvider.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrQuad.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrRecordingContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrRectanizer_pow2.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrRectanizer_skyline.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrReducedClip.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrRenderTarget.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrRenderTargetContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrRenderTargetOpList.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrRenderTargetProxy.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrResourceAllocator.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrResourceCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrResourceProvider.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrSKSLPrettyPrint.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrSWMaskHelper.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrShaderCaps.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrShaderVar.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrShape.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrSoftwarePathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrStencilAttachment.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrStencilSettings.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrStyle.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrSurface.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrSurfaceContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrSurfaceProxy.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTessellator.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTestUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTexture.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTextureAdjuster.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTextureContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTextureMaker.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTextureOpList.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTextureProducer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTextureProxy.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrTextureRenderTargetProxy.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrXferProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/GrYUVProvider.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/SkGpuDevice.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/SkGpuDevice_drawTexture.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/SkGr.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCAtlas.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCClipPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCClipProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCConicShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCCoverageProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCCoverageProcessor_GSImpl.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCCoverageProcessor_VSImpl.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCCubicShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCDrawPathsOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCFillGeometry.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCFiller.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCPathCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCPathProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCPerFlushResources.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCQuadraticShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCStrokeGeometry.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCCStroker.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ccpr/GrCoverageCountingPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrAARectEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrAlphaThresholdFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrBezierEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrBicubicEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrBitmapTextGeoProc.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrBlurredEdgeFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrCircleBlurFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrCircleEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrConfigConversionEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrConstColorProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrConvexPolyEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrCoverageSetOpXP.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrCustomXfermode.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrDisableColorXP.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrDistanceFieldGeoProc.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrEllipseEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrGaussianConvolutionFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrLumaColorFilterEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrMagnifierEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrMatrixConvolutionEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrOvalEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrPorterDuffXferProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrPremulInputFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrRRectBlurEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrRRectEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrRectBlurEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrSRGBEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrShadowGeoProc.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrSimpleTextureEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrSkSLFP.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrTextureDomain.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrXfermodeFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/effects/GrYUVtoRGBEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLAssembleInterface.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLCaps.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLCreateNullInterface.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLExtensions.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLGLSL.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLGpu.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLGpuCommandBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLGpuProgramCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLInterface.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLPathRendering.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLProgram.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLProgramDataManager.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLRenderTarget.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLSemaphore.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLStencilAttachment.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLTestInterface.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLTexture.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLTextureRenderTarget.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLUniformHandler.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLUtil.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLVaryingHandler.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/GrGLVertexArray.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/builders/GrGLProgramBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/builders/GrGLShaderStringBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gl/egl/GrGLMakeNativeInterface_egl.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSL.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLBlend.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLFragmentProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLFragmentShaderBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLGeometryProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLPrimitiveProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLProgramBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLProgramDataManager.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLShaderBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLUtil.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLVarying.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLVertexGeoBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/glsl/GrGLSLXferProcessor.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrClampedGradientEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrDualIntervalGradientColorizer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrGradientBitmapCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrGradientShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrLinearGradientLayout.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrRadialGradientLayout.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrSingleIntervalGradientColorizer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrSweepGradientLayout.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrTextureGradientColorizer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrTiledGradientEffect.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrTwoPointConicalGradientLayout.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/gradients/GrUnrolledBinaryGradientColorizer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/mock/GrMockGpu.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrAAConvexPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrAAConvexTessellator.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrAAFillRRectOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrAAHairLinePathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrAALinearizingConvexPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrAtlasTextOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrClearOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrClearStencilClipOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrCopySurfaceOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDashLinePathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDashOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDebugMarkerOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDefaultPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDrawAtlasOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDrawPathOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDrawVerticesOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrDrawableOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrFillRectOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrLatticeOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrMeshDrawOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrOvalOpFactory.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrQuadPerEdgeAA.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrRegionOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrSemaphoreOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrShadowRRectOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrSimpleMeshDrawOpHelper.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrSmallPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrStencilAndCoverPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrStencilPathOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrStrokeRectOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrTessellatingPathRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/ops/GrTextureOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrAtlasManager.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrDistanceFieldAdjustTable.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrSDFMaskFilter.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrStrikeCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrTextBlob.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrTextBlobCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrTextBlobVertexRegenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/text/GrTextContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkAMDMemoryAllocator.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkBufferView.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkCaps.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkCommandBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkCommandPool.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkCopyManager.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkCopyPipeline.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkDescriptorPool.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkDescriptorSet.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkDescriptorSetManager.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkExtensions.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkFramebuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkGpu.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkGpuCommandBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkImage.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkImageView.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkIndexBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkInterface.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkMemory.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkPipeline.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkPipelineLayout.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkPipelineState.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkPipelineStateBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkPipelineStateCache.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkPipelineStateDataManager.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkRenderPass.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkRenderTarget.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkResourceProvider.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkSampler.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkSamplerYcbcrConversion.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkSecondaryCBDrawContext.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkSemaphore.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkStencilAttachment.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkTexture.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkTextureRenderTarget.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkTransferBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkTypesPriv.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkUniformBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkUniformHandler.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkUtil.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkVaryingHandler.cpp
    ${ANDROID_ROOT}/external/skqp/src/gpu/vk/GrVkVertexBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkImage.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkImage_Gpu.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkImage_GpuBase.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkImage_GpuYUVA.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkImage_Lazy.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkImage_Raster.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkSurface.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkSurface_Gpu.cpp
    ${ANDROID_ROOT}/external/skqp/src/image/SkSurface_Raster.cpp
    ${ANDROID_ROOT}/external/skqp/src/images/SkImageEncoder.cpp
    ${ANDROID_ROOT}/external/skqp/src/images/SkJPEGWriteUtility.cpp
    ${ANDROID_ROOT}/external/skqp/src/images/SkJpegEncoder.cpp
    ${ANDROID_ROOT}/external/skqp/src/images/SkPngEncoder.cpp
    ${ANDROID_ROOT}/external/skqp/src/images/SkWebpEncoder.cpp
    ${ANDROID_ROOT}/external/skqp/src/lazy/SkDiscardableMemoryPool.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkAddIntersections.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkDConicLineIntersection.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkDCubicLineIntersection.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkDCubicToQuads.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkDLineIntersection.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkDQuadLineIntersection.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkIntersections.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpAngle.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpCoincidence.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpContour.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpCubicHull.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpEdgeBuilder.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpSegment.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkOpSpan.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsAsWinding.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsCommon.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsConic.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsCubic.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsCurve.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsDebug.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsLine.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsOp.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsQuad.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsRect.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsSimplify.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsTSect.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsTightBounds.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsTypes.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathOpsWinding.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkPathWriter.cpp
    ${ANDROID_ROOT}/external/skqp/src/pathops/SkReduceOrder.cpp
    ${ANDROID_ROOT}/external/skqp/src/pdf/SkDocument_PDF_None.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkDebug_android.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkDiscardableMemory_none.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkFontMgr_empty_factory.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkGlobalInitialization_default.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkImageGenerator_skia.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkMemory_malloc.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkOSFile_posix.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkOSFile_stdio.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkOSLibrary_posix.cpp
    ${ANDROID_ROOT}/external/skqp/src/ports/SkTLS_pthread.cpp
    ${ANDROID_ROOT}/external/skqp/src/sfnt/SkOTTable_name.cpp
    ${ANDROID_ROOT}/external/skqp/src/sfnt/SkOTUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkBitmapProcShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkColorFilterShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkColorShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkComposeShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkImageShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkLightingShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkLights.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkLocalMatrixShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkPerlinNoiseShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkPictureShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/SkShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/gradients/Sk4fGradientBase.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/gradients/Sk4fLinearGradient.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/gradients/SkGradientShader.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/gradients/SkLinearGradient.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/gradients/SkRadialGradient.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/gradients/SkSweepGradient.cpp
    ${ANDROID_ROOT}/external/skqp/src/shaders/gradients/SkTwoPointConicalGradient.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLCFGGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLCPPCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLCPPUniformCTypes.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLCompiler.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLGLSLCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLHCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLIRGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLInterpreter.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLJIT.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLLexer.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLMetalCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLOutputStream.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLParser.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLPipelineStageCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLSPIRVCodeGenerator.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLString.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/SkSLUtil.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/ir/SkSLSetting.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/ir/SkSLSymbolTable.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/ir/SkSLType.cpp
    ${ANDROID_ROOT}/external/skqp/src/sksl/ir/SkSLVariableReference.cpp
    ${ANDROID_ROOT}/external/skqp/src/svg/SkSVGCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/src/svg/SkSVGDevice.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/Sk3D.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkAnimCodecPlayer.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkBase64.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkCamera.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkCanvasStack.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkCanvasStateUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkDashPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkEventTracer.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkFloatToDecimal.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkFrontBufferedStream.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkInterpolator.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkJSON.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkJSONWriter.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkMatrix22.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkMultiPictureDocument.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkNWayCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkNullCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkOSPath.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkPaintFilterCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkParse.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkParseColor.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkParsePath.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkPatchUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkPolyUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkShadowTessellator.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkShadowUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkTextUtils.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkThreadUtils_pthread.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkThreadUtils_win.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkUTF.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/SkWhitelistTypefaces.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/mac/SkCreateCGImageRef.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/mac/SkStream_mac.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/win/SkAutoCoInitialize.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/win/SkDWrite.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/win/SkDWriteFontFileStream.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/win/SkDWriteGeometrySink.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/win/SkHRESULT.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/win/SkIStream.cpp
    ${ANDROID_ROOT}/external/skqp/src/utils/win/SkWGL_win.cpp
    ${ANDROID_ROOT}/external/skqp/src/xml/SkDOM.cpp
    ${ANDROID_ROOT}/external/skqp/src/xml/SkXMLParser.cpp
    ${ANDROID_ROOT}/external/skqp/src/xml/SkXMLWriter.cpp
    ${ANDROID_ROOT}/external/skqp/src/xps/SkXPSDevice.cpp
    ${ANDROID_ROOT}/external/skqp/src/xps/SkXPSDocument.cpp
    ${ANDROID_ROOT}/external/skqp/tests/AAClipTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/AdvancedBlendTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/AndroidCodecTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/AnimatedImageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/AnnotationTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ApplyGammaTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ArenaAllocTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/AsADashTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BadIcoTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BitSetTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BitmapCopyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BitmapGetColorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BitmapTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BlendTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BlitMaskClip.cpp
    ${ANDROID_ROOT}/external/skqp/tests/BlurTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CachedDataTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CachedDecodingPixelRefTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CanvasStateHelpers.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CanvasStateTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CanvasTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ChecksumTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ClearTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ClipBoundsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ClipCubicTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ClipStackTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ClipperTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CodecAnimTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CodecExactReadTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CodecPartialTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CodecRecommendedTypeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CodecTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ColorFilterTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ColorMatrixTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ColorPrivTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ColorSpaceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ColorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CopySurfaceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/CubicMapTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DashPathEffectTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DataRefTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DefaultPathRendererTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DeferredDisplayListTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DequeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DetermineDomainModeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DeviceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DiscardableMemoryPoolTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DiscardableMemoryTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DrawBitmapRectTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DrawOpAtlasTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DrawPathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DrawTextTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/DynamicHashTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/EGLImageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/EmptyPathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/EncodeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/EncodedInfoTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ExifTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/F16StagesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FillPathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FitsInTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FlattenDrawableTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FlattenableFactoryToName.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FlattenableNameToFactory.cpp
    ${ANDROID_ROOT}/external/skqp/tests/Float16Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FloatingPointTextureTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FontHostStreamTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FontHostTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FontMgrTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FontNamesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/FrontBufferedStreamTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GLProgramsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GeometryTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GifTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GlyphRunTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GpuDrawPathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GpuLayerCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GpuRectanizerTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrAHardwareBufferTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrAllocatorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrCCPRTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrContextAbandonTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrContextFactoryTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrGLExtensionsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrMemoryPoolTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrMeshTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrMipMappedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrOpListFlushTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrPipelineDynamicStateTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrPorterDuffTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrQuadListTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrSKSLPrettyPrintTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrShapeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrSurfaceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrTRecorderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrTestingBackendTextureUploadTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrTextureMipMapInvalidationTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GrUploadPixelsTests.cpp
    ${ANDROID_ROOT}/external/skqp/tests/GradientTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/HSVRoundTripTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/HashTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/HighContrastFilterTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ICCTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageFilterCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageFilterTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageFrom565Bitmap.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageGeneratorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageIsOpaqueTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageNewShaderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ImageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/IncrTopoSortTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/IndexedPngOverflowTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/InfRectTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/InsetConvexPolyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/InterpolatorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/InvalidIndexedPngTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/IsClosedSingleContourTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/JSONTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/LListTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/LRUCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/LayerDrawLooperTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/LazyProxyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MD5Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MallocPixelRefTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MaskCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/Matrix44Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MatrixClipCollapseTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MatrixTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MemoryTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MemsetTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MessageBusTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MetaDataTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/MipMapTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/NonlinearBlendingTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/OSPathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/OffsetSimplePolyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/OnFlushCallbackTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/OnceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/OpChainTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/OverAlignedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFDeflateWStreamTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFDocumentTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFGlyphsToUnicodeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFJpegEmbedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFMetadataAttributeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFOpaqueSrcModeToSrcOverTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFPrimitivesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PDFTaggedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PackBitsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PackedConfigsTextureTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PaintImageFilterTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PaintTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ParametricStageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ParsePathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathCoverageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathMeasureTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsAngleIdeas.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsAngleTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsAsWindingTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsBattles.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsBoundsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsBuildUseTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsBuilderConicTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsBuilderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsChalkboardTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsConicIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsConicLineIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsConicQuadIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsCubicConicIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsCubicIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsCubicIntersectionTestData.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsCubicLineIntersectionIdeas.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsCubicLineIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsCubicQuadIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsCubicReduceOrderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsDCubicTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsDLineTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsDPointTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsDRectTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsDVectorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsDebug.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsExtendedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsFuzz763Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsInverseTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsIssue3651.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsLineIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsLineParametetersTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsOpCircleThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsOpCubicThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsOpLoopThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsOpRectThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsOpTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsQuadIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsQuadIntersectionTestData.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsQuadLineIntersectionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsQuadLineIntersectionThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsQuadReduceOrderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSimplifyDegenerateThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSimplifyFailTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSimplifyQuadThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSimplifyQuadralateralsThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSimplifyRectThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSimplifyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSimplifyTrianglesThreadedTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsSkpTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsTestCommon.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsThreadedCommon.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsThreeWayTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsTigerTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsTightBoundsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathOpsTypesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathRendererCacheTests.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PictureBBHTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PictureShaderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PictureTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PinnedImageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PixelRefTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/Point3Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PointTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PolyUtilsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PremulAlphaRoundTripTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PrimitiveProcessorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ProcessorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/PromiseImageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ProxyConversionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ProxyRefTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ProxyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/QuickRejectTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RRectInPathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RTreeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RandomTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ReadPixelsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ReadWriteAlphaTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/Reader32Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RecordDrawTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RecordOptsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RecordPatternTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RecordTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RecorderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RecordingXfermodeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RectTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RectangleTextureTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RefCntTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RegionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RenderTargetContextTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ResourceAllocatorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ResourceCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/RoundRectTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SRGBReadWritePixelsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SRGBTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SVGDeviceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SafeMathTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ScalarTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ScaleToSidesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SerialProcsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SerializationTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ShaderOpacityTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ShaderTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ShadowTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SizeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkBase64Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkColor4fTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkColorSpaceXformStepsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkDOMTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkFixed15Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkGaussFilterTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkImageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkLiteDLTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkNxTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkPEGTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkRasterPipelineTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkRemoteGlyphCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkResourceCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSLErrorTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSLFPTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSLGLSLTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSLJITTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSLMemoryLayoutTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSLMetalTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSLSPIRVTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkSharedMutexTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SkUTFTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SortTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SpecialImageTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SpecialSurfaceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SrcOverTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/StreamBufferTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/StreamTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/StringTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/StrokeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/StrokerTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SubsetPath.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SurfaceSemaphoreTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SurfaceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/SwizzlerTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TArrayTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TDPQueueTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TLazyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TableColorFilterTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TemplatesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TessellatingPathRendererTests.cpp
    ${ANDROID_ROOT}/external/skqp/tests/Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TestTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TestUtils.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TextBlobCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TextBlobTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TextureProxyTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TextureStripAtlasManagerTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/Time.cpp
    ${ANDROID_ROOT}/external/skqp/tests/ToSRGBColorFilter.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TopoSortTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TraceMemoryDumpTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TracingTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TransferPixelsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/TypefaceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/UnicodeTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/UtilsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VerticesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VkBackendSurfaceTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VkDrawableTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VkHardwareBufferTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VkMakeCopyPipelineTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VkPriorityExtensionTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VkWrapTests.cpp
    ${ANDROID_ROOT}/external/skqp/tests/VptrTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/WindowRectanglesTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/WritePixelsTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/Writer32Test.cpp
    ${ANDROID_ROOT}/external/skqp/tests/YUVCacheTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/YUVTest.cpp
    ${ANDROID_ROOT}/external/skqp/tests/image-bitmap.cpp
    ${ANDROID_ROOT}/external/skqp/tests/skbug5221.cpp
    ${ANDROID_ROOT}/external/skqp/tests/skbug6389.cpp
    ${ANDROID_ROOT}/external/skqp/tests/skbug6653.cpp
    ${ANDROID_ROOT}/external/skqp/third_party/etc1/etc1.cpp
    ${ANDROID_ROOT}/external/skqp/third_party/gif/SkGifImageReader.cpp
    ${ANDROID_ROOT}/external/skqp/third_party/skcms/skcms.cc
    ${ANDROID_ROOT}/external/skqp/tools/AndroidSkDebugToStdOut.cpp
    ${ANDROID_ROOT}/external/skqp/tools/CrashHandler.cpp
    ${ANDROID_ROOT}/external/skqp/tools/DDLPromiseImageHelper.cpp
    ${ANDROID_ROOT}/external/skqp/tools/DDLTileHelper.cpp
    ${ANDROID_ROOT}/external/skqp/tools/LsanSuppressions.cpp
    ${ANDROID_ROOT}/external/skqp/tools/ProcStats.cpp
    ${ANDROID_ROOT}/external/skqp/tools/Resources.cpp
    ${ANDROID_ROOT}/external/skqp/tools/UrlDataManager.cpp
    ${ANDROID_ROOT}/external/skqp/tools/debugger/SkDebugCanvas.cpp
    ${ANDROID_ROOT}/external/skqp/tools/debugger/SkDrawCommand.cpp
    ${ANDROID_ROOT}/external/skqp/tools/debugger/SkJsonWriteBuffer.cpp
    ${ANDROID_ROOT}/external/skqp/tools/flags/SkCommandLineFlags.cpp
    ${ANDROID_ROOT}/external/skqp/tools/flags/SkCommonFlags.cpp
    ${ANDROID_ROOT}/external/skqp/tools/flags/SkCommonFlagsConfig.cpp
    ${ANDROID_ROOT}/external/skqp/tools/fonts/SkRandomScalerContext.cpp
    ${ANDROID_ROOT}/external/skqp/tools/fonts/SkTestFontMgr.cpp
    ${ANDROID_ROOT}/external/skqp/tools/fonts/SkTestSVGTypeface.cpp
    ${ANDROID_ROOT}/external/skqp/tools/fonts/SkTestTypeface.cpp
    ${ANDROID_ROOT}/external/skqp/tools/fonts/sk_tool_utils_font.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/GrContextFactory.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/GrTest.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/MemoryCache.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/ProxyUtils.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/TestContext.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/atlastext/GLTestAtlasTextRenderer.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/gl/GLTestContext.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/gl/command_buffer/GLTestContext_command_buffer.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/gl/egl/CreatePlatformGLTestContext_egl.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/gl/null/NullGLTestContext.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/mock/MockTestContext.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/vk/VkTestContext.cpp
    ${ANDROID_ROOT}/external/skqp/tools/gpu/vk/VkTestUtils.cpp
    ${ANDROID_ROOT}/external/skqp/tools/random_parse_path.cpp
    ${ANDROID_ROOT}/external/skqp/tools/sk_tool_utils.cpp
    ${ANDROID_ROOT}/external/skqp/tools/skqp/src/jni_skqp.cpp
    ${ANDROID_ROOT}/external/skqp/tools/skqp/src/skqp.cpp
    ${ANDROID_ROOT}/external/skqp/tools/skqp/src/skqp_model.cpp
    ${ANDROID_ROOT}/external/skqp/tools/timer/Timer.cpp
    ${ANDROID_ROOT}/external/skqp/tools/trace/SkChromeTracingTracer.cpp
    ${ANDROID_ROOT}/external/skqp/tools/trace/SkDebugfTracer.cpp
    ${ANDROID_ROOT}/external/skqp/tools/trace/SkEventTracingPriv.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/skqp/experimental/svg/model -Iexternal/skqp/gm -Iexternal/skqp/include/android -Iexternal/skqp/include/atlastext -Iexternal/skqp/include/c -Iexternal/skqp/include/codec -Iexternal/skqp/include/config -Iexternal/skqp/include/core -Iexternal/skqp/include/docs -Iexternal/skqp/include/effects -Iexternal/skqp/include/encode -Iexternal/skqp/include/gpu -Iexternal/skqp/include/pathops -Iexternal/skqp/include/ports -Iexternal/skqp/include/private -Iexternal/skqp/include/svg -Iexternal/skqp/include/third_party/vulkan -Iexternal/skqp/include/utils -Iexternal/skqp/include/utils/mac -Iexternal/skqp/modules/sksg/include -Iexternal/skqp/platform_tools/android/vulkan -Iexternal/skqp/src/c -Iexternal/skqp/src/codec -Iexternal/skqp/src/core -Iexternal/skqp/src/effects -Iexternal/skqp/src/fonts -Iexternal/skqp/src/gpu -Iexternal/skqp/src/image -Iexternal/skqp/src/images -Iexternal/skqp/src/lazy -Iexternal/skqp/src/opts -Iexternal/skqp/src/pathops -Iexternal/skqp/src/pdf -Iexternal/skqp/src/ports -Iexternal/skqp/src/sfnt -Iexternal/skqp/src/shaders -Iexternal/skqp/src/shaders/gradients -Iexternal/skqp/src/sksl -Iexternal/skqp/src/utils -Iexternal/skqp/src/utils/win -Iexternal/skqp/src/xml -Iexternal/skqp/tests -Iexternal/skqp/third_party/etc1 -Iexternal/skqp/third_party/gif -Iexternal/skqp/third_party/vulkanmemoryallocator -Iexternal/skqp/tools -Iexternal/skqp/tools/debugger -Iexternal/skqp/tools/flags -Iexternal/skqp/tools/fonts -Iexternal/skqp/tools/gpu -Iexternal/skqp/tools/gpu/vk -Iexternal/skqp/tools/skqp/src -Iexternal/skqp/tools/timer -Iexternal/skqp/tools/trace'
# Raw param [2] = '-Iexternal/skqp'
# Raw param [3] = '-D__ANDROID_API__=26'
# Raw param [4] = '${config.ArmClangThumbCflags}'
# Raw param [5] = '${config.ArmClangCflags}'
# Raw param [6] = '${config.CommonClangGlobalCflags}'
# Raw param [7] = '${config.DeviceClangGlobalCflags}'
# Raw param [8] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [9] = '-Iexternal/expat/lib'
# Raw param [10] = '-Iexternal/libjpeg-turbo'
# Raw param [11] = '-Iexternal/jsoncpp/include'
# Raw param [12] = '-Iexternal/libpng'
# Raw param [13] = '-Iexternal/webp/include'
# Raw param [14] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++/include'
# Raw param [15] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# FLAG '-D__ANDROID_API__=26' became -D__ANDROID_API__=26
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
include_directories(SYSTEM 
    "${ANDROID_ROOT}/-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

include_directories( 
    "${ANDROID_ROOT}/external/skqp/experimental/svg/model -Iexternal/skqp/gm -Iexternal/skqp/include/android -Iexternal/skqp/include/atlastext -Iexternal/skqp/include/c -Iexternal/skqp/include/codec -Iexternal/skqp/include/config -Iexternal/skqp/include/core -Iexternal/skqp/include/docs -Iexternal/skqp/include/effects -Iexternal/skqp/include/encode -Iexternal/skqp/include/gpu -Iexternal/skqp/include/pathops -Iexternal/skqp/include/ports -Iexternal/skqp/include/private -Iexternal/skqp/include/svg -Iexternal/skqp/include/third_party/vulkan -Iexternal/skqp/include/utils -Iexternal/skqp/include/utils/mac -Iexternal/skqp/modules/sksg/include -Iexternal/skqp/platform_tools/android/vulkan -Iexternal/skqp/src/c -Iexternal/skqp/src/codec -Iexternal/skqp/src/core -Iexternal/skqp/src/effects -Iexternal/skqp/src/fonts -Iexternal/skqp/src/gpu -Iexternal/skqp/src/image -Iexternal/skqp/src/images -Iexternal/skqp/src/lazy -Iexternal/skqp/src/opts -Iexternal/skqp/src/pathops -Iexternal/skqp/src/pdf -Iexternal/skqp/src/ports -Iexternal/skqp/src/sfnt -Iexternal/skqp/src/shaders -Iexternal/skqp/src/shaders/gradients -Iexternal/skqp/src/sksl -Iexternal/skqp/src/utils -Iexternal/skqp/src/utils/win -Iexternal/skqp/src/xml -Iexternal/skqp/tests -Iexternal/skqp/third_party/etc1 -Iexternal/skqp/third_party/gif -Iexternal/skqp/third_party/vulkanmemoryallocator -Iexternal/skqp/tools -Iexternal/skqp/tools/debugger -Iexternal/skqp/tools/flags -Iexternal/skqp/tools/fonts -Iexternal/skqp/tools/gpu -Iexternal/skqp/tools/gpu/vk -Iexternal/skqp/tools/skqp/src -Iexternal/skqp/tools/timer -Iexternal/skqp/tools/trace"
    "${ANDROID_ROOT}/external/skqp"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
    "${ANDROID_ROOT}/external/jsoncpp/include"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/external/webp/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/skqp/experimental/svg/model -Iexternal/skqp/gm -Iexternal/skqp/include/android -Iexternal/skqp/include/atlastext -Iexternal/skqp/include/c -Iexternal/skqp/include/codec -Iexternal/skqp/include/config -Iexternal/skqp/include/core -Iexternal/skqp/include/docs -Iexternal/skqp/include/effects -Iexternal/skqp/include/encode -Iexternal/skqp/include/gpu -Iexternal/skqp/include/pathops -Iexternal/skqp/include/ports -Iexternal/skqp/include/private -Iexternal/skqp/include/svg -Iexternal/skqp/include/third_party/vulkan -Iexternal/skqp/include/utils -Iexternal/skqp/include/utils/mac -Iexternal/skqp/modules/sksg/include -Iexternal/skqp/platform_tools/android/vulkan -Iexternal/skqp/src/c -Iexternal/skqp/src/codec -Iexternal/skqp/src/core -Iexternal/skqp/src/effects -Iexternal/skqp/src/fonts -Iexternal/skqp/src/gpu -Iexternal/skqp/src/image -Iexternal/skqp/src/images -Iexternal/skqp/src/lazy -Iexternal/skqp/src/opts -Iexternal/skqp/src/pathops -Iexternal/skqp/src/pdf -Iexternal/skqp/src/ports -Iexternal/skqp/src/sfnt -Iexternal/skqp/src/shaders -Iexternal/skqp/src/shaders/gradients -Iexternal/skqp/src/sksl -Iexternal/skqp/src/utils -Iexternal/skqp/src/utils/win -Iexternal/skqp/src/xml -Iexternal/skqp/tests -Iexternal/skqp/third_party/etc1 -Iexternal/skqp/third_party/gif -Iexternal/skqp/third_party/vulkanmemoryallocator -Iexternal/skqp/tools -Iexternal/skqp/tools/debugger -Iexternal/skqp/tools/flags -Iexternal/skqp/tools/fonts -Iexternal/skqp/tools/gpu -Iexternal/skqp/tools/gpu/vk -Iexternal/skqp/tools/skqp/src -Iexternal/skqp/tools/timer -Iexternal/skqp/tools/trace/**/*.h"
    "${ANDROID_ROOT}/external/skqp/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
    "${ANDROID_ROOT}/external/jsoncpp/include/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/external/webp/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_API__=26")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_API__=26")
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
# Raw param [0] = '-U_FORTIFY_SOURCE'
# Raw param [1] = '-DATRACE_TAG=ATRACE_TAG_VIEW'
# Raw param [2] = '-DSKIA_DLL'
# Raw param [3] = '-DSKIA_IMPLEMENTATION=1'
# Raw param [4] = '-DSK_PRINT_CODEC_MESSAGES'
# Raw param [5] = '-D_FORTIFY_SOURCE=1'
# Raw param [6] = '-Wall'
# Raw param [7] = '-Werror'
# Raw param [8] = '-Weverything'
# Raw param [9] = '-Wextra'
# Raw param [10] = '-Winit-self'
# Raw param [11] = '-Wno-bad-function-cast'
# Raw param [12] = '-Wno-cast-align'
# Raw param [13] = '-Wno-cast-qual'
# Raw param [14] = '-Wno-conversion'
# Raw param [15] = '-Wno-covered-switch-default'
# Raw param [16] = '-Wno-deprecated'
# Raw param [17] = '-Wno-deprecated-declarations'
# Raw param [18] = '-Wno-disabled-macro-expansion'
# Raw param [19] = '-Wno-documentation'
# Raw param [20] = '-Wno-documentation-unknown-command'
# Raw param [21] = '-Wno-double-promotion'
# Raw param [22] = '-Wno-exit-time-destructors'
# Raw param [23] = '-Wno-float-equal'
# Raw param [24] = '-Wno-format-nonliteral'
# Raw param [25] = '-Wno-global-constructors'
# Raw param [26] = '-Wno-implicit-fallthrough'
# Raw param [27] = '-Wno-missing-field-initializers'
# Raw param [28] = '-Wno-missing-noreturn'
# Raw param [29] = '-Wno-missing-prototypes'
# Raw param [30] = '-Wno-missing-variable-declarations'
# Raw param [31] = '-Wno-newline-eof'
# Raw param [32] = '-Wno-nonportable-include-path'
# Raw param [33] = '-Wno-nonportable-system-include-path'
# Raw param [34] = '-Wno-old-style-cast'
# Raw param [35] = '-Wno-padded'
# Raw param [36] = '-Wno-pedantic'
# Raw param [37] = '-Wno-reserved-id-macro'
# Raw param [38] = '-Wno-shadow'
# Raw param [39] = '-Wno-shift-sign-overflow'
# Raw param [40] = '-Wno-signed-enum-bitfield'
# Raw param [41] = '-Wno-switch-enum'
# Raw param [42] = '-Wno-thread-safety-analysis'
# Raw param [43] = '-Wno-undef'
# Raw param [44] = '-Wno-unknown-warning-option'
# Raw param [45] = '-Wno-unreachable-code'
# Raw param [46] = '-Wno-unreachable-code-break'
# Raw param [47] = '-Wno-unreachable-code-return'
# Raw param [48] = '-Wno-unused-macros'
# Raw param [49] = '-Wno-unused-member-function'
# Raw param [50] = '-Wno-unused-parameter'
# Raw param [51] = '-Wno-unused-template'
# Raw param [52] = '-Wno-unused-variable'
# Raw param [53] = '-Wno-zero-as-null-pointer-constant'
# Raw param [54] = '-Wpointer-arith'
# Raw param [55] = '-Wsign-compare'
# Raw param [56] = '-Wvla'
# Raw param [57] = '-fvisibility=hidden'
# Raw param [58] = '-Wno-unused-parameter'
# Raw param [59] = '-Wno-unused-variable'
# Raw param [60] = '-target armv7a-linux-androideabi'
# Raw param [61] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [62] = '-fPIC'
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-DATRACE_TAG=ATRACE_TAG_VIEW' became -DATRACE_TAG=ATRACE_TAG_VIEW
# FLAG '-DSKIA_DLL' became -DSKIA_DLL
# FLAG '-DSKIA_IMPLEMENTATION=1' became -DSKIA_IMPLEMENTATION=1
# FLAG '-DSK_PRINT_CODEC_MESSAGES' became -DSK_PRINT_CODEC_MESSAGES
# FLAG '-D_FORTIFY_SOURCE=1' became -D_FORTIFY_SOURCE=1
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Weverything' became -Weverything
# FLAG '-Wextra' became -Wextra
# FLAG '-Winit-self' became -Winit-self
# FLAG '-Wno-bad-function-cast' became -Wno-bad-function-cast
# FLAG '-Wno-cast-align' became -Wno-cast-align
# FLAG '-Wno-cast-qual' became -Wno-cast-qual
# FLAG '-Wno-conversion' became -Wno-conversion
# FLAG '-Wno-covered-switch-default' became -Wno-covered-switch-default
# FLAG '-Wno-deprecated' became -Wno-deprecated
# FLAG '-Wno-deprecated-declarations' became -Wno-deprecated-declarations
# FLAG '-Wno-disabled-macro-expansion' became -Wno-disabled-macro-expansion
# FLAG '-Wno-documentation' became -Wno-documentation
# FLAG '-Wno-documentation-unknown-command' became -Wno-documentation-unknown-command
# FLAG '-Wno-double-promotion' became -Wno-double-promotion
# FLAG '-Wno-exit-time-destructors' became -Wno-exit-time-destructors
# FLAG '-Wno-float-equal' became -Wno-float-equal
# FLAG '-Wno-format-nonliteral' became -Wno-format-nonliteral
# FLAG '-Wno-global-constructors' became -Wno-global-constructors
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-missing-noreturn' became -Wno-missing-noreturn
# FLAG '-Wno-missing-prototypes' became -Wno-missing-prototypes
# FLAG '-Wno-missing-variable-declarations' became -Wno-missing-variable-declarations
# FLAG '-Wno-newline-eof' became -Wno-newline-eof
# FLAG '-Wno-nonportable-include-path' became -Wno-nonportable-include-path
# FLAG '-Wno-nonportable-system-include-path' became -Wno-nonportable-system-include-path
# FLAG '-Wno-old-style-cast' became -Wno-old-style-cast
# FLAG '-Wno-padded' became -Wno-padded
# FLAG '-Wno-pedantic' became -Wno-pedantic
# FLAG '-Wno-reserved-id-macro' became -Wno-reserved-id-macro
# FLAG '-Wno-shadow' became -Wno-shadow
# FLAG '-Wno-shift-sign-overflow' became -Wno-shift-sign-overflow
# FLAG '-Wno-signed-enum-bitfield' became -Wno-signed-enum-bitfield
# FLAG '-Wno-switch-enum' became -Wno-switch-enum
# FLAG '-Wno-thread-safety-analysis' became -Wno-thread-safety-analysis
# FLAG '-Wno-undef' became -Wno-undef
# FLAG '-Wno-unknown-warning-option' became -Wno-unknown-warning-option
# FLAG '-Wno-unreachable-code' became -Wno-unreachable-code
# FLAG '-Wno-unreachable-code-break' became -Wno-unreachable-code-break
# FLAG '-Wno-unreachable-code-return' became -Wno-unreachable-code-return
# FLAG '-Wno-unused-macros' became -Wno-unused-macros
# FLAG '-Wno-unused-member-function' became -Wno-unused-member-function
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-template' became -Wno-unused-template
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-Wno-zero-as-null-pointer-constant' became -Wno-zero-as-null-pointer-constant
# FLAG '-Wpointer-arith' became -Wpointer-arith
# FLAG '-Wsign-compare' became -Wsign-compare
# FLAG '-Wvla' became -Wvla
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSKIA_DLL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSKIA_IMPLEMENTATION=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSK_PRINT_CODEC_MESSAGES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Weverything")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Winit-self")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-bad-function-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-cast-align")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-cast-qual")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-conversion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-covered-switch-default")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-disabled-macro-expansion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-documentation")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-documentation-unknown-command")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-double-promotion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-exit-time-destructors")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-float-equal")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format-nonliteral")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-global-constructors")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-noreturn")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-prototypes")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-variable-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-newline-eof")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-nonportable-include-path")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-nonportable-system-include-path")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-old-style-cast")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-padded")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-pedantic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-shadow")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-shift-sign-overflow")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-signed-enum-bitfield")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-switch-enum")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-thread-safety-analysis")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-undef")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unknown-warning-option")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unreachable-code")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unreachable-code-break")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unreachable-code-return")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-macros")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-member-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-template")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-zero-as-null-pointer-constant")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wpointer-arith")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wsign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wvla")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSKIA_DLL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSKIA_IMPLEMENTATION=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSK_PRINT_CODEC_MESSAGES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Weverything")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Winit-self")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-bad-function-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-cast-align")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-cast-qual")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-conversion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-covered-switch-default")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-disabled-macro-expansion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-documentation")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-documentation-unknown-command")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-double-promotion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-exit-time-destructors")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-float-equal")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format-nonliteral")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-global-constructors")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-noreturn")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-prototypes")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-variable-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-newline-eof")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-nonportable-include-path")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-nonportable-system-include-path")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-old-style-cast")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-padded")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-pedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-reserved-id-macro")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-shadow")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-shift-sign-overflow")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-signed-enum-bitfield")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-switch-enum")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-analysis")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-undef")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unknown-warning-option")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unreachable-code")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unreachable-code-break")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unreachable-code-return")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-macros")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-member-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-template")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-zero-as-null-pointer-constant")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wpointer-arith")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wvla")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
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
# Raw param [3] = '-Wno-abstract-vbase-init'
# Raw param [4] = '-Wno-c++98-compat'
# Raw param [5] = '-Wno-c++98-compat-pedantic'
# Raw param [6] = '-Wno-extra-semi-stmt'
# Raw param [7] = '-Wno-noexcept-type'
# Raw param [8] = '-Wno-undefined-func-template'
# Raw param [9] = '-Wno-weak-vtables'
# Raw param [10] = '-Wnon-virtual-dtor'
# Raw param [11] = '-fexceptions'
# Raw param [12] = '-fno-rtti'
# Raw param [13] = '${config.ArmClangCppflags}'
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
# FLAG '-Wno-abstract-vbase-init' became -Wno-abstract-vbase-init
# FLAG '-Wno-c++98-compat' became -Wno-c++98-compat
# FLAG '-Wno-c++98-compat-pedantic' became -Wno-c++98-compat-pedantic
# FLAG '-Wno-extra-semi-stmt' became -Wno-extra-semi-stmt
# FLAG '-Wno-noexcept-type' became -Wno-noexcept-type
# FLAG '-Wno-undefined-func-template' became -Wno-undefined-func-template
# FLAG '-Wno-weak-vtables' became -Wno-weak-vtables
# FLAG '-Wnon-virtual-dtor' became -Wnon-virtual-dtor
# FLAG '-fexceptions' became -fexceptions
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.ArmClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-abstract-vbase-init")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-c++98-compat")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-c++98-compat-pedantic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-extra-semi-stmt")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-noexcept-type")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-undefined-func-template")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-weak-vtables")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wnon-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexceptions")
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


add_executable(libskqp_app ${SOURCE_FILES})
