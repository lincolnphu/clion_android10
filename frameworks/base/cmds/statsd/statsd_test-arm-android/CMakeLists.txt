# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(statsd_test)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/aidl/frameworks/base/core/java/android/os/IStatsCompanionService.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/aidl/frameworks/base/core/java/android/os/IStatsManager.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/aidl/frameworks/base/core/java/android/os/IStatsPullerCallback.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/active_config_list.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/statsd_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/uid_data.pb.cc
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/FieldValue.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/hash.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/stats_log_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/anomaly/AlarmMonitor.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/anomaly/AlarmTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/anomaly/AnomalyTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/anomaly/DurationAnomalyTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/anomaly/subscriber_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/condition/CombinationConditionTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/condition/condition_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/condition/SimpleConditionTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/condition/ConditionWizard.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/condition/StateTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/config/ConfigKey.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/config/ConfigListener.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/config/ConfigManager.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/GpuStatsPuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/Perfetto.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/Perfprofd.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/StatsPuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/StatsCallbackPuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/StatsCompanionServicePuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/SubsystemSleepStatePuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/PowerStatsPuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/ResourceHealthManagerPuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/TrainInfoPuller.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/StatsPullerManager.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/external/puller_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/logd/LogEvent.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/logd/LogEventQueue.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/matchers/CombinationLogMatchingTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/matchers/EventMatcherWizard.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/matchers/matcher_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/matchers/SimpleLogMatchingTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/MetricProducer.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/EventMetricProducer.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/CountMetricProducer.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/DurationMetricProducer.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/duration_helper/OringDurationTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/duration_helper/MaxDurationTracker.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/ValueMetricProducer.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/GaugeMetricProducer.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/MetricsManager.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/metrics/metrics_manager_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/packages/UidMap.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/storage/StorageManager.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/StatsLogProcessor.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/StatsService.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/statscompanion_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/subscriber/IncidentdReporter.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/subscriber/SubscriberReporter.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/HashableDimensionKey.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/guardrail/StatsdStats.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/socket/StatsSocketListener.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/shell/ShellSubscriber.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/shell/shell_config.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/aidl/system/extras/perfprofd/binder_interface/aidl/android/os/IPerfProfd.cpp
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/atom_field_options.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/atoms.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/stats_log.pb.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/src/shell/shell_data.pb.cc
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/AlarmMonitor_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/anomaly/AlarmTracker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/anomaly/AnomalyTracker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/ConfigManager_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/external/puller_util_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/external/GpuStatsPuller_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/external/IncidentReportArgs_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/external/StatsPuller_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/indexed_priority_queue_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/LogEntryMatcher_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/LogEvent_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/log_event/LogEventQueue_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/MetricsManager_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/StatsLogProcessor_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/StatsService_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/UidMap_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/FieldValue_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/condition/CombinationConditionTracker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/condition/SimpleConditionTracker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/condition/StateTracker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/condition/ConditionTimer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/OringDurationTracker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/MaxDurationTracker_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/CountMetricProducer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/DurationMetricProducer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/EventMetricProducer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/ValueMetricProducer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/GaugeMetricProducer_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/guardrail/StatsdStats_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/metrics/metrics_test_helper.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/statsd_test_util.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/storage/StorageManager_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/WakelockDuration_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/MetricActivation_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/MetricConditionLink_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/Alarm_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/Attribution_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/GaugeMetric_e2e_push_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/GaugeMetric_e2e_pull_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/ValueMetric_pull_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/DimensionInCondition_e2e_combination_AND_cond_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/DimensionInCondition_e2e_combination_OR_cond_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/DimensionInCondition_e2e_simple_cond_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/Anomaly_count_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/Anomaly_duration_sum_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/ConfigTtl_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/PartialBucket_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/e2e/DurationMetric_e2e_test.cpp
    ${ANDROID_ROOT}/frameworks/base/cmds/statsd/tests/shell/ShellSubscriber_test.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '-Iframeworks/base/cmds/statsd/src'
