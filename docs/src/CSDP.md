Table of contents:

```@contents
Pages = ["CSDP.md"]
Depth = 4
```


Compilation warmup gives an estimate of 45 seconds of compilation time.

## CSDP 
These tests were run on October 6, 2020 at 10:43 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 5 minutes, 7 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">CSDP tests</td>
<td style="text-align:center;color:green;">2005</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2012</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">372</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">379</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">138</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_satisfy_problems</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_transpose_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_diag_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_conv_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_multiply_atom</td>
<td style="text-align:center;color:green;">19</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">19</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_hcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_vcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_index_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_permuteddims_matrix</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_Partial_transpose</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_add_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom_for_matrix_variables</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dualvalue</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_Diagonal_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_sum_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_reshape_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_multiply_atom</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_trace_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_negate_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">99</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">99</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">62</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">45</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">51</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">1633</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1633</td>
</tr></table>
```

### Errors

```julia
Error in testset affine_Diagonal_atom:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  ArgumentError: Empty constraint MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}(5): MathOptInterface.ScalarAffineFunction{Float64}(MathOptInterface.ScalarAffineTerm{Float64}[], 0.0)-in-MathOptInterface.EqualTo{Float64}(1.0). Not supported by CSDP.
  Stacktrace:
   [1] load_constraint(::CSDP.Optimizer, ::MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}, ::MathOptInterface.ScalarAffineFunction{Float64}, ::MathOptInterface.EqualTo{Float64}) at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:275
   [2] load_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::MathOptInterface.Utilities.IndexMap, ::Array{MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}},1}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:711
   [3] pass_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::MathOptInterface.Utilities.IndexMap, ::Array{DataType,1}, ::Array{Array{var"#s280",1} where var"#s280"<:(MathOptInterface.ConstraintIndex{MathOptInterface.SingleVariable,S} where S),1}, ::Array{Type{var"#s309"} where var"#s309"<:MathOptInterface.AbstractVectorSet,1}, ::Array{Array{var"#s304",1} where var"#s304"<:(MathOptInterface.ConstraintIndex{MathOptInterface.VectorOfVariables,S} where S),1}, ::typeof(MathOptInterface.Utilities.load_constraints), ::typeof(MathOptInterface.Utilities.load); filter_constraints::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:353
   [4] allocate_load(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:776
   [5] #automatic_copy_to#113 at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:23 [inlined]
   [6] #copy_to#19 at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:155 [inlined]
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize! at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264 [inlined]
   [10] solve!(::Convex.Problem{Float64}, ::CSDP.Optimizer; check_vexity::Bool, verbose::Bool, warmstart::Bool, silent_solver::Bool) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:245
   [11] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:223 [inlined]
   [12] solve!(::Convex.Problem{Float64}, ::var"#1#2"; kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:192
   [13] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:191 [inlined]
   [14] #2 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/convex.jl:12 [inlined]
   [15] affine_Diagonal_atom(::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}, ::Val{true}, ::Float64, ::Float64, ::Type{Float64}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:516
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}})(::String, ::typeof(Convex.ProblemDepot.affine_Diagonal_atom)) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problem_depot.jl:80
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(Convex.ProblemDepot.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::var"#1#2"; variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:11
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sdp_matrix_frac_atom_both_arguments_variable:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  ArgumentError: Empty constraint MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}(11): MathOptInterface.ScalarAffineFunction{Float64}(MathOptInterface.ScalarAffineTerm{Float64}[], 0.0)-in-MathOptInterface.EqualTo{Float64}(-0.0). Not supported by CSDP.
  Stacktrace:
   [1] load_constraint(::CSDP.Optimizer, ::MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}, ::MathOptInterface.ScalarAffineFunction{Float64}, ::MathOptInterface.EqualTo{Float64}) at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:275
   [2] load_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::MathOptInterface.Utilities.IndexMap, ::Array{MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}},1}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:711
   [3] pass_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::MathOptInterface.Utilities.IndexMap, ::Array{DataType,1}, ::Array{Array{var"#s280",1} where var"#s280"<:(MathOptInterface.ConstraintIndex{MathOptInterface.SingleVariable,S} where S),1}, ::Array{Type{var"#s309"} where var"#s309"<:MathOptInterface.AbstractVectorSet,1}, ::Array{Array{var"#s304",1} where var"#s304"<:(MathOptInterface.ConstraintIndex{MathOptInterface.VectorOfVariables,S} where S),1}, ::typeof(MathOptInterface.Utilities.load_constraints), ::typeof(MathOptInterface.Utilities.load); filter_constraints::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:353
   [4] allocate_load(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:776
   [5] #automatic_copy_to#113 at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:23 [inlined]
   [6] #copy_to#19 at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:155 [inlined]
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize! at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264 [inlined]
   [10] solve!(::Convex.Problem{Float64}, ::CSDP.Optimizer; check_vexity::Bool, verbose::Bool, warmstart::Bool, silent_solver::Bool) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:245
   [11] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:223 [inlined]
   [12] solve!(::Convex.Problem{Float64}, ::var"#1#2"; kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:192
   [13] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:191 [inlined]
   [14] #2 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/convex.jl:12 [inlined]
   [15] sdp_matrix_frac_atom_both_arguments_variable(::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}, ::Val{true}, ::Float64, ::Float64, ::Type{Float64}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:175
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}})(::String, ::typeof(Convex.ProblemDepot.sdp_matrix_frac_atom_both_arguments_variable)) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problem_depot.jl:80
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(Convex.ProblemDepot.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::var"#1#2"; variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:11
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sdp_nuclear_norm_atom:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  ArgumentError: Empty constraint MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}(33): MathOptInterface.ScalarAffineFunction{Float64}(MathOptInterface.ScalarAffineTerm{Float64}[], 0.0)-in-MathOptInterface.EqualTo{Float64}(-0.0). Not supported by CSDP.
  Stacktrace:
   [1] load_constraint(::CSDP.Optimizer, ::MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}, ::MathOptInterface.ScalarAffineFunction{Float64}, ::MathOptInterface.EqualTo{Float64}) at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:275
   [2] load_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::MathOptInterface.Utilities.IndexMap, ::Array{MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}},1}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:711
   [3] pass_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::MathOptInterface.Utilities.IndexMap, ::Array{DataType,1}, ::Array{Array{var"#s280",1} where var"#s280"<:(MathOptInterface.ConstraintIndex{MathOptInterface.SingleVariable,S} where S),1}, ::Array{Type{var"#s309"} where var"#s309"<:MathOptInterface.AbstractVectorSet,1}, ::Array{Array{var"#s304",1} where var"#s304"<:(MathOptInterface.ConstraintIndex{MathOptInterface.VectorOfVariables,S} where S),1}, ::typeof(MathOptInterface.Utilities.load_constraints), ::typeof(MathOptInterface.Utilities.load); filter_constraints::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:353
   [4] allocate_load(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:776
   [5] #automatic_copy_to#113 at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:23 [inlined]
   [6] #copy_to#19 at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:155 [inlined]
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize! at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264 [inlined]
   [10] solve!(::Convex.Problem{Float64}, ::CSDP.Optimizer; check_vexity::Bool, verbose::Bool, warmstart::Bool, silent_solver::Bool) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:245
   [11] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:223 [inlined]
   [12] solve!(::Convex.Problem{Float64}, ::var"#1#2"; kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:192
   [13] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:191 [inlined]
   [14] #2 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/convex.jl:12 [inlined]
   [15] sdp_nuclear_norm_atom(::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}, ::Val{true}, ::Float64, ::Float64, ::Type{Float64}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:79
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}})(::String, ::typeof(Convex.ProblemDepot.sdp_nuclear_norm_atom)) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problem_depot.jl:80
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(Convex.ProblemDepot.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::var"#1#2"; variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:11
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sdp_operator_norm_atom:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  ArgumentError: Empty constraint MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}(22): MathOptInterface.ScalarAffineFunction{Float64}(MathOptInterface.ScalarAffineTerm{Float64}[], 0.0)-in-MathOptInterface.EqualTo{Float64}(-0.0). Not supported by CSDP.
  Stacktrace:
   [1] load_constraint(::CSDP.Optimizer, ::MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}, ::MathOptInterface.ScalarAffineFunction{Float64}, ::MathOptInterface.EqualTo{Float64}) at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:275
   [2] load_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::MathOptInterface.Utilities.IndexMap, ::Array{MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}},1}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:711
   [3] pass_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::MathOptInterface.Utilities.IndexMap, ::Array{DataType,1}, ::Array{Array{var"#s280",1} where var"#s280"<:(MathOptInterface.ConstraintIndex{MathOptInterface.SingleVariable,S} where S),1}, ::Array{Type{var"#s309"} where var"#s309"<:MathOptInterface.AbstractVectorSet,1}, ::Array{Array{var"#s304",1} where var"#s304"<:(MathOptInterface.ConstraintIndex{MathOptInterface.VectorOfVariables,S} where S),1}, ::typeof(MathOptInterface.Utilities.load_constraints), ::typeof(MathOptInterface.Utilities.load); filter_constraints::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:353
   [4] allocate_load(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:776
   [5] #automatic_copy_to#113 at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:23 [inlined]
   [6] #copy_to#19 at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:155 [inlined]
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize! at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264 [inlined]
   [10] solve!(::Convex.Problem{Float64}, ::CSDP.Optimizer; check_vexity::Bool, verbose::Bool, warmstart::Bool, silent_solver::Bool) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:245
   [11] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:223 [inlined]
   [12] solve!(::Convex.Problem{Float64}, ::var"#1#2"; kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:192
   [13] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:191 [inlined]
   [14] (::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"})(::Convex.Problem{Float64}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/convex.jl:12
   [15] sdp_operator_norm_atom(::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}, ::Val{true}, ::Float64, ::Float64, ::Type{Float64}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:93
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}})(::String, ::typeof(Convex.ProblemDepot.sdp_operator_norm_atom)) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problem_depot.jl:80
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(Convex.ProblemDepot.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::var"#1#2"; variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:11
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sdp_Partial_trace:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  ArgumentError: Empty constraint MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}(21): MathOptInterface.ScalarAffineFunction{Float64}(MathOptInterface.ScalarAffineTerm{Float64}[], 0.0)-in-MathOptInterface.EqualTo{Float64}(-0.0). Not supported by CSDP.
  Stacktrace:
   [1] load_constraint(::CSDP.Optimizer, ::MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}, ::MathOptInterface.ScalarAffineFunction{Float64}, ::MathOptInterface.EqualTo{Float64}) at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:275
   [2] load_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::MathOptInterface.Utilities.IndexMap, ::Array{MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}},1}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:711
   [3] pass_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::MathOptInterface.Utilities.IndexMap, ::Array{DataType,1}, ::Array{Array{var"#s280",1} where var"#s280"<:(MathOptInterface.ConstraintIndex{MathOptInterface.SingleVariable,S} where S),1}, ::Array{Type{var"#s309"} where var"#s309"<:MathOptInterface.AbstractVectorSet,1}, ::Array{Array{var"#s304",1} where var"#s304"<:(MathOptInterface.ConstraintIndex{MathOptInterface.VectorOfVariables,S} where S),1}, ::typeof(MathOptInterface.Utilities.load_constraints), ::typeof(MathOptInterface.Utilities.load); filter_constraints::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:353
   [4] allocate_load(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:776
   [5] #automatic_copy_to#113 at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:23 [inlined]
   [6] #copy_to#19 at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:155 [inlined]
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize! at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264 [inlined]
   [10] solve!(::Convex.Problem{Float64}, ::CSDP.Optimizer; check_vexity::Bool, verbose::Bool, warmstart::Bool, silent_solver::Bool) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:245
   [11] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:223 [inlined]
   [12] solve!(::Convex.Problem{Float64}, ::var"#1#2"; kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:192
   [13] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:191 [inlined]
   [14] (::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"})(::Convex.Problem{Float64}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/convex.jl:12
   [15] sdp_Partial_trace(::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}, ::Val{true}, ::Float64, ::Float64, ::Type{Float64}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:254
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}})(::String, ::typeof(Convex.ProblemDepot.sdp_Partial_trace)) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problem_depot.jl:80
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(Convex.ProblemDepot.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::var"#1#2"; variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:11
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sdp_sigma_max_atom:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  ArgumentError: Empty constraint MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}(22): MathOptInterface.ScalarAffineFunction{Float64}(MathOptInterface.ScalarAffineTerm{Float64}[], 0.0)-in-MathOptInterface.EqualTo{Float64}(-0.0). Not supported by CSDP.
  Stacktrace:
   [1] load_constraint(::CSDP.Optimizer, ::MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}, ::MathOptInterface.ScalarAffineFunction{Float64}, ::MathOptInterface.EqualTo{Float64}) at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:275
   [2] load_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::MathOptInterface.Utilities.IndexMap, ::Array{MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}},1}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:711
   [3] pass_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::MathOptInterface.Utilities.IndexMap, ::Array{DataType,1}, ::Array{Array{var"#s280",1} where var"#s280"<:(MathOptInterface.ConstraintIndex{MathOptInterface.SingleVariable,S} where S),1}, ::Array{Type{var"#s309"} where var"#s309"<:MathOptInterface.AbstractVectorSet,1}, ::Array{Array{var"#s304",1} where var"#s304"<:(MathOptInterface.ConstraintIndex{MathOptInterface.VectorOfVariables,S} where S),1}, ::typeof(MathOptInterface.Utilities.load_constraints), ::typeof(MathOptInterface.Utilities.load); filter_constraints::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:353
   [4] allocate_load(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:776
   [5] #automatic_copy_to#113 at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:23 [inlined]
   [6] #copy_to#19 at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:155 [inlined]
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize! at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264 [inlined]
   [10] solve!(::Convex.Problem{Float64}, ::CSDP.Optimizer; check_vexity::Bool, verbose::Bool, warmstart::Bool, silent_solver::Bool) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:245
   [11] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:223 [inlined]
   [12] solve!(::Convex.Problem{Float64}, ::var"#1#2"; kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:192
   [13] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:191 [inlined]
   [14] #2 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/convex.jl:12 [inlined]
   [15] sdp_sigma_max_atom(::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}, ::Val{true}, ::Float64, ::Float64, ::Type{Float64}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:107
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}})(::String, ::typeof(Convex.ProblemDepot.sdp_sigma_max_atom)) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problem_depot.jl:80
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(Convex.ProblemDepot.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::var"#1#2"; variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:11
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sdp_matrix_frac_atom:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  ArgumentError: Empty constraint MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}(11): MathOptInterface.ScalarAffineFunction{Float64}(MathOptInterface.ScalarAffineTerm{Float64}[], 0.0)-in-MathOptInterface.EqualTo{Float64}(-0.0). Not supported by CSDP.
  Stacktrace:
   [1] load_constraint(::CSDP.Optimizer, ::MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}}, ::MathOptInterface.ScalarAffineFunction{Float64}, ::MathOptInterface.EqualTo{Float64}) at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:275
   [2] load_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::MathOptInterface.Utilities.IndexMap, ::Array{MathOptInterface.ConstraintIndex{MathOptInterface.ScalarAffineFunction{Float64},MathOptInterface.EqualTo{Float64}},1}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:711
   [3] pass_constraints(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::MathOptInterface.Utilities.IndexMap, ::Array{DataType,1}, ::Array{Array{var"#s280",1} where var"#s280"<:(MathOptInterface.ConstraintIndex{MathOptInterface.SingleVariable,S} where S),1}, ::Array{Type{var"#s309"} where var"#s309"<:MathOptInterface.AbstractVectorSet,1}, ::Array{Array{var"#s304",1} where var"#s304"<:(MathOptInterface.ConstraintIndex{MathOptInterface.VectorOfVariables,S} where S),1}, ::typeof(MathOptInterface.Utilities.load_constraints), ::typeof(MathOptInterface.Utilities.load); filter_constraints::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:353
   [4] allocate_load(::CSDP.Optimizer, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Bool, ::Nothing) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:776
   [5] #automatic_copy_to#113 at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/copy.jl:23 [inlined]
   [6] #copy_to#19 at /home/runner/.julia/packages/CSDP/2oto4/src/MOI_wrapper.jl:155 [inlined]
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize! at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264 [inlined]
   [10] solve!(::Convex.Problem{Float64}, ::CSDP.Optimizer; check_vexity::Bool, verbose::Bool, warmstart::Bool, silent_solver::Bool) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:245
   [11] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:223 [inlined]
   [12] solve!(::Convex.Problem{Float64}, ::var"#1#2"; kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:192
   [13] solve! at /home/runner/.julia/packages/Convex/aYxJA/src/solution.jl:191 [inlined]
   [14] #2 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/convex.jl:12 [inlined]
   [15] sdp_matrix_frac_atom(::ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}, ::Val{true}, ::Float64, ::Float64, ::Type{Float64}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:160
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}})(::String, ::typeof(Convex.ProblemDepot.sdp_matrix_frac_atom)) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,ConvexTests.ConvexBench.var"#2#3"{var"#1#2"}}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problem_depot.jl:80
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(Convex.ProblemDepot.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::var"#1#2"; variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:11
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:             307s / 100%            21.1GiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1     202s  65.9%    202s   13.5GiB  64.3%  13.5GiB
   socp                     1    83.6s  27.3%   83.6s   5.43GiB  25.8%  5.43GiB
     sdsos_term_fixed       1    17.6s  5.73%   17.6s   1.15GiB  5.45%  1.15GiB
     sdsos_horn             1    11.9s  3.90%   11.9s    804MiB  3.74%   804MiB
     sdsos_options_...      1    10.5s  3.43%   10.5s    145MiB  0.67%   145MiB
     sdsos_concave_...      1    9.02s  2.94%   9.02s    600MiB  2.79%   600MiB
     sdsos_univaria...      1    6.73s  2.20%   6.73s    522MiB  2.42%   522MiB
     sdsos_cheby_un...      1    6.68s  2.18%   6.68s    470MiB  2.18%   470MiB
     sdsos_univaria...      1    5.25s  1.71%   5.25s    343MiB  1.59%   343MiB
     sdsos_scaled_u...      1    3.45s  1.12%   3.45s    251MiB  1.17%   251MiB
     sdsos_quartic_...      1    3.41s  1.11%   3.41s    233MiB  1.08%   233MiB
     sdsos_term             1    2.91s  0.95%   2.91s    171MiB  0.79%   171MiB
     sdsos_quartic_...      1    1.39s  0.45%   1.39s   23.1MiB  0.11%  23.1MiB
     sdsos_scaled_b...      1   57.0ms  0.02%  57.0ms   5.68MiB  0.03%  5.68MiB
     sdsos_bivariat...      1   18.8ms  0.01%  18.8ms    662KiB  0.00%   662KiB
   sdp                      1    83.1s  27.1%   83.1s   5.79GiB  27.5%  5.79GiB
     sosdemo5_infea...      1    7.65s  2.50%   7.65s    580MiB  2.69%   580MiB
     quartic_ideal_rem      1    5.81s  1.90%   5.81s    460MiB  2.14%   460MiB
     rearrangement          1    5.28s  1.73%   5.28s    361MiB  1.67%   361MiB
     sos_horn               1    4.39s  1.44%   4.39s    247MiB  1.15%   247MiB
     simple_matrix          1    3.67s  1.20%   3.67s    297MiB  1.38%   297MiB
     sos_concave_th...      1    3.61s  1.18%   3.61s    224MiB  1.04%   224MiB
     quartic_ideal          1    3.33s  1.09%   3.33s    202MiB  0.94%   202MiB
     sos_scaled_biv...      1    3.29s  1.08%   3.29s    197MiB  0.92%   197MiB
     chebyshev              1    3.20s  1.05%   3.20s    176MiB  0.82%   176MiB
     sos_term_fixed         1    3.16s  1.03%   3.16s    199MiB  0.92%   199MiB
     quartic_ideal_4        1    2.97s  0.97%   2.97s    194MiB  0.90%   194MiB
     sos_term               1    2.86s  0.93%   2.86s    147MiB  0.68%   147MiB
     maxcut                 1    2.83s  0.92%   2.83s    133MiB  0.62%   133MiB
     sos_cheby_univ...      1    2.79s  0.91%   2.79s    177MiB  0.82%   177MiB
     quartic_feasib...      1    2.65s  0.87%   2.65s    118MiB  0.55%   118MiB
     sos_options_pr...      1    2.55s  0.83%   2.55s    125MiB  0.58%   125MiB
     sos_quartic_co...      1    2.44s  0.80%   2.44s    159MiB  0.74%   159MiB
     quartic_ideal_...      1    2.41s  0.79%   2.41s    155MiB  0.72%   155MiB
     BPT12e399_rem          1    2.12s  0.69%   2.12s   72.0MiB  0.33%  72.0MiB
     sos_univariate...      1    1.71s  0.56%   1.71s    102MiB  0.47%   102MiB
     sosdemo10              1    1.26s  0.41%   1.26s    107MiB  0.50%   107MiB
     quadratic_infe...      1    965ms  0.32%   965ms   76.6MiB  0.36%  76.6MiB
     sosdemo9               1    947ms  0.31%   947ms   41.0MiB  0.19%  41.0MiB
     sosdemo5_feasible      1    811ms  0.26%   811ms   24.2MiB  0.11%  24.2MiB
     choi                   1    607ms  0.20%   607ms   41.7MiB  0.19%  41.7MiB
     quadratic_feas...      1    403ms  0.13%   403ms   27.3MiB  0.13%  27.3MiB
     sos_univariate...      1    393ms  0.13%   393ms   15.1MiB  0.07%  15.1MiB
     motzkin                1    360ms  0.12%   360ms   4.90MiB  0.02%  4.90MiB
     sos_quartic_co...      1    272ms  0.09%   272ms   15.9MiB  0.07%  15.9MiB
     BPT12e399_maxd...      1    229ms  0.07%   229ms   7.89MiB  0.04%  7.89MiB
     quartic_infeas...      1    105ms  0.03%   105ms   1.97MiB  0.01%  1.97MiB
     quartic_infeas...      1   85.5ms  0.03%  85.5ms    634KiB  0.00%   634KiB
     quartic_ideal_...      1   52.1ms  0.02%  52.1ms   1.69MiB  0.01%  1.69MiB
     sos_bivariate_...      1   26.7ms  0.01%  26.7ms    657KiB  0.00%   657KiB
     sos_scaled_uni...      1   26.6ms  0.01%  26.6ms    655KiB  0.00%   655KiB
     quadratic_infe...      1   24.6ms  0.01%  24.6ms    604KiB  0.00%   604KiB
     quartic_feasib...      1   24.1ms  0.01%  24.1ms    552KiB  0.00%   552KiB
     quadratic_feas...      1   17.8ms  0.01%  17.8ms    510KiB  0.00%   510KiB
   lp                       1    34.9s  11.4%   34.9s   2.30GiB  10.9%  2.30GiB
     dsos_options_p...      1    6.14s  2.00%   6.14s    328MiB  1.53%   328MiB
     dsos_univariat...      1    3.94s  1.29%   3.94s    237MiB  1.10%   237MiB
     dsos_concave_t...      1    3.88s  1.27%   3.88s    247MiB  1.15%   247MiB
     dsos_cheby_biv...      1    3.71s  1.21%   3.71s    220MiB  1.02%   220MiB
     dsos_horn              1    3.24s  1.06%   3.24s    345MiB  1.60%   345MiB
     dsos_term_fixed        1    3.14s  1.03%   3.14s    187MiB  0.87%   187MiB
     dsos_term              1    2.92s  0.95%   2.92s    153MiB  0.71%   153MiB
     dsos_scaled_bi...      1    2.89s  0.94%   2.89s    183MiB  0.85%   183MiB
     dsos_quartic_c...      1    2.37s  0.77%   2.37s    159MiB  0.74%   159MiB
     dsos_bivariate...      1    480ms  0.16%   480ms   17.3MiB  0.08%  17.3MiB
     dsos_quartic_c...      1    326ms  0.11%   326ms   16.4MiB  0.08%  16.4MiB
     dsos_scaled_un...      1   15.9ms  0.01%  15.9ms    770KiB  0.00%   770KiB
     dsos_univariat...      1   14.3ms  0.00%  14.3ms    769KiB  0.00%   769KiB
     dsos_cheby_uni...      1   12.9ms  0.00%  12.9ms    781KiB  0.00%   781KiB
 Convex                     1     105s  34.1%    105s   7.51GiB  35.7%  7.51GiB
   affine                   1    35.0s  11.4%   35.0s   2.86GiB  13.6%  2.86GiB
     affine_Partial...      1    5.30s  1.73%   5.30s    340MiB  1.58%   340MiB
     affine_Diagona...      1    3.77s  1.23%   3.77s    271MiB  1.26%   271MiB
     affine_permute...      1    2.91s  0.95%   2.91s    384MiB  1.79%   384MiB
     affine_dot_mul...      1    2.91s  0.95%   2.91s    154MiB  0.72%   154MiB
     affine_hcat_atom       1    2.63s  0.86%   2.63s    176MiB  0.82%   176MiB
     affine_multipl...      1    2.35s  0.77%   2.35s    214MiB  0.99%   214MiB
     affine_transpo...      1    1.74s  0.57%   1.74s   83.1MiB  0.39%  83.1MiB
     affine_vcat_atom       1    1.40s  0.46%   1.40s   96.0MiB  0.45%  96.0MiB
     affine_add_atom        1    1.16s  0.38%   1.16s   65.7MiB  0.30%  65.7MiB
     affine_satisfy...      1    1.04s  0.34%   1.04s   55.7MiB  0.26%  55.7MiB
     affine_conv_atom       1    884ms  0.29%   884ms   49.4MiB  0.23%  49.4MiB
     affine_dot_atom        1    785ms  0.26%   785ms   23.8MiB  0.11%  23.8MiB
     affine_reshape...      1    754ms  0.25%   754ms   26.6MiB  0.12%  26.6MiB
     affine_dualvalue       1    741ms  0.24%   741ms   71.6MiB  0.33%  71.6MiB
     affine_index_atom      1    692ms  0.23%   692ms   42.3MiB  0.20%  42.3MiB
     affine_sum_atom        1    611ms  0.20%   611ms   28.2MiB  0.13%  28.2MiB
     affine_diag_atom       1    402ms  0.13%   402ms   13.3MiB  0.06%  13.3MiB
     affine_kron_atom       1    215ms  0.07%   215ms   10.8MiB  0.05%  10.8MiB
     affine_dot_ato...      1    126ms  0.04%   126ms   5.04MiB  0.02%  5.04MiB
     affine_negate_...      1   96.4ms  0.03%  96.4ms   3.63MiB  0.02%  3.63MiB
     affine_trace_atom      1   53.2ms  0.02%  53.2ms   2.51MiB  0.01%  2.51MiB
   socp                     1    31.7s  10.4%   31.7s   1.94GiB  9.24%  1.94GiB
     socp_rational_...      1    7.09s  2.31%   7.09s    136MiB  0.63%   136MiB
     socp_dual_mini...      1    5.66s  1.85%   5.66s    454MiB  2.11%   454MiB
     socp_quad_form...      1    3.26s  1.06%   3.26s   35.8MiB  0.17%  35.8MiB
     socp_dual_norm...      1    1.37s  0.45%   1.37s   63.5MiB  0.29%  63.5MiB
     socp_inv_pos_atom      1    1.37s  0.45%   1.37s   62.6MiB  0.29%  62.6MiB
     socp_sum_squar...      1    1.34s  0.44%   1.34s   89.7MiB  0.42%  89.7MiB
     socp_quad_over...      1    1.09s  0.36%   1.09s   27.7MiB  0.13%  27.7MiB
     socp_rational_...      1    996ms  0.33%   996ms   9.64MiB  0.04%  9.64MiB
     socp_fix_multi...      1    986ms  0.32%   986ms   31.1MiB  0.14%  31.1MiB
     socp_square_atom       1    867ms  0.28%   867ms   13.2MiB  0.06%  13.2MiB
     socp_rational_...      1    813ms  0.27%   813ms   37.0MiB  0.17%  37.0MiB
     socp_dual_frob...      1    771ms  0.25%   771ms   24.4MiB  0.11%  24.4MiB
     socp_norm_cons...      1    500ms  0.16%   500ms   25.8MiB  0.12%  25.8MiB
     socp_geo_mean_...      1    499ms  0.16%   499ms   24.9MiB  0.12%  24.9MiB
     socp_huber_atom        1    498ms  0.16%   498ms   31.2MiB  0.15%  31.2MiB
     socp_fix_and_f...      1    125ms  0.04%   125ms   5.61MiB  0.03%  5.61MiB
     socp_sqrt_atom         1   68.9ms  0.02%  68.9ms   1.49MiB  0.01%  1.49MiB
   sdp                      1    19.0s  6.20%   19.0s   1.23GiB  5.86%  1.23GiB
     sdp_operator_n...      1    3.16s  1.03%   3.16s    239MiB  1.11%   239MiB
     sdp_sum_larges...      1    1.63s  0.53%   1.63s   38.7MiB  0.18%  38.7MiB
     sdp_dual_lambd...      1    1.58s  0.51%   1.58s   73.0MiB  0.34%  73.0MiB
     sdp_matrix_fra...      1    1.39s  0.45%   1.39s   85.0MiB  0.39%  85.0MiB
     sdp_Complex_Va...      1    1.25s  0.41%   1.25s   41.0MiB  0.19%  41.0MiB
     sdp_lambda_min...      1    1.06s  0.35%   1.06s   40.5MiB  0.19%  40.5MiB
     sdp_matrix_fra...      1    983ms  0.32%   983ms   50.2MiB  0.23%  50.2MiB
     sdp_Partial_trace      1    898ms  0.29%   898ms   56.7MiB  0.26%  56.7MiB
     sdp_Issue_198          1    781ms  0.25%   781ms   37.2MiB  0.17%  37.2MiB
     sdp_socp_sumsq...      1    729ms  0.24%   729ms   40.7MiB  0.19%  40.7MiB
     sdp_sdp_variables      1    620ms  0.20%   620ms   24.9MiB  0.12%  24.9MiB
     sdp_nuclear_no...      1    456ms  0.15%   456ms   33.7MiB  0.16%  33.7MiB
     sdp_Real_Varia...      1    394ms  0.13%   394ms   5.69MiB  0.03%  5.69MiB
     sdp_socp_abs_atom      1    371ms  0.12%   371ms   22.3MiB  0.10%  22.3MiB
     sdp_socp_norm2...      1    343ms  0.11%   343ms   22.3MiB  0.10%  22.3MiB
     sdp_sdp_constr...      1    338ms  0.11%   338ms   8.07MiB  0.04%  8.07MiB
     sdp_kron_atom          1    253ms  0.08%   253ms   20.2MiB  0.09%  20.2MiB
     sdp_sigma_max_...      1    174ms  0.06%   174ms   12.8MiB  0.06%  12.8MiB
   constant                 1    10.4s  3.39%   10.4s    937MiB  4.35%   937MiB
     constant_fix!_...      1    3.87s  1.26%   3.87s    262MiB  1.21%   262MiB
     constant_Issue...      1    3.08s  1.00%   3.08s    315MiB  1.46%   315MiB
     constant_Issue...      1    943ms  0.31%   943ms   63.7MiB  0.30%  63.7MiB
     constant_fix!_...      1    641ms  0.21%   641ms   42.4MiB  0.20%  42.4MiB
     constant_Test_...      1    346ms  0.11%   346ms   18.5MiB  0.09%  18.5MiB
     constant_fix!_...      1    282ms  0.09%   282ms   20.0MiB  0.09%  20.0MiB
   lp                       1    8.12s  2.65%   8.12s    533MiB  2.47%   533MiB
     lp_min_atom            1    1.16s  0.38%   1.16s   42.2MiB  0.20%  42.2MiB
     lp_max_atom            1    1.13s  0.37%   1.13s   34.7MiB  0.16%  34.7MiB
     lp_dotsort_atom        1    980ms  0.32%   980ms   57.1MiB  0.27%  57.1MiB
     lp_sumlargest_...      1    672ms  0.22%   672ms   43.7MiB  0.20%  43.7MiB
     lp_sumsmallest...      1    665ms  0.22%   665ms   42.3MiB  0.20%  42.3MiB
     lp_minimum_atom        1    484ms  0.16%   484ms   26.8MiB  0.12%  26.8MiB
     lp_maximum_atom        1    362ms  0.12%   362ms   12.1MiB  0.06%  12.1MiB
     lp_dual_abs_atom       1    310ms  0.10%   310ms   17.4MiB  0.08%  17.4MiB
     lp_dual_norm_i...      1    255ms  0.08%   255ms   3.73MiB  0.02%  3.73MiB
     lp_neg_atom            1    252ms  0.08%   252ms   10.9MiB  0.05%  10.9MiB
     lp_dual_norm_1...      1    238ms  0.08%   238ms   3.37MiB  0.02%  3.37MiB
     lp_pos_atom            1    150ms  0.05%   150ms   5.89MiB  0.03%  5.89MiB
     lp_hinge_loss_...      1    206μs  0.00%   206μs   47.7KiB  0.00%  47.7KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## CSDP (dualized)
These tests were run on October 6, 2020 at 10:46 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"sdp_Complex_Semidefinite_constraint"]
```

### Tests

Tests took 2 minutes, 18 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">CSDP tests</td>
<td style="text-align:center;color:green;">1722</td>
<td style="text-align:center;color:red;">25</td>
<td style="text-align:center;color:red;">32</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1779</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">367</td>
<td style="text-align:center;color:red;">25</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">392</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">26</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_166</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;constant_Issue_228</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_vectors</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_with_complex_numbers</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;constant_Test_double_fix!</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;constant_fix!_and_multiply</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">117</td>
<td style="text-align:center;color:red;">22</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_satisfy_problems</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_transpose_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_diag_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_conv_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_multiply_atom</td>
<td style="text-align:center;color:green;">13</td>
<td style="text-align:center;color:red;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">19</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_hcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_vcat_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_index_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_permuteddims_matrix</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_Partial_transpose</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_add_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dot_atom_for_matrix_variables</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_dualvalue</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_Diagonal_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_sum_atom</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_reshape_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_multiply_atom</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_trace_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;affine_negate_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">99</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">99</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">62</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">62</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">63</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">64</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">1355</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">32</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1387</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">398</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">401</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_horn</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_sum</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_concave_then_convex_cubic</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_options_pricing</td>
<td style="text-align:center;color:green;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">451</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">454</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_sum</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_options_pricing</td>
<td style="text-align:center;color:green;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_cheby_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_horn</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_concave_then_convex_cubic</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">506</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">26</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">532</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_infeasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;simple_matrix</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_concave_then_convex_cubic</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rearrangement</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;maxcut</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=3.9 it should be infeasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=4.1 it should be feasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_rem</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_feasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;chebyshev</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_horn</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_rem</td>
<td style="text-align:center;color:green;">48</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">48</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;motzkin</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_maxdegree</td>
<td style="text-align:center;color:green;">56</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">56</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_options_pricing</td>
<td style="text-align:center;color:green;">10</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_sum</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;choi</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4_rem</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_2_rem</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr></table>
```

