# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(trace_to_text)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen/gen/external/perfetto/protos/perfetto/common/android_log_constants.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen/gen/external/perfetto/protos/perfetto/common/commit_data_request.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen/gen/external/perfetto/protos/perfetto/common/descriptor.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen/gen/external/perfetto/protos/perfetto/common/observable_events.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen/gen/external/perfetto/protos/perfetto/common/sys_stats_counters.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen/gen/external/perfetto/protos/perfetto/common/trace_stats.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen/gen/external/perfetto/protos/perfetto/common/android_log_constants.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen/gen/external/perfetto/protos/perfetto/common/commit_data_request.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen/gen/external/perfetto/protos/perfetto/common/descriptor.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen/gen/external/perfetto/protos/perfetto/common/observable_events.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen/gen/external/perfetto/protos/perfetto/common/sys_stats_counters.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen/gen/external/perfetto/protos/perfetto/common/trace_stats.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/android/android_log_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/android/packages_list_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/chrome/chrome_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/data_source_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/data_source_descriptor.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/ftrace/ftrace_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/inode_file/inode_file_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/power/android_power_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/process_stats/process_stats_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/profiling/heapprofd_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/sys_stats/sys_stats_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/test_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen/gen/external/perfetto/protos/perfetto/config/trace_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/android/android_log_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/android/packages_list_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/chrome/chrome_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/data_source_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/data_source_descriptor.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/ftrace/ftrace_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/inode_file/inode_file_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/power/android_power_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/process_stats/process_stats_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/profiling/heapprofd_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/sys_stats/sys_stats_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/test_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen/gen/external/perfetto/protos/perfetto/config/trace_config.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_android_zero_gen/gen/external/perfetto/protos/perfetto/metrics/android/mem_metric.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_zero_gen/gen/external/perfetto/protos/perfetto/metrics/metrics.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_lite_gen/gen/external/perfetto/protos/perfetto/trace/android/android_log.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_lite_gen/gen/external/perfetto/protos/perfetto/trace/android/packages_list.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_zero_gen/gen/external/perfetto/protos/perfetto/trace/android/android_log.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_zero_gen/gen/external/perfetto/protos/perfetto/trace/android/packages_list.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_lite_gen/gen/external/perfetto/protos/perfetto/trace/chrome/chrome_trace_event.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_zero_gen/gen/external/perfetto/protos/perfetto/trace/chrome/chrome_trace_event.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_lite_gen/gen/external/perfetto/protos/perfetto/trace/filesystem/inode_file_map.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_zero_gen/gen/external/perfetto/protos/perfetto/trace/filesystem/inode_file_map.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/binder.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/block.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/cgroup.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/clk.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/compaction.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ext4.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/f2fs.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/fence.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/filemap.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace_event.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace_event_bundle.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace_stats.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/generic.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/i2c.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ipi.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/irq.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/kmem.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/lowmemorykiller.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/mdss.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/mm_event.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/oom.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/power.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/raw_syscalls.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/regulator.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/sched.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/signal.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/sync.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/systrace.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/task.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/test_bundle_wrapper.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/vmscan.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/workqueue.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/binder.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/block.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/cgroup.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/clk.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/compaction.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ext4.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/f2fs.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/fence.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/filemap.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace_event.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace_event_bundle.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ftrace_stats.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/generic.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/i2c.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/ipi.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/irq.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/kmem.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/lowmemorykiller.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/mdss.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/mm_event.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/oom.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/power.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/raw_syscalls.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/regulator.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/sched.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/signal.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/sync.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/systrace.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/task.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/test_bundle_wrapper.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/vmscan.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen/gen/external/perfetto/protos/perfetto/trace/ftrace/workqueue.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_lite_gen/gen/external/perfetto/protos/perfetto/trace/interned_data/interned_data.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_zero_gen/gen/external/perfetto/protos/perfetto/trace/interned_data/interned_data.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_lite_gen/gen/external/perfetto/protos/perfetto/trace/test_event.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_lite_gen/gen/external/perfetto/protos/perfetto/trace/trace.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_lite_gen/gen/external/perfetto/protos/perfetto/trace/trace_packet.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_minimal_lite_gen/gen/external/perfetto/protos/perfetto/trace/clock_snapshot.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_minimal_lite_gen/gen/external/perfetto/protos/perfetto/trace/system_info.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_minimal_lite_gen/gen/external/perfetto/protos/perfetto/trace/trigger.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_lite_gen/gen/external/perfetto/protos/perfetto/trace/power/battery_counters.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_lite_gen/gen/external/perfetto/protos/perfetto/trace/power/power_rails.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_zero_gen/gen/external/perfetto/protos/perfetto/trace/power/battery_counters.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_zero_gen/gen/external/perfetto/protos/perfetto/trace/power/power_rails.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_lite_gen/gen/external/perfetto/protos/perfetto/trace/profiling/profile_packet.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_zero_gen/gen/external/perfetto/protos/perfetto/trace/profiling/profile_packet.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_lite_gen/gen/external/perfetto/protos/perfetto/trace/ps/process_stats.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_lite_gen/gen/external/perfetto/protos/perfetto/trace/ps/process_tree.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_zero_gen/gen/external/perfetto/protos/perfetto/trace/ps/process_stats.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_zero_gen/gen/external/perfetto/protos/perfetto/trace/ps/process_tree.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_lite_gen/gen/external/perfetto/protos/perfetto/trace/sys_stats/sys_stats.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_zero_gen/gen/external/perfetto/protos/perfetto/trace/sys_stats/sys_stats.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen/gen/external/perfetto/protos/perfetto/trace/track_event/debug_annotation.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen/gen/external/perfetto/protos/perfetto/trace/track_event/process_descriptor.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen/gen/external/perfetto/protos/perfetto/trace/track_event/task_execution.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen/gen/external/perfetto/protos/perfetto/trace/track_event/thread_descriptor.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen/gen/external/perfetto/protos/perfetto/trace/track_event/track_event.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen/gen/external/perfetto/protos/perfetto/trace/track_event/debug_annotation.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen/gen/external/perfetto/protos/perfetto/trace/track_event/process_descriptor.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen/gen/external/perfetto/protos/perfetto/trace/track_event/task_execution.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen/gen/external/perfetto/protos/perfetto/trace/track_event/thread_descriptor.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen/gen/external/perfetto/protos/perfetto/trace/track_event/track_event.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen/gen/external/perfetto/protos/perfetto/trace/clock_snapshot.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen/gen/external/perfetto/protos/perfetto/trace/system_info.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen/gen/external/perfetto/protos/perfetto/trace/test_event.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen/gen/external/perfetto/protos/perfetto/trace/trace.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen/gen/external/perfetto/protos/perfetto/trace/trace_packet.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen/gen/external/perfetto/protos/perfetto/trace/trigger.pbzero.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_third_party_pprof_lite_gen/gen/external/perfetto/protos/third_party/pprof/profile.pb.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/event.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/file_utils.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/metatrace.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/paged_memory.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/pipe.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/string_splitter.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/string_utils.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/string_view.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/temp_file.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/thread_checker.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/thread_task_runner.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/time.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/unix_task_runner.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/virtual_destructors.cc
    ${ANDROID_ROOT}/external/perfetto/src/base/watchdog_posix.cc
    ${ANDROID_ROOT}/external/perfetto/src/protozero/message.cc
    ${ANDROID_ROOT}/external/perfetto/src/protozero/message_handle.cc
    ${ANDROID_ROOT}/external/perfetto/src/protozero/proto_decoder.cc
    ${ANDROID_ROOT}/external/perfetto/src/protozero/scattered_heap_buffer.cc
    ${ANDROID_ROOT}/external/perfetto/src/protozero/scattered_stream_null_delegate.cc
    ${ANDROID_ROOT}/external/perfetto/src/protozero/scattered_stream_writer.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/android_logs_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/args_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/args_tracker.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/clock_tracker.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/counter_definitions_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/counter_values_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/event_tracker.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/filtered_row_index.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/ftrace_descriptors.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/ftrace_utils.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/fuchsia_provider_view.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/fuchsia_trace_parser.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/fuchsia_trace_tokenizer.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/fuchsia_trace_utils.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/heap_profile_tracker.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/instants_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/metrics/metrics.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/process_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/process_tracker.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/proto_trace_parser.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/proto_trace_tokenizer.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/query_constraints.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/raw_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/row_iterators.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/sched_slice_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/slice_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/slice_tracker.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/span_join_operator_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/sql_stats_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/sqlite3_str_split.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/stats_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/storage_columns.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/storage_schema.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/storage_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/string_pool.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/string_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/syscall_tracker.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/thread_table.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/trace_processor.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/trace_processor_context.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/trace_processor_impl.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/trace_sorter.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/trace_storage.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/virtual_destructors.cc
    ${ANDROID_ROOT}/external/perfetto/src/trace_processor/window_operator_table.cc
    ${ANDROID_ROOT}/external/perfetto/tools/trace_to_text/main.cc
    ${ANDROID_ROOT}/external/perfetto/tools/trace_to_text/proto_full_utils.cc
    ${ANDROID_ROOT}/external/perfetto/tools/trace_to_text/trace_to_profile.cc
    ${ANDROID_ROOT}/external/perfetto/tools/trace_to_text/trace_to_systrace.cc
    ${ANDROID_ROOT}/external/perfetto/tools/trace_to_text/trace_to_text.cc
    ${ANDROID_ROOT}/external/perfetto/tools/trace_to_text/utils.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/perfetto/include'
