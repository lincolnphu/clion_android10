# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libskia)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/skia/src/android/SkAndroidFrameworkUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/android/SkAnimatedImage.cpp
    ${ANDROID_ROOT}/external/skia/src/android/SkBitmapRegionCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/android/SkBitmapRegionDecoder.cpp
    ${ANDROID_ROOT}/external/skia/src/c/sk_effects.cpp
    ${ANDROID_ROOT}/external/skia/src/c/sk_imageinfo.cpp
    ${ANDROID_ROOT}/external/skia/src/c/sk_paint.cpp
    ${ANDROID_ROOT}/external/skia/src/c/sk_surface.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkAndroidCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkAndroidCodecAdapter.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpBaseCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpMaskCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpRLECodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkBmpStandardCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkCodecImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkColorTable.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkEncodedInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkGifCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkIcoCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkJpegCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkJpegDecoderMgr.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkJpegUtility.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkMaskSwizzler.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkMasks.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkPngCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkSampledCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkSampler.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkStreamBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkSwizzler.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkWbmpCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkWebpCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAAClip.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkATrace.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAlphaRuns.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAnalyticEdge.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAnnotation.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkArenaAlloc.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkAutoPixmapStorage.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBBHFactory.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBigPicture.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmap.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapController.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapProcState.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapProcState_matrixProcs.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBitmapProvider.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlendMode.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitRow_D32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_A8.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_ARGB32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_RGB565.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlitter_Sprite.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlurMF.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBlurMask.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCachedData.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCanvasPriv.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkClipStack.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkClipStackDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColor.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorMatrixFilterRowMajor255.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpace.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXformCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXformSteps.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkColorSpaceXformer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkContourMeasure.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkConvertPixels.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCoverageDelta.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCpu.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCubicClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkCubicMap.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkData.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDataTable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDebug.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDeferredDisplayList.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDeferredDisplayListRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDeque.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDescriptor.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDistanceFieldGen.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDocument.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDraw.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDrawLooper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDrawShadowInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDraw_text.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDraw_vertices.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkDrawable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkEdge.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkEdgeBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkEdgeClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkExecutor.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFlattenable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFont.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontDescriptor.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontLCDConfig.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontMgr.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontPriv.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkFontStream.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGaussFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGeometry.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGlobalInitialization_core.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGlyph.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGlyphRun.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGlyphRunPainter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGpuBlurUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkGraphics.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkHalf.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkICC.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageFilterCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkImageInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLatticeIter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLineClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLiteDL.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLiteRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkLocalMatrixImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMD5.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMallocPixelRef.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMask.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskBlurFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMaskGamma.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMatrix.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMatrix44.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMatrixImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMiniRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMipMap.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkModeColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkMultiPictureDraw.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkNormalFlatSource.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkNormalMapSource.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkNormalSource.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkOpts.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkOverdrawCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPaint.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPaintPriv.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPathMeasure.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPathRef.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPath_serial.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPicture.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureData.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureFlat.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureImageGenerator.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPicturePlayback.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureRecord.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPictureRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPixelRef.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPixmap.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPoint.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPoint3.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPromiseImageTexture.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkPtrRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkQuadClipper.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRRect.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRTree.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRWBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRasterClip.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRasterPipeline.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRasterPipelineBlitter.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkReadBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecord.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecordDraw.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecordOpts.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecordedDrawable.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecorder.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRecords.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRect.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRegion.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRegion_path.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkRemoteGlyphCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkResourceCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScalar.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScalerContext.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_AAAPath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_AntiPath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_Antihair.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_DAAPath.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_Hairline.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkScan_Path.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSemaphore.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSharedMutex.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpecialImage.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpecialSurface.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpinlock.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpriteBlitter_ARGB32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSpriteBlitter_RGB565.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStream.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStrike.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStrikeCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkString.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStringUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStroke.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStrokeRec.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkStrokerPriv.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSurfaceCharacterization.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkSwizzle.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTLS.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTSearch.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTaskGroup.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTextBlob.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkThreadID.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTime.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTypeface.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTypefaceCache.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkTypeface_remote.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkUnPreMultiply.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkVertState.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkVertices.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkWriteBuffer.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkWriter32.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkXfermode.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkXfermodeInterpretation.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkYUVASizeInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/core/SkYUVPlanesCache.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/Sk1DPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/Sk2DPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkColorMatrix.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkColorMatrixFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkCornerPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkDashPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkDiscretePathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkEmbossMask.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkEmbossMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkHighContrastFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkLayerDrawLooper.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkLumaColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkOpPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkOverdrawColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkPackBits.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkShaderMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkTableColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkTableMaskFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkToSRGBColorFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/SkTrimPathEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkAlphaThresholdFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkArithmeticImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkBlurImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkColorFilterImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkComposeImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkDisplacementMapEffect.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkDropShadowImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkImageSource.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkLightingImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkMagnifierImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkMatrixConvolutionImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkMergeImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkMorphologyImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkOffsetImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkPaintImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkPictureImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkTileImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/effects/imagefilters/SkXfermodeImageFilter.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkImage.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkImage_Lazy.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkImage_Raster.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkSurface.cpp
    ${ANDROID_ROOT}/external/skia/src/image/SkSurface_Raster.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkImageEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkJPEGWriteUtility.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkJpegEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkPngEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/images/SkWebpEncoder.cpp
    ${ANDROID_ROOT}/external/skia/src/lazy/SkDiscardableMemoryPool.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkAddIntersections.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDConicLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDCubicLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDCubicToQuads.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkDQuadLineIntersection.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkIntersections.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpAngle.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpCoincidence.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpContour.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpCubicHull.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpEdgeBuilder.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpSegment.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkOpSpan.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsAsWinding.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsCommon.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsConic.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsCubic.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsCurve.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsDebug.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsLine.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsOp.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsQuad.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsRect.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsSimplify.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsTSect.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsTightBounds.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsTypes.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathOpsWinding.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkPathWriter.cpp
    ${ANDROID_ROOT}/external/skia/src/pathops/SkReduceOrder.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkClusterator.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkDeflate.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkJpegInfo.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkKeyedImage.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFBitmap.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFConvertType1FontStream.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFDocument.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFFont.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFFormXObject.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFGradientShader.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFGraphicState.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFMakeCIDGlyphWidthsArray.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFMakeToUnicodeCmap.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFMetadata.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFResourceDict.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFShader.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFSubsetFont.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFTag.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFTypes.cpp
    ${ANDROID_ROOT}/external/skia/src/pdf/SkPDFUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkDiscardableMemory_none.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontHost_FreeType.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontHost_FreeType_common.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontMgr_custom.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontMgr_custom_empty.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkFontMgr_custom_empty_factory.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkGlobalInitialization_default.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkImageGenerator_skia.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkMemory_malloc.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkOSFile_stdio.cpp
    ${ANDROID_ROOT}/external/skia/src/sfnt/SkOTTable_name.cpp
    ${ANDROID_ROOT}/external/skia/src/sfnt/SkOTUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkBitmapProcShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkColorFilterShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkColorShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkComposeShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkImageShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkLightingShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkLights.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkLocalMatrixShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkPerlinNoiseShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkPictureShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/SkShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/Sk4fGradientBase.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/Sk4fLinearGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkGradientShader.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkLinearGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkRadialGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkSweepGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/shaders/gradients/SkTwoPointConicalGradient.cpp
    ${ANDROID_ROOT}/external/skia/src/svg/SkSVGCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/svg/SkSVGDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/Sk3D.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkAnimCodecPlayer.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkBase64.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkCamera.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkCanvasStack.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkCanvasStateUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkDashPath.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkEventTracer.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkFloatToDecimal.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkFrontBufferedStream.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkInterpolator.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkJSON.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkJSONWriter.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkMatrix22.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkMetaData.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkMultiPictureDocument.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkNWayCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkNullCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkOSPath.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkPaintFilterCanvas.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkParse.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkParseColor.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkParsePath.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkPatchUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkPolyUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkShadowTessellator.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkShadowUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkTextUtils.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkThreadUtils_pthread.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkThreadUtils_win.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkUTF.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/SkWhitelistTypefaces.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/mac/SkCreateCGImageRef.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/mac/SkStream_mac.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkAutoCoInitialize.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkDWrite.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkDWriteFontFileStream.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkDWriteGeometrySink.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkHRESULT.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkIStream.cpp
    ${ANDROID_ROOT}/external/skia/src/utils/win/SkWGL_win.cpp
    ${ANDROID_ROOT}/external/skia/src/xml/SkDOM.cpp
    ${ANDROID_ROOT}/external/skia/src/xml/SkXMLParser.cpp
    ${ANDROID_ROOT}/external/skia/src/xml/SkXMLWriter.cpp
    ${ANDROID_ROOT}/external/skia/third_party/etc1/etc1.cpp
    ${ANDROID_ROOT}/external/skia/third_party/gif/SkGifImageReader.cpp
    ${ANDROID_ROOT}/external/skia/third_party/skcms/skcms.cc
    ${ANDROID_ROOT}/external/skia/src/opts/SkOpts_avx.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkOpts_hsw.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkOpts_sse41.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkOpts_sse42.cpp
    ${ANDROID_ROOT}/external/skia/src/opts/SkOpts_ssse3.cpp
    ${ANDROID_ROOT}/external/skia/src/codec/SkRawCodec.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkDebug_stdio.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkOSFile_posix.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkOSLibrary_posix.cpp
    ${ANDROID_ROOT}/external/skia/src/ports/SkTLS_pthread.cpp
    ${ANDROID_ROOT}/external/skia/src/xps/SkXPSDevice.cpp
    ${ANDROID_ROOT}/external/skia/src/xps/SkXPSDocument.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/skia/include/android -Iexternal/skia/include/atlastext -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/docs -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/include/config/linux'
