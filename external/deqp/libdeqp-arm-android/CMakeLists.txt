# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libdeqp)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/deqp/execserver/xsDefs.cpp
    ${ANDROID_ROOT}/external/deqp/execserver/xsExecutionServer.cpp
    ${ANDROID_ROOT}/external/deqp/execserver/xsPosixFileReader.cpp
    ${ANDROID_ROOT}/external/deqp/execserver/xsPosixTestProcess.cpp
    ${ANDROID_ROOT}/external/deqp/execserver/xsProtocol.cpp
    ${ANDROID_ROOT}/external/deqp/execserver/xsTcpServer.cpp
    ${ANDROID_ROOT}/external/deqp/execserver/xsTestDriver.cpp
    ${ANDROID_ROOT}/external/deqp/execserver/xsTestProcess.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeBatchExecutor.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeBatchResult.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeCallQueue.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeCommLink.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeContainerFormatParser.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeDefs.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeLocalTcpIpLink.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeTcpIpLink.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeTestCaseListParser.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeTestCaseResult.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeTestLogParser.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeTestLogWriter.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeTestResultParser.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeXMLParser.cpp
    ${ANDROID_ROOT}/external/deqp/executor/xeXMLWriter.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkAllocationCallbackUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkApiVersion.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkBarrierUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkBinaryRegistry.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkBufferWithMemory.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkBuilderUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkCmdUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkDebugReportUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkDefs.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkDeviceUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkImageUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkImageWithMemory.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkMemUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkNullDriver.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkObjUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkPlatform.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkPrograms.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkQueryUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkRef.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkRefUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkRenderDocUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkShaderProgram.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkShaderToSpirV.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkSpirVAsm.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkSpirVProgram.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkStrUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkTypeUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkWsiPlatform.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkWsiUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/framework/vulkan/vkYCbCrImageWithMemory.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiBufferAndImageAllocationUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiBufferComputeInstance.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiBufferViewAccessTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiBufferViewCreateTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiCommandBuffersTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiComputeInstanceResultBuffer.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiCopiesAndBlittingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiDescriptorPoolTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiDescriptorSetTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiDeviceInitializationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiDriverPropertiesTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiExternalMemoryTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiFeatureInfo.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiFillBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiGetMemoryCommitment.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiGranularityTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiImageClearingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiMaintenance3Check.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiMemoryRequirementInvarianceTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiNullHandleTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiObjectManagementTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiPipelineTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiSmokeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/api/vktApiVersionCheck.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/binding_model/vktBindingDescriptorSetRandomTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/binding_model/vktBindingDescriptorUpdateTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/binding_model/vktBindingModelTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/binding_model/vktBindingShaderAccessTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/clipping/vktClippingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/compute/vktComputeBasicComputeShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/compute/vktComputeIndirectComputeDispatchTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/compute/vktComputeShaderBuiltinVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/compute/vktComputeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/compute/vktComputeTestsUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/conditional_rendering/vktConditionalClearAttachmentTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/conditional_rendering/vktConditionalDispatchTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/conditional_rendering/vktConditionalDrawAndClearTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/conditional_rendering/vktConditionalDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/conditional_rendering/vktConditionalRenderingTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/conditional_rendering/vktConditionalTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/device_group/vktDeviceGroupRendering.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktBasicDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawBaseClass.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawBufferObjectUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawCreateInfoUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawDifferingInterpolationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawImageObjectUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawIndexedTest.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawIndirectTest.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawInstancedTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawInvertedDepthRangesTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawNegativeViewportHeightTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawShaderDrawParametersTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawShaderLayerTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawShaderViewportIndexTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawSimpleTest.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/draw/vktDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/dynamic_state/vktDynamicStateBaseClass.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/dynamic_state/vktDynamicStateCBTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/dynamic_state/vktDynamicStateDSTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/dynamic_state/vktDynamicStateGeneralTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/dynamic_state/vktDynamicStateRSTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/dynamic_state/vktDynamicStateTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/dynamic_state/vktDynamicStateVPTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/fragment_ops/vktFragmentOperationsEarlyFragmentTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/fragment_ops/vktFragmentOperationsMakeUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/fragment_ops/vktFragmentOperationsScissorMultiViewportTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/fragment_ops/vktFragmentOperationsScissorTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/fragment_ops/vktFragmentOperationsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryBasicClass.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryBasicGeometryShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryEmitGeometryShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryInputGeometryShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryInstancedRenderingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryLayeredRenderingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryTestsUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/geometry/vktGeometryVaryingGeometryShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageAtomicOperationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageCompressionTranscodingSupport.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageLoadStoreTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageLoadStoreUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageMultisampleLoadStoreTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageMutableTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageQualifiersTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageSizeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageTestsUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageTexture.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/image/vktImageTranscodingSupportTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory/vktMemoryAllocationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory/vktMemoryBindingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory/vktMemoryExternalMemoryHostTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory/vktMemoryMappingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory/vktMemoryPipelineBarrierTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory/vktMemoryRequirementsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory/vktMemoryTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/memory_model/vktMemoryModelMessagePassing.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/multiview/vktMultiViewRenderPassUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/multiview/vktMultiViewRenderTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/multiview/vktMultiViewRenderUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/multiview/vktMultiViewTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pch.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineBlendTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineCacheTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineClearUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineDepthTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineDerivativeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineDynamicOffsetTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineEarlyDestroyTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineFramebufferAttachmentTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineImageSamplingInstance.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineImageUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineImageViewTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineInputAssemblyTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMakeUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMatchedAttachmentsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleBase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleBaseResolve.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleBaseResolveAndPerSampleFetch.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleInterpolationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleSampleLocationsExtTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleShaderBuiltInTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineMultisampleTestsUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelinePushConstantTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelinePushDescriptorTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineReferenceRenderer.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineRenderToImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineSamplerTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineSpecConstantTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineSpecConstantUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineStencilExportTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineStencilTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineTimestampTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineVertexInputTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/pipeline/vktPipelineVertexUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemAttachmentClearTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemAttachmentLoadTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemBlitImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemBufferValidator.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemClearColorImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemContext.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemCopyBufferToImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemCopyImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemCopyImageToBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemFillUpdateCopyBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemImageValidator.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemShaderImageAccessTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemStorageBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemUtils.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemWorkgroupStorageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemWsiSwapchainTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/protected_memory/vktProtectedMemYCbCrConversionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/query_pool/vktQueryPoolOcclusionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/query_pool/vktQueryPoolStatisticsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/query_pool/vktQueryPoolTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/rasterization/vktRasterizationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassDepthStencilResolveTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassMultisampleResolveTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassMultisampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassSampleReadTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassSparseRenderTargetTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassSubpassDependencyTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassTestsUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/renderpass/vktRenderPassUnusedAttachmentTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/robustness/vktRobustBufferAccessWithVariablePointersTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/robustness/vktRobustnessBufferAccessTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/robustness/vktRobustnessTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/robustness/vktRobustnessUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/robustness/vktRobustnessVertexAccessTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktAtomicOperationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktOpaqueTypeIndexingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktShaderBuiltinPrecisionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktShaderBuiltinTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktShaderCommonFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktShaderExecutor.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktShaderIntegerFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderexecutor/vktShaderPackingFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRender.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderBuiltinVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderDerivateTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderDiscardTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderIndexingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderLimitTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderLoopTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderMatrixTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderOperatorTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderReturnTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderStructTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderSwitchTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderTextureFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/shaderrender/vktShaderRenderTextureGatherTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesBase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesBufferMemoryAliasing.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesBufferSparseBinding.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesBufferSparseResidency.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesImageAlignedMipSize.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesImageBlockShapes.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesImageMemoryAliasing.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesImageSparseBinding.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesImageSparseResidency.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesMipmapSparseResidency.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesQueueBindSparseTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesShaderIntrinsics.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesShaderIntrinsicsBase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesShaderIntrinsicsSampled.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesShaderIntrinsicsStorage.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/sparse_resources/vktSparseResourcesTestsUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsm16bitStorageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsm8bitStorageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmCompositeInsertTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmComputeShaderCase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmComputeShaderTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmConditionalBranchTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmCrossStageInterfaceTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmFloatControlsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmGraphicsShaderTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmImageSamplerTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmIndexingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmInstructionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmLoopDepInfTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmLoopDepLenTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmPointerParameterTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmSpirvVersionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmTypeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmUboMatrixPaddingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmUtils.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmVariableInitTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmVariablePointersTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmVaryingNameTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/spirv_assembly/vktSpvAsmWorkgroupMemoryTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ssbo/vktSSBOLayoutCase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ssbo/vktSSBOLayoutTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsArithmeticTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsBallotBroadcastTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsBallotOtherTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsBallotTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsBasicTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsBuiltinMaskVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsBuiltinVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsClusteredTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsPartitionedTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsQuadTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsShapeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsShuffleTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsTestsUtils.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/subgroups/vktSubgroupsVoteTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationBasicEventTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationBasicFenceTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationBasicSemaphoreTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationCrossInstanceSharingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationInternallySynchronizedObjectsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationOperation.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationOperationMultiQueueTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationOperationSingleQueueTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationSmokeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/synchronization/vktSynchronizationWin32KeyedMutexTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationCommonEdgeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationCoordinatesTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationFractionalSpacingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationGeometryGridRenderTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationGeometryPassthroughTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationGeometryPointSizeTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationInvarianceTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationLimitsTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationMiscDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationPrimitiveDiscardTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationShaderInputOutputTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationUserDefinedIO.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/tessellation/vktTessellationWindingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktSampleVerifier.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktSampleVerifierUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureCompressedFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureFilteringAnisotropyTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureFilteringExplicitLodTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureMipmapTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureShadowTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureSwizzleTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/texture/vktTextureTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ubo/vktRandomUniformBlockCase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ubo/vktUniformBlockCase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ubo/vktUniformBlockTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/util/vktDrawUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/util/vktExternalMemoryUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vkrunner/vktVkRunnerExampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vkrunner/vktVkRunnerTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vktInfoTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vktShaderLibrary.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vktTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vktTestCaseUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vktTestGroupUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vktTestPackage.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/vktTestPackageEntry.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiColorSpaceTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiDisplayTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiDisplayTimingTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiIncrementalPresentTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiSharedPresentableImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiSurfaceTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiSwapchainTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/wsi/vktWsiTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ycbcr/vktYCbCrConversionTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ycbcr/vktYCbCrCopyTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ycbcr/vktYCbCrFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ycbcr/vktYCbCrImageQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ycbcr/vktYCbCrTests.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ycbcr/vktYCbCrUtil.cpp
    ${ANDROID_ROOT}/external/deqp/external/vulkancts/modules/vulkan/ycbcr/vktYCbCrViewTests.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuApp.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuArray.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuAstcUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuBilinearImageCompare.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuCPUWarmup.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuCommandLine.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuCompressedTexture.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuEither.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuFactoryRegistry.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuFloat.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuFloatFormat.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuFunctionLibrary.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuFuzzyImageCompare.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuImageCompare.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuImageIO.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuInterval.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuMatrix.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuMaybe.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuPlatform.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuRGBA.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuRandomValueIterator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuRasterizationVerifier.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuRenderTarget.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuResource.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuResultCollector.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuSeedBuilder.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuStringTemplate.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuSurface.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuSurfaceAccess.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTestContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTestHierarchyIterator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTestHierarchyUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTestLog.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTestPackage.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTestSessionExecutor.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTexCompareVerifier.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTexLookupVerifier.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTexVerifierUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTexture.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuTextureUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/common/tcuThreadUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deDefs.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deFloat16.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deFloat16Test.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deInt32.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deInt32Test.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deMath.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deMathTest.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deMemory.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deRandom.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deSha1.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/debase/deString.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deAppendList.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deArrayBuffer.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deArrayUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deBlockBuffer.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deCommandLine.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deDirectoryIterator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deDynamicLibrary.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deFilePath.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deMemPool.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deMeta.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deMutex.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/dePoolArray.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/dePoolString.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deProcess.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deRandom.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deRingBuffer.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deSTLUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deSemaphore.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deSha1.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deSharedPtr.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deSocket.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deSpinBarrier.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deStringUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deThread.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deThreadLocal.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deThreadSafeRingBuffer.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/deUniquePtr.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/decpp/pch.cpp
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deimage/deImage.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deimage/deTarga.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/deMemPool.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolArray.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolHash.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolHashArray.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolHashSet.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolHeap.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolMultiSet.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolSet.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolStringBuilder.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/depool/dePoolTest.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/destream/deFileStream.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/destream/deRingbuffer.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/destream/deStreamCpyThread.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/destream/deThreadStream.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/deAtomic.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/deSingleton.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/deThreadTest.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/unix/deMutexUnix.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/unix/deNamedSemaphoreUnix.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/unix/deSemaphoreUnix.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/unix/deThreadLocalUnix.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/unix/deThreadUnix.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/win32/deMutexWin32.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/win32/deSemaphoreWin32.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/win32/deThreadLocalWin32.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/dethread/win32/deThreadWin32.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deClock.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deCommandLine.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deDynamicLibrary.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deFile.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deProcess.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deSocket.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deTimer.c
    ${ANDROID_ROOT}/external/deqp/framework/delibs/deutil/deTimerTest.c
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluCallLogWrapper.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluConfigFilter.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluConfigInfo.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluGLContextFactory.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluGLFunctionLoader.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluGLUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluNativeDisplay.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluNativePixmap.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluNativeWindow.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluPlatform.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluStaticESLibrary.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluStrUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluUnique.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/egluUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/wrapper/eglwDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/wrapper/eglwFunctions.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/wrapper/eglwLibrary.cpp
    ${ANDROID_ROOT}/external/deqp/framework/egl/wrapper/eglwWrapper.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluCallLogWrapper.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluContextFactory.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluContextInfo.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluDrawUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluDummyRenderContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluFboRenderContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluObjectWrapper.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluPixelTransfer.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluPlatform.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluProgramInterfaceQuery.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluRenderConfig.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluRenderContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluShaderLibrary.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluShaderProgram.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluShaderUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluStateReset.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluStrUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluTexture.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluTextureTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluTextureUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluVarType.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/gluVarTypeUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/simplereference/sglrContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/simplereference/sglrContextUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/simplereference/sglrContextWrapper.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/simplereference/sglrGLContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/simplereference/sglrReferenceContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/simplereference/sglrReferenceUtils.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/simplereference/sglrShaderProgram.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwFunctions.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwInitES20Direct.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwInitES30Direct.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwInitES31Direct.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwInitES32Direct.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwInitFunctions.cpp
    ${ANDROID_ROOT}/external/deqp/framework/opengl/wrapper/glwWrapper.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidAssets.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidExecService.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidInternals.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidJNI.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidMain.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidNativeActivity.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidPlatform.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidPlatformCapabilityQueryJNI.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidRenderActivity.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidTestActivity.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidUtil.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuAndroidWindow.cpp
    ${ANDROID_ROOT}/external/deqp/framework/platform/android/tcuTestLogParserJNI.cpp
    ${ANDROID_ROOT}/external/deqp/framework/qphelper/qpCrashHandler.c
    ${ANDROID_ROOT}/external/deqp/framework/qphelper/qpDebugOut.c
    ${ANDROID_ROOT}/external/deqp/framework/qphelper/qpInfo.c
    ${ANDROID_ROOT}/external/deqp/framework/qphelper/qpTestLog.c
    ${ANDROID_ROOT}/external/deqp/framework/qphelper/qpWatchDog.c
    ${ANDROID_ROOT}/external/deqp/framework/qphelper/qpXmlWriter.c
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgBinaryOps.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgBuiltinFunctions.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgExecutionContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgExpression.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgExpressionGenerator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgFunctionGenerator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgGeneratorState.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgNameAllocator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgParameters.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgPrettyPrinter.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgProgramExecutor.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgProgramGenerator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgSamplers.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgShader.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgShaderGenerator.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgStatement.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgToken.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgUtils.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgVariable.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgVariableManager.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgVariableType.cpp
    ${ANDROID_ROOT}/external/deqp/framework/randomshaders/rsgVariableValue.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrDefs.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrFragmentOperations.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrMultisamplePixelBufferAccess.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrPrimitivePacket.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrRasterizer.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrRenderer.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrShaders.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrShadingContext.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrVertexAttrib.cpp
    ${ANDROID_ROOT}/external/deqp/framework/referencerenderer/rrVertexPacket.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglAndroidUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglApiCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglBufferAgeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglChooseConfigReference.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglChooseConfigTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglClientExtensionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglColorClearCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglColorClearTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglConfigList.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglCreateContextExtTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglCreateContextTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglCreateSurfaceTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglGLES1RenderUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglGLES2RenderUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglGLES2SharedRenderingPerfTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglGLES2SharingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglGLES2SharingThreadedTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglGetFrameTimestampsTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglGetProcAddressTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglImageFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglImageUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglInfoTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglMakeCurrentPerfTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglMemoryStressTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglMultiContextTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglMultiThreadTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglMutableRenderBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglNativeColorMappingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglNativeCoordMappingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglNegativeApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglNegativePartialUpdateTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglPartialUpdateTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglPreservingSwapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglQueryConfigTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglQueryContextTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglQuerySurfaceTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglRenderCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglRenderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglResizeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglRobustnessTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglSimpleConfigCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglSurfacelessContextTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglSwapBuffersTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglSwapBuffersWithDamageTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglSyncTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglTestPackage.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglTestPackageEntry.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglThreadCleanUpTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglVGRenderUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/egl/teglWideColorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/accuracy/es2aAccuracyTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/accuracy/es2aTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/accuracy/es2aTextureMipmapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/accuracy/es2aVaryingInterpolationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fApiCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fAttribLocationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fBlendTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fBooleanStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fBufferObjectQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fBufferTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fBufferWriteTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fClippingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fColorClearTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDebugMarkerTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDefaultVertexAttributeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDepthRangeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDepthStencilClearTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDepthStencilTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDepthTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDitheringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFboApiTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFboCompletenessTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFboRenderTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFboStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFloatStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFlushFinishTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFragOpInteractionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fFunctionalTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fImplementationLimitTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fIntegerStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fLifetimeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fLightAmountTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fMultisampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fMultisampledRenderToTextureTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fNegativeBufferApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fNegativeFragmentApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fNegativeShaderApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fNegativeStateApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fNegativeTextureApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fNegativeVertexArrayApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fPolygonOffsetTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fPrerequisiteTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fRandomFragmentOpTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fRandomShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fRasterizationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fRboStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fReadPixelsTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fScissorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderAlgorithmTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderBuiltinVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderConstExprTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderDiscardTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderExecuteTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderFragDataTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderIndexingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderInvarianceTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderLoopTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderMatrixTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderOperatorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderReturnTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderStructTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fShaderTextureFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fStencilTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fStringQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureCompletenessTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureMipmapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureSizeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureSpecificationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureUnitTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fTextureWrapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fUniformApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fVertexArrayTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/functional/es2fVertexTextureTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pBlendTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pDrawCallBatchingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pPerformanceTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pRedundantStateChangeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pShaderCompilationCases.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pShaderCompilerTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pShaderControlStatementTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pShaderOperatorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pShaderOptimizationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pStateChangeCallTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pStateChangeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pTextureCases.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pTextureCountTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pTextureFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/performance/es2pTextureUploadTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/stress/es2sDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/stress/es2sLongRunningTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/stress/es2sMemoryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/stress/es2sSpecialFloatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/stress/es2sStressTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/stress/es2sVertexArrayTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/tes2CapabilityTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/tes2Context.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/tes2InfoTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/tes2TestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/tes2TestPackage.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles2/tes2TestPackageEntry.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/accuracy/es3aAccuracyTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/accuracy/es3aTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/accuracy/es3aTextureMipmapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/accuracy/es3aVaryingInterpolationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fASTCDecompressionCases.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fApiCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fAttribLocationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fBlendTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fBooleanStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fBufferCopyTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fBufferMapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fBufferObjectQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fBufferWriteTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fBuiltinPrecisionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fClippingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fColorClearTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fCompressedTextureTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fDefaultVertexArrayObjectTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fDefaultVertexAttributeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fDepthStencilClearTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fDepthStencilTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fDepthTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fDitheringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboColorbufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboCompletenessTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboDepthbufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboInvalidateTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboMultisampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboRenderTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboStencilbufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFboTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFloatStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFlushFinishTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFragDepthTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFragOpInteractionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFragmentOutputTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFramebufferBlitTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fFunctionalTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fImplementationLimitTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fIndexedStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fInstancedRenderingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fInteger64StateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fIntegerStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fInternalFormatQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fLifetimeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fMultisampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fMultiviewTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fNegativeBufferApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fNegativeFragmentApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fNegativeShaderApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fNegativeStateApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fNegativeTextureApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fNegativeVertexArrayApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fOcclusionQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fPixelBufferObjectTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fPolygonOffsetTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fPrerequisiteTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fPrimitiveRestartTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fRandomFragmentOpTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fRandomShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fRasterizationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fRasterizerDiscardTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fRboStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fReadPixelsTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fSamplerObjectTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fSamplerStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fScissorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderBuiltinVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderCommonFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderConstExprTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderDerivateTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderDiscardTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderFragDataTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderIndexingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderInvarianceTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderLoopTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderMatrixTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderMetamorphicTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderOperatorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderPackingFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderPrecisionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderReturnTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderStructTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderSwitchTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fShaderTextureFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fStencilTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fStringQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fSyncTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureMipmapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureShadowTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureSizeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureSpecificationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureSwizzleTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureUnitTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTextureWrapTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fTransformFeedbackTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fUniformApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fUniformBlockTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fVertexArrayObjectTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fVertexArrayTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/functional/es3fVertexTextureTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pBlendTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pBufferDataUploadTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pDepthTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pPerformanceTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pRedundantStateChangeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pShaderCompilationCases.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pShaderCompilerTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pShaderControlStatementTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pShaderOperatorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pShaderOptimizationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pStateChangeCallTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pStateChangeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pTextureCases.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pTextureCountTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/performance/es3pTextureFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sLongRunningShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sLongRunningTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sLongShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sMemoryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sOcclusionQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sSpecialFloatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sStressTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sSyncTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/stress/es3sVertexArrayTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/tes3Context.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/tes3InfoTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/tes3TestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/tes3TestPackage.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles3/tes3TestPackageEntry.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fAdvancedBlendTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fAndroidExtensionPackES31ATests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fAtomicCounterTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fBasicComputeShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fBooleanStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fBuiltinPrecisionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fComputeShaderBuiltinVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fCopyImageTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fDebugTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fDefaultVertexArrayObjectTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fDrawBuffersIndexedTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fDrawElementsBaseVertexTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fFboColorbufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fFboNoAttachmentTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fFboSRGBWriteControlTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fFboTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fFboTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fFramebufferDefaultStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fFunctionalTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fGeometryShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fIndexedStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fIndirectComputeDispatchTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fInfoLogQueryShared.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fIntegerStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fInternalFormatQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fLayoutBindingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fMultisampleShaderRenderCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fMultisampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeAdvancedBlendEquationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeAtomicCounterTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeBufferApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeComputeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeFragmentApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativePreciseTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeSSBOBlockTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeSampleVariablesTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeShaderApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeShaderDirectiveTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeShaderFramebufferFetchTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeShaderFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeShaderImageLoadStoreTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeShaderStorageTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeStateApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeTessellationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeTestShared.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeTextureApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fNegativeVertexArrayApiTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fOpaqueTypeIndexingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fPrimitiveBoundingBoxTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fProgramInterfaceDefinition.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fProgramInterfaceDefinitionUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fProgramInterfaceQueryTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fProgramInterfaceQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fProgramPipelineStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fProgramStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fProgramUniformTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSRGBDecodeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSSBOArrayLengthTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSSBOLayoutCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSSBOLayoutTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSampleShadingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSampleVariableTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSamplerStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSeparateShaderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderAtomicOpTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderBuiltinConstantTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderCommonFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderFramebufferFetchTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderHelperInvocationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderImageLoadStoreTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderIntegerFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderMultisampleInterpolationStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderMultisampleInterpolationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderPackingFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderSharedVarTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderTextureSizeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fShaderUniformIntegerFunctionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fStencilTexturingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fSynchronizationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTessellationGeometryInteractionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTessellationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureBorderClampTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureBufferTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureFilteringTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureGatherTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureLevelStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureMultisampleTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureSpecificationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fTextureStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fUniformBlockTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fUniformLocationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fVertexAttributeBindingStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/functional/es31fVertexAttributeBindingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/stress/es31sDrawTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/stress/es31sStressTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/stress/es31sTessellationGeometryInteractionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/stress/es31sVertexAttributeBindingTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/tes31Context.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/tes31InfoTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/tes31TestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/tes31TestPackage.cpp
    ${ANDROID_ROOT}/external/deqp/modules/gles31/tes31TestPackageEntry.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsAttributeLocationTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsBufferTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsBuiltinPrecisionTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsCalibration.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsDrawTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsFboCompletenessTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsFboUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsFragOpInteractionCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsFragmentOpUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsInteractionTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsLifetimeTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsLongStressCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsLongStressTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsMemoryStressCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsRandomShaderCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsRandomShaderProgram.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsRandomUniformBlockCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsSamplerObjectTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsScissorTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsShaderConstExprTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsShaderExecUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsShaderLibrary.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsShaderLibraryCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsShaderPerformanceCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsShaderPerformanceMeasurer.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsShaderRenderCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsStateChangePerfTestCases.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsStateQueryUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsTextureBufferCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsTextureStateQueryTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsTextureTestUtil.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsUniformBlockCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/glshared/glsVertexArrayTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditAstcTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditBuildInfoTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditDelibsTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditFrameworkTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditImageCompareTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditImageIOTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditSRGB8ConversionTest.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditSeedBuilderTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditTestCase.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditTestLogTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditTestPackage.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditTestPackageEntry.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditTextureFormatTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/internal/ditVulkanTests.cpp
    ${ANDROID_ROOT}/external/deqp/modules/pch.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/deqp/execserver -Iexternal/deqp/executor -Iexternal/deqp/external/vulkancts/framework/vulkan -Iexternal/deqp/external/vulkancts/modules/vulkan/api -Iexternal/deqp/external/vulkancts/modules/vulkan/binding_model -Iexternal/deqp/external/vulkancts/modules/vulkan/clipping -Iexternal/deqp/external/vulkancts/modules/vulkan/compute -Iexternal/deqp/external/vulkancts/modules/vulkan/conditional_rendering -Iexternal/deqp/external/vulkancts/modules/vulkan/device_group -Iexternal/deqp/external/vulkancts/modules/vulkan/draw -Iexternal/deqp/external/vulkancts/modules/vulkan/dynamic_state -Iexternal/deqp/external/vulkancts/modules/vulkan/fragment_ops -Iexternal/deqp/external/vulkancts/modules/vulkan/geometry -Iexternal/deqp/external/vulkancts/modules/vulkan/image -Iexternal/deqp/external/vulkancts/modules/vulkan/memory -Iexternal/deqp/external/vulkancts/modules/vulkan/memory_model -Iexternal/deqp/external/vulkancts/modules/vulkan/multiview -Iexternal/deqp/external/vulkancts/modules/vulkan -Iexternal/deqp/external/vulkancts/modules/vulkan/pipeline -Iexternal/deqp/external/vulkancts/modules/vulkan/protected_memory -Iexternal/deqp/external/vulkancts/modules/vulkan/query_pool -Iexternal/deqp/external/vulkancts/modules/vulkan/rasterization -Iexternal/deqp/external/vulkancts/modules/vulkan/renderpass -Iexternal/deqp/external/vulkancts/modules/vulkan/robustness -Iexternal/deqp/external/vulkancts/modules/vulkan/shaderexecutor -Iexternal/deqp/external/vulkancts/modules/vulkan/shaderrender -Iexternal/deqp/external/vulkancts/modules/vulkan/sparse_resources -Iexternal/deqp/external/vulkancts/modules/vulkan/spirv_assembly -Iexternal/deqp/external/vulkancts/modules/vulkan/ssbo -Iexternal/deqp/external/vulkancts/modules/vulkan/subgroups -Iexternal/deqp/external/vulkancts/modules/vulkan/synchronization -Iexternal/deqp/external/vulkancts/modules/vulkan/tessellation -Iexternal/deqp/external/vulkancts/modules/vulkan/texture -Iexternal/deqp/external/vulkancts/modules/vulkan/ubo -Iexternal/deqp/external/vulkancts/modules/vulkan/util -Iexternal/deqp/external/vulkancts/modules/vulkan/vkrunner -Iexternal/deqp/external/vulkancts/modules/vulkan/wsi -Iexternal/deqp/external/vulkancts/modules/vulkan/ycbcr -Iexternal/deqp/framework/common -Iexternal/deqp/framework/delibs/debase -Iexternal/deqp/framework/delibs/decpp -Iexternal/deqp/framework/delibs/deimage -Iexternal/deqp/framework/delibs/depool -Iexternal/deqp/framework/delibs/destream -Iexternal/deqp/framework/delibs/dethread -Iexternal/deqp/framework/delibs/dethread/unix -Iexternal/deqp/framework/delibs/dethread/win32 -Iexternal/deqp/framework/delibs/deutil -Iexternal/deqp/framework/egl -Iexternal/deqp/framework/egl/wrapper -Iexternal/deqp/framework/opengl -Iexternal/deqp/framework/opengl/simplereference -Iexternal/deqp/framework/opengl/wrapper -Iexternal/deqp/framework/platform/android -Iexternal/deqp/framework/qphelper -Iexternal/deqp/framework/randomshaders -Iexternal/deqp/framework/referencerenderer -Iexternal/deqp/modules/egl -Iexternal/deqp/modules/gles2/accuracy -Iexternal/deqp/modules/gles2/functional -Iexternal/deqp/modules/gles2/performance -Iexternal/deqp/modules/gles2/stress -Iexternal/deqp/modules/gles2 -Iexternal/deqp/modules/gles3/accuracy -Iexternal/deqp/modules/gles3/functional -Iexternal/deqp/modules/gles3/performance -Iexternal/deqp/modules/gles3/stress -Iexternal/deqp/modules/gles3 -Iexternal/deqp/modules/gles31/functional -Iexternal/deqp/modules/gles31/stress -Iexternal/deqp/modules/gles31 -Iexternal/deqp/modules/glshared -Iexternal/deqp/modules/internal -Iexternal/deqp/modules'