### Errors

```julia
Error in testset constant_Test_double_fix!:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/constant.jl:55
  Expression: ≈(prob.optval, 4.0, atol = atol, rtol = rtol)
   Evaluated: 18.212499062499763 ≈ 4.0 (atol=0.001, rtol=0.0)

Error in testset constant_Test_double_fix!:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/constant.jl:62
  Expression: ≈(prob.optval, 0.5, atol = atol, rtol = rtol)
   Evaluated: 0.7249998881966014 ≈ 0.5 (atol=0.001, rtol=0.0)

Error in testset affine_conv_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:532
  Expression: ≈(p.optval, 3, atol = atol, rtol = rtol)
   Evaluated: 4.349913870305508 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_conv_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:545
  Expression: ≈(p.optval, 3, atol = atol, rtol = rtol)
   Evaluated: 4.349913870305508 ≈ 3 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:332
  Expression: ≈(p.optval, 6, atol = atol, rtol = rtol)
   Evaluated: -35.0599971339922 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:333
  Expression: ≈(evaluate(sum((dot(*))(x, [1, 2, 3]))), 6, atol = atol, rtol = rtol)
   Evaluated: -35.05999721145187 ≈ 6 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:368
  Expression: ≈(p.optval, 9, atol = atol, rtol = rtol)
   Evaluated: 64.3499957397182 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:369
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol = atol, rtol = rtol)
   Evaluated: 7.149999535241995 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:380
  Expression: ≈(p.optval, 9, atol = atol, rtol = rtol)
   Evaluated: 64.3499957397182 ≈ 9 (atol=0.001, rtol=0.0)

Error in testset affine_dot_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:381
  Expression: ≈((evaluate(x[1, 1]))[1], 1, atol = atol, rtol = rtol)
   Evaluated: 7.149999535241995 ≈ 1 (atol=0.001, rtol=0.0)

Error in testset affine_Partial_transpose:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:653
  Expression: ≈(partialtranspose(S, 1, dims), evaluate(Rt1), atol = atol, rtol = rtol)
   Evaluated: Complex{Float64}[0.699099299094827 + 0.19677551106850055im 0.9554591230023455 + 0.4198079605681324im … 0.7065891799305992 + 0.940503883137046im 0.40773702050152716 + 0.6497797672675623im; 0.8483406283023749 + 0.806661485420773im 0.48357563701098183 + 0.23327645776720574im … 0.6733429037088214 + 0.06578114592435247im 0.654351332722948 + 0.00877165325325202im; … ; 0.4494441273824197 + 0.4823295036204429im 0.9345649458128715 + 0.6413216757205125im … 0.9334619120894365 + 0.17684670619413123im 0.8678203214709206 + 0.6535961889584374im; 0.07343603970494006 + 0.7639310735325im 0.33138950856445937 + 0.98467429854786im … 0.2580519300500794 + 0.9276650613258279im 0.8713880561668039 + 0.5687418929903736im] ≈ Complex{Float64}[0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; … ; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im] (atol=0.001, rtol=0.0)

Error in testset affine_Partial_transpose:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:654
  Expression: ≈(partialtranspose(S, 2, dims), evaluate(Rt2), atol = atol, rtol = rtol)
   Evaluated: Complex{Float64}[0.699099299094827 + 0.19677551106850055im 0.9554591230023455 + 0.4198079605681324im … 0.04246699319812741 + 0.10081207973974493im 0.07655000724806094 + 0.9977955685196491im; 0.8483406283023749 + 0.806661485420773im 0.48357563701098183 + 0.23327645776720574im … 0.021383710064760475 + 0.24289141496649824im 0.24736541242389865 + 0.5682217273197376im; … ; 0.567775594167242 + 0.9951279002794222im 0.08420353853047802 + 0.4306290362243599im … 0.9334619120894365 + 0.17684670619413123im 0.8678203214709206 + 0.6535961889584374im; 0.571329069727889 + 0.9690219973447176im 0.9960993818337707 + 0.8023443646392476im … 0.2580519300500794 + 0.9276650613258279im 0.8713880561668039 + 0.5687418929903736im] ≈ Complex{Float64}[0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; … ; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im] (atol=0.001, rtol=0.0)

Error in testset affine_Partial_transpose:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:655
  Expression: ≈(partialtranspose(S, 3, dims), evaluate(Rt3), atol = atol, rtol = rtol)
   Evaluated: Complex{Float64}[0.699099299094827 + 0.19677551106850055im 0.8483406283023749 + 0.806661485420773im … 0.25875703797981386 + 0.23320294011827647im 0.3628625449221543 + 0.6381560709523029im; 0.9554591230023455 + 0.4198079605681324im 0.48357563701098183 + 0.23327645776720574im … 0.21707819328524458 + 0.800556523872735im 0.5260307281243644 + 0.5164820336808222im; … ; 0.9410044329661877 + 0.7164915841996107im 0.7942176578848801 + 0.24861407392918222im … 0.9334619120894365 + 0.17684670619413123im 0.2580519300500794 + 0.9276650613258279im; 0.01334698719287597 + 0.921993309529411im 0.027056331242949705 + 0.055920597561612606im … 0.8678203214709206 + 0.6535961889584374im 0.8713880561668039 + 0.5687418929903736im] ≈ Complex{Float64}[0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; … ; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im; 0.0 + 0.0im 0.0 + 0.0im … 0.0 + 0.0im 0.0 + 0.0im] (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:94
  Expression: ≈(p.optval, 4.4, atol = atol, rtol = rtol)
   Evaluated: 33.14999836658321 ≈ 4.4 (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:95
  Expression: ≈((evaluate(dot([2.0; 2.0], x)))[1], 4.4, atol = atol, rtol = rtol)
   Evaluated: 33.149998444364954 ≈ 4.4 (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom_for_matrix_variables:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:108
  Expression: ≈(p.optval, 8.8, atol = atol, rtol = rtol)
   Evaluated: 70.6660242200822 ≈ 8.8 (atol=0.001, rtol=0.0)

Error in testset affine_dot_atom_for_matrix_variables:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:109
  Expression: ≈((evaluate(dot(fill(2.0, (2, 2)), x)))[1], 8.8, atol = atol, rtol = rtol)
   Evaluated: 70.66602430989681 ≈ 8.8 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:427
  Expression: ≈(p.optval, sum(b .+ c), atol = atol, rtol = rtol)
   Evaluated: 60.212880917840096 ≈ 6.42039176784122 (atol=0.001, rtol=0.0)

Error in testset affine_reshape_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:428
  Expression: ≈(evaluate(sum(vec(X) + b)), sum(b .+ c), atol = atol, rtol = rtol)
   Evaluated: 60.212881093089116 ≈ 6.42039176784122 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:33
  Expression: ≈(p.optval, 4, atol = atol, rtol = rtol)
   Evaluated: 5.599998881966009 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:34
  Expression: ≈((evaluate(2.0x))[1], 4, atol = atol, rtol = rtol)
   Evaluated: 5.599999105572807 ≈ 4 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:46
  Expression: ≈(p.optval, 2.93333, atol = atol, rtol = rtol)
   Evaluated: 24.470369255498596 ≈ 2.93333 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:47
  Expression: ≈((evaluate([2 2] * x))[1], 2.93333, atol = atol, rtol = rtol)
   Evaluated: 24.47036933328034 ≈ 2.93333 (atol=0.001, rtol=0.0)

Error in testset affine_multiply_atom:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/affine.jl:48
  Expression: ≈(vec(evaluate(A * x)), [1.1; 1.1], atol = atol, rtol = rtol)
   Evaluated: [9.176388499980128, 9.176388499980126] ≈ [1.1, 1.1] (atol=0.001, rtol=0.0)

Error in testset sdp_Real_Variables_with_complex_equality_constraints:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:314
  Expression: x1 == x2
   Evaluated: [0.06485656915977099, 0.08309649923835177, 0.23743459600490116, 0.5699636711901669, 0.6443483595990795, 0.40997366545916575, 0.5043350036805111, 0.5449579988222665, 0.39503133789524786, 0.755883312965018] == [0.06485656915979, 0.08309649923836354, 0.2374345960048704, 0.5699636711902052, 0.6443483595990935, 0.4099736654591575, 0.504335003680535, 0.5449579988222681, 0.3950313378952389, 0.7558833129649861]

Error in testset sdsos_horn:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] horn_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::SumOfSquares.NonnegPolyInnerCone{SumOfSquares.ScaledDiagonallyDominantConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/horn.jl:33
   [14] sdsos_horn_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/horn.jl:65 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sdsos_horn_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset sdsos_univariate_sum:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] univariate_sum_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::SumOfSquares.NonnegPolyInnerCone{SumOfSquares.ScaledDiagonallyDominantConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/univariate_sum.jl:17
   [14] sdsos_univariate_sum_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/univariate_sum.jl:43 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sdsos_univariate_sum_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset sdsos_concave_then_convex_cubic:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] concave_then_convex_cubic_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Type{SumOfSquares.ScaledDiagonallyDominantConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/concave_then_convex_cubic.jl:23
   [14] sdsos_concave_then_convex_cubic_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/concave_then_convex_cubic.jl:50 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sdsos_concave_then_convex_cubic_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset dsos_univariate_sum:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] univariate_sum_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::SumOfSquares.NonnegPolyInnerCone{SumOfSquares.DiagonallyDominantConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/univariate_sum.jl:17
   [14] dsos_univariate_sum_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/univariate_sum.jl:45 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.dsos_univariate_sum_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset dsos_horn:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] horn_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::SumOfSquares.NonnegPolyInnerCone{SumOfSquares.DiagonallyDominantConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/horn.jl:33
   [14] dsos_horn_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/horn.jl:67 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.dsos_horn_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset dsos_concave_then_convex_cubic:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] concave_then_convex_cubic_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Type{SumOfSquares.DiagonallyDominantConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/concave_then_convex_cubic.jl:23
   [14] dsos_concave_then_convex_cubic_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/concave_then_convex_cubic.jl:55 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.dsos_concave_then_convex_cubic_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset sosdemo5_infeasible:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] sosdemo5_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Bool, ::Float64) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/sosdemo5.jl:62
   [14] sosdemo5_infeasible_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/sosdemo5.jl:72 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo5_infeasible_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset simple_matrix:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] simple_matrix_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/simple_matrix.jl:20
   [14] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [15] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.simple_matrix_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sos_concave_then_convex_cubic:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] concave_then_convex_cubic_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Type{MathOptInterface.PositiveSemidefiniteConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/concave_then_convex_cubic.jl:23
   [14] sos_concave_then_convex_cubic_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/concave_then_convex_cubic.jl:45 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sos_concave_then_convex_cubic_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset rearrangement:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] rearrangement_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/rearrangement.jl:23
   [14] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [15] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.rearrangement_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset with γ=3.9 it should be infeasible:
Error During Test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/maxcut.jl:29
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] macro expansion at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/maxcut.jl:32 [inlined]
   [14] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1190 [inlined]
   [15] maxcut_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/maxcut.jl:29
   [16] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [20] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.maxcut_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [26] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [28] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [31] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [36] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion at ./timing.jl:310 [inlined]
   [38] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [40] include(::Function, ::Module, ::String) at ./Base.jl:380
   [41] include(::Module, ::String) at ./Base.jl:368
   [42] exec_options(::Base.JLOptions) at ./client.jl:296
   [43] _start() at ./client.jl:506
  

Error in testset with γ=4.1 it should be feasible:
Error During Test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/maxcut.jl:29
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] macro expansion at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/maxcut.jl:32 [inlined]
   [14] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1190 [inlined]
   [15] maxcut_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/maxcut.jl:29
   [16] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [17] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [20] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [21] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [22] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.maxcut_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [23] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [26] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [27] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [28] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [31] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [32] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [33] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [36] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [37] macro expansion at ./timing.jl:310 [inlined]
   [38] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [39] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [40] include(::Function, ::Module, ::String) at ./Base.jl:380
   [41] include(::Module, ::String) at ./Base.jl:368
   [42] exec_options(::Base.JLOptions) at ./client.jl:296
   [43] _start() at ./client.jl:506
  

Error in testset quartic_ideal_rem:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] quartic_ideal_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Nothing, ::Bool) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:17
   [14] quartic_ideal_rem_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:39 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_rem_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset sosdemo5_feasible:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] sosdemo5_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Bool, ::Float64) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/sosdemo5.jl:62
   [14] sosdemo5_feasible_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/sosdemo5.jl:73 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo5_feasible_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset sosdemo9:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] sosdemo9_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/sosdemo9.jl:17
   [14] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [15] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo9_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset quartic_ideal:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] quartic_ideal_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Nothing, ::Bool) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:17
   [14] quartic_ideal_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:35 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quartic_feasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quartic_feasible_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:93 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_feasible_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset sos_horn:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] horn_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::SumOfSquares.NonnegPolyInnerCone{MathOptInterface.PositiveSemidefiniteConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/horn.jl:33
   [14] sos_horn_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/horn.jl:63 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sos_horn_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quadratic_infeasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quadratic_infeasible_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:81 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_infeasible_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quadratic_feasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quadratic_feasible_scaled_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:87 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_feasible_scaled_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quartic_ideal_4:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] quartic_ideal_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Bool) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:17
   [14] quartic_ideal_4_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:37 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_4_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quadratic_infeasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quadratic_infeasible_scaled_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:83 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_infeasible_scaled_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quadratic_feasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quadratic_feasible_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:85 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quadratic_feasible_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset motzkin:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] motzkin_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/motzkin.jl:17
   [14] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [15] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.motzkin_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset sosdemo10:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] sosdemo10_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/sosdemo10.jl:31
   [14] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [15] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sosdemo10_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset quartic_infeasible_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quartic_infeasible_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:89 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_infeasible_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quartic_infeasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quartic_infeasible_scaled_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:91 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_infeasible_scaled_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset sos_univariate_sum:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] univariate_sum_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::SumOfSquares.NonnegPolyInnerCone{MathOptInterface.PositiveSemidefiniteConeTriangle}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/univariate_sum.jl:17
   [14] sos_univariate_sum_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/univariate_sum.jl:41 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.sos_univariate_sum_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset choi:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] choi_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/choi.jl:32
   [14] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [15] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [16] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [17] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [18] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [19] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [20] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.choi_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [21] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [22] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [23] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [24] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [25] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [26] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [27] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [28] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [29] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [30] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [31] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [32] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [33] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [34] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [35] macro expansion at ./timing.jl:310 [inlined]
   [36] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [37] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [38] include(::Function, ::Module, ::String) at ./Base.jl:380
   [39] include(::Module, ::String) at ./Base.jl:368
   [40] exec_options(::Base.JLOptions) at ./client.jl:296
   [41] _start() at ./client.jl:506
  

Error in testset quartic_feasible_scaled_lyapunov_switched_system:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] lyapunov_switched_system_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Float64, ::Bool, ::Type{T} where T) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:55
   [14] quartic_feasible_scaled_lyapunov_switched_system_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/lyapunov_switched_system.jl:95 [inlined] (repeats 2 times)
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_feasible_scaled_lyapunov_switched_system_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quartic_ideal_4_rem:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] quartic_ideal_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Bool) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:17
   [14] quartic_ideal_4_rem_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:43 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_4_rem_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

Error in testset quartic_ideal_2_rem:
Error During Test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:37
  Got exception outside of a @test
  FEASIBILITY_SENSE is not supported
  Stacktrace:
   [1] error(::MathOptInterface.OptimizationSense, ::String) at ./error.jl:42
   [2] set_dual_model_sense(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/objective_coefficients.jl:10
   [3] dualize(::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}, ::Dualization.DualProblem{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::DualNames, ::Array{MathOptInterface.VariableIndex,1}, ::Bool) at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:30
   [4] #dualize#2 at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [5] dualize at /home/runner/.julia/packages/Dualization/LvJXR/src/dualize.jl:16 [inlined]
   [6] copy_to(::DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}}, ::MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}; kwargs::Base.Iterators.Pairs{Symbol,Bool,Tuple{Symbol},NamedTuple{(:copy_names,),Tuple{Bool}}}) at /home/runner/.julia/packages/Dualization/LvJXR/src/MOI_wrapper.jl:111
   [7] attach_optimizer(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:150
   [8] optimize!(::MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:211
   [9] optimize!(::MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{DualOptimizer{Float64,MathOptInterface.Bridges.LazyBridgeOptimizer{MathOptInterface.Utilities.CachingOptimizer{CSDP.Optimizer,MathOptInterface.Utilities.UniversalFallback{Dualization.DualizableModel{Float64}}}}},MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Bridges/bridge_optimizer.jl:264
   [10] optimize!(::MathOptInterface.Utilities.CachingOptimizer{MathOptInterface.AbstractOptimizer,MathOptInterface.Utilities.UniversalFallback{MathOptInterface.Utilities.Model{Float64}}}) at /home/runner/.julia/packages/MathOptInterface/k7UUH/src/Utilities/cachingoptimizer.jl:215
   [11] optimize!(::JuMP.Model, ::Nothing; bridge_constraints::Bool, ignore_optimize_hook::Bool, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:130
   [12] optimize! at /home/runner/.julia/packages/JuMP/e0Uc2/src/optimizer_interface.jl:106 [inlined] (repeats 2 times)
   [13] quartic_ideal_test(::Function, ::MathOptInterface.Test.TestConfig{Float64}, ::Int64, ::Bool) at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:17
   [14] quartic_ideal_2_rem_test at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/quartic_ideal.jl:41 [inlined]
   [15] _test at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:31 [inlined]
   [16] #3 at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36 [inlined]
   [17] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [18] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [19] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:38 [inlined]
   [20] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [21] (::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)})(::String, ::ConvexTests.SumOfSquaresBench.var"#3#4"{typeof(ConvexTests.SumOfSquaresBench.Tests.quartic_ideal_2_rem_test)}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:36
   [22] foreach_problem(::ConvexTests.var"#3#4"{DataType,Float64,Float64,TimerOutputs.TimerOutput,typeof(dual_opt)}, ::String, ::Nothing; exclude::Array{Regex,1}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/sumofsquares.jl:36
   [23] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [24] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [25] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:35 [inlined]
   [26] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [27] _run_tests(::Function, ::Dict{String,Dict{String,Function}}, ::typeof(ConvexTests.SumOfSquaresBench.foreach_problem), ::Nothing; exclude::Array{Regex,1}, T::Type{T} where T, atol::Float64, rtol::Float64, to::TimerOutputs.TimerOutput) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:33
   [28] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [29] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [30] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:52 [inlined]
   [31] macro expansion at /home/runner/.julia/packages/TimerOutputs/dVnaw/src/TimerOutput.jl:190 [inlined]
   [32] _run_tests(::Function; to::TimerOutputs.TimerOutput, excluded_modules::Array{Module,1}, kws::Base.Iterators.Pairs{Symbol,Any,Tuple{Symbol,Symbol},NamedTuple{(:T, :exclude),Tuple{DataType,Array{Regex,1}}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:50
   [33] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [34] macro expansion at /buildworker/worker/package_linux64/build/usr/share/julia/stdlib/v1.5/Test/src/Test.jl:1115 [inlined]
   [35] macro expansion at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:77 [inlined]
   [36] macro expansion at ./timing.jl:310 [inlined]
   [37] do_tests(::String, ::typeof(dual_opt); variant::String, first::Bool, last::Bool, description::String, T::Type{T} where T, exclude::Array{Regex,1}, kwargs::Base.Iterators.Pairs{Union{},Union{},Tuple{},NamedTuple{(),Tuple{}}}) at /home/runner/work/ConvexTests.jl/ConvexTests.jl/src/ConvexTests.jl:75
   [38] top-level scope at /home/runner/work/ConvexTests.jl/ConvexTests.jl/CSDP/test.jl:17
   [39] include(::Function, ::Module, ::String) at ./Base.jl:380
   [40] include(::Module, ::String) at ./Base.jl:368
   [41] exec_options(::Base.JLOptions) at ./client.jl:296
   [42] _start() at ./client.jl:506
  

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:             139s / 99.1%           8.58GiB / 99.1%    

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1    85.9s  62.3%   85.9s   5.00GiB  58.9%  5.00GiB
   sdp                      1    33.7s  24.5%   33.7s   2.16GiB  25.4%  2.16GiB
     sosdemo5_infea...      1    2.49s  1.81%   2.49s    178MiB  2.05%   178MiB
     rearrangement          1    1.99s  1.44%   1.99s    125MiB  1.43%   125MiB
     quartic_ideal_rem      1    1.94s  1.41%   1.94s    124MiB  1.43%   124MiB
     sos_options_pr...      1    1.90s  1.38%   1.90s   30.0MiB  0.34%  30.0MiB
     sos_horn               1    1.80s  1.31%   1.80s    110MiB  1.27%   110MiB
     sos_term_fixed         1    1.65s  1.20%   1.65s   93.0MiB  1.07%  93.0MiB
     chebyshev              1    1.61s  1.17%   1.61s   84.4MiB  0.97%  84.4MiB
     sos_cheby_univ...      1    1.59s  1.15%   1.59s   85.2MiB  0.98%  85.2MiB
     sos_scaled_biv...      1    1.55s  1.12%   1.55s   89.9MiB  1.03%  89.9MiB
     sos_concave_th...      1    1.32s  0.96%   1.32s   76.7MiB  0.88%  76.7MiB
     quartic_ideal_4        1    1.26s  0.92%   1.26s   79.0MiB  0.91%  79.0MiB
     sos_quartic_co...      1    1.22s  0.89%   1.22s   72.2MiB  0.83%  72.2MiB
     quartic_ideal          1    1.16s  0.84%   1.16s   71.7MiB  0.82%  71.7MiB
     quartic_ideal_...      1    1.15s  0.84%   1.15s   67.6MiB  0.78%  67.6MiB
     simple_matrix          1    1.08s  0.78%   1.08s   71.7MiB  0.82%  71.7MiB
     sos_term               1    978ms  0.71%   978ms   44.6MiB  0.51%  44.6MiB
     BPT12e399_rem          1    699ms  0.51%   699ms   20.6MiB  0.24%  20.6MiB
     sos_univariate...      1    498ms  0.36%   498ms   15.1MiB  0.17%  15.1MiB
     BPT12e399_maxd...      1    491ms  0.36%   491ms   12.9MiB  0.15%  12.9MiB
     sos_univariate...      1    382ms  0.28%   382ms   23.6MiB  0.27%  23.6MiB
     quadratic_infe...      1    266ms  0.19%   266ms   8.31MiB  0.10%  8.31MiB
     maxcut                 1    177ms  0.13%   177ms   4.52MiB  0.05%  4.52MiB
     quartic_ideal_...      1    154ms  0.11%   154ms    752KiB  0.01%   752KiB
     quadratic_feas...      1    145ms  0.11%   145ms    847KiB  0.01%   847KiB
     quadratic_infe...      1    137ms  0.10%   137ms    792KiB  0.01%   792KiB
     quartic_infeas...      1    137ms  0.10%   137ms    840KiB  0.01%   840KiB
     sos_quartic_co...      1    128ms  0.09%   128ms    701KiB  0.01%   701KiB
     sosdemo5_feasible      1    128ms  0.09%   128ms   14.8MiB  0.17%  14.8MiB
     choi                   1    127ms  0.09%   127ms   1.02MiB  0.01%  1.02MiB
     quartic_infeas...      1    127ms  0.09%   127ms    825KiB  0.01%   825KiB
     quartic_feasib...      1    122ms  0.09%   122ms    840KiB  0.01%   840KiB
     sos_bivariate_...      1    122ms  0.09%   122ms    871KiB  0.01%   871KiB
     sos_scaled_uni...      1    122ms  0.09%   122ms    869KiB  0.01%   869KiB
     quadratic_feas...      1    119ms  0.09%   119ms    785KiB  0.01%   785KiB
     sosdemo10              1    118ms  0.09%   118ms   1.92MiB  0.02%  1.92MiB
     motzkin                1    116ms  0.08%   116ms    751KiB  0.01%   751KiB
     sosdemo9               1    113ms  0.08%   113ms   1.11MiB  0.01%  1.11MiB
     quartic_feasib...      1    113ms  0.08%   113ms    825KiB  0.01%   825KiB
   socp                     1    33.2s  24.1%   33.2s   1.78GiB  21.0%  1.78GiB
     sdsos_term_fixed       1    7.26s  5.27%   7.26s    467MiB  5.36%   467MiB
     sdsos_options_...      1    6.44s  4.67%   6.44s   32.8MiB  0.38%  32.8MiB
     sdsos_horn             1    3.89s  2.82%   3.89s    251MiB  2.89%   251MiB
     sdsos_univaria...      1    3.28s  2.38%   3.28s    228MiB  2.62%   228MiB
     sdsos_concave_...      1    2.45s  1.78%   2.45s    157MiB  1.81%   157MiB
     sdsos_term             1    1.99s  1.44%   1.99s    164MiB  1.89%   164MiB
     sdsos_scaled_u...      1    1.63s  1.18%   1.63s   91.5MiB  1.05%  91.5MiB
     sdsos_cheby_un...      1    1.61s  1.17%   1.61s   86.7MiB  1.00%  86.7MiB
     sdsos_univaria...      1    1.17s  0.85%   1.17s   68.8MiB  0.79%  68.8MiB
     sdsos_quartic_...      1    1.15s  0.83%   1.15s   74.0MiB  0.85%  74.0MiB
     sdsos_quartic_...      1    828ms  0.60%   828ms   1.10MiB  0.01%  1.10MiB
     sdsos_scaled_b...      1    127ms  0.09%   127ms    881KiB  0.01%   881KiB
     sdsos_bivariat...      1    121ms  0.09%   121ms    879KiB  0.01%   879KiB
   lp                       1    19.0s  13.7%   19.0s   1.06GiB  12.5%  1.06GiB
     dsos_options_p...      1    4.01s  2.91%   4.01s    160MiB  1.84%   160MiB
     dsos_univariat...      1    2.27s  1.65%   2.27s    131MiB  1.50%   131MiB
     dsos_cheby_biv...      1    2.15s  1.56%   2.15s    123MiB  1.41%   123MiB
     dsos_concave_t...      1    1.82s  1.32%   1.82s    107MiB  1.23%   107MiB
     dsos_scaled_bi...      1    1.58s  1.14%   1.58s   86.7MiB  1.00%  86.7MiB
     dsos_term_fixed        1    1.56s  1.13%   1.56s   83.6MiB  0.96%  83.6MiB
     dsos_quartic_c...      1    1.13s  0.82%   1.13s   71.2MiB  0.82%  71.2MiB
     dsos_quartic_c...      1    1.03s  0.74%   1.03s   65.8MiB  0.76%  65.8MiB
     dsos_term              1    973ms  0.71%   973ms   43.5MiB  0.50%  43.5MiB
     dsos_bivariate...      1    555ms  0.40%   555ms   15.1MiB  0.17%  15.1MiB
     dsos_horn              1    153ms  0.11%   153ms   0.99MiB  0.01%  0.99MiB
     dsos_scaled_un...      1    116ms  0.08%   116ms    868KiB  0.01%   868KiB
     dsos_cheby_uni...      1    115ms  0.08%   115ms    879KiB  0.01%   879KiB
     dsos_univariat...      1    113ms  0.08%   113ms    867KiB  0.01%   867KiB
 Convex                     1    51.9s  37.7%   51.9s   3.50GiB  41.1%  3.50GiB
   constant                 1    17.2s  12.5%   17.2s   1.38GiB  16.3%  1.38GiB
     constant_Issue...      1    13.4s  9.72%   13.4s   1.07GiB  12.6%  1.07GiB
     constant_Test_...      1    2.40s  1.74%   2.40s    189MiB  2.17%   189MiB
     constant_fix!_...      1    289ms  0.21%   289ms   9.26MiB  0.11%  9.26MiB
     constant_fix!_...      1    172ms  0.13%   172ms   8.38MiB  0.10%  8.38MiB
     constant_Issue...      1   84.0ms  0.06%  84.0ms   8.02MiB  0.09%  8.02MiB
     constant_fix!_...      1   55.1ms  0.04%  55.1ms   2.96MiB  0.03%  2.96MiB
   socp                     1    13.0s  9.44%   13.0s    735MiB  8.44%   735MiB
     socp_dual_mini...      1    4.41s  3.20%   4.41s    301MiB  3.46%   301MiB
     socp_rational_...      1    3.15s  2.28%   3.15s   20.9MiB  0.24%  20.9MiB
     socp_rational_...      1    621ms  0.45%   621ms   7.22MiB  0.08%  7.22MiB
     socp_dual_norm...      1    507ms  0.37%   507ms   47.2MiB  0.54%  47.2MiB
     socp_huber_atom        1    492ms  0.36%   492ms   11.4MiB  0.13%  11.4MiB
     socp_dual_frob...      1    379ms  0.28%   379ms   17.6MiB  0.20%  17.6MiB
     socp_inv_pos_atom      1    352ms  0.26%   352ms   11.0MiB  0.13%  11.0MiB
     socp_quad_form...      1    307ms  0.22%   307ms   20.9MiB  0.24%  20.9MiB
     socp_fix_multi...      1    303ms  0.22%   303ms   29.1MiB  0.33%  29.1MiB
     socp_square_atom       1    235ms  0.17%   235ms   12.8MiB  0.15%  12.8MiB
     socp_sum_squar...      1    203ms  0.15%   203ms   9.80MiB  0.11%  9.80MiB
     socp_rational_...      1    196ms  0.14%   196ms   8.91MiB  0.10%  8.91MiB
     socp_quad_over...      1    175ms  0.13%   175ms   7.38MiB  0.08%  7.38MiB
     socp_fix_and_f...      1    108ms  0.08%   108ms   3.25MiB  0.04%  3.25MiB
     socp_geo_mean_...      1    101ms  0.07%   101ms   4.39MiB  0.05%  4.39MiB
     socp_norm_cons...      1    468μs  0.00%   468μs   62.7KiB  0.00%  62.7KiB
     socp_sqrt_atom         1   87.5μs  0.00%  87.5μs   22.2KiB  0.00%  22.2KiB
   sdp                      1    10.0s  7.23%   10.0s    538MiB  6.18%   538MiB
     sdp_Partial_trace      1    1.27s  0.92%   1.27s    104MiB  1.20%   104MiB
     sdp_matrix_fra...      1    1.11s  0.80%   1.11s   88.3MiB  1.01%  88.3MiB
     sdp_sum_larges...      1    1.08s  0.78%   1.08s   10.1MiB  0.12%  10.1MiB
     sdp_sdp_variables      1    1.08s  0.78%   1.08s   24.0MiB  0.28%  24.0MiB
     sdp_Complex_Va...      1    656ms  0.48%   656ms   8.19MiB  0.09%  8.19MiB
     sdp_dual_lambd...      1    503ms  0.36%   503ms   20.5MiB  0.24%  20.5MiB
     sdp_operator_n...      1    408ms  0.30%   408ms   11.7MiB  0.13%  11.7MiB
     sdp_Real_Varia...      1    331ms  0.24%   331ms   4.78MiB  0.05%  4.78MiB
     sdp_nuclear_no...      1    329ms  0.24%   329ms   16.2MiB  0.19%  16.2MiB
     sdp_matrix_fra...      1    299ms  0.22%   299ms   11.8MiB  0.14%  11.8MiB
     sdp_Issue_198          1    274ms  0.20%   274ms   5.27MiB  0.06%  5.27MiB
     sdp_sigma_max_...      1    241ms  0.17%   241ms   12.2MiB  0.14%  12.2MiB
     sdp_lambda_min...      1    226ms  0.16%   226ms   3.32MiB  0.04%  3.32MiB
     sdp_socp_sumsq...      1    200ms  0.15%   200ms   9.30MiB  0.11%  9.30MiB
     sdp_sdp_constr...      1    175ms  0.13%   175ms   7.90MiB  0.09%  7.90MiB
     sdp_kron_atom          1    118ms  0.09%   118ms   6.45MiB  0.07%  6.45MiB
     sdp_socp_abs_atom      1   74.1ms  0.05%  74.1ms   4.42MiB  0.05%  4.42MiB
     sdp_socp_norm2...      1   71.3ms  0.05%  71.3ms   3.84MiB  0.04%  3.84MiB
   affine                   1    7.42s  5.38%   7.42s    582MiB  6.68%   582MiB
     affine_dot_mul...      1    737ms  0.53%   737ms   29.6MiB  0.34%  29.6MiB
     affine_Partial...      1    588ms  0.43%   588ms    112MiB  1.29%   112MiB
     affine_multipl...      1    578ms  0.42%   578ms   31.5MiB  0.36%  31.5MiB
     affine_transpo...      1    550ms  0.40%   550ms   19.6MiB  0.23%  19.6MiB
     affine_index_atom      1    465ms  0.34%   465ms   21.0MiB  0.24%  21.0MiB
     affine_reshape...      1    440ms  0.32%   440ms   14.7MiB  0.17%  14.7MiB
     affine_sum_atom        1    425ms  0.31%   425ms   18.5MiB  0.21%  18.5MiB
     affine_diag_atom       1    329ms  0.24%   329ms   12.8MiB  0.15%  12.8MiB
     affine_hcat_atom       1    213ms  0.15%   213ms   6.19MiB  0.07%  6.19MiB
     affine_vcat_atom       1    201ms  0.15%   201ms   9.26MiB  0.11%  9.26MiB
     affine_Diagona...      1    189ms  0.14%   189ms   17.0MiB  0.20%  17.0MiB
     affine_add_atom        1    153ms  0.11%   153ms   9.43MiB  0.11%  9.43MiB
     affine_dualvalue       1    134ms  0.10%   134ms   11.7MiB  0.13%  11.7MiB
     affine_conv_atom       1    134ms  0.10%   134ms   8.07MiB  0.09%  8.07MiB
     affine_satisfy...      1   88.1ms  0.06%  88.1ms   4.56MiB  0.05%  4.56MiB
     affine_dot_atom        1   73.7ms  0.05%  73.7ms   5.67MiB  0.07%  5.67MiB
     affine_dot_ato...      1   69.0ms  0.05%  69.0ms   3.38MiB  0.04%  3.38MiB
     affine_permute...      1   64.0ms  0.05%  64.0ms   0.99MiB  0.01%  0.99MiB
     affine_negate_...      1   51.9ms  0.04%  51.9ms   2.35MiB  0.03%  2.35MiB
     affine_trace_atom      1   47.7ms  0.03%  47.7ms   2.52MiB  0.03%  2.52MiB
     affine_kron_atom       1    174μs  0.00%   174μs   29.1KiB  0.00%  29.1KiB
   lp                       1    4.36s  3.17%   4.36s    310MiB  3.56%   310MiB
     lp_minimum_atom        1    526ms  0.38%   526ms   17.3MiB  0.20%  17.3MiB
     lp_min_atom            1    433ms  0.31%   433ms   15.4MiB  0.18%  15.4MiB
     lp_maximum_atom        1    371ms  0.27%   371ms   11.1MiB  0.13%  11.1MiB
     lp_dotsort_atom        1    367ms  0.27%   367ms   17.9MiB  0.21%  17.9MiB
     lp_sumlargest_...      1    364ms  0.26%   364ms   29.7MiB  0.34%  29.7MiB
     lp_max_atom            1    343ms  0.25%   343ms   15.4MiB  0.18%  15.4MiB
     lp_sumsmallest...      1    302ms  0.22%   302ms   17.5MiB  0.20%  17.5MiB
     lp_dual_abs_atom       1    275ms  0.20%   275ms   14.7MiB  0.17%  14.7MiB
     lp_neg_atom            1    106ms  0.08%   106ms   3.95MiB  0.05%  3.95MiB
     lp_pos_atom            1   79.9ms  0.06%  79.9ms   5.83MiB  0.07%  5.83MiB
     lp_dual_norm_1...      1   69.3ms  0.05%  69.3ms   3.31MiB  0.04%  3.31MiB
     lp_dual_norm_i...      1   68.7ms  0.05%  68.7ms   3.34MiB  0.04%  3.34MiB
     lp_hinge_loss_...      1   80.2μs  0.00%  80.2μs   21.4KiB  0.00%  21.4KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## Version information
`versioninfo()`:
```julia
Julia Version 1.5.2
Commit 539f3ce943 (2020-09-23 23:17 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) Platinum 8171M CPU @ 2.60GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-9.0.1 (ORCJIT, skylake-avx512)
```

Manifest:
```julia
Status `~/work/ConvexTests.jl/ConvexTests.jl/CSDP/Manifest.toml`
  [1520ce14] AbstractTrees v0.3.3
  [6e4b80f9] BenchmarkTools v0.5.0
  [b99e7846] BinaryProvider v0.5.10
  [6e34b625] Bzip2_jll v1.0.6+4
  [0a46da34] CSDP v0.6.1
  [9ce75daa] CSDP_jll v6.2.0+9
  [49dc2e85] Calculus v0.5.1
  [523fee87] CodecBzip2 v0.7.2
  [944b1d66] CodecZlib v0.7.0
  [bbf7d656] CommonSubexpressions v0.3.0
  [34da2185] Compat v2.2.1
  [e66e0078] CompilerSupportLibraries_jll v0.3.3+0
  [f65535da] Convex v0.13.7
  [cb7cb77b] ConvexTests v0.1.0 `~/work/ConvexTests.jl/ConvexTests.jl`
  [9a962f9c] DataAPI v1.3.0
  [864edb3b] DataStructures v0.17.20
  [e2d170a0] DataValueInterfaces v1.0.0
  [163ba53b] DiffResults v1.0.2
  [b552c78f] DiffRules v1.0.1
  [191a621a] Dualization v0.3.2
  [7c1d4256] DynamicPolynomials v0.3.13
  [f6369f11] ForwardDiff v0.10.12
  [92fee26a] GZip v0.5.1
  [c27321d9] Glob v1.3.0
  [cd3eb016] HTTP v0.8.19
  [83e8ac13] IniFile v0.5.0
  [82899510] IteratorInterfaceExtensions v1.0.0
  [682c06a0] JSON v0.21.1
  [7d188eb4] JSONSchema v0.3.2
  [4076af6c] JuMP v0.21.4
  [1914dd2f] MacroTools v0.5.5
  [b8f27783] MathOptInterface v0.9.17
  [fdba3010] MathProgBase v0.7.8
  [739be429] MbedTLS v1.0.2
  [c8ffd9c3] MbedTLS_jll v2.16.8+0
  [be282fd4] MultivariateBases v0.1.2
  [f4abf1af] MultivariateMoments v0.3.0
  [102ac46a] MultivariatePolynomials v0.3.10
  [d8a4904e] MutableArithmetics v0.2.10
  [77ba4419] NaNMath v0.3.4
  [656ef2d0] OpenBLAS32_jll v0.3.9+4
  [efe28fd5] OpenSpecFun_jll v0.5.3+3
  [bac558e1] OrderedCollections v1.3.1
  [69de0a69] Parsers v1.0.10
  [ddf597a6] PolyJuMP v0.4.1
  [189a3867] Reexport v0.2.0
  [af85af4c] RowEchelon v0.1.1
  [8e049039] SemialgebraicSets v0.2.2
  [169818f4] SemidefiniteModels v0.1.1
  [276daf66] SpecialFunctions v0.10.3
  [90137ffa] StaticArrays v0.12.4
  [4b9e565b] SumOfSquares v0.4.2
  [f9bf3ced] TableTestSets v0.1.0 `https://github.com/ericphanson/TableTestSets.jl#master`
  [3783bdb8] TableTraits v1.0.0
  [bd369af6] Tables v1.1.0
  [a759f4b9] TimerOutputs v0.5.6
  [3bb67fe8] TranscodingStreams v0.9.5
  [a5390f91] ZipFile v0.9.2
  [83775a58] Zlib_jll v1.2.11+16
  [2a0f44e3] Base64
  [ade2ca70] Dates
  [8bb1440f] DelimitedFiles
  [8ba89e20] Distributed
  [9fa8497b] Future
  [b77e0a4c] InteractiveUtils
  [76f85450] LibGit2
  [8f399da3] Libdl
  [37e2e46d] LinearAlgebra
  [56ddb016] Logging
  [d6f4376e] Markdown
  [a63ad114] Mmap
  [44cfe95a] Pkg
  [de0858da] Printf
  [3fa0cd96] REPL
  [9a3f8284] Random
  [ea8e919c] SHA
  [9e88b42a] Serialization
  [1a1011a3] SharedArrays
  [6462fe0b] Sockets
  [2f01184e] SparseArrays
  [10745b16] Statistics
  [8dfed614] Test
  [cf7118a7] UUIDs
  [4ec0a83e] Unicode
```
