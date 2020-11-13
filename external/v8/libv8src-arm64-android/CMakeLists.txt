# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(libv8src)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/v8/src/accessors.cc
    ${ANDROID_ROOT}/external/v8/src/address-map.cc
    ${ANDROID_ROOT}/external/v8/src/allocation.cc
    ${ANDROID_ROOT}/external/v8/src/api-arguments.cc
    ${ANDROID_ROOT}/external/v8/src/api-natives.cc
    ${ANDROID_ROOT}/external/v8/src/api.cc
    ${ANDROID_ROOT}/external/v8/src/arguments.cc
    ${ANDROID_ROOT}/external/v8/src/asmjs/asm-js.cc
    ${ANDROID_ROOT}/external/v8/src/asmjs/asm-parser.cc
    ${ANDROID_ROOT}/external/v8/src/asmjs/asm-scanner.cc
    ${ANDROID_ROOT}/external/v8/src/asmjs/asm-types.cc
    ${ANDROID_ROOT}/external/v8/src/asmjs/switch-logic.cc
    ${ANDROID_ROOT}/external/v8/src/assembler.cc
    ${ANDROID_ROOT}/external/v8/src/assert-scope.cc
    ${ANDROID_ROOT}/external/v8/src/ast/ast-function-literal-id-reindexer.cc
    ${ANDROID_ROOT}/external/v8/src/ast/ast-value-factory.cc
    ${ANDROID_ROOT}/external/v8/src/ast/ast.cc
    ${ANDROID_ROOT}/external/v8/src/ast/context-slot-cache.cc
    ${ANDROID_ROOT}/external/v8/src/ast/modules.cc
    ${ANDROID_ROOT}/external/v8/src/ast/prettyprinter.cc
    ${ANDROID_ROOT}/external/v8/src/ast/scopes.cc
    ${ANDROID_ROOT}/external/v8/src/ast/variables.cc
    ${ANDROID_ROOT}/external/v8/src/bailout-reason.cc
    ${ANDROID_ROOT}/external/v8/src/basic-block-profiler.cc
    ${ANDROID_ROOT}/external/v8/src/bignum-dtoa.cc
    ${ANDROID_ROOT}/external/v8/src/bignum.cc
    ${ANDROID_ROOT}/external/v8/src/bit-vector.cc
    ${ANDROID_ROOT}/external/v8/src/bootstrapper.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-api.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-arguments-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-array-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-array.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-arraybuffer.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-async-function-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-async-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-async-generator-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-async-iterator-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-bigint.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-boolean-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-boolean.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-call-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-call.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-callsite.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-collections-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-collections.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-console-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-console.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-constructor-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-conversion-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-dataview.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-date-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-date.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-debug-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-error.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-function-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-function.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-generator-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-global-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-global.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-handler-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-ic-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-internal-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-internal.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-interpreter-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-interpreter.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-intl-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-intl.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-iterator-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-json.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-lazy-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-math-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-math.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-number-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-number.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-object-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-object.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-promise-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-promise.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-proxy-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-reflect-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-reflect.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-regexp-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-regexp.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-sharedarraybuffer-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-sharedarraybuffer.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-string-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-string.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-symbol-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-symbol.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-trace.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-typed-array-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-typed-array.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins-wasm-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/builtins.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/constants-table-builder.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/growable-fixed-array-gen.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/setup-builtins-internal.cc
    ${ANDROID_ROOT}/external/v8/src/cached-powers.cc
    ${ANDROID_ROOT}/external/v8/src/cancelable-task.cc
    ${ANDROID_ROOT}/external/v8/src/char-predicates.cc
    ${ANDROID_ROOT}/external/v8/src/code-factory.cc
    ${ANDROID_ROOT}/external/v8/src/code-reference.cc
    ${ANDROID_ROOT}/external/v8/src/code-stub-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/code-stubs.cc
    ${ANDROID_ROOT}/external/v8/src/codegen.cc
    ${ANDROID_ROOT}/external/v8/src/compilation-cache.cc
    ${ANDROID_ROOT}/external/v8/src/compilation-statistics.cc
    ${ANDROID_ROOT}/external/v8/src/compiler-dispatcher/compiler-dispatcher-job.cc
    ${ANDROID_ROOT}/external/v8/src/compiler-dispatcher/compiler-dispatcher-tracer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler-dispatcher/compiler-dispatcher.cc
    ${ANDROID_ROOT}/external/v8/src/compiler-dispatcher/optimizing-compile-dispatcher.cc
    ${ANDROID_ROOT}/external/v8/src/compiler-dispatcher/unoptimized-compile-job.cc
    ${ANDROID_ROOT}/external/v8/src/compiler.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/access-builder.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/access-info.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/all-nodes.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/basic-block-instrumentor.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/branch-elimination.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/bytecode-analysis.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/bytecode-graph-builder.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/bytecode-liveness-map.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/c-linkage.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/checkpoint-elimination.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/code-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/code-generator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/common-node-cache.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/common-operator-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/common-operator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/compilation-dependencies.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/compiler-source-position-table.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/constant-folding-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/control-equivalence.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/control-flow-optimizer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/dead-code-elimination.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/effect-control-linearizer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/escape-analysis-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/escape-analysis.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/frame-elider.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/frame-states.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/frame.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/gap-resolver.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/graph-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/graph-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/graph-trimmer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/graph-visualizer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/graph.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/instruction-scheduler.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/instruction-selector.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/instruction.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/int64-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-call-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-context-specialization.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-create-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-generic-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-graph.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-heap-broker.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-heap-copy-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-inlining-heuristic.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-inlining.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-intrinsic-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-native-context-specialization.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-operator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-type-hint-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/js-typed-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/jump-threading.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/linkage.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/live-range-separator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/load-elimination.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/loop-analysis.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/loop-peeling.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/loop-variable-optimizer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/machine-graph-verifier.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/machine-graph.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/machine-operator-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/machine-operator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/memory-optimizer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/move-optimizer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/node-cache.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/node-marker.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/node-matchers.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/node-origin-table.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/node-properties.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/node.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/opcodes.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/operation-typer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/operator-properties.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/operator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/osr.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/pipeline-statistics.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/pipeline.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/property-access-builder.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/raw-machine-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/redundancy-elimination.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/register-allocator-verifier.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/register-allocator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/representation-change.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/schedule.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/scheduler.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/select-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/simd-scalar-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/simplified-lowering.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/simplified-operator-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/simplified-operator.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/state-values-utils.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/store-store-elimination.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/type-cache.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/type-narrowing-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/typed-optimization.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/typer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/types.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/value-numbering-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/verifier.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/wasm-compiler.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/zone-stats.cc
    ${ANDROID_ROOT}/external/v8/src/contexts.cc
    ${ANDROID_ROOT}/external/v8/src/conversions.cc
    ${ANDROID_ROOT}/external/v8/src/counters.cc
    ${ANDROID_ROOT}/external/v8/src/date.cc
    ${ANDROID_ROOT}/external/v8/src/dateparser.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug-coverage.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug-evaluate.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug-frames.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug-scope-iterator.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug-scopes.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug-stack-trace-iterator.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug-type-profile.cc
    ${ANDROID_ROOT}/external/v8/src/debug/debug.cc
    ${ANDROID_ROOT}/external/v8/src/debug/liveedit.cc
    ${ANDROID_ROOT}/external/v8/src/deoptimize-reason.cc
    ${ANDROID_ROOT}/external/v8/src/deoptimizer.cc
    ${ANDROID_ROOT}/external/v8/src/disassembler.cc
    ${ANDROID_ROOT}/external/v8/src/diy-fp.cc
    ${ANDROID_ROOT}/external/v8/src/dtoa.cc
    ${ANDROID_ROOT}/external/v8/src/eh-frame.cc
    ${ANDROID_ROOT}/external/v8/src/elements-kind.cc
    ${ANDROID_ROOT}/external/v8/src/elements.cc
    ${ANDROID_ROOT}/external/v8/src/execution.cc
    ${ANDROID_ROOT}/external/v8/src/extensions/externalize-string-extension.cc
    ${ANDROID_ROOT}/external/v8/src/extensions/free-buffer-extension.cc
    ${ANDROID_ROOT}/external/v8/src/extensions/gc-extension.cc
    ${ANDROID_ROOT}/external/v8/src/extensions/ignition-statistics-extension.cc
    ${ANDROID_ROOT}/external/v8/src/extensions/statistics-extension.cc
    ${ANDROID_ROOT}/external/v8/src/extensions/trigger-failure-extension.cc
    ${ANDROID_ROOT}/external/v8/src/external-reference-table.cc
    ${ANDROID_ROOT}/external/v8/src/external-reference.cc
    ${ANDROID_ROOT}/external/v8/src/fast-dtoa.cc
    ${ANDROID_ROOT}/external/v8/src/feedback-vector.cc
    ${ANDROID_ROOT}/external/v8/src/field-type.cc
    ${ANDROID_ROOT}/external/v8/src/fixed-dtoa.cc
    ${ANDROID_ROOT}/external/v8/src/flags.cc
    ${ANDROID_ROOT}/external/v8/src/frames.cc
    ${ANDROID_ROOT}/external/v8/src/futex-emulation.cc
    ${ANDROID_ROOT}/external/v8/src/gdb-jit.cc
    ${ANDROID_ROOT}/external/v8/src/global-handles.cc
    ${ANDROID_ROOT}/external/v8/src/handler-table.cc
    ${ANDROID_ROOT}/external/v8/src/handles.cc
    ${ANDROID_ROOT}/external/v8/src/heap/array-buffer-collector.cc
    ${ANDROID_ROOT}/external/v8/src/heap/array-buffer-tracker.cc
    ${ANDROID_ROOT}/external/v8/src/heap/code-stats.cc
    ${ANDROID_ROOT}/external/v8/src/heap/concurrent-marking.cc
    ${ANDROID_ROOT}/external/v8/src/heap/embedder-tracing.cc
    ${ANDROID_ROOT}/external/v8/src/heap/factory.cc
    ${ANDROID_ROOT}/external/v8/src/heap/gc-idle-time-handler.cc
    ${ANDROID_ROOT}/external/v8/src/heap/gc-tracer.cc
    ${ANDROID_ROOT}/external/v8/src/heap/heap-controller.cc
    ${ANDROID_ROOT}/external/v8/src/heap/heap.cc
    ${ANDROID_ROOT}/external/v8/src/heap/incremental-marking-job.cc
    ${ANDROID_ROOT}/external/v8/src/heap/incremental-marking.cc
    ${ANDROID_ROOT}/external/v8/src/heap/invalidated-slots.cc
    ${ANDROID_ROOT}/external/v8/src/heap/item-parallel-job.cc
    ${ANDROID_ROOT}/external/v8/src/heap/mark-compact.cc
    ${ANDROID_ROOT}/external/v8/src/heap/marking.cc
    ${ANDROID_ROOT}/external/v8/src/heap/memory-reducer.cc
    ${ANDROID_ROOT}/external/v8/src/heap/object-stats.cc
    ${ANDROID_ROOT}/external/v8/src/heap/objects-visiting.cc
    ${ANDROID_ROOT}/external/v8/src/heap/scavenge-job.cc
    ${ANDROID_ROOT}/external/v8/src/heap/scavenger.cc
    ${ANDROID_ROOT}/external/v8/src/heap/setup-heap-internal.cc
    ${ANDROID_ROOT}/external/v8/src/heap/spaces.cc
    ${ANDROID_ROOT}/external/v8/src/heap/store-buffer.cc
    ${ANDROID_ROOT}/external/v8/src/heap/stress-marking-observer.cc
    ${ANDROID_ROOT}/external/v8/src/heap/stress-scavenge-observer.cc
    ${ANDROID_ROOT}/external/v8/src/heap/sweeper.cc
    ${ANDROID_ROOT}/external/v8/src/ic/accessor-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/ic/binary-op-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/ic/call-optimization.cc
    ${ANDROID_ROOT}/external/v8/src/ic/handler-configuration.cc
    ${ANDROID_ROOT}/external/v8/src/ic/ic-stats.cc
    ${ANDROID_ROOT}/external/v8/src/ic/ic.cc
    ${ANDROID_ROOT}/external/v8/src/ic/keyed-store-generic.cc
    ${ANDROID_ROOT}/external/v8/src/ic/stub-cache.cc
    ${ANDROID_ROOT}/external/v8/src/icu_util.cc
    ${ANDROID_ROOT}/external/v8/src/identity-map.cc
    ${ANDROID_ROOT}/external/v8/src/instruction-stream.cc
    ${ANDROID_ROOT}/external/v8/src/interface-descriptors.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-array-accessor.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-array-builder.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-array-iterator.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-array-random-iterator.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-array-writer.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-decoder.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-flags.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-generator.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-label.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-node.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-operands.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-register-optimizer.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-register.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecode-source-info.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/bytecodes.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/constant-array-builder.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/control-flow-builders.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/handler-table-builder.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/interpreter-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/interpreter-generator.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/interpreter-intrinsics-generator.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/interpreter-intrinsics.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/interpreter.cc
    ${ANDROID_ROOT}/external/v8/src/interpreter/setup-interpreter-internal.cc
    ${ANDROID_ROOT}/external/v8/src/intl.cc
    ${ANDROID_ROOT}/external/v8/src/isolate.cc
    ${ANDROID_ROOT}/external/v8/src/json-parser.cc
    ${ANDROID_ROOT}/external/v8/src/json-stringifier.cc
    ${ANDROID_ROOT}/external/v8/src/keys.cc
    ${ANDROID_ROOT}/external/v8/src/layout-descriptor.cc
    ${ANDROID_ROOT}/external/v8/src/log-utils.cc
    ${ANDROID_ROOT}/external/v8/src/log.cc
    ${ANDROID_ROOT}/external/v8/src/lookup-cache.cc
    ${ANDROID_ROOT}/external/v8/src/lookup.cc
    ${ANDROID_ROOT}/external/v8/src/machine-type.cc
    ${ANDROID_ROOT}/external/v8/src/map-updater.cc
    ${ANDROID_ROOT}/external/v8/src/messages.cc
    ${ANDROID_ROOT}/external/v8/src/objects-debug.cc
    ${ANDROID_ROOT}/external/v8/src/objects-printer.cc
    ${ANDROID_ROOT}/external/v8/src/objects.cc
    ${ANDROID_ROOT}/external/v8/src/objects/bigint.cc
    ${ANDROID_ROOT}/external/v8/src/objects/debug-objects.cc
    ${ANDROID_ROOT}/external/v8/src/objects/intl-objects.cc
    ${ANDROID_ROOT}/external/v8/src/objects/js-array-buffer.cc
    ${ANDROID_ROOT}/external/v8/src/objects/js-collator.cc
    ${ANDROID_ROOT}/external/v8/src/objects/js-list-format.cc
    ${ANDROID_ROOT}/external/v8/src/objects/js-locale.cc
    ${ANDROID_ROOT}/external/v8/src/objects/js-plural-rules.cc
    ${ANDROID_ROOT}/external/v8/src/objects/js-relative-time-format.cc
    ${ANDROID_ROOT}/external/v8/src/objects/literal-objects.cc
    ${ANDROID_ROOT}/external/v8/src/objects/managed.cc
    ${ANDROID_ROOT}/external/v8/src/objects/module.cc
    ${ANDROID_ROOT}/external/v8/src/objects/ordered-hash-table.cc
    ${ANDROID_ROOT}/external/v8/src/objects/scope-info.cc
    ${ANDROID_ROOT}/external/v8/src/objects/template-objects.cc
    ${ANDROID_ROOT}/external/v8/src/optimized-compilation-info.cc
    ${ANDROID_ROOT}/external/v8/src/ostreams.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/expression-scope-reparenter.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/func-name-inferrer.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/parse-info.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/parser.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/parsing.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/pattern-rewriter.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/preparsed-scope-data.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/preparser.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/rewriter.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/scanner-character-streams.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/scanner.cc
    ${ANDROID_ROOT}/external/v8/src/parsing/token.cc
    ${ANDROID_ROOT}/external/v8/src/pending-compilation-error-handler.cc
    ${ANDROID_ROOT}/external/v8/src/perf-jit.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/allocation-tracker.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/cpu-profiler.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/heap-profiler.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/heap-snapshot-generator.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/profile-generator.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/profiler-listener.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/sampling-heap-profiler.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/strings-storage.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/tick-sample.cc
    ${ANDROID_ROOT}/external/v8/src/profiler/tracing-cpu-profiler.cc
    ${ANDROID_ROOT}/external/v8/src/property-descriptor.cc
    ${ANDROID_ROOT}/external/v8/src/property.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/interpreter-irregexp.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/jsregexp.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/regexp-ast.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/regexp-macro-assembler-irregexp.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/regexp-macro-assembler-tracer.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/regexp-macro-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/regexp-parser.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/regexp-stack.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/regexp-utils.cc
    ${ANDROID_ROOT}/external/v8/src/register-configuration.cc
    ${ANDROID_ROOT}/external/v8/src/reloc-info.cc
    ${ANDROID_ROOT}/external/v8/src/runtime-profiler.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-array.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-atomics.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-bigint.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-classes.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-collections.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-compiler.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-date.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-debug.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-forin.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-function.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-futex.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-generator.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-internal.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-interpreter.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-intl.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-literals.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-maths.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-module.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-numbers.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-object.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-operators.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-promise.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-proxy.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-regexp.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-scopes.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-strings.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-symbol.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-test.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-typedarray.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime-wasm.cc
    ${ANDROID_ROOT}/external/v8/src/runtime/runtime.cc
    ${ANDROID_ROOT}/external/v8/src/safepoint-table.cc
    ${ANDROID_ROOT}/external/v8/src/setup-isolate-full.cc
    ${ANDROID_ROOT}/external/v8/src/simulator-base.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/builtin-deserializer-allocator.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/builtin-deserializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/builtin-serializer-allocator.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/builtin-serializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/builtin-snapshot-utils.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/code-serializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/default-deserializer-allocator.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/default-serializer-allocator.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/deserializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/natives-common.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/object-deserializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/partial-deserializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/partial-serializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/serializer-common.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/serializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/snapshot-common.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/snapshot-source-sink.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/startup-deserializer.cc
    ${ANDROID_ROOT}/external/v8/src/snapshot/startup-serializer.cc
    ${ANDROID_ROOT}/external/v8/src/source-position-table.cc
    ${ANDROID_ROOT}/external/v8/src/source-position.cc
    ${ANDROID_ROOT}/external/v8/src/startup-data-util.cc
    ${ANDROID_ROOT}/external/v8/src/string-builder.cc
    ${ANDROID_ROOT}/external/v8/src/string-case.cc
    ${ANDROID_ROOT}/external/v8/src/string-stream.cc
    ${ANDROID_ROOT}/external/v8/src/strtod.cc
    ${ANDROID_ROOT}/external/v8/src/tracing/trace-event.cc
    ${ANDROID_ROOT}/external/v8/src/tracing/traced-value.cc
    ${ANDROID_ROOT}/external/v8/src/tracing/tracing-category-observer.cc
    ${ANDROID_ROOT}/external/v8/src/transitions.cc
    ${ANDROID_ROOT}/external/v8/src/trap-handler/handler-inside.cc
    ${ANDROID_ROOT}/external/v8/src/trap-handler/handler-outside.cc
    ${ANDROID_ROOT}/external/v8/src/trap-handler/handler-shared.cc
    ${ANDROID_ROOT}/external/v8/src/turbo-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/type-hints.cc
    ${ANDROID_ROOT}/external/v8/src/unicode-decoder.cc
    ${ANDROID_ROOT}/external/v8/src/unicode.cc
    ${ANDROID_ROOT}/external/v8/src/unoptimized-compilation-info.cc
    ${ANDROID_ROOT}/external/v8/src/uri.cc
    ${ANDROID_ROOT}/external/v8/src/utils.cc
    ${ANDROID_ROOT}/external/v8/src/v8.cc
    ${ANDROID_ROOT}/external/v8/src/v8threads.cc
    ${ANDROID_ROOT}/external/v8/src/value-serializer.cc
    ${ANDROID_ROOT}/external/v8/src/vector-slot-pair.cc
    ${ANDROID_ROOT}/external/v8/src/version.cc
    ${ANDROID_ROOT}/external/v8/src/visitors.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/baseline/liftoff-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/baseline/liftoff-compiler.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/function-body-decoder.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/function-compiler.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/jump-table-assembler.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/local-decl-encoder.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/memory-tracing.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/module-compiler.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/module-decoder.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/signature-map.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/streaming-decoder.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-code-manager.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-debug.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-engine.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-external-refs.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-features.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-interpreter.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-js.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-memory.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-module-builder.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-module.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-objects.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-opcodes.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-result.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-serialization.cc
    ${ANDROID_ROOT}/external/v8/src/wasm/wasm-text.cc
    ${ANDROID_ROOT}/external/v8/src/zone/accounting-allocator.cc
    ${ANDROID_ROOT}/external/v8/src/zone/zone-segment.cc
    ${ANDROID_ROOT}/external/v8/src/zone/zone.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/assembler-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/code-stubs-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/codegen-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/cpu-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/decoder-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/deoptimizer-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/disasm-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/eh-frame-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/frame-constants-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/instructions-arm64-constants.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/instructions-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/instrument-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/interface-descriptors-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/macro-assembler-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/simulator-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/simulator-logic-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/arm64/utils-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/builtins/arm64/builtins-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/arm64/code-generator-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/arm64/instruction-scheduler-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/arm64/instruction-selector-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/compiler/arm64/unwinding-info-writer-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/debug/arm64/debug-arm64.cc
    ${ANDROID_ROOT}/external/v8/src/regexp/arm64/regexp-macro-assembler-arm64.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file_cc/gen/builtins-base-from-dsl-gen.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file_cc/gen/builtins-array-from-dsl-gen.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file_cc/gen/builtins-typed-array-from-dsl-gen.cc
    ${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file_cc/gen/builtins-data-view-from-dsl-gen.cc
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/v8/src'
# Raw param [2] = '-Iexternal/v8'
# Raw param [3] = ''
# Raw param [4] = '${config.Arm64ClangCflags}'
# Raw param [5] = '${config.CommonClangGlobalCflags}'
# Raw param [6] = '${config.DeviceClangGlobalCflags}'
# Raw param [7] = '${config.Arm64ClangArmv8ACflags} ${config.Arm64ClangKryoCflags}'
# Raw param [8] = '-Iexternal/icu/icu4c/source/common'
# Raw param [9] = '-Iexternal/icu/android_icu4c/include'
# Raw param [10] = '-Iexternal/icu/icu4c/source/i18n'
# Raw param [11] = '-Iexternal/libcxx/include'
# Raw param [12] = '-Iexternal/libcxxabi/include'
# Raw param [13] = '-Ibionic/libc/include'
# Raw param [14] = '-D__LIBC_API__=10000'
# Raw param [15] = '-D__LIBM_API__=10000'
# Raw param [16] = '-D__LIBDL_API__=10000'
# Raw param [17] = '-Iout/soong/.intermediates/external/v8/v8_torque_file_cc/gen'
# Raw param [18] = '-Iout/soong/.intermediates/external/v8/v8_torque_file/gen'
# variable ${config.ClangExternalCflags} = '-Wno-enum-compare -Wno-enum-compare-switch -Wno-null-pointer-arithmetic -Wno-null-dereference'
# Raw param [0] = '-Wno-enum-compare'
# Raw param [1] = '-Wno-enum-compare-switch'
# Raw param [2] = '-Wno-null-pointer-arithmetic'
# Raw param [3] = '-Wno-null-dereference'
# FLAG '-Wno-enum-compare' became -Wno-enum-compare
# FLAG '-Wno-enum-compare-switch' became -Wno-enum-compare-switch
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-null-dereference' became -Wno-null-dereference
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
    "${ANDROID_ROOT}/external/v8/src"
    "${ANDROID_ROOT}/external/v8"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n"
    "${ANDROID_ROOT}/external/libcxx/include"
    "${ANDROID_ROOT}/external/libcxxabi/include"
    "${ANDROID_ROOT}/bionic/libc/include"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file_cc/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/v8/src/**/*.h"
    "${ANDROID_ROOT}/external/v8/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/common/**/*.h"
    "${ANDROID_ROOT}/external/icu/android_icu4c/include/**/*.h"
    "${ANDROID_ROOT}/external/icu/icu4c/source/i18n/**/*.h"
    "${ANDROID_ROOT}/external/libcxx/include/**/*.h"
    "${ANDROID_ROOT}/external/libcxxabi/include/**/*.h"
    "${ANDROID_ROOT}/bionic/libc/include/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file_cc/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/v8/v8_torque_file/gen/**/*.h"
)
list (APPEND SOURCE_FILES ${TMP_HEADERS})

