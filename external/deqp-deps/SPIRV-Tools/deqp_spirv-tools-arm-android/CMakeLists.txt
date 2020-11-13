# THIS FILE WAS AUTOMATICALY GENERATED!
# ANY MODIFICATION WILL BE OVERWRITTEN!

# To improve project view in Clion    :
# Tools > CMake > Change Project Root  

cmake_minimum_required(VERSION 3.5)
project(deqp_spirv-tools)
set(ANDROID_ROOT /media/zoopwn/new/android_source)

set(CMAKE_C_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang")
set(CMAKE_CXX_COMPILER "${ANDROID_ROOT}/prebuilts/clang/host/linux-x86/clang-r353983c/bin/clang++")
list(APPEND
     SOURCE_FILES
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/assembly_grammar.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/binary.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/diagnostic.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/disassemble.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/enum_string_mapping.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/ext_inst.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/extensions.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/id_descriptor.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/libspirv.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/name_mapper.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opcode.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/operand.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/parsed_operand.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/pch_source.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/print.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/software_version.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/spirv_endian.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/spirv_optimizer_options.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/spirv_reducer_options.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/spirv_target_env.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/spirv_validator_options.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/table.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/text.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/text_handler.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/util/bit_vector.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/util/parse_number.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/util/string_utils.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/util/timer.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/basic_block.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/construct.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/function.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/instruction.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_adjacency.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_annotation.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_arithmetics.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_atomics.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_barriers.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_bitwise.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_builtins.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_capability.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_cfg.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_composites.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_constants.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_conversion.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_datarules.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_debug.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_decorations.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_derivatives.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_execution_limitations.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_extensions.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_function.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_id.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_image.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_instruction.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_interfaces.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_layout.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_literals.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_logicals.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_memory.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_memory_semantics.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_mode_setting.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_non_uniform.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_primitives.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_scopes.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validate_type.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/val/validation_state.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/aggressive_dead_code_elim_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/basic_block.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/block_merge_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/build_module.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/ccp_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/cfg.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/cfg_cleanup_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/combine_access_chains.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/common_uniform_elim_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/compact_ids_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/composite.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/const_folding_rules.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/constants.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/copy_prop_arrays.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/dead_branch_elim_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/dead_insert_elim_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/dead_variable_elimination.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/decoration_manager.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/def_use_manager.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/dominator_analysis.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/dominator_tree.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/eliminate_dead_constant_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/eliminate_dead_functions_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/feature_manager.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/flatten_decoration_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/fold.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/fold_spec_constant_op_and_composite_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/folding_rules.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/freeze_spec_constant_value_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/function.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/if_conversion.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/inline_exhaustive_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/inline_opaque_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/inline_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/inst_bindless_check_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/instruction.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/instruction_list.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/instrument_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/ir_context.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/ir_loader.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/licm_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/local_access_chain_convert_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/local_redundancy_elimination.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/local_single_block_elim_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/local_single_store_elim_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/local_ssa_elim_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_dependence.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_dependence_helpers.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_descriptor.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_fission.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_fusion.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_fusion_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_peeling.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_unroller.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_unswitch_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/loop_utils.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/mem_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/merge_return_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/module.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/optimizer.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/pass_manager.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/pch_source_opt.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/private_to_local_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/process_lines_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/propagator.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/reduce_load_size.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/redundancy_elimination.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/register_pressure.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/remove_duplicates_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/replace_invalid_opc.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/scalar_analysis.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/scalar_analysis_simplification.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/scalar_replacement_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/set_spec_constant_default_value_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/simplification_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/ssa_rewrite_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/strength_reduction_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/strip_debug_info_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/strip_reflect_info_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/struct_cfg_analysis.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/type_manager.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/types.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/unify_const_pass.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/upgrade_memory_model.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/value_number_table.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/vector_dce.cpp
    ${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/opt/workaround1209.cpp
)

# GLOBAL FLAGS:
# Raw param [0] = '${config.ClangExternalCflags}'
# Raw param [1] = '-Iexternal/deqp-deps/SPIRV-Tools/include'
# Raw param [2] = '-Iexternal/deqp-deps/SPIRV-Tools/source'
# Raw param [3] = '-Iexternal/deqp-deps/SPIRV-Headers/include'
# Raw param [4] = '-Iexternal/deqp-deps/SPIRV-Tools'
# Raw param [5] = '-D__ANDROID_API__=27'
# Raw param [6] = '${config.ArmClangThumbCflags}'
# Raw param [7] = '${config.ArmClangCflags}'
# Raw param [8] = '${config.CommonClangGlobalCflags}'
# Raw param [9] = '${config.DeviceClangGlobalCflags}'
# Raw param [10] = '${config.ArmToolchainClangCflags} ${config.ArmClangArmv8ACflags} ${config.ArmClangKryoCflags}'
# Raw param [11] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++/include'
# Raw param [12] = '-isystem prebuilts/ndk/current/sources/cxx-stl/llvm-libc++abi/include'
# Raw param [13] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.0/gen'
# Raw param [14] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.1/gen'
# Raw param [15] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.2/gen'
# Raw param [16] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_unified1/gen'
# Raw param [17] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_debuginfo/gen'
# Raw param [18] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-gcn-shader/gen'
# Raw param [19] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-ballot/gen'
# Raw param [20] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-explicit-vertex-parameter/gen'
# Raw param [21] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-trinary-minmax/gen'
# Raw param [22] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_enum_string_mapping/gen'
# Raw param [23] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_generators_inc/gen'
# Raw param [24] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_build_version_inc/gen'
# Raw param [25] = '-Iout/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_lang_headers/gen'
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
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/include"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Headers/include"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.0/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.1/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.2/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_unified1/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_debuginfo/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-gcn-shader/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-ballot/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-explicit-vertex-parameter/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-trinary-minmax/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_enum_string_mapping/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_generators_inc/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_build_version_inc/gen"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_lang_headers/gen"
)

file (GLOB_RECURSE TMP_HEADERS
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/include/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/source/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Headers/include/**/*.h"
    "${ANDROID_ROOT}/external/deqp-deps/SPIRV-Tools/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.0/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.1/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_1.2/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_unified1/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_debuginfo/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-gcn-shader/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-ballot/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-explicit-vertex-parameter/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_grammar_tables_amd-shader-trinary-minmax/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_enum_string_mapping/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_generators_inc/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_build_version_inc/gen/**/*.h"
    "${ANDROID_ROOT}/out/soong/.intermediates/external/deqp-deps/SPIRV-Tools/deqp_gen_spvtools_lang_headers/gen/**/*.h"
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
# Raw param [0] = '-Wall'
# Raw param [1] = '-Werror'
# Raw param [2] = '-target armv7a-linux-androideabi'
# Raw param [3] = '-B${config.ArmGccRoot}/arm-linux-androideabi/bin'
# Raw param [4] = '-fPIC'
# FLAG '-Wall' became -Wall
# FLAG '-Werror' became -Werror
# FLAG '-target armv7a-linux-androideabi' became -target armv7a-linux-androideabi
# FLAG '-B${config.ArmGccRoot}/arm-linux-androideabi/bin' became -B${config.ArmGccRoot}/arm-linux-androideabi/bin
# FLAG '-fPIC' became -fPIC
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Wall")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -Werror")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -target armv7a-linux-androideabi")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -B${config.ArmGccRoot}/arm-linux-androideabi/bin")
set(CMAKE_C_FLAGS "${CMAKE_C_FLAGS} -fPIC")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wall")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Werror")
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
# Raw param [3] = '-Wno-implicit-fallthrough'
# Raw param [4] = '-fno-rtti'
# Raw param [5] = '${config.ArmClangCppflags}'
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
# FLAG '-Wno-implicit-fallthrough' became -Wno-implicit-fallthrough
# FLAG '-fno-rtti' became -fno-rtti
# variable ${config.ArmClangCppflags} = ''
# Raw param [0] = ''
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=gnu++17")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wsign-promo")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -D_LIBCPP_ENABLE_THREAD_SAFETY_ANNOTATIONS")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-thread-safety-negative")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-gnu-include-next")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -fvisibility-inlines-hidden")
set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -Wno-implicit-fallthrough")
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


add_executable(deqp_spirv-tools ${SOURCE_FILES})
