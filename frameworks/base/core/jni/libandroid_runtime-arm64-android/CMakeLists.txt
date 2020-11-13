# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libandroid_runtime)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/base/core/jni/AndroidRuntime.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_content_NativeLibraryHelper.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_google_android_gles_jni_EGLImpl.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_google_android_gles_jni_GLImpl.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_app_Activity.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_app_ActivityThread.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_app_NativeActivity.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_app_admin_SecurityLog.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_EGL14.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_EGL15.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_EGLExt.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES10.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES10Ext.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES11.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES11Ext.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES20.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES30.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES31.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES31Ext.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_opengl_GLES32.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_database_CursorWindow.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_database_SQLiteCommon.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_database_SQLiteConnection.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_database_SQLiteGlobal.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_database_SQLiteDebug.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_graphics_Canvas.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_graphics_ColorSpace.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_graphics_drawable_AnimatedVectorDrawable.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_graphics_drawable_VectorDrawable.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_graphics_Picture.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_CompositionSamplingListener.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_DisplayEventReceiver.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_DisplayListCanvas.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_TextureLayer.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_InputChannel.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_InputDevice.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_InputEventReceiver.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_InputEventSender.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_InputQueue.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_KeyCharacterMap.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_KeyEvent.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_MotionEvent.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_PointerIcon.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_RenderNode.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_RenderNodeAnimator.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_Surface.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_SurfaceControl.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_SurfaceSession.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_TextureView.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_ThreadedRenderer.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_view_VelocityTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_text_AndroidCharacter.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_text_Hyphenator.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_Debug.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_GraphicsEnvironment.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_HidlSupport.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_HwBinder.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_HwBlob.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_HwParcel.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_HwRemoteBinder.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_NativeHandle.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_MemoryFile.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_MessageQueue.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_Parcel.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_SELinux.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_SharedMemory.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_SystemClock.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_SystemProperties.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_Trace.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_UEventObserver.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_VintfObject.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_os_VintfRuntimeInfo.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_net_LocalSocketImpl.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_net_NetUtils.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_nio_utils.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_AssetManager.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_Binder.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_EventLog.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_Log.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_StatsLog.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_MemoryIntArray.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_PathParser.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_Process.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_StringBlock.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_XmlBlock.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_jar_StrictJarFile.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/AnimatedImageDrawable.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Bitmap.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/BitmapFactory.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/ByteBufferStreamAdaptor.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Camera.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/CanvasProperty.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/ColorFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/FontFamily.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/FontUtils.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/CreateJavaOutputStreamAdaptor.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/GIFMovie.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/GraphicBuffer.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Graphics.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/ImageDecoder.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Interpolator.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/MaskFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Matrix.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Movie.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/MovieImpl.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/NinePatch.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/NinePatchPeeker.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Paint.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/PaintFilter.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Path.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/PathMeasure.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/PathEffect.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Picture.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/BitmapRegionDecoder.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Region.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Shader.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/SurfaceTexture.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Typeface.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/Utils.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/YuvToJpegEncoder.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/fonts/Font.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/fonts/FontFamily.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/pdf/PdfDocument.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/pdf/PdfEditor.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/pdf/PdfRenderer.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/pdf/PdfUtils.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/text/LineBreaker.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/text/MeasuredText.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioEffectDescriptor.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioRecord.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioSystem.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioTrack.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioAttributes.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioProductStrategies.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioVolumeGroups.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_AudioVolumeGroupCallback.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_DeviceCallback.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_JetPlayer.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_MediaMetricsJNI.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_MicrophoneInfo.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_midi.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_RemoteDisplay.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_media_ToneGenerator.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_Camera.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_camera2_CameraMetadata.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_camera2_legacy_LegacyCameraDevice.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_camera2_legacy_PerfMeasurement.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_camera2_DngCreator.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_display_DisplayViewport.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_HardwareBuffer.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_SensorManager.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_SerialPort.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_SoundTrigger.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_UsbDevice.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_UsbDeviceConnection.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_UsbRequest.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_location_ActivityRecognitionHardware.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_util_FileObserver.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/opengl/poly_clip.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android/opengl/util.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_server_NetworkManagementSocketTagger.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_ddm_DdmHandleNativeHeap.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_backup_BackupDataInput.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_backup_BackupDataOutput.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_backup_FileBackupHelperBase.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_backup_BackupHelperDispatcher.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_app_backup_FullBackup.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_content_res_ApkAssets.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_content_res_ObbScanner.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_content_res_Configuration.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_animation_PropertyValuesHolder.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_security_Scrypt.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_os_AtomicDirectory.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_os_ClassLoaderFactory.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_os_FuseAppLoop.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_os_Zygote.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_os_ZygoteInit.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_util_VirtualRefBasePtr.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/com_android_internal_view_animation_NativeInterpolatorFactoryHelper.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/hwbinder/EphemeralStorage.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/fd_utils.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_input_InputWindowHandle.cpp
    ${ANDROID_ROOT}/frameworks/base/core/jni/android_hardware_input_InputApplicationHandle.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/jni/android_util_StatsLogInternal.cpp/gen/android_util_StatsLogInternal.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/base/core/jni -Iframeworks/base/core/jni/include'