# Raw param [2] = '-Iexternal/skia/include/config/linux -Iexternal/skia/include/android -Iexternal/skia/include/atlastext -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/docs -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/etc1 -Iexternal/skia/third_party/gif -Iexternal/skia/third_party/skcms'
# Raw param [3] = '-Iexternal/skia'
# Raw param [4] = ''
# Raw param [5] = '${config.LinuxClangCflags} ${config.LinuxX86ClangCflags}'
# Raw param [6] = '${config.CommonClangGlobalCflags}'
# Raw param [7] = '${config.HostClangGlobalCflags}'
# Raw param [8] = ''
# Raw param [9] = '-Isystem/core/libcutils/include'
# Raw param [10] = '-Isystem/core/libprocessgroup/include'
# Raw param [11] = '-Iframeworks/native/libs/arect/include'
# Raw param [12] = '-Iexternal/sfntly/cpp/src'
# Raw param [13] = '-Iexternal/webp/include'
# Raw param [14] = '-Iexternal/libcxx/include'
# Raw param [15] = '-Iexternal/libcxxabi/include'
# Raw param [16] = '-Iexternal/icu/libandroidicu/include'
# Raw param [17] = '-Iexternal/dng_sdk/source'
# Raw param [18] = '-Iexternal/expat/lib'
# Raw param [19] = '-Iexternal/freetype/include'
# Raw param [20] = '-Iexternal/libjpeg-turbo'
# Raw param [21] = '-Isystem/core/liblog/include'
# Raw param [22] = '-Iexternal/piex'
# Raw param [23] = '-Iexternal/libpng'
# Raw param [24] = '-Iexternal/zlib'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
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
    "${ANDROID_ROOT}/external/skia/include/android -Iexternal/skia/include/atlastext -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/docs -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/include/config/linux"
    "${ANDROID_ROOT}/external/skia/include/config/linux -Iexternal/skia/include/android -Iexternal/skia/include/atlastext -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/docs -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/etc1 -Iexternal/skia/third_party/gif -Iexternal/skia/third_party/skcms"
    "${ANDROID_ROOT}/external/skia"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/external/sfntly/cpp/src"
    "${ANDROID_ROOT}/external/webp/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include"
    "${ANDROID_ROOT}/external/dng_sdk/source"
    "${ANDROID_ROOT}/external/expat/lib"
    "${ANDROID_ROOT}/external/freetype/include"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/piex"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/external/zlib"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/skia/include/android -Iexternal/skia/include/atlastext -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/docs -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/include/config/linux/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/config/linux -Iexternal/skia/include/android -Iexternal/skia/include/atlastext -Iexternal/skia/include/c -Iexternal/skia/include/codec -Iexternal/skia/include/config -Iexternal/skia/include/core -Iexternal/skia/include/docs -Iexternal/skia/include/effects -Iexternal/skia/include/encode -Iexternal/skia/include/gpu -Iexternal/skia/include/pathops -Iexternal/skia/include/ports -Iexternal/skia/include/private -Iexternal/skia/include/svg -Iexternal/skia/include/utils -Iexternal/skia/include/utils/mac -Iexternal/skia/src/c -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/fonts -Iexternal/skia/src/gpu -Iexternal/skia/src/image -Iexternal/skia/src/images -Iexternal/skia/src/lazy -Iexternal/skia/src/opts -Iexternal/skia/src/pathops -Iexternal/skia/src/pdf -Iexternal/skia/src/ports -Iexternal/skia/src/sfnt -Iexternal/skia/src/shaders -Iexternal/skia/src/shaders/gradients -Iexternal/skia/src/sksl -Iexternal/skia/src/utils -Iexternal/skia/src/utils/win -Iexternal/skia/src/xml -Iexternal/skia/third_party/etc1 -Iexternal/skia/third_party/gif -Iexternal/skia/third_party/skcms/**/*.h"
    "${ANDROID_ROOT}/external/skia/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/external/sfntly/cpp/src/**/*.h"
    "${ANDROID_ROOT}/external/webp/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include/**/*.h"
    "${ANDROID_ROOT}/external/dng_sdk/source/**/*.h"
    "${ANDROID_ROOT}/external/expat/lib/**/*.h"
    "${ANDROID_ROOT}/external/freetype/include/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/piex/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
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
# Raw param [2] = '-U_FORTIFY_SOURCE'
# Raw param [3] = '-DATRACE_TAG=ATRACE_TAG_VIEW'
# Raw param [4] = '-DSKIA_DLL'
# Raw param [5] = '-DSKIA_IMPLEMENTATION=1'
# Raw param [6] = '-DSK_PRINT_CODEC_MESSAGES'
# Raw param [7] = '-D_FORTIFY_SOURCE=1'
# Raw param [8] = '-Wno-implicit-fallthrough'
# Raw param [9] = '-Wno-missing-field-initializers'
# Raw param [10] = '-Wno-thread-safety-analysis'
# Raw param [11] = '-Wno-unused-parameter'
# Raw param [12] = '-Wno-unused-variable'
# Raw param [13] = '-fvisibility=hidden'
# Raw param [14] = '-mssse3'
# Raw param [15] = '-target i686-linux-gnu'
# Raw param [16] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [17] = '-fPIC'
# Raw param [18] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-DATRACE_TAG=ATRACE_TAG_VIEW' became -DATRACE_TAG=ATRACE_TAG_VIEW
# FLAG '-DSKIA_DLL' became -DSKIA_DLL
# FLAG '-DSKIA_IMPLEMENTATION=1' became -DSKIA_IMPLEMENTATION=1
# FLAG '-DSK_PRINT_CODEC_MESSAGES' became -DSK_PRINT_CODEC_MESSAGES
# FLAG '-D_FORTIFY_SOURCE=1' became -D_FORTIFY_SOURCE=1
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-thread-safety-analysis' became -Wno-thread-safety-analysis
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-mssse3' became -mssse3
# FLAG '-target i686-linux-gnu' became -target i686-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSKIA_DLL")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSKIA_IMPLEMENTATION=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DSK_PRINT_CODEC_MESSAGES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_FORTIFY_SOURCE=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-thread-safety-analysis")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -mssse3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target i686-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -U_FORTIFY_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DATRACE_TAG=ATRACE_TAG_VIEW")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSKIA_DLL")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSKIA_IMPLEMENTATION=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DSK_PRINT_CODEC_MESSAGES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_FORTIFY_SOURCE=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-analysis")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -mssse3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target i686-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
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
# Raw param [3] = '-fexceptions'
# Raw param [4] = ''
# Raw param [5] = '-nostdinc++'
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
# FLAG '-fexceptions' became -fexceptions
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexceptions")
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


add_executable(libskia ${SOURCE_FILES})