# Raw param [1] = '-Iframeworks/base/cmds/statsd'
# Raw param [2] = '${config.ArmClangThumbCflags}'
# Raw param [3] = '${config.ArmClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.DeviceClangGlobalCflags}'
# Raw param [6] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [7] = '-Iout/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd'
# Raw param [8] = '-Iout/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto'
# Raw param [9] = '-Iout/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/aidl'
# Raw param [10] = '-Iexternal/googletest/googletest/include'
# Raw param [11] = '-Ihardware/interfaces/health/2.0/utils/libhealthhalutils/include'
# Raw param [12] = '-Iexternal/googletest/googlemock/include'
# Raw param [13] = '-Iexternal/protobuf/src'
# Raw param [14] = '-Iout/soong/.intermediates/frameworks/base/libplatformprotos/android_arm_armv8-a_kryo_core_static/gen/proto/frameworks/base'
# Raw param [15] = '-Iout/soong/.intermediates/frameworks/base/libplatformprotos/android_arm_armv8-a_kryo_core_static/gen/proto'
# Raw param [16] = '-Isystem/core/base/include'
# Raw param [17] = '-Iframeworks/native/libs/binder/include'
# Raw param [18] = '-Isystem/core/libcutils/include'
# Raw param [19] = '-Isystem/core/libutils/include'
# Raw param [20] = '-Isystem/core/libbacktrace/include'
# Raw param [21] = '-Isystem/core/liblog/include'
# Raw param [22] = '-Isystem/core/libsystem/include'
# Raw param [23] = '-Isystem/core/libprocessgroup/include'
# Raw param [24] = '-Iout/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [25] = '-Iframeworks/native/libs/graphicsenv/include'
# Raw param [26] = '-Iframeworks/base/libs/incident/include'
# Raw param [27] = '-Iframeworks/native/libs/incidentcompanion/binder'
# Raw param [28] = '-Iframeworks/native/libs/incidentcompanion/include'
# Raw param [29] = '-Iout/soong/.intermediates/frameworks/native/libs/incidentcompanion/libincidentcompanion/android_arm_armv8-a_kryo_core_static/gen/aidl'
# Raw param [30] = '-Iout/soong/.intermediates/frameworks/base/libs/incident/libincident/android_arm_armv8-a_kryo_core_shared/gen/aidl'
# Raw param [31] = '-Iframeworks/base/libs/services/include'
# Raw param [32] = '-Iframeworks/base/libs/protoutil/include'
# Raw param [33] = '-Iout/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen'
# Raw param [34] = '-Ihardware/libhardware/include'
# Raw param [35] = '-Isystem/media/audio/include'
# Raw param [36] = '-Isystem/bt/types'
# Raw param [37] = '-Ihardware/libhardware_legacy/include'
# Raw param [38] = '-Isystem/libhidl/base/include'
# Raw param [39] = '-Isystem/libhidl/transport/include'
# Raw param [40] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen'
# Raw param [41] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen'
# Raw param [42] = '-Iout/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen'
# Raw param [43] = '-Iout/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen'
# Raw param [44] = '-Isystem/libhwbinder/include'
# Raw param [45] = '-Iout/soong/.intermediates/frameworks/hardware/interfaces/stats/1.0/android.frameworks.stats@1.0_genc++_headers/gen'
# Raw param [46] = '-Iout/soong/.intermediates/hardware/interfaces/health/1.0/android.hardware.health@1.0_genc++_headers/gen'
# Raw param [47] = '-Iout/soong/.intermediates/hardware/interfaces/health/2.0/android.hardware.health@2.0_genc++_headers/gen'
# Raw param [48] = '-Iout/soong/.intermediates/hardware/interfaces/power/1.0/android.hardware.power@1.0_genc++_headers/gen'
# Raw param [49] = '-Iout/soong/.intermediates/hardware/interfaces/power/1.1/android.hardware.power@1.1_genc++_headers/gen'
# Raw param [50] = '-Iout/soong/.intermediates/hardware/interfaces/power/stats/1.0/android.hardware.power.stats@1.0_genc++_headers/gen'
# Raw param [51] = '-Isystem/core/libpackagelistparser/include'
# Raw param [52] = '-Isystem/core/libsysutils/include'
# Raw param [53] = '-Iexternal/libcxx/include'
# Raw param [54] = '-Iexternal/libcxxabi/include'
# Raw param [55] = '-Ibionic/libc/include'
# Raw param [56] = '-D__LIBC_API__=10000'
# Raw param [57] = '-D__LIBM_API__=10000'
# Raw param [58] = '-D__LIBDL_API__=10000'
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
# FLAG '-D__LIBC_API__=10000' became -D__LIBC_API__=10000
# FLAG '-D__LIBM_API__=10000' became -D__LIBM_API__=10000
# FLAG '-D__LIBDL_API__=10000' became -D__LIBDL_API__=10000
include_directories( 
    "${ANDROID_ROOT}/frameworks/base/cmds/statsd/src"
    "${ANDROID_ROOT}/frameworks/base/cmds/statsd"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/aidl"
    "${ANDROID_ROOT}/external/googletest/googletest/include"
    "${ANDROID_ROOT}/hardware/interfaces/health/2.0/utils/libhealthhalutils/include"
    "${ANDROID_ROOT}/external/googletest/googlemock/include"
    "${ANDROID_ROOT}/external/protobuf/src"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm_armv8-a_kryo_core_static/gen/proto/frameworks/base"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm_armv8-a_kryo_core_static/gen/proto"
    "${ANDROID_ROOT}/system/core/base/include"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include"
    "${ANDROID_ROOT}/system/core/libcutils/include"
    "${ANDROID_ROOT}/system/core/libutils/include"
    "${ANDROID_ROOT}/system/core/libbacktrace/include"
    "${ANDROID_ROOT}/system/core/liblog/include"
    "${ANDROID_ROOT}/system/core/libsystem/include"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/native/libs/graphicsenv/include"
    "${ANDROID_ROOT}/frameworks/base/libs/incident/include"
    "${ANDROID_ROOT}/frameworks/native/libs/incidentcompanion/binder"
    "${ANDROID_ROOT}/frameworks/native/libs/incidentcompanion/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/incidentcompanion/libincidentcompanion/android_arm_armv8-a_kryo_core_static/gen/aidl"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/incident/libincident/android_arm_armv8-a_kryo_core_shared/gen/aidl"
    "${ANDROID_ROOT}/frameworks/base/libs/services/include"
    "${ANDROID_ROOT}/frameworks/base/libs/protoutil/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen"
    "${ANDROID_ROOT}/hardware/libhardware/include"
    "${ANDROID_ROOT}/system/media/audio/include"
    "${ANDROID_ROOT}/system/bt/types"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include"
    "${ANDROID_ROOT}/system/libhidl/base/include"
    "${ANDROID_ROOT}/system/libhidl/transport/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/libhwbinder/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/hardware/interfaces/stats/1.0/android.frameworks.stats@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/health/1.0/android.hardware.health@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/health/2.0/android.hardware.health@2.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/power/1.0/android.hardware.power@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/power/1.1/android.hardware.power@1.1_genc++_headers/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/power/stats/1.0/android.hardware.power.stats@1.0_genc++_headers/gen"
    "${ANDROID_ROOT}/system/core/libpackagelistparser/include"
    "${ANDROID_ROOT}/system/core/libsysutils/include"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/frameworks/base/cmds/statsd/src/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/cmds/statsd/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/frameworks/base/cmds/statsd/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/proto/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/cmds/statsd/statsd_test/android_arm_armv8-a_kryo_core/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googletest/include/**/*.h"
    "${ANDROID_ROOT}/hardware/interfaces/health/2.0/utils/libhealthhalutils/include/**/*.h"
    "${ANDROID_ROOT}/external/googletest/googlemock/include/**/*.h"
    "${ANDROID_ROOT}/external/protobuf/src/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm_armv8-a_kryo_core_static/gen/proto/frameworks/base/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libplatformprotos/android_arm_armv8-a_kryo_core_static/gen/proto/**/*.h"
    "${ANDROID_ROOT}/system/core/base/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/binder/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libcutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libutils/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libbacktrace/include/**/*.h"
    "${ANDROID_ROOT}/system/core/liblog/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsystem/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libprocessgroup/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/binder/libbinder/android_arm_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/graphicsenv/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/incident/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/incidentcompanion/binder/**/*.h"
    "${ANDROID_ROOT}/frameworks/native/libs/incidentcompanion/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/native/libs/incidentcompanion/libincidentcompanion/android_arm_armv8-a_kryo_core_static/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/libs/incident/libincident/android_arm_armv8-a_kryo_core_shared/gen/aidl/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/services/include/**/*.h"
    "${ANDROID_ROOT}/frameworks/base/libs/protoutil/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/base/tools/stats_log_api_gen/statslog.h/gen/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware/include/**/*.h"
    "${ANDROID_ROOT}/system/media/audio/include/**/*.h"
    "${ANDROID_ROOT}/system/bt/types/**/*.h"
    "${ANDROID_ROOT}/hardware/libhardware_legacy/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/base/include/**/*.h"
    "${ANDROID_ROOT}/system/libhidl/transport/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.0/android.hidl.manager@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.1/android.hidl.manager@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/manager/1.2/android.hidl.manager@1.2_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/system/libhidl/transport/base/1.0/android.hidl.base@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/libhwbinder/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/frameworks/hardware/interfaces/stats/1.0/android.frameworks.stats@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/health/1.0/android.hardware.health@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/health/2.0/android.hardware.health@2.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/power/1.0/android.hardware.power@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/power/1.1/android.hardware.power@1.1_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/hardware/interfaces/power/stats/1.0/android.hardware.power.stats@1.0_genc++_headers/gen/**/*.h"
    "${ANDROID_ROOT}/system/core/libpackagelistparser/include/**/*.h"
    "${ANDROID_ROOT}/system/core/libsysutils/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

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
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__LIBDL_API__=10000")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBC_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBM_API__=10000")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__LIBDL_API__=10000")