# Raw param [2] = '-Iexternal/deqp-deps/SPIRV-Headers/include'
# Raw param [3] = '-Iexternal/deqp'
# Raw param [4] = '-D__ANDROID_API__=27'
# Raw param [5] = '${config.ArmClangThumbCflags}'
# Raw param [6] = '${config.ArmClangCflags}'
# Raw param [7] = '${config.CommonClangGlobalCflags}'
# Raw param [8] = '${config.DeviceClangGlobalCflags}'
# Raw param [9] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [10] = '-Iexternal/libpng'
# Raw param [11] = '-Iexternal/deqp-deps/glslang'
# Raw param [12] = '-Iexternal/deqp-deps/glslang/glslang/OSDependent'
# Raw param [13] = '-Iexternal/deqp-deps/glslang/OGLCompilersDLL'
# Raw param [14] = '-Iexternal/deqp-deps/glslang/SPIRV'
# Raw param [15] = '-Iexternal/deqp-deps/SPIRV-Tools/include'
# Raw param [16] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++/include'
# Raw param [17] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# FLAG '-D__ANDROID_API__=27' became -D__ANDROID_API__=27
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
    "${ANDROID_ROOT}/external/deqp/execserver -Iexternal/deqp/executor -Iexternal/deqp/external/vulkancts/framework/vulkan -Iexternal/deqp/external/vulkancts/modules/vulkan/api -Iexternal/deqp/external/vulkancts/modules/vulkan/binding_model -Iexternal/deqp/external/vulkancts/modules/vulkan/clipping -Iexternal/deqp/external/vulkancts/modules/vulkan/compute -Iexternal/deqp/external/vulkancts/modules/vulkan/conditional_rendering -Iexternal/deqp/external/vulkancts/modules/vulkan/device_group -Iexternal/deqp/external/vulkancts/modules/vulkan/draw -Iexternal/deqp/external/vulkancts/modules/vulkan/dynamic_state -Iexternal/deqp/external/vulkancts/modules/vulkan/fragment_ops -Iexternal/deqp/external/vulkancts/modules/vulkan/geometry -Iexternal/deqp/external/vulkancts/modules/vulkan/image -Iexternal/deqp/external/vulkancts/modules/vulkan/memory -Iexternal/deqp/external/vulkancts/modules/vulkan/memory_model -Iexternal/deqp/external/vulkancts/modules/vulkan/multiview -Iexternal/deqp/external/vulkancts/modules/vulkan -Iexternal/deqp/external/vulkancts/modules/vulkan/pipeline -Iexternal/deqp/external/vulkancts/modules/vulkan/protected_memory -Iexternal/deqp/external/vulkancts/modules/vulkan/query_pool -Iexternal/deqp/external/vulkancts/modules/vulkan/rasterization -Iexternal/deqp/external/vulkancts/modules/vulkan/renderpass -Iexternal/deqp/external/vulkancts/modules/vulkan/robustness -Iexternal/deqp/external/vulkancts/modules/vulkan/shaderexecutor -Iexternal/deqp/external/vulkancts/modules/vulkan/shaderrender -Iexternal/deqp/external/vulkancts/modules/vulkan/sparse_resources -Iexternal/deqp/external/vulkancts/modules/vulkan/spirv_assembly -Iexternal/deqp/external/vulkancts/modules/vulkan/ssbo -Iexternal/deqp/external/vulkancts/modules/vulkan/subgroups -Iexternal/deqp/external/vulkancts/modules/vulkan/synchronization -Iexternal/deqp/external/vulkancts/modules/vulkan/tessellation -Iexternal/deqp/external/vulkancts/modules/vulkan/texture -Iexternal/deqp/external/vulkancts/modules/vulkan/ubo -Iexternal/deqp/external/vulkancts/modules/vulkan/util -Iexternal/deqp/external/vulkancts/modules/vulkan/vkrunner -Iexternal/deqp/external/vulkancts/modules/vulkan/wsi -Iexternal/deqp/external/vulkancts/modules/vulkan/ycbcr -Iexternal/deqp/framework/common -Iexternal/deqp/framework/delibs/debase -Iexternal/deqp/framework/delibs/decpp -Iexternal/deqp/framework/delibs/deimage -Iexternal/deqp/framework/delibs/depool -Iexternal/deqp/framework/delibs/destream -Iexternal/deqp/framework/delibs/dethread -Iexternal/deqp/framework/delibs/dethread/unix -Iexternal/deqp/framework/delibs/dethread/win32 -Iexternal/deqp/framework/delibs/deutil -Iexternal/deqp/framework/egl -Iexternal/deqp/framework/egl/wrapper -Iexternal/deqp/framework/opengl -Iexternal/deqp/framework/opengl/simplereference -Iexternal/deqp/framework/opengl/wrapper -Iexternal/deqp/framework/platform/android -Iexternal/deqp/framework/qphelper -Iexternal/deqp/framework/randomshaders -Iexternal/deqp/framework/referencerenderer -Iexternal/deqp/modules/egl -Iexternal/deqp/modules/gles2/accuracy -Iexternal/deqp/modules/gles2/functional -Iexternal/deqp/modules/gles2/performance -Iexternal/deqp/modules/gles2/stress -Iexternal/deqp/modules/gles2 -Iexternal/deqp/modules/gles3/accuracy -Iexternal/deqp/modules/gles3/functional -Iexternal/deqp/modules/gles3/performance -Iexternal/deqp/modules/gles3/stress -Iexternal/deqp/modules/gles3 -Iexternal/deqp/modules/gles31/functional -Iexternal/deqp/modules/gles31/stress -Iexternal/deqp/modules/gles31 -Iexternal/deqp/modules/glshared -Iexternal/deqp/modules/internal -Iexternal/deqp/modules"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Headers/include"
    "${ANDROID_ROOT}/external/deqp"
    "${ANDROID_ROOT}/external/libpng"
    "${ANDROID_ROOT}/external/deqp-deps/glslang"
    "${ANDROID_ROOT}/external/deqp-deps/glslang/glslang/OSDependent"
    "${ANDROID_ROOT}/external/deqp-deps/glslang/OGLCompilersDLL"
    "${ANDROID_ROOT}/external/deqp-deps/glslang/SPIRV"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/deqp/execserver -Iexternal/deqp/executor -Iexternal/deqp/external/vulkancts/framework/vulkan -Iexternal/deqp/external/vulkancts/modules/vulkan/api -Iexternal/deqp/external/vulkancts/modules/vulkan/binding_model -Iexternal/deqp/external/vulkancts/modules/vulkan/clipping -Iexternal/deqp/external/vulkancts/modules/vulkan/compute -Iexternal/deqp/external/vulkancts/modules/vulkan/conditional_rendering -Iexternal/deqp/external/vulkancts/modules/vulkan/device_group -Iexternal/deqp/external/vulkancts/modules/vulkan/draw -Iexternal/deqp/external/vulkancts/modules/vulkan/dynamic_state -Iexternal/deqp/external/vulkancts/modules/vulkan/fragment_ops -Iexternal/deqp/external/vulkancts/modules/vulkan/geometry -Iexternal/deqp/external/vulkancts/modules/vulkan/image -Iexternal/deqp/external/vulkancts/modules/vulkan/memory -Iexternal/deqp/external/vulkancts/modules/vulkan/memory_model -Iexternal/deqp/external/vulkancts/modules/vulkan/multiview -Iexternal/deqp/external/vulkancts/modules/vulkan -Iexternal/deqp/external/vulkancts/modules/vulkan/pipeline -Iexternal/deqp/external/vulkancts/modules/vulkan/protected_memory -Iexternal/deqp/external/vulkancts/modules/vulkan/query_pool -Iexternal/deqp/external/vulkancts/modules/vulkan/rasterization -Iexternal/deqp/external/vulkancts/modules/vulkan/renderpass -Iexternal/deqp/external/vulkancts/modules/vulkan/robustness -Iexternal/deqp/external/vulkancts/modules/vulkan/shaderexecutor -Iexternal/deqp/external/vulkancts/modules/vulkan/shaderrender -Iexternal/deqp/external/vulkancts/modules/vulkan/sparse_resources -Iexternal/deqp/external/vulkancts/modules/vulkan/spirv_assembly -Iexternal/deqp/external/vulkancts/modules/vulkan/ssbo -Iexternal/deqp/external/vulkancts/modules/vulkan/subgroups -Iexternal/deqp/external/vulkancts/modules/vulkan/synchronization -Iexternal/deqp/external/vulkancts/modules/vulkan/tessellation -Iexternal/deqp/external/vulkancts/modules/vulkan/texture -Iexternal/deqp/external/vulkancts/modules/vulkan/ubo -Iexternal/deqp/external/vulkancts/modules/vulkan/util -Iexternal/deqp/external/vulkancts/modules/vulkan/vkrunner -Iexternal/deqp/external/vulkancts/modules/vulkan/wsi -Iexternal/deqp/external/vulkancts/modules/vulkan/ycbcr -Iexternal/deqp/framework/common -Iexternal/deqp/framework/delibs/debase -Iexternal/deqp/framework/delibs/decpp -Iexternal/deqp/framework/delibs/deimage -Iexternal/deqp/framework/delibs/depool -Iexternal/deqp/framework/delibs/destream -Iexternal/deqp/framework/delibs/dethread -Iexternal/deqp/framework/delibs/dethread/unix -Iexternal/deqp/framework/delibs/dethread/win32 -Iexternal/deqp/framework/delibs/deutil -Iexternal/deqp/framework/egl -Iexternal/deqp/framework/egl/wrapper -Iexternal/deqp/framework/opengl -Iexternal/deqp/framework/opengl/simplereference -Iexternal/deqp/framework/opengl/wrapper -Iexternal/deqp/framework/platform/android -Iexternal/deqp/framework/qphelper -Iexternal/deqp/framework/randomshaders -Iexternal/deqp/framework/referencerenderer -Iexternal/deqp/modules/egl -Iexternal/deqp/modules/gles2/accuracy -Iexternal/deqp/modules/gles2/functional -Iexternal/deqp/modules/gles2/performance -Iexternal/deqp/modules/gles2/stress -Iexternal/deqp/modules/gles2 -Iexternal/deqp/modules/gles3/accuracy -Iexternal/deqp/modules/gles3/functional -Iexternal/deqp/modules/gles3/performance -Iexternal/deqp/modules/gles3/stress -Iexternal/deqp/modules/gles3 -Iexternal/deqp/modules/gles31/functional -Iexternal/deqp/modules/gles31/stress -Iexternal/deqp/modules/gles31 -Iexternal/deqp/modules/glshared -Iexternal/deqp/modules/internal -Iexternal/deqp/modules/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Headers/include/**/*.h"
    "${ANDROID_ROOT}/external/deqp/**/*.h"
    "${ANDROID_ROOT}/external/libpng/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/glslang/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/glslang/glslang/OSDependent/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/glslang/OGLCompilersDLL/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/glslang/SPIRV/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__ANDROID_API__=27")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__ANDROID_API__=27")
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
# Raw param [0] = '-DDEQP_SUPPORT_GLES1=1'
# Raw param [1] = '-DDE_ANDROID_API=28'
# Raw param [2] = '-D_XOPEN_SOURCE=600'
# Raw param [3] = ''-DDEQP_TARGET_NAME="android"''
# Raw param [4] = '-DQP_SUPPORT_PNG=1'
# Raw param [5] = '-DDEQP_HAVE_GLSLANG=1'
# Raw param [6] = '-DDEQP_HAVE_SPIRV_TOOLS=1'
# Raw param [7] = '-Wall'
# Raw param [8] = '-Werror'
# Raw param [9] = '-Wconversion'
# Raw param [10] = '-fwrapv'
# Raw param [11] = '-Wno-implicit-fallthrough'
# Raw param [12] = '-Wno-sign-conversion'
# Raw param [13] = '-target armv7a-linux-androideabi'
# Raw param [14] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [15] = '-fPIC'
# FLAG '-DDEQP_SUPPORT_GLES1=1' became -DDEQP_SUPPORT_GLES1=1
# FLAG '-DDE_ANDROID_API=28' became -DDE_ANDROID_API=28
# FLAG '-D_XOPEN_SOURCE=600' became -D_XOPEN_SOURCE=600
# FLAG ''-DDEQP_TARGET_NAME="android"'' became -DDEQP_TARGET_NAME=\\\"android\\\"
# FLAG '-DQP_SUPPORT_PNG=1' became -DQP_SUPPORT_PNG=1
# FLAG '-DDEQP_HAVE_GLSLANG=1' became -DDEQP_HAVE_GLSLANG=1
# FLAG '-DDEQP_HAVE_SPIRV_TOOLS=1' became -DDEQP_HAVE_SPIRV_TOOLS=1
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wconversion' became -Wconversion
# FLAG '-fwrapv' became -fwrapv
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wno-sign-conversion' became -Wno-sign-conversion
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDEQP_SUPPORT_GLES1=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDE_ANDROID_API=28")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_XOPEN_SOURCE=600")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDEQP_TARGET_NAME=\\\"android\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DQP_SUPPORT_PNG=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDEQP_HAVE_GLSLANG=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DDEQP_HAVE_SPIRV_TOOLS=1")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wconversion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fwrapv")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-conversion")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDEQP_SUPPORT_GLES1=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDE_ANDROID_API=28")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_XOPEN_SOURCE=600")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDEQP_TARGET_NAME=\\\"android\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DQP_SUPPORT_PNG=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDEQP_HAVE_GLSLANG=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DDEQP_HAVE_SPIRV_TOOLS=1")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wconversion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fwrapv")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-conversion")
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
# Raw param [3] = '-Wno-non-virtual-dtor'
# Raw param [4] = '-Wno-delete-non-virtual-dtor'
# Raw param [5] = '-Wno-implicit-int-conversion'
# Raw param [6] = '-Wno-missing-field-initializers'
# Raw param [7] = '-Wno-switch'
# Raw param [8] = '-Wno-unused-variable'
# Raw param [9] = '-fexceptions'
# Raw param [10] = '-frtti'
# Raw param [11] = '${config.ArmClangCppflags}'
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
# FLAG '-Wno-non-virtual-dtor' became -Wno-non-virtual-dtor
# FLAG '-Wno-delete-non-virtual-dtor' became -Wno-delete-non-virtual-dtor
# FLAG '-Wno-implicit-int-conversion' became -Wno-implicit-int-conversion
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-switch' became -Wno-switch
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-fexceptions' became -fexceptions
# FLAG '-frtti' became -frtti
# variable ${config.ArmClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-delete-non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-int-conversion")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fexceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -frtti")

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


add_executable(libdeqp ${SOURCE_FILES})
