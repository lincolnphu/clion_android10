# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libLLVMCodeGen)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/AggressiveAntiDepBreaker.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/AllocationOrder.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/Analysis.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/AtomicExpandPass.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/BasicTargetTransformInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/BranchFolding.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/BuiltinGCs.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/CalcSpillWeights.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/CallingConvLower.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/CodeGen.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/CodeGenPrepare.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/CriticalAntiDepBreaker.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/DFAPacketizer.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/DeadMachineInstructionElim.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/DetectDeadLanes.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/DwarfEHPrepare.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/EarlyIfConversion.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/EdgeBundles.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ExecutionDepsFix.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ExpandISelPseudos.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ExpandPostRAPseudos.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/FaultMaps.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/FuncletLayout.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/GCMetadata.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/GCMetadataPrinter.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/GCRootLowering.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/GCStrategy.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/GlobalMerge.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/IfConversion.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ImplicitNullChecks.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/InlineSpiller.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/InterferenceCache.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/InterleavedAccessPass.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/IntrinsicLowering.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LLVMTargetMachine.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LatencyPriorityQueue.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LexicalScopes.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveDebugValues.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveDebugVariables.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveInterval.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveIntervalAnalysis.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveIntervalUnion.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LivePhysRegs.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveRangeCalc.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveRangeEdit.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveRegMatrix.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveStackAnalysis.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LiveVariables.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LocalStackSlotAllocation.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/LowerEmuTLS.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MIRPrinter.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MIRPrintingPass.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineBasicBlock.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineBlockFrequencyInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineBlockPlacement.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineBranchProbabilityInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineCSE.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineCombiner.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineCopyPropagation.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineDominanceFrontier.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineDominators.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineFunction.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineFunctionAnalysis.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineFunctionPass.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineFunctionPrinterPass.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineInstr.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineInstrBundle.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineLICM.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineLoopInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineModuleInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineModuleInfoImpls.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachinePassRegistry.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachinePipeliner.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachinePostDominators.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineRegionInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineRegisterInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineSSAUpdater.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineScheduler.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineSink.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineTraceMetrics.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/MachineVerifier.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/OptimizePHIs.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PHIElimination.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PHIEliminationUtils.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ParallelCG.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PatchableFunction.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PeepholeOptimizer.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PostRAHazardRecognizer.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PostRASchedulerList.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PreISelIntrinsicLowering.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ProcessImplicitDefs.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PrologEpilogInserter.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/PseudoSourceValue.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegAllocBase.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegAllocBasic.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegAllocFast.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegAllocGreedy.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegAllocPBQP.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegUsageInfoCollector.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegUsageInfoPropagate.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegisterClassInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegisterCoalescer.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegisterPressure.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegisterScavenging.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RegisterUsageInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/RenameIndependentSubregs.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/SafeStack.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/SafeStackColoring.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/SafeStackLayout.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ScheduleDAG.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ScheduleDAGInstrs.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ScheduleDAGPrinter.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ScoreboardHazardRecognizer.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ShadowStackGCLowering.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/ShrinkWrap.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/SjLjEHPrepare.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/SlotIndexes.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/SpillPlacement.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/SplitKit.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/StackColoring.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/StackMapLivenessAnalysis.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/StackMaps.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/StackProtector.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/StackSlotColoring.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TailDuplication.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TailDuplicator.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetFrameLoweringImpl.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetInstrInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetLoweringBase.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetLoweringObjectFileImpl.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetOptionsImpl.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetPassConfig.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetRegisterInfo.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TargetSchedule.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/TwoAddressInstructionPass.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/UnreachableBlockElim.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/VirtRegMap.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/WinEHPrepare.cpp
    ${ANDROID_ROOT}/external/llvm/lib/CodeGen/XRayInstrumentation.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/llvm/lib/CodeGen'
# Raw param [2] = ''
# Raw param [3] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [4] = '${config.CommonClangGlobalCflags}'
# Raw param [5] = '${config.HostClangGlobalCflags}'
# Raw param [6] = ''
# Raw param [7] = '-Iexternal/llvm/include'
# Raw param [8] = '-Iexternal/llvm/host/include'
# Raw param [9] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-attributes/gen'
# Raw param [10] = '-Iout/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen'
# Raw param [11] = '-Iexternal/libcxx/include'
# Raw param [12] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/llvm/lib/CodeGen"
    "${ANDROID_ROOT}/external/llvm/include"
    "${ANDROID_ROOT}/external/llvm/host/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/llvm/lib/CodeGen/**/*.h"
    "${ANDROID_ROOT}/external/llvm/include/**/*.h"
    "${ANDROID_ROOT}/external/llvm/host/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-attributes/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/llvm/llvm-gen-intrinsics/gen/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
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
# Raw param [0] = '-D_GNU_SOURCE'
# Raw param [1] = '-D__STDC_LIMIT_MACROS'
# Raw param [2] = '-D__STDC_CONSTANT_MACROS'
# Raw param [3] = '-D__STDC_FORMAT_MACROS'
# Raw param [4] = '-fomit-frame-pointer'
# Raw param [5] = '-Wall'
# Raw param [6] = '-W'
# Raw param [7] = '-Wno-cast-qual'
# Raw param [8] = '-Wno-sign-compare'
# Raw param [9] = '-Wno-unused-parameter'
# Raw param [10] = '-Wno-missing-field-initializers'
# Raw param [11] = '-Wno-implicit-fallthrough'
# Raw param [12] = '-Wwrite-strings'
# Raw param [13] = '-Werror'
# Raw param [14] = '-Dsprintf=sprintf'
# Raw param [15] = '-W'
# Raw param [16] = '-Wall'
# Raw param [17] = '-Wno-unused-lambda-capture'
# Raw param [18] = '-Wno-unused-parameter'
# Raw param [19] = '-target x86_64-linux-gnu'
# Raw param [20] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [21] = '-fPIC'
# Raw param [22] = '-D_USING_LIBCXX'
# FLAG '-D_GNU_SOURCE' became -D_GNU_SOURCE
# FLAG '-D__STDC_LIMIT_MACROS' became -D__STDC_LIMIT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-Wall' became -Wall
# FLAG '-W' became -W
# FLAG '-Wno-cast-qual' became -Wno-cast-qual
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wwrite-strings' became -Wwrite-strings
# FLAG '-Werror' became -Werror
# FLAG '-Dsprintf=sprintf' became -Dsprintf=sprintf
# FLAG '-W' became -W
# FLAG '-Wall' became -Wall
# FLAG '-Wno-unused-lambda-capture' became -Wno-unused-lambda-capture
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_GNU_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-cast-qual")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wwrite-strings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Dsprintf=sprintf")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -W")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-lambda-capture")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_GNU_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-cast-qual")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wwrite-strings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Dsprintf=sprintf")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -W")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-lambda-capture")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
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
# Raw param [3] = '-Wno-sign-promo'
# Raw param [4] = '-std=c++11'
# Raw param [5] = '-fno-rtti'
# Raw param [6] = '-fno-exceptions'
# Raw param [7] = '-Woverloaded-virtual'
# Raw param [8] = ''
# Raw param [9] = '-nostdinc++'
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
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-std=c++11' became -std=c++11
# FLAG '-fno-rtti' became -fno-rtti
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-Woverloaded-virtual' became -Woverloaded-virtual
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Woverloaded-virtual")
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


add_executable(libLLVMCodeGen ${SOURCE_FILES})