# Raw param [2] = '-Iexternal/perfetto'
# Raw param [3] = ''
# Raw param [4] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.HostClangGlobalCflags}'
# Raw param [7] = ''
# Raw param [8] = '-Iexternal/googletest/googletest/include'
# Raw param [9] = '-Iexternal/sqlite/dist'
# Raw param [10] = '-Iexternal/sqlite/android'
# Raw param [11] = '-Isystem/core/liblog/include'
# Raw param [12] = '-Iexternal/protobuf/src'
# Raw param [13] = '-Iexternal/libcxx/include'
# Raw param [14] = '-Iexternal/libcxxabi/include'
# Raw param [15] = '-Iout/soong/.intermediates/external/perfetto/gen_merged_sql_metrics/gen'
# Raw param [16] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [17] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [18] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [19] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [20] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_android_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [21] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [22] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [23] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [24] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [25] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [26] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [27] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [28] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [29] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [30] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [31] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [32] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [33] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_minimal_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [34] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [35] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [36] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [37] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [38] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [39] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [40] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [41] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [42] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen_headers/gen/external/perfetto/protos'
# Raw param [43] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [44] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen_headers/gen/external/perfetto/protos'
# Raw param [45] = '-Iout/soong/.intermediates/external/perfetto/perfetto_protos_third_party_pprof_lite_gen_headers/gen/external/perfetto/protos'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
# variable ${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags} = '-Wa,--noexecstack -fPIC -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=2 -fstack-protector -D__STDC_FORMAT_MACROS -D__STDC_CONSTANT_MACROS --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8 --sysroot prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8/sysroot -fstack-protector-strong -m64'
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
# Raw param [11] = '-m64'
# FLAG '-Wa,--noexecstack' became -Wa,--noexecstack
# FLAG '-fPIC' became -fPIC
# FLAG '-U_FORTIFY_SOURCE' became -U_FORTIFY_SOURCE
# FLAG '-D_FORTIFY_SOURCE=2' became -D_FORTIFY_SOURCE=2
# FLAG '-fstack-protector' became -fstack-protector
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '--gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8' became --gcc-toolchain=prebuilts/gcc/linux-x86/host/x86_64-linux-glibc2.17-4.8
# FLAG '-fstack-protector-strong' became -fstack-protector-strong
# FLAG '-m64' became -m64
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
    "${ANDROID_ROOT}/external/perfetto/include"
    "${ANDROID_ROOT}/external/perfetto"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/external/sqlite/dist"
    "${ANDROID_ROOT}/external/sqlite/android"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/gen_merged_sql_metrics/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_android_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_minimal_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen_headers/gen/external/perfetto/protos"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_third_party_pprof_lite_gen_headers/gen/external/perfetto/protos"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/perfetto/include/**/*.h"
    "${ANDROID_ROOT}/external/perfetto/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/external/sqlite/dist/**/*.h"
    "${ANDROID_ROOT}/external/sqlite/android/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/gen_merged_sql_metrics/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_common_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_config_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_android_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_metrics_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_android_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_chrome_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_filesystem_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ftrace_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_interned_data_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_minimal_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_power_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_profiling_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_ps_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_sys_stats_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_track_event_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_perfetto_trace_zero_gen_headers/gen/external/perfetto/protos/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/perfetto/perfetto_protos_third_party_pprof_lite_gen_headers/gen/external/perfetto/protos/**/*.h"
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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -m64")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -m64")
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
# Raw param [2] = '-Oz'
# Raw param [3] = '-Wno-error=return-type'
# Raw param [4] = '-Wno-sign-compare'
# Raw param [5] = '-Wno-sign-promo'
# Raw param [6] = '-Wno-unused-parameter'
# Raw param [7] = '-fvisibility=hidden'
# Raw param [8] = '-DGOOGLE_PROTOBUF_NO_RTTI'
# Raw param [9] = '-DGOOGLE_PROTOBUF_NO_STATIC_INITIALIZER'
# Raw param [10] = '-DPERFETTO_BUILD_WITH_ANDROID'
# Raw param [11] = '-DPERFETTO_BUILD_WITH_ANDROID_USERDEBUG'
# Raw param [12] = '-target x86_64-linux-gnu'
# Raw param [13] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [14] = '-fPIE'
# Raw param [15] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Oz' became -Oz
# FLAG '-Wno-error=return-type' became -Wno-error=return-type
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-DGOOGLE_PROTOBUF_NO_RTTI' became -DGOOGLE_PROTOBUF_NO_RTTI
# FLAG '-DGOOGLE_PROTOBUF_NO_STATIC_INITIALIZER' became -DGOOGLE_PROTOBUF_NO_STATIC_INITIALIZER
# FLAG '-DPERFETTO_BUILD_WITH_ANDROID' became -DPERFETTO_BUILD_WITH_ANDROID
# FLAG '-DPERFETTO_BUILD_WITH_ANDROID_USERDEBUG' became -DPERFETTO_BUILD_WITH_ANDROID_USERDEBUG
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIE' became -fPIE
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Oz")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-error=return-type")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-promo")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGOOGLE_PROTOBUF_NO_STATIC_INITIALIZER")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DPERFETTO_BUILD_WITH_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DPERFETTO_BUILD_WITH_ANDROID_USERDEBUG")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Oz")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-error=return-type")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGOOGLE_PROTOBUF_NO_STATIC_INITIALIZER")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DPERFETTO_BUILD_WITH_ANDROID")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DPERFETTO_BUILD_WITH_ANDROID_USERDEBUG")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIE")
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
# Raw param [3] = ''
# Raw param [4] = '-nostdinc++'
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
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
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


add_executable(trace_to_text ${SOURCE_FILES})