# Raw param [1] = '-Iframeworks/base/core/jni/android/graphics'
# Raw param [2] = '-Ibionic/libc/private -Iexternal/skia/include/private -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/images -Iframeworks/base/media/jni -Isystem/media/camera/include -Isystem/media/private/camera/include'
# Raw param [3] = '-Iframeworks/base/core/jni'
# Raw param [4] = ''
# Raw param [5] = '${config.Arm64ClangCflags}'
# Raw param [6] = '${config.CommonClangGlobalCflags}'
# Raw param [7] = '${config.DeviceClangGlobalCflags}'
# Raw param [8] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [9] = '-Ibionic/libc/async_safe/include'
# Raw param [10] = '-Isystem/core/liblog/include'
# Raw param [11] = '-Iexternal/giflib'
# Raw param [12] = '-Ibionic/libc/seccomp/include'
# Raw param [13] = '-Isystem/core/libgrallocusage/include'
# Raw param [14] = '-Iexternal/scrypt/lib/crypto'
# Raw param [15] = '-Isystem/core/libstats/include'
# Raw param [16] = '-Isystem/bpf/libbpf_android/include'
# Raw param [17] = '-Isystem/netd/libnetdbpf/include'
# Raw param [18] = '-Isystem/netd/libnetdutils/include'
# Raw param [19] = '-Isystem/core/base/include'
# Raw param [20] = '-Isystem/core/libmemtrack/include'
# Raw param [21] = '-Iframeworks/base/libs/androidfw/include'
# Raw param [22] = '-Iexternal/zlib'
# Raw param [23] = '-Isystem/core/libappfuse/include'
# Raw param [24] = '-Iexternal/boringssl/src/include'
# Raw param [25] = '-Ilibnativehelper/include'
# Raw param [26] = '-Ilibnativehelper/header_only_include'
# Raw param [27] = '-Ilibnativehelper/platform_include'
# Raw param [28] = '-D__LIBNATIVEHELPER_API__=1'
# Raw param [29] = '-Isystem/core/libcutils/include'
# Raw param [30] = '-Isystem/core/libprocessgroup/include'
# Raw param [31] = '-Isystem/core/debuggerd/include'
# Raw param [32] = '-Isystem/core/debuggerd/common/include'
# Raw param [33] = '-Isystem/core/libutils/include'
# Raw param [34] = '-Isystem/core/libbacktrace/include'
# Raw param [35] = '-Isystem/core/libsystem/include'
# Raw param [36] = '-Iframeworks/native/libs/binder/include'
# Raw param [37] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [38] = '-Iframeworks/native/libs/nativebase/include'
# Raw param [39] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [40] = '-Ihardware/libhardware/include'
# Raw param [41] = '-Isystem/media/audio/include'
# Raw param [42] = '-Isystem/bt/types'
# Raw param [43] = '-Iframeworks/native/libs/ui/include'
# Raw param [44] = '-Iframeworks/native/libs/arect/include'
# Raw param [45] = '-Iframeworks/native/libs/math/include'
# Raw param [46] = '-Isystem/libhidl/base/include'
# Raw param [47] = '-Isystem/libhidl/transport/include'
# Raw param [48] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [49] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [50] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen'
# Raw param [51] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [52] = '-Isystem/libhwbinder/include'
# Raw param [53] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen'
# Raw param [54] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen'
# Raw param [55] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen'
# Raw param [56] = '-Iframeworks/native/libs/graphicsenv/include'
# Raw param [57] = '-Iframeworks/native/libs/gui/include'
# Raw param [58] = '-Iout/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen'
# Raw param [59] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen'
# Raw param [60] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen'
# Raw param [61] = '-Isystem/libhidl/transport/token/1.0/utils/include'
# Raw param [62] = '-Iframeworks/native/opengl/libs/EGL/include'
# Raw param [63] = '-Iframeworks/native/opengl/include'
# Raw param [64] = '-Iframeworks/native/libs/nativewindow/include-private'
# Raw param [65] = '-Iframeworks/native/libs/sensor/include'
# Raw param [66] = '-Iframeworks/av/camera/include'
# Raw param [67] = '-Iframeworks/av/camera/include/camera'
# Raw param [68] = '-Isystem/media/camera/include'
# Raw param [69] = '-Iout/soong/.intermediates/frameworks/av/camera/libcamera_client/android_arm64_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [70] = '-Iexternal/sqlite/dist'
# Raw param [71] = '-Iexternal/sqlite/android'
# Raw param [72] = '-Iexternal/vulkan-headers/include'
# Raw param [73] = '-Isystem/core/libziparchive/include'
# Raw param [74] = '-Ihardware/libhardware_legacy/include'
# Raw param [75] = '-Iexternal/selinux/libselinux/include'
# Raw param [76] = '-Iexternal/icu/libandroidicu/include'
# Raw param [77] = '-D__LIBANDROIDICU_API__=1'
# Raw param [78] = '-Iframeworks/av/media/libmedia/include'
# Raw param [79] = '-Iframeworks/av/media/libstagefright/include'
# Raw param [80] = '-Iframeworks/av/media/ndk/include'
# Raw param [81] = '-Iexternal/sonivox/arm-wt-22k/include'
# Raw param [82] = '-Iframeworks/av/media/libaudioclient/include'
# Raw param [83] = '-Iout/soong/.intermediates/frameworks/av/media/libaudioclient/libaudioclient/android_arm64_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [84] = '-Iframeworks/av/media/libmedia/aidl'
# Raw param [85] = '-Iframeworks/native/headers/media_plugin'
# Raw param [86] = '-Iframeworks/native/headers/media_plugin/media/openmax'
# Raw param [87] = '-Iframeworks/av/media/libstagefright/foundation/include'
# Raw param [88] = '-Iout/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen'
# Raw param [89] = '-Iout/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm64_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [90] = '-Iframeworks/av/media/libmediametrics/include'
# Raw param [91] = '-Isystem/core/libmeminfo/include'
# Raw param [92] = '-Iexternal/libjpeg-turbo'
# Raw param [93] = '-Isystem/core/libusbhost/include'
# Raw param [94] = '-Iexternal/harfbuzz_ng/src'
# Raw param [95] = '-Iexternal/pdfium/public'
# Raw param [96] = '-Iframeworks/av/media/img_utils/include'
# Raw param [97] = '-Isystem/netd/include'
# Raw param [98] = '-Iframeworks/minikin/include'
# Raw param [99] = '-Iexternal/googletest/googletest/include'
# Raw param [100] = '-Isystem/core/libnativebridge/include'
# Raw param [101] = '-Isystem/core/libnativeloader/include'
# Raw param [102] = '-Isystem/core/libmemunreachable/include'
# Raw param [103] = '-Isystem/libvintf/include'
# Raw param [104] = '-Isystem/libvintf'
# Raw param [105] = '-Isystem/tools/hidl/utils/include'
# Raw param [106] = '-Iframeworks/base/libs/hwui'
# Raw param [107] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui'
# Raw param [108] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/proto'
# Raw param [109] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include'
# Raw param [110] = '-Iexternal/skia/include/android'
# Raw param [111] = '-Iexternal/skia/include/atlastext'
# Raw param [112] = '-Iexternal/skia/include/c'
# Raw param [113] = '-Iexternal/skia/include/codec'
# Raw param [114] = '-Iexternal/skia/include/config'
# Raw param [115] = '-Iexternal/skia/include/core'
# Raw param [116] = '-Iexternal/skia/include/docs'
# Raw param [117] = '-Iexternal/skia/include/effects'
# Raw param [118] = '-Iexternal/skia/include/encode'
# Raw param [119] = '-Iexternal/skia/include/gpu'
# Raw param [120] = '-Iexternal/skia/include/pathops'
# Raw param [121] = '-Iexternal/skia/include/ports'
# Raw param [122] = '-Iexternal/skia/include/svg'
# Raw param [123] = '-Iexternal/skia/include/utils'
# Raw param [124] = '-Iexternal/skia/include/utils/mac'
# Raw param [125] = '-Iexternal/skia/include/config/android'
# Raw param [126] = '-Iexternal/protobuf/src'
# Raw param [127] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/proto/frameworks/base/libs/hwui'
# Raw param [128] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/proto'
# Raw param [129] = '-Iout/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/sysprop/include'
# Raw param [130] = '-Iout/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen'
# Raw param [131] = '-Isystem/server_configurable_flags/libflags/include'
# Raw param [132] = '-Iexternal/libcxx/include'
# Raw param [133] = '-Iexternal/libcxxabi/include'
# Raw param [134] = '-Ibionic/libc/include'
# Raw param [135] = '-D__LIBC_API__=10000'
# Raw param [136] = '-D__LIBM_API__=10000'
# Raw param [137] = '-D__LIBDL_API__=10000'
# Raw param [138] = '-Iout/soong/.intermediates/frameworks/base/core/jni/android_util_StatsLogInternal.cpp/gen'
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
# FLAG '-D__LIBNATIVEHELPER_API__=1' became -D__LIBNATIVEHELPER_API__=1
# FLAG '-D__LIBANDROIDICU_API__=1' became -D__LIBANDROIDICU_API__=1
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/frameworks/base/core/jni -Iframeworks/base/core/jni/include"
    "${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics"
    "${ANDROID_ROOT}/bionic/libc/private -Iexternal/skia/include/private -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/images -Iframeworks/base/media/jni -Isystem/media/camera/include -Isystem/media/private/camera/include"
    "${ANDROID_ROOT}/frameworks/base/core/jni"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/giflib"
    "${ANDROID_ROOT}/bionic/libc/seccomp/include"
    "${ANDROID_ROOT}/system/core/libgrallocusage/include"
    "${ANDROID_ROOT}/external/scrypt/lib/crypto"
    "${ANDROID_ROOT}/system/core/libstats/include"
    "${ANDROID_ROOT}/system/bpf/libbpf_android/include"
    "${ANDROID_ROOT}/system/netd/libnetdbpf/include"
    "${ANDROID_ROOT}/system/netd/libnetdutils/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/system/core/libmemtrack/include"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include"
    "${ANDROID_ROOT}/external/zlib"
    "${ANDROID_ROOT}/system/core/libappfuse/include"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/libnativehelper/include"
    "${ANDROID_ROOT}/libnativehelper/header_only_include"
    "${ANDROID_ROOT}/libnativehelper/platform_include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/system/core/debuggerd/include"
    "${ANDROID_ROOT}/system/core/debuggerd/common/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include"
    "${ANDROID_ROOT}/system/libhidl/base/include"
    "${ANDROID_ROOT}/system/libhidl/transport/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhwbinder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/frameworks/native/libs/graphicsenv/include"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include"
    "${ANDROID_ROOT}/frameworks/native/opengl/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private"
    "${ANDROID_ROOT}/frameworks/native/libs/sensor/include"
    "${ANDROID_ROOT}/frameworks/av/camera/include"
    "${ANDROID_ROOT}/frameworks/av/camera/include/camera"
    "${ANDROID_ROOT}/system/media/camera/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/camera/libcamera_client/android_arm64_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/external/sqlite/dist"
    "${ANDROID_ROOT}/external/sqlite/android"
    "${ANDROID_ROOT}/external/vulkan-headers/include"
    "${ANDROID_ROOT}/system/core/libziparchive/include"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include"
    "${ANDROID_ROOT}/external/selinux/libselinux/include"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/include"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include"
    "${ANDROID_ROOT}/frameworks/av/media/ndk/include"
    "${ANDROID_ROOT}/external/sonivox/arm-wt-22k/include"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libaudioclient/libaudioclient/android_arm64_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/aidl"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/media/openmax"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/foundation/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm64_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/av/media/libmediametrics/include"
    "${ANDROID_ROOT}/system/core/libmeminfo/include"
    "${ANDROID_ROOT}/external/libjpeg-turbo"
    "${ANDROID_ROOT}/system/core/libusbhost/include"
    "${ANDROID_ROOT}/external/harfbuzz_ng/src"
    "${ANDROID_ROOT}/external/pdfium/public"
    "${ANDROID_ROOT}/frameworks/av/media/img_utils/include"
    "${ANDROID_ROOT}/system/netd/include"
    "${ANDROID_ROOT}/frameworks/minikin/include"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/system/core/libnativebridge/include"
    "${ANDROID_ROOT}/system/core/libnativeloader/include"
    "${ANDROID_ROOT}/system/core/libmemunreachable/include"
    "${ANDROID_ROOT}/system/libvintf/include"
    "${ANDROID_ROOT}/system/libvintf"
    "${ANDROID_ROOT}/system/tools/hidl/utils/include"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include"
    "${ANDROID_ROOT}/external/skia/include/android"
    "${ANDROID_ROOT}/external/skia/include/atlastext"
    "${ANDROID_ROOT}/external/skia/include/c"
    "${ANDROID_ROOT}/external/skia/include/codec"
    "${ANDROID_ROOT}/external/skia/include/config"
    "${ANDROID_ROOT}/external/skia/include/core"
    "${ANDROID_ROOT}/external/skia/include/docs"
    "${ANDROID_ROOT}/external/skia/include/effects"
    "${ANDROID_ROOT}/external/skia/include/encode"
    "${ANDROID_ROOT}/external/skia/include/gpu"
    "${ANDROID_ROOT}/external/skia/include/pathops"
    "${ANDROID_ROOT}/external/skia/include/ports"
    "${ANDROID_ROOT}/external/skia/include/svg"
    "${ANDROID_ROOT}/external/skia/include/utils"
    "${ANDROID_ROOT}/external/skia/include/utils/mac"
    "${ANDROID_ROOT}/external/skia/include/config/android"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/proto/frameworks/base/libs/hwui"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/sysprop/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen"
    "${ANDROID_ROOT}/system/server_configurable_flags/libflags/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/jni/android_util_StatsLogInternal.cpp/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/base/core/jni -Iframeworks/base/core/jni/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/core/jni/android/graphics/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/private -Iexternal/skia/include/private -Iexternal/skia/src/codec -Iexternal/skia/src/core -Iexternal/skia/src/effects -Iexternal/skia/src/image -Iexternal/skia/src/images -Iframeworks/base/media/jni -Isystem/media/camera/include -Isystem/media/private/camera/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/core/jni/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/async_safe/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/giflib/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/seccomp/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libgrallocusage/include/**/*.h"
    "${ANDROID_ROOT}/external/scrypt/lib/crypto/**/*.h"
    "${ANDROID_ROOT}/system/core/libstats/include/**/*.h"
    "${ANDROID_ROOT}/system/bpf/libbpf_android/include/**/*.h"
    "${ANDROID_ROOT}/system/netd/libnetdbpf/include/**/*.h"
    "${ANDROID_ROOT}/system/netd/libnetdutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libmemtrack/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/androidfw/include/**/*.h"
    "${ANDROID_ROOT}/external/zlib/**/*.h"
    "${ANDROID_ROOT}/system/core/libappfuse/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/header_only_include/**/*.h"
    "${ANDROID_ROOT}/libnativehelper/platform_include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/system/core/debuggerd/include/**/*.h"
    "${ANDROID_ROOT}/system/core/debuggerd/common/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/base/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhwbinder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/graphicsenv/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/gui/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/1.0/android.hardware.media@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/1.0/android.hardware.graphics.bufferqueue@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/bufferqueue/2.0/android.hardware.graphics.bufferqueue@2.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/token/1.0/utils/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/libs/EGL/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/opengl/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/sensor/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/camera/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/camera/include/camera/**/*.h"
    "${ANDROID_ROOT}/system/media/camera/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/camera/libcamera_client/android_arm64_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/external/sqlite/dist/**/*.h"
    "${ANDROID_ROOT}/external/sqlite/android/**/*.h"
    "${ANDROID_ROOT}/external/vulkan-headers/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libziparchive/include/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include/**/*.h"
    "${ANDROID_ROOT}/external/selinux/libselinux/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/libandroidicu/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/ndk/include/**/*.h"
    "${ANDROID_ROOT}/external/sonivox/arm-wt-22k/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libaudioclient/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libaudioclient/libaudioclient/android_arm64_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libmedia/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/headers/media_plugin/media/openmax/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libstagefright/foundation/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/media/omx/1.0/android.hardware.media.omx@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/av/media/libmedia/libmedia_omx/android_arm64_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/libmediametrics/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libmeminfo/include/**/*.h"
    "${ANDROID_ROOT}/external/libjpeg-turbo/**/*.h"
    "${ANDROID_ROOT}/system/core/libusbhost/include/**/*.h"
    "${ANDROID_ROOT}/external/harfbuzz_ng/src/**/*.h"
    "${ANDROID_ROOT}/external/pdfium/public/**/*.h"
    "${ANDROID_ROOT}/frameworks/av/media/img_utils/include/**/*.h"
    "${ANDROID_ROOT}/system/netd/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/minikin/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativebridge/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libnativeloader/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libmemunreachable/include/**/*.h"
    "${ANDROID_ROOT}/system/libvintf/include/**/*.h"
    "${ANDROID_ROOT}/system/libvintf/**/*.h"
    "${ANDROID_ROOT}/system/tools/hidl/utils/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/proto/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_static/gen/sysprop/include/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/android/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/atlastext/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/c/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/codec/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/config/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/core/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/docs/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/effects/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/encode/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/gpu/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/pathops/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/ports/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/svg/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/utils/mac/**/*.h"
    "${ANDROID_ROOT}/external/skia/include/config/android/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/proto/frameworks/base/libs/hwui/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/hwui/libhwui/android_arm64_armv8-a_kryo_core_shared/gen/sysprop/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen/**/*.h"
    "${ANDROID_ROOT}/system/server_configurable_flags/libflags/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/core/jni/android_util_StatsLogInternal.cpp/gen/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBNATIVEHELPER_API__=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBANDROIDICU_API__=1")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBNATIVEHELPER_API__=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBANDROIDICU_API__=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-Wno-unused-parameter'
