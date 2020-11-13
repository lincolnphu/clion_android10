# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(NeuralNetworksTest_mt_static)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/TestNeuralNetworksWrapper.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/TestMain.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/abs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/add.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/add_broadcast_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/add_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/add_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/add_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/argmax_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/argmax_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/argmax_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/argmin_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/argmin_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/argmin_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_4_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_5.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_float_5_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_quant8_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_quant8_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_quant8_5.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/avg_pool_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/axis_aligned_bbox_transform.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/batch_to_space.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/batch_to_space_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/batch_to_space_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/batch_to_space_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/batch_to_space_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/batch_to_space_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bbox_graph.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm_aux_input.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm_cifg_peephole.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm_float16_batch_major.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm_float16_batch_major_aux_input.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm_float16_batch_major_merge_outputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm_merge_outputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_lstm_norm_fw_output.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/bidirectional_sequence_rnn.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/box_with_nms_limit_gaussian.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/box_with_nms_limit_hard.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/box_with_nms_limit_linear.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/cast.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/channel_shuffle.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float16_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float16_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float16_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_mixed_quant.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_quant8_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/concat_zero_sized.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv2d_dilation.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv2d_per_channel.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv2d_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_1_h3_w2_SAME.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_1_h3_w2_SAME_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_1_h3_w2_VALID.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_1_h3_w2_VALID_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_3_h3_w2_SAME.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_3_h3_w2_SAME_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_3_h3_w2_VALID.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_3_h3_w2_VALID_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_channels.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_channels_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_channels_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_channels_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_large_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_large_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_large_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_float_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_channels.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_channels_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_large_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_overflow.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_overflow_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/conv_quant8_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depth_to_space_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_dilation.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large_2_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large_2_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_large_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_float_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_per_channel.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_quant8_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_quant8_large_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_quant8_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv2d_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/depthwise_conv_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/dequantize.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/dequantize_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/dequantize_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/detection_postprocess.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/div.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/div_broadcast_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/div_broadcast_float_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/div_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/div_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/embedding_lookup.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/embedding_lookup_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/equal.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/exp.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/expand_dims.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/floor.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/floor_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/floor_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_4d_simple.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_4d_simple_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_large_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_large_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_large_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_float_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_quant8_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_quant8_large_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_quant8_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/fully_connected_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/gather.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/gather_higher_rank.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/generate_proposals.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/greater.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/greater_equal.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/grouped_conv2d.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/hashtable_lookup_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/hashtable_lookup_float_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/hashtable_lookup_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/heatmap_max_keypoint.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/instance_normalization.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization_axis.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization_large_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_normalization_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_pool_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_pool_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_pool_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_pool_float_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_pool_float_large_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_pool_float_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/l2_pool_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/layer_norm_lstm.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/less.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/less_equal.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_norm_float_4_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/local_response_normalization_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/log.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/log_softmax.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logical_and.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logical_not.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logical_or.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logistic_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logistic_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logistic_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logistic_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logistic_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logistic_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/logistic_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_4_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_deprecated.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lsh_projection_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_state.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_state2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_state2_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_state2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_state_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm2_state_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state2_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state3_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm3_state_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_state.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_state2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_state2_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_state2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_state_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/lstm_state_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_float_4_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_quant8_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_quant8_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/max_pool_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/maximum.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mean_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/minimum.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mobilenet_224_gender_basic_fixed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mobilenet_224_gender_basic_fixed_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mobilenet_quantized.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mul.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mul_broadcast_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mul_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mul_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mul_relu.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mul_relu_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/mul_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/neg.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/not_equal.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_all_dims.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_low_rank.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_low_rank_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_quant8_nonzero.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_v2_1_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_v2_1_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_v2_all_dims.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_v2_all_dims_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_v2_low_rank.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pad_v2_low_rank_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/pow.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/prelu.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/quantize.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/quantized_lstm.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/random_multinomial.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/random_multinomial_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reduce_all.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reduce_any.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reduce_max.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reduce_min.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reduce_prod.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reduce_sum.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu1_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu1_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu1_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu1_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu1_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu1_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu1_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu6_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu6_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu6_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu6_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu6_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu6_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu6_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/relu_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reshape.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reshape_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reshape_quant8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reshape_quant8_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reshape_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reshape_weights_as_inputs.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/reshape_weights_as_inputs_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/resize_bilinear.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/resize_bilinear_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/resize_bilinear_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/resize_bilinear_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/resize_bilinear_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/resize_nearest_neighbor.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/rnn.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/rnn_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/rnn_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/rnn_state.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/rnn_state_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/roi_align.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/roi_pooling.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/rsqrt.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/select_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sin.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/slice.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/softmax_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/softmax_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/softmax_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/softmax_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/softmax_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/softmax_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/softmax_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_quant8_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_quant8_nonzero.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_batch_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/space_to_depth_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_float_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_float_5.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_int32_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_int32_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_int32_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_int32_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_quant8_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/split_quant8_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sqrt.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/squeeze.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/squeeze_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/squeeze_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/squeeze_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/squeeze_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/squeeze_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_10.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_10_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_11.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_11_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_3_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_4_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_5.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_5_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_6.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_6_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_7.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_7_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_8_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_9.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_float_9_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_qaunt8_10.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_qaunt8_11.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_4.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_5.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_6.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_7.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_8.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_quant8_9.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/strided_slice_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sub.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sub_broadcast_float.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sub_broadcast_float_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sub_quantized_different_scales.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sub_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sub_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/sub_v1_2_broadcast.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf2_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_bias_present.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_bias_present_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_bias_present_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_state.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_state_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/svdf_state_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/tanh.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/tanh_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/tanh_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/tile_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/tile_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/tile_3.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/topk_v2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_conv2d.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_conv2d_large.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_float16.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_float_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_float_1_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_quant8_1.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_relaxed.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/transpose_v1_2.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_1step.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_batch_major_norm_peephole_projection.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_batch_major_peephole_projection_bias.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_cifg_peephole.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_f16_batch_major.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_f16_norm_peephole_projection.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_layer_norm_cifg_peephole.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_lstm_norm_peephole_projection.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/generated/tests/unidirectional_sequence_rnn.mod.py.cpp
    ${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/TestGenerated.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/ml/nn/runtime/test'
# Raw param [1] = ''
# Raw param [2] = '${config.Arm64ClangCflags}'
# Raw param [3] = '${config.CommonClangGlobalCflags}'
# Raw param [4] = '${config.DeviceClangGlobalCflags}'
# Raw param [5] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [6] = '-Iframeworks/ml/nn/tools/test_generator/include'
# Raw param [7] = '-Iframeworks/ml/nn/runtime'
# Raw param [8] = '-Iexternal/googletest/googletest/include'
# Raw param [9] = '-Iexternal/libcxx/include'
# Raw param [10] = '-Iexternal/boringssl/src/include'
# Raw param [11] = '-Iexternal/googletest/googlemock/include'
# Raw param [12] = '-Iframeworks/ml/nn/runtime/include'
# Raw param [13] = '-Iframeworks/native/cmds/lshal/libprocpartition/include'
# Raw param [14] = '-Ibuild/soong/cc/libbuildversion/include'
# Raw param [15] = '-Iframeworks/ml/nn/common/include'
# Raw param [16] = '-Iframeworks/native/libs/arect/include'
# Raw param [17] = '-Iframeworks/ml/nn/driver/sample'
# Raw param [18] = '-Iframeworks/native/libs/nativewindow/include'
# Raw param [19] = '-Iframeworks/native/libs/nativewindow/include-private'
# Raw param [20] = '-Iframeworks/native/libs/nativebase/include'
# Raw param [21] = '-Isystem/core/base/include'
# Raw param [22] = '-Iframeworks/native/libs/binder/include'
# Raw param [23] = '-Isystem/core/libcutils/include'
# Raw param [24] = '-Isystem/core/libutils/include'
# Raw param [25] = '-Isystem/core/libbacktrace/include'
# Raw param [26] = '-Isystem/core/liblog/include'
# Raw param [27] = '-Isystem/core/libsystem/include'
# Raw param [28] = '-Isystem/core/libprocessgroup/include'
# Raw param [29] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [30] = '-Isystem/libfmq/include'
# Raw param [31] = '-Isystem/libhidl/base/include'
# Raw param [32] = '-Isystem/libhidl/transport/include'
# Raw param [33] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [34] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [35] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen'
# Raw param [36] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [37] = '-Isystem/libhwbinder/include'
# Raw param [38] = '-Isystem/libhidl/libhidlmemory/include'
# Raw param [39] = '-Iout/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen'
# Raw param [40] = '-Iout/soong/.intermediates/system/libhidl/transport/memory/token/1.0/android.hidl.memory.token@1.0_genc++_headers/gen'
# Raw param [41] = '-Ihardware/libhardware/include'
# Raw param [42] = '-Isystem/media/audio/include'
# Raw param [43] = '-Isystem/bt/types'
# Raw param [44] = '-Iframeworks/native/libs/ui/include'
# Raw param [45] = '-Iframeworks/native/libs/math/include'
# Raw param [46] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen'
# Raw param [47] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen'
# Raw param [48] = '-Iout/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen'
# Raw param [49] = '-Iout/soong/.intermediates/hardware/interfaces/neuralnetworks/1.0/android.hardware.neuralnetworks@1.0_genc++_headers/gen'
# Raw param [50] = '-Iout/soong/.intermediates/hardware/interfaces/neuralnetworks/1.1/android.hardware.neuralnetworks@1.1_genc++_headers/gen'
# Raw param [51] = '-Iout/soong/.intermediates/system/libhidl/transport/safe_union/1.0/android.hidl.safe_union@1.0_genc++_headers/gen'
# Raw param [52] = '-Iout/soong/.intermediates/hardware/interfaces/neuralnetworks/1.2/android.hardware.neuralnetworks@1.2_genc++_headers/gen'
# Raw param [53] = '-Iout/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen'
# Raw param [54] = '-Iexternal/libcxxabi/include'
# Raw param [55] = '-Ibionic/libc/include'
# Raw param [56] = '-D__LIBC_API__=10000'
# Raw param [57] = '-D__LIBM_API__=10000'
# Raw param [58] = '-D__LIBDL_API__=10000'
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
    "${ANDROID_ROOT}/frameworks/ml/nn/runtime/test"
    "${ANDROID_ROOT}/frameworks/ml/nn/tools/test_generator/include"
    "${ANDROID_ROOT}/frameworks/ml/nn/runtime"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/boringssl/src/include"
    "${ANDROID_ROOT}/external/googletest/googlemock/include"
    "${ANDROID_ROOT}/frameworks/ml/nn/runtime/include"
    "${ANDROID_ROOT}/frameworks/native/cmds/lshal/libprocpartition/include"
    "${ANDROID_ROOT}/build/soong/cc/libbuildversion/include"
    "${ANDROID_ROOT}/frameworks/ml/nn/common/include"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include"
    "${ANDROID_ROOT}/frameworks/ml/nn/driver/sample"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/system/libfmq/include"
    "${ANDROID_ROOT}/system/libhidl/base/include"
    "${ANDROID_ROOT}/system/libhidl/transport/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhwbinder/include"
    "${ANDROID_ROOT}/system/libhidl/libhidlmemory/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/token/1.0/android.hidl.memory.token@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/neuralnetworks/1.0/android.hardware.neuralnetworks@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/neuralnetworks/1.1/android.hardware.neuralnetworks@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/safe_union/1.0/android.hidl.safe_union@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/neuralnetworks/1.2/android.hardware.neuralnetworks@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/ml/nn/runtime/test/**/*.h"
    "${ANDROID_ROOT}/frameworks/ml/nn/tools/test_generator/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/ml/nn/runtime/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/boringssl/src/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googlemock/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/ml/nn/runtime/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/cmds/lshal/libprocpartition/include/**/*.h"
    "${ANDROID_ROOT}/build/soong/cc/libbuildversion/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/ml/nn/common/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/arect/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/ml/nn/driver/sample/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativewindow/include-private/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/nativebase/include/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm64_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/system/libfmq/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/base/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhwbinder/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/libhidlmemory/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/1.0/android.hidl.memory@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/memory/token/1.0/android.hidl.memory.token@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/ui/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/math/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.0/android.hardware.graphics.common@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.1/android.hardware.graphics.common@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/graphics/common/1.2/android.hardware.graphics.common@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/neuralnetworks/1.0/android.hardware.neuralnetworks@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/neuralnetworks/1.1/android.hardware.neuralnetworks@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/safe_union/1.0/android.hidl.safe_union@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/neuralnetworks/1.2/android.hardware.neuralnetworks@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/allocator/1.0/android.hidl.allocator@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-Wall'
# Raw param [1] = '-Wextra'
# Raw param [2] = '-Werror'
# Raw param [3] = '-O3'
# Raw param [4] = '-DNNTEST_MULTITHREADED'
# Raw param [5] = '-DNN_DEBUGGABLE'
# Raw param [6] = '-target aarch64-linux-android'
# Raw param [7] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [8] = '-DANDROID_STRICT'
# Raw param [9] = '-fPIE'
# Raw param [10] = '-DGTEST_HAS_STD_STRING'
# Raw param [11] = '-DGTEST_OS_LINUX_ANDROID'
# Raw param [12] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Wextra' became -Wextra
# FLAG '-Werror' became -Werror
# FLAG '-O3' became -O3
# FLAG '-DNNTEST_MULTITHREADED' became -DNNTEST_MULTITHREADED
# FLAG '-DNN_DEBUGGABLE' became -DNN_DEBUGGABLE
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-DGTEST_OS_LINUX_ANDROID' became -DGTEST_OS_LINUX_ANDROID
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wextra")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -O3")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNNTEST_MULTITHREADED")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DNN_DEBUGGABLE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wextra")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -O3")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNNTEST_MULTITHREADED")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DNN_DEBUGGABLE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGTEST_OS_LINUX_ANDROID")
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


add_executable(NeuralNetworksTest_mt_static ${SOURCE_FILES})