set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-dereference")
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
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-enum-compare-switch")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-dereference")
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
# Raw param [1] = '-Werror'
# Raw param [2] = '-Wno-endif-labels'
# Raw param [3] = '-Wno-implicit-fallthrough'
# Raw param [4] = '-Wno-import'
# Raw param [5] = '-Wno-format'
# Raw param [6] = '-Wno-unused-variable'
# Raw param [7] = '-Wno-unused-parameter'
# Raw param [8] = '-Wno-unused-private-field'
# Raw param [9] = '-Wno-sign-compare'
# Raw param [10] = '-Wno-missing-field-initializers'
# Raw param [11] = '-Wno-ignored-qualifiers'
# Raw param [12] = '-Wno-undefined-var-template'
# Raw param [13] = '-Wno-null-pointer-arithmetic'
# Raw param [14] = '-Wno-non-virtual-dtor'
# Raw param [15] = '-Wno-user-defined-warnings'
# Raw param [16] = '-Wno-unused-lambda-capture'
# Raw param [17] = '-fno-exceptions'
# Raw param [18] = '-fvisibility=hidden'
# Raw param [19] = '-DENABLE_DEBUGGER_SUPPORT'
# Raw param [20] = '-DENABLE_LOGGING_AND_PROFILING'
# Raw param [21] = '-DENABLE_VMSTATE_TRACKING'
# Raw param [22] = '-DV8_NATIVE_REGEXP'
# Raw param [23] = '-DV8_INTL_SUPPORT'
# Raw param [24] = '-DV8_CONCURRENT_MARKING'
# Raw param [25] = '-std=gnu++0x'
# Raw param [26] = '-Os'
# Raw param [27] = '-DV8_TARGET_ARCH_ARM64'
# Raw param [28] = '-DANDROID_LINK_SHARED_ICU4C'
# Raw param [29] = '-target aarch64-linux-android'
# Raw param [30] = '-B${config.Arm64GccRoot}/aarch64-linux-android/bin'
# Raw param [31] = '-fPIC'
# Raw param [32] = '-D_USING_LIBCXX'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-Wno-endif-labels' became -Wno-endif-labels
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-Wno-import' became -Wno-import
# FLAG '-Wno-format' became -Wno-format
# FLAG '-Wno-unused-variable' became -Wno-unused-variable
# FLAG '-Wno-unused-parameter' became -Wno-unused-parameter
# FLAG '-Wno-unused-private-field' became -Wno-unused-private-field
# FLAG '-Wno-sign-compare' became -Wno-sign-compare
# FLAG '-Wno-missing-field-initializers' became -Wno-missing-field-initializers
# FLAG '-Wno-ignored-qualifiers' became -Wno-ignored-qualifiers
# FLAG '-Wno-undefined-var-template' became -Wno-undefined-var-template
# FLAG '-Wno-null-pointer-arithmetic' became -Wno-null-pointer-arithmetic
# FLAG '-Wno-non-virtual-dtor' became -Wno-non-virtual-dtor
# FLAG '-Wno-user-defined-warnings' became -Wno-user-defined-warnings
# FLAG '-Wno-unused-lambda-capture' became -Wno-unused-lambda-capture
# FLAG '-fno-exceptions' became -fno-exceptions
# FLAG '-fvisibility=hidden' became -fvisibility=hidden
# FLAG '-DENABLE_DEBUGGER_SUPPORT' became -DENABLE_DEBUGGER_SUPPORT
# FLAG '-DENABLE_LOGGING_AND_PROFILING' became -DENABLE_LOGGING_AND_PROFILING
# FLAG '-DENABLE_VMSTATE_TRACKING' became -DENABLE_VMSTATE_TRACKING
# FLAG '-DV8_NATIVE_REGEXP' became -DV8_NATIVE_REGEXP
# FLAG '-DV8_INTL_SUPPORT' became -DV8_INTL_SUPPORT
# FLAG '-DV8_CONCURRENT_MARKING' became -DV8_CONCURRENT_MARKING
# FLAG '-std=gnu++0x' became -std=gnu++0x
# FLAG '-Os' became -Os
# FLAG '-DV8_TARGET_ARCH_ARM64' became -DV8_TARGET_ARCH_ARM64
# FLAG '-DANDROID_LINK_SHARED_ICU4C' became -DANDROID_LINK_SHARED_ICU4C
# FLAG '-target aarch64-linux-android' became -target aarch64-linux-android
# FLAG '-B${config.Arm64GccRoot}/aarch64-linux-android/bin' became -B${config.Arm64GccRoot}/aarch64-linux-android/bin
# FLAG '-fPIC' became -fPIC
# FLAG '-D_USING_LIBCXX' became -D_USING_LIBCXX
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-endif-labels")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-import")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-format")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-variable")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-parameter")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-private-field")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-sign-compare")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-undefined-var-template")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-non-virtual-dtor")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-user-defined-warnings")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wno-unused-lambda-capture")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fno-exceptions")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fvisibility=hidden")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_DEBUGGER_SUPPORT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_LOGGING_AND_PROFILING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DENABLE_VMSTATE_TRACKING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DV8_NATIVE_REGEXP")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DV8_INTL_SUPPORT")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DV8_CONCURRENT_MARKING")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -std=gnu++0x")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Os")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DV8_TARGET_ARCH_ARM64")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -DANDROID_LINK_SHARED_ICU4C")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target aarch64-linux-android")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -D_USING_LIBCXX")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-endif-labels")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-import")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-format")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-variable")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-parameter")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-private-field")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-sign-compare")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-missing-field-initializers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-ignored-qualifiers")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-undefined-var-template")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-null-pointer-arithmetic")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-non-virtual-dtor")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-user-defined-warnings")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-unused-lambda-capture")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fno-exceptions")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility=hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_DEBUGGER_SUPPORT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_LOGGING_AND_PROFILING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DENABLE_VMSTATE_TRACKING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DV8_NATIVE_REGEXP")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DV8_INTL_SUPPORT")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DV8_CONCURRENT_MARKING")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++0x")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Os")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DV8_TARGET_ARCH_ARM64")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -DANDROID_LINK_SHARED_ICU4C")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -target aarch64-linux-android")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -B${config.Arm64GccRoot}/aarch64-linux-android/bin")
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


add_executable(libv8src ${SOURCE_FILES})