# Raw param [1] = '-Wno-non-virtual-dtor'
# Raw param [2] = '-Wno-parentheses'
# Raw param [3] = '-DGL_GLEXT_PROTOTYPES'
# Raw param [4] = '-DEGL_EGLEXT_PROTOTYPES'
# Raw param [5] = '-DU_USING_ICU_NAMESPACE=0'
# Raw param [6] = '-Wall'
# Raw param [7] = '-Werror'
# Raw param [8] = '-Wno-error=deprecated-declarations'
# Raw param [9] = '-Wunused'
# Raw param [10] = '-Wunreachable-code'
# Raw param [11] = '-target aarch64-linux-android'
# Raw param [12] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [13] = '-DANDROID_STRICT'
# Raw param [14] = '-fPIC'
# Raw param [15] = '-D_USING_LIBCXX'
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-non-virtual-dtor' became -Wno-non-virtual-dtor
# FLAG '-Wno-parentheses' became -Wno-parentheses
# FLAG '-DGL_GLEXT_PROTOTYPES' became -DGL_GLEXT_PROTOTYPES
# FLAG '-DEGL_EGLEXT_PROTOTYPES' became -DEGL_EGLEXT_PROTOTYPES
# FLAG '-DU_USING_ICU_NAMESPACE=0' became -DU_USING_ICU_NAMESPACE=0
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-error=deprecated-declarations' became -Wno-error=deprecated-declarations
# FLAG '-Wunused' became -Wunused
# FLAG '-Wunreachable-code' became -Wunreachable-code
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-non-virtual-dtor")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-parentheses")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGL_GLEXT_PROTOTYPES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DEGL_EGLEXT_PROTOTYPES")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DU_USING_ICU_NAMESPACE=0")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=deprecated-declarations")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunused")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wunreachable-code")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-parentheses")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGL_GLEXT_PROTOTYPES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DEGL_EGLEXT_PROTOTYPES")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DU_USING_ICU_NAMESPACE=0")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=deprecated-declarations")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunused")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wunreachable-code")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
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
# Raw param [3] = '-Wno-conversion-null'
# Raw param [4] = '-fno-rtti'
# Raw param [5] = '${config.Arm64ClangCppflags}'
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
# FLAG '-Wno-conversion-null' became -Wno-conversion-null
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.Arm64ClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-conversion-null")
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


add_executable(libandroid_runtime ${SOURCE_FILES})