# CFLAGS:
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-missing-field-initializers'
# Raw param [3] = '-Wno-unused-variable'
# Raw param [4] = '-Wno-unused-function'
# Raw param [5] = '-Wno-unused-parameter'
# Raw param [6] = '-target armv7a-linux-androideabi'
# Raw param [7] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [8] = '-DANDROID_STRICT'
# Raw param [9] = '-DGOOGLE_PROTOBUF_NO_RTTI'
# Raw param [10] = '-fPIE'
# Raw param [11] = '-DGTEST_HAS_STD_STRING'
# Raw param [12] = '-DGTEST_OS_LINUX_ANDROID'
# Raw param [13] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-DANDROID_STRICT' became -DANDROID_STRICT
# FLAG '-DGOOGLE_PROTOBUF_NO_RTTI' became -DGOOGLE_PROTOBUF_NO_RTTI
# FLAG '-fPIE' became -fPIE
# FLAG '-DGTEST_HAS_STD_STRING' became -DGTEST_HAS_STD_STRING
# FLAG '-DGTEST_OS_LINUX_ANDROID' became -DGTEST_OS_LINUX_ANDROID
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_STRICT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_HAS_STD_STRING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DGTEST_OS_LINUX_ANDROID")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_STRICT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DGOOGLE_PROTOBUF_NO_RTTI")
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
# Raw param [4] = '${config.ArmClangCppflags}'
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
# variable ${config.ArmClangCppflags} = ''
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
# Raw param [1] = '${config.ArmIncludeFlags}'
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
# variable ${config.ArmIncludeFlags} = '-isystem bionic/libc/include -isystem bionic/libc/kernel/uapi -isystem bionic/libc/kernel/uapi/asm-arm -isystem bionic/libc/kernel/android/scsi -isystem bionic/libc/kernel/android/uapi'
# Raw param [0] = '-isystem'
# Raw param [1] = 'bionic/libc/include'
# Raw param [2] = '-isystem'
# Raw param [3] = 'bionic/libc/kernel/uapi'
# Raw param [4] = '-isystem'
# Raw param [5] = 'bionic/libc/kernel/uapi/asm-arm'
# Raw param [6] = '-isystem'
# Raw param [7] = 'bionic/libc/kernel/android/scsi'
# Raw param [8] = '-isystem'
# Raw param [9] = 'bionic/libc/kernel/android/uapi'
# variable ${config.CommonNativehelperInclude} = '-Ilibnativehelper/include_jni'
# Raw param [0] = '-Ilibnativehelper/include_jni'
include_directories(SYSTEM 
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/scsi"
    "${ANDROID_ROOT}/bionic/libc/kernel/android/uapi"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/kernel/uapi/asm-arm/**/*.h"
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


add_executable(statsd_test ${SOURCE_FILES})
