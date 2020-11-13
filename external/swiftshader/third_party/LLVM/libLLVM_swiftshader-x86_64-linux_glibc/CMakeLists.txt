# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libLLVM_swiftshader)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/AliasAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/AliasSetTracker.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/BasicAliasAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/BranchProbabilityInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/CaptureTracking.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/ConstantFolding.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/DebugInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/DIBuilder.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/InstructionSimplify.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/IVUsers.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/Loads.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/LoopInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/LoopPass.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/MemoryBuiltins.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/MemoryDependenceAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/NoAliasAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/PathNumbering.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/PHITransAddr.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/ProfileInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/ScalarEvolution.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/ScalarEvolutionExpander.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/ScalarEvolutionNormalization.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/TypeBasedAliasAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Analysis/ValueTracking.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/DAGCombiner.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/FastISel.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/FunctionLoweringInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/InstrEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/LegalizeDAG.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/LegalizeFloatTypes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/LegalizeIntegerTypes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/LegalizeTypes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/LegalizeTypesGeneric.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/LegalizeVectorOps.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/LegalizeVectorTypes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/ScheduleDAGFast.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/ScheduleDAGList.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/ScheduleDAGRRList.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/ScheduleDAGSDNodes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/SelectionDAG.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/SelectionDAGBuilder.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/SelectionDAGISel.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/SelectionDAGPrinter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/TargetLowering.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SelectionDAG/TargetSelectionDAGInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/AggressiveAntiDepBreaker.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/AllocationOrder.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/Analysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/BranchFolding.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/CalcSpillWeights.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/CallingConvLower.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/CodeGen.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/CodePlacementOpt.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/CriticalAntiDepBreaker.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/DeadMachineInstructionElim.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/DwarfEHPrepare.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/EdgeBundles.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ELFCodeEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ELFWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ExecutionDepsFix.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ExpandISelPseudos.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ExpandPostRAPseudos.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/GCMetadata.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/GCStrategy.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/IfConversion.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/InlineSpiller.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/InterferenceCache.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/IntrinsicLowering.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LatencyPriorityQueue.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LexicalScopes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveDebugVariables.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveIntervalAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveInterval.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveIntervalUnion.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveRangeCalc.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveRangeEdit.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveStackAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LiveVariables.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LLVMTargetMachine.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/LocalStackSlotAllocation.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineBasicBlock.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineBlockFrequencyInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineBranchProbabilityInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineCSE.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineDominators.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineFunctionAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineFunction.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineFunctionPass.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineFunctionPrinterPass.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineInstr.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineLICM.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineLoopInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineLoopRanges.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineModuleInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineModuleInfoImpls.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachinePassRegistry.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineRegisterInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineSink.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineSSAUpdater.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/MachineVerifier.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ObjectCodeEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/OcamlGC.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/OptimizePHIs.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/Passes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/PeepholeOptimizer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/PHIElimination.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/PHIEliminationUtils.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/PostRASchedulerList.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ProcessImplicitDefs.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/PrologEpilogInserter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/PseudoSourceValue.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegAllocBasic.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegAllocFast.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegAllocGreedy.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegAllocLinearScan.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegAllocPBQP.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegisterClassInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegisterCoalescer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RegisterScavenging.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/RenderMachineFunction.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ScheduleDAG.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ScheduleDAGEmit.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ScheduleDAGInstrs.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ScheduleDAGPrinter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ScoreboardHazardRecognizer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ShadowStackGC.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/ShrinkWrapping.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SjLjEHPrepare.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SlotIndexes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/Spiller.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SpillPlacement.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/SplitKit.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/Splitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/StackProtector.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/StackSlotColoring.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/StrongPHIElimination.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/TailDuplication.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/TargetInstrInfoImpl.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/TargetLoweringObjectFileImpl.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/TwoAddressInstructionPass.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/UnreachableBlockElim.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/VirtRegMap.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/CodeGen/VirtRegRewriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/JIT/Intercept.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/JIT/JIT.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/JIT/JITDebugRegisterer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/JIT/JITDwarfEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/JIT/JITEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/JIT/JITMemoryManager.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/JIT/OProfileJITEventListener.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/ExecutionEngine.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/ExecutionEngine/TargetSelect.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/ELFObjectWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MachObjectWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCAsmBackend.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCAsmInfoCOFF.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCAsmInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCAsmInfoDarwin.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCAsmStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCAssembler.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCAtom.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCCodeEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCCodeGenInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCContext.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCDisassembler.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCDwarf.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCELF.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCELFObjectTargetWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCELFStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCExpr.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCInst.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCInstPrinter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCInstrAnalysis.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCLabel.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCLoggingStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCMachObjectTargetWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCMachOStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCModule.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCNullStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCObjectFileInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCObjectStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCObjectWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCPureStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCSectionCOFF.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCSection.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCSectionELF.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCSectionMachO.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCSubtargetInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCSymbol.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCTargetAsmLexer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCValue.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/MCWin64EH.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/SubtargetFeature.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/WinCOFFObjectWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/MC/WinCOFFStreamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Allocator.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/APFloat.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/APInt.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/APSInt.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Atomic.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/BlockFrequency.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/BranchProbability.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/circular_raw_ostream.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/CommandLine.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/ConstantRange.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/CrashRecoveryContext.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/DAGDeltaAlgorithm.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/DataExtractor.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Debug.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/DeltaAlgorithm.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Disassembler.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Dwarf.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/DynamicLibrary.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Errno.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/ErrorHandling.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/FileUtilities.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/FoldingSet.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/FormattedStream.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/GraphWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Host.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/IncludeFile.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/IntEqClasses.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/IntervalMap.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/IsInf.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/IsNAN.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/ManagedStatic.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/MemoryBuffer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Memory.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/MemoryObject.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Mutex.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Path.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/PathV2.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/PluginLoader.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/PrettyStackTrace.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Process.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Program.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/raw_os_ostream.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/raw_ostream.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Regex.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/RWMutex.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/SearchForAddressOfSpecialSymbol.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Signals.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/SmallPtrSet.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/SmallVector.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/SourceMgr.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Statistic.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/StringExtras.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/StringMap.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/StringPool.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/StringRef.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/system_error.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/SystemUtils.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/TargetRegistry.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Threading.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/ThreadLocal.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Timer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/TimeValue.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/ToolOutputFile.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Triple.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Twine.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Support/Valgrind.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/Mangler.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/Target.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetData.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetELFWriterInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetFrameLowering.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetInstrInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetLibraryInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetLoweringObjectFile.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetMachine.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetRegisterInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/TargetSubtargetInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineAddSub.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineAndOrXor.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineCalls.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineCasts.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineCompares.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineLoadStoreAlloca.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineMulDivRem.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombinePHI.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineSelect.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineShifts.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineSimplifyDemanded.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstCombineVectorOps.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/InstCombine/InstructionCombining.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/ADCE.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/CodeGenPrepare.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/DeadStoreElimination.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/GVN.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/LICM.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/LoopStrengthReduce.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/Reassociate.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/Reg2Mem.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/ScalarReplAggregates.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/SCCP.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Scalar/SimplifyCFGPass.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/AddrModeMatcher.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/BasicBlockUtils.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/BreakCriticalEdges.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/BuildLibCalls.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/DemoteRegToStack.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/InstructionNamer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/LCSSA.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/Local.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/LoopSimplify.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/LowerInvoke.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/LowerSwitch.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/Mem2Reg.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/PromoteMemoryToRegister.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/SimplifyCFG.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/SSAUpdater.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Transforms/Utils/UnifyFunctionExitNodes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/AsmWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Attributes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/AutoUpgrade.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/BasicBlock.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/ConstantFold.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Constants.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Core.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/DebugInfoProbe.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/DebugLoc.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Dominators.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Function.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/GCOV.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Globals.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/GVMaterializer.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/InlineAsm.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Instruction.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Instructions.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/IntrinsicInst.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/IRBuilder.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/LeakDetector.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/LLVMContext.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/LLVMContextImpl.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Metadata.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Module.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Pass.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/PassManager.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/PassRegistry.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/PrintModulePass.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Type.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Use.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/User.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Value.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/ValueSymbolTable.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/ValueTypes.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/VMCore/Verifier.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/InstPrinter/X86ATTInstPrinter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/InstPrinter/X86InstComments.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/InstPrinter/X86IntelInstPrinter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/MCTargetDesc/X86AsmBackend.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/MCTargetDesc/X86MachObjectWriter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/MCTargetDesc/X86MCAsmInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/MCTargetDesc/X86MCCodeEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/MCTargetDesc/X86MCTargetDesc.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/TargetInfo/X86TargetInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/Utils/X86ShuffleDecode.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86CodeEmitter.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86ELFWriterInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86FastISel.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86FloatingPoint.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86FrameLowering.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86InstrInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86ISelDAGToDAG.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86ISelLowering.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86JITInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86RegisterInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86SelectionDAGInfo.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86Subtarget.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86TargetMachine.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86TargetObjectFile.cpp
    ${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/X86VZeroUpper.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/swiftshader/third_party/LLVM/include-linux -Iexternal/swiftshader/third_party/LLVM/include'
# Raw param [2] = '-Iexternal/swiftshader/third_party/LLVM/lib/Target/X86'
# Raw param [3] = '-Iexternal/swiftshader/third_party/LLVM'
# Raw param [4] = ''
# Raw param [5] = '${config.LinuxClangCflags} ${config.LinuxX8664ClangCflags}'
# Raw param [6] = '${config.CommonClangGlobalCflags}'
# Raw param [7] = '${config.HostClangGlobalCflags}'
# Raw param [8] = ''
# Raw param [9] = '-Iexternal/libcxx/include'
# Raw param [10] = '-Iexternal/libcxxabi/include'
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
    "${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/include-linux -Iexternal/swiftshader/third_party/LLVM/include"
    "${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86"
    "${ANDROID_ROOT}/external/swiftshader/third_party/LLVM"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/include-linux -Iexternal/swiftshader/third_party/LLVM/include/**/*.h"
    "${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/lib/Target/X86/**/*.h"
    "${ANDROID_ROOT}/external/swiftshader/third_party/LLVM/**/*.h"
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
# Raw param [0] = '-Xclang'
# Raw param [1] = '-fuse-init-array'
# Raw param [2] = '-fno-operator-names'
# Raw param [3] = '-msse2'
# Raw param [4] = '-Werror'
# Raw param [5] = '-Wwrite-strings'
# Raw param [6] = '-Os'
# Raw param [7] = '-fomit-frame-pointer'
# Raw param [8] = '-ffunction-sections'
# Raw param [9] = '-fdata-sections'
# Raw param [10] = '-D_GNU_SOURCE'
# Raw param [11] = '-D__STDC_LIMIT_MACROS'
# Raw param [12] = '-D__STDC_CONSTANT_MACROS'
# Raw param [13] = '-D__STDC_FORMAT_MACROS'
# Raw param [14] = ''-DLOG_TAG="libLLVM_swiftshader"''
# Raw param [15] = '-Wno-implicit-fallthrough'
# Raw param [16] = '-Wno-unused-result'
# Raw param [17] = '-Wno-unused-function'
# Raw param [18] = '-Wno-unused-variable'
# Raw param [19] = '-Wno-unused-parameter'
# Raw param [20] = '-Wno-unused-local-typedef'
# Raw param [21] = '-Wno-unused-private-field'
# Raw param [22] = '-Wno-unneeded-internal-declaration'
# Raw param [23] = '-target x86_64-linux-gnu'
# Raw param [24] = '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin'
# Raw param [25] = '-fPIC'
# Raw param [26] = '-D_USING_LIBCXX'
# FLAG '-Xclang' became -Xclang
# FLAG '-fuse-init-array' became -fuse-init-array
# FLAG '-fno-operator-names' became -fno-operator-names
# FLAG '-msse2' became -msse2
# FLAG '-Werror' became -Werror
# FLAG '-Wwrite-strings' became -Wwrite-strings
# FLAG '-Os' became -Os
# FLAG '-fomit-frame-pointer' became -fomit-frame-pointer
# FLAG '-ffunction-sections' became -ffunction-sections
# FLAG '-fdata-sections' became -fdata-sections
# FLAG '-D_GNU_SOURCE' became -D_GNU_SOURCE
# FLAG '-D__STDC_LIMIT_MACROS' became -D__STDC_LIMIT_MACROS
# FLAG '-D__STDC_CONSTANT_MACROS' became -D__STDC_CONSTANT_MACROS
# FLAG '-D__STDC_FORMAT_MACROS' became -D__STDC_FORMAT_MACROS
# FLAG ''-DLOG_TAG="libLLVM_swiftshader"'' became -DLOG_TAG=\\\"libLLVM_swiftshader\\\"
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wno-unused-result' became -Wno-unused-result
# FLAG '-Wno-unused-function' became -Wno-unused-function
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-local-typedef' became -Wno-unused-local-typedef
# FLAG '-Wno-unused-private-field' became -Wno-unused-private-field
# FLAG '-Wno-unneeded-internal-declaration' became -Wno-unneeded-internal-declaration
# FLAG '-target x86_64-linux-gnu' became -target x86_64-linux-gnu
# FLAG '-B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin' became -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Xclang")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fuse-init-array")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-operator-names")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -msse2")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wwrite-strings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fomit-frame-pointer")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -ffunction-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fdata-sections")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_GNU_SOURCE")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DLOG_TAG=\\\"libLLVM_swiftshader\\\"")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-result")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-function")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-local-typedef")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-private-field")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unneeded-internal-declaration")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Xclang")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fuse-init-array")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-operator-names")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -msse2")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wwrite-strings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fomit-frame-pointer")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -ffunction-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fdata-sections")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_GNU_SOURCE")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_LIMIT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_CONSTANT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D__STDC_FORMAT_MACROS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DLOG_TAG=\\\"libLLVM_swiftshader\\\"")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-result")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-function")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-local-typedef")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-private-field")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unneeded-internal-declaration")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target x86_64-linux-gnu")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.LinuxGccRoot}/${config.LinuxGccTriple}/bin")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_USING_LIBCXX")

# C ONLY FLAGS:
# Raw param [0] = '-std=c99'
# Raw param [1] = '${config.CommonGlobalConlyflags}'
# FLAG '-std=c99' became -std=c99
# variable ${config.CommonGlobalConlyflags} = ''
# Raw param [0] = ''
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=c99")

# CPP FLAGS:
# Raw param [0] = '-std=c++11'
# Raw param [1] = '${config.CommonClangGlobalCppflags}'
# Raw param [2] = '${config.HostGlobalCppflags}'
# Raw param [3] = '-Woverloaded-virtual'
# Raw param [4] = '-Wno-sign-promo'
# Raw param [5] = '-Wno-undefined-var-template'
# Raw param [6] = '-fno-rtti'
# Raw param [7] = '-fno-exceptions'
# Raw param [8] = ''
# Raw param [9] = '-nostdinc++'
# FLAG '-std=c++11' became -std=c++11
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
# FLAG '-Woverloaded-virtual' became -Woverloaded-virtual
# FLAG '-Wno-sign-promo' became -Wno-sign-promo
# FLAG '-Wno-undefined-var-template' became -Wno-undefined-var-template
# FLAG '-fno-rtti' became -fno-rtti
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-nostdinc++' became -nostdinc++
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Woverloaded-virtual")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-undefined-var-template")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-rtti")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
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


add_executable(libLLVM_swiftshader ${SOURCE_FILES})
