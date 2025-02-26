Table of contents:

```@contents
Pages = ["ECOS.md"]
Depth = 4
```


Compilation warmup gives an estimate of 47 seconds of compilation time.

## ECOS 
These tests were run on October 6, 2020 at 10:42 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip", r"sdp"]
```

### Tests

Tests took 3 minutes, 17 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">ECOS tests</td>
<td style="text-align:center;color:green;">1301</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1304</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">355</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">355</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">946</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">949</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">445</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">448</td>
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
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
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
<td style="text-align:center;color:green;">13</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">13</td>
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
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">501</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">501</td>
</tr></table>
```

### Errors

```julia
Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:             198s / 99.0%           14.7GiB / 99.3%    

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1     127s  65.2%    127s   8.58GiB  58.9%  8.58GiB
   socp                     1    91.3s  46.7%   91.3s   6.40GiB  43.9%  6.40GiB
     sdsos_term_fixed       1    22.6s  11.6%   22.6s   1.46GiB  10.0%  1.46GiB
     sdsos_horn             1    12.9s  6.58%   12.9s    915MiB  6.13%   915MiB
     sdsos_concave_...      1    10.0s  5.11%   10.0s    662MiB  4.44%   662MiB
     sdsos_univaria...      1    8.97s  4.59%   8.97s    667MiB  4.47%   667MiB
     sdsos_cheby_un...      1    7.26s  3.71%   7.26s    482MiB  3.23%   482MiB
     sdsos_options_...      1    6.59s  3.37%   6.59s    334MiB  2.24%   334MiB
     sdsos_univaria...      1    5.70s  2.91%   5.70s    377MiB  2.52%   377MiB
     sdsos_scaled_u...      1    3.97s  2.03%   3.97s    263MiB  1.76%   263MiB
     sdsos_term             1    3.89s  1.99%   3.89s    270MiB  1.81%   270MiB
     sdsos_quartic_...      1    3.82s  1.95%   3.82s    245MiB  1.64%   245MiB
     sdsos_quartic_...      1    692ms  0.35%   692ms   23.0MiB  0.15%  23.0MiB
     sdsos_scaled_b...      1   63.8ms  0.03%  63.8ms   5.66MiB  0.04%  5.66MiB
     sdsos_bivariat...      1   28.8ms  0.01%  28.8ms    641KiB  0.00%   641KiB
   lp                       1    35.9s  18.4%   35.9s   2.17GiB  14.9%  2.17GiB
     dsos_options_p...      1    5.58s  2.85%   5.58s    338MiB  2.26%   338MiB
     dsos_concave_t...      1    4.46s  2.28%   4.46s    271MiB  1.82%   271MiB
     dsos_cheby_biv...      1    4.05s  2.07%   4.05s    226MiB  1.52%   226MiB
     dsos_univariat...      1    3.76s  1.92%   3.76s    225MiB  1.51%   225MiB
     dsos_term_fixed        1    3.64s  1.86%   3.64s    199MiB  1.33%   199MiB
     dsos_scaled_bi...      1    3.31s  1.69%   3.31s    195MiB  1.30%   195MiB
     dsos_quartic_c...      1    2.81s  1.44%   2.81s    171MiB  1.14%   171MiB
     dsos_horn              1    2.72s  1.39%   2.72s    165MiB  1.11%   165MiB
     dsos_term              1    2.72s  1.39%   2.72s    139MiB  0.93%   139MiB
     dsos_bivariate...      1    775ms  0.40%   775ms   24.7MiB  0.17%  24.7MiB
     dsos_quartic_c...      1    144ms  0.07%   144ms   15.9MiB  0.11%  15.9MiB
     dsos_scaled_un...      1   26.9ms  0.01%  26.9ms    629KiB  0.00%   629KiB
     dsos_cheby_uni...      1   22.5ms  0.01%  22.5ms    640KiB  0.00%   640KiB
     dsos_univariat...      1   15.0ms  0.01%  15.0ms    628KiB  0.00%   628KiB
 Convex                     1    68.2s  34.8%   68.2s   5.99GiB  41.1%  5.99GiB
   affine                   1    29.7s  15.2%   29.7s   2.68GiB  18.4%  2.68GiB
     affine_Partial...      1    3.29s  1.68%   3.29s    323MiB  2.16%   323MiB
     affine_permute...      1    2.96s  1.51%   2.96s    384MiB  2.57%   384MiB
     affine_hcat_atom       1    2.75s  1.41%   2.75s    176MiB  1.18%   176MiB
     affine_dot_mul...      1    2.55s  1.30%   2.55s    149MiB  1.00%   149MiB
     affine_multipl...      1    2.27s  1.16%   2.27s    213MiB  1.43%   213MiB
     affine_transpo...      1    1.52s  0.77%   1.52s   82.9MiB  0.56%  82.9MiB
     affine_vcat_atom       1    1.37s  0.70%   1.37s   95.7MiB  0.64%  95.7MiB
     affine_Diagona...      1    1.29s  0.66%   1.29s    111MiB  0.74%   111MiB
     affine_satisfy...      1    1.14s  0.58%   1.14s   55.5MiB  0.37%  55.5MiB
     affine_add_atom        1    1.12s  0.57%   1.12s   65.6MiB  0.44%  65.6MiB
     affine_conv_atom       1    931ms  0.48%   931ms   49.3MiB  0.33%  49.3MiB
     affine_dualvalue       1    772ms  0.39%   772ms   71.5MiB  0.48%  71.5MiB
     affine_dot_atom        1    752ms  0.38%   752ms   23.8MiB  0.16%  23.8MiB
     affine_index_atom      1    688ms  0.35%   688ms   41.8MiB  0.28%  41.8MiB
     affine_reshape...      1    636ms  0.33%   636ms   26.3MiB  0.18%  26.3MiB
     affine_sum_atom        1    465ms  0.24%   465ms   28.0MiB  0.19%  28.0MiB
     affine_kron_atom       1    222ms  0.11%   222ms   10.8MiB  0.07%  10.8MiB
     affine_diag_atom       1    150ms  0.08%   150ms   13.1MiB  0.09%  13.1MiB
     affine_dot_ato...      1    126ms  0.06%   126ms   4.99MiB  0.03%  4.99MiB
     affine_negate_...      1   96.0ms  0.05%  96.0ms   3.61MiB  0.02%  3.61MiB
     affine_trace_atom      1   52.1ms  0.03%  52.1ms   2.47MiB  0.02%  2.47MiB
   socp                     1    18.4s  9.40%   18.4s   1.63GiB  11.2%  1.63GiB
     socp_quad_form...      1    2.61s  1.33%   2.61s   34.8MiB  0.23%  34.8MiB
     socp_dual_mini...      1    2.36s  1.21%   2.36s    156MiB  1.05%   156MiB
     socp_rational_...      1    1.49s  0.76%   1.49s    131MiB  0.88%   131MiB
     socp_sum_squar...      1    1.15s  0.59%   1.15s   83.8MiB  0.56%  83.8MiB
     socp_inv_pos_atom      1    957ms  0.49%   957ms   61.6MiB  0.41%  61.6MiB
     socp_quad_over...      1    865ms  0.44%   865ms   27.5MiB  0.18%  27.5MiB
     socp_dual_norm...      1    795ms  0.41%   795ms   62.9MiB  0.42%  62.9MiB
     socp_rational_...      1    572ms  0.29%   572ms   36.4MiB  0.24%  36.4MiB
     socp_norm_cons...      1    513ms  0.26%   513ms   25.8MiB  0.17%  25.8MiB
     socp_fix_multi...      1    497ms  0.25%   497ms   30.5MiB  0.20%  30.5MiB
     socp_dual_frob...      1    422ms  0.22%   422ms   23.4MiB  0.16%  23.4MiB
     socp_huber_atom        1    418ms  0.21%   418ms   31.0MiB  0.21%  31.0MiB
     socp_square_atom       1    389ms  0.20%   389ms   12.7MiB  0.08%  12.7MiB
     socp_geo_mean_...      1    353ms  0.18%   353ms   24.6MiB  0.16%  24.6MiB
     socp_rational_...      1    163ms  0.08%   163ms   8.50MiB  0.06%  8.50MiB
     socp_fix_and_f...      1   82.8ms  0.04%  82.8ms   5.52MiB  0.04%  5.52MiB
     socp_sqrt_atom         1   78.2ms  0.04%  78.2ms   1.49MiB  0.01%  1.49MiB
   constant                 1    10.4s  5.33%   10.4s    916MiB  6.14%   916MiB
     constant_fix!_...      1    3.70s  1.89%   3.70s    262MiB  1.75%   262MiB
     constant_Issue...      1    3.24s  1.66%   3.24s    308MiB  2.06%   308MiB
     constant_Issue...      1    854ms  0.44%   854ms   49.9MiB  0.33%  49.9MiB
     constant_fix!_...      1    677ms  0.35%   677ms   42.3MiB  0.28%  42.3MiB
     constant_Test_...      1    362ms  0.18%   362ms   18.4MiB  0.12%  18.4MiB
     constant_fix!_...      1    300ms  0.15%   300ms   20.3MiB  0.14%  20.3MiB
   lp                       1    5.63s  2.88%   5.63s    495MiB  3.32%   495MiB
     lp_dotsort_atom        1    857ms  0.44%   857ms   56.5MiB  0.38%  56.5MiB
     lp_sumlargest_...      1    572ms  0.29%   572ms   43.2MiB  0.29%  43.2MiB
     lp_min_atom            1    563ms  0.29%   563ms   38.5MiB  0.26%  38.5MiB
     lp_max_atom            1    423ms  0.22%   423ms   30.9MiB  0.21%  30.9MiB
     lp_minimum_atom        1    354ms  0.18%   354ms   25.6MiB  0.17%  25.6MiB
     lp_dual_abs_atom       1    287ms  0.15%   287ms   17.2MiB  0.12%  17.2MiB
     lp_sumsmallest...      1    277ms  0.14%   277ms   19.8MiB  0.13%  19.8MiB
     lp_maximum_atom        1    238ms  0.12%   238ms   12.0MiB  0.08%  12.0MiB
     lp_neg_atom            1    231ms  0.12%   231ms   10.8MiB  0.07%  10.8MiB
     lp_dual_norm_i...      1    102ms  0.05%   102ms   3.60MiB  0.02%  3.60MiB
     lp_pos_atom            1   84.5ms  0.04%  84.5ms   5.79MiB  0.04%  5.79MiB
     lp_dual_norm_1...      1   70.0ms  0.04%  70.0ms   3.26MiB  0.02%  3.26MiB
     lp_hinge_loss_...      1    239μs  0.00%   239μs   47.7KiB  0.00%  47.7KiB
   exp                      1    3.72s  1.90%   3.72s    284MiB  1.90%   284MiB
     exp_log_atom           1    1.37s  0.70%   1.37s   99.3MiB  0.67%  99.3MiB
     exp_entropy_atom       1    478ms  0.24%   478ms   34.4MiB  0.23%  34.4MiB
     exp_log_sum_ex...      1    327ms  0.17%   327ms   22.3MiB  0.15%  22.3MiB
     exp_exp_atom           1    313ms  0.16%   313ms   17.2MiB  0.12%  17.2MiB
     exp_logistic_l...      1    275ms  0.14%   275ms   12.9MiB  0.09%  12.9MiB
     exp_log_perspe...      1    256ms  0.13%   256ms   14.9MiB  0.10%  14.9MiB
     exp_relative_e...      1   59.0ms  0.03%  59.0ms   4.56MiB  0.03%  4.56MiB
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
Status `~/work/ConvexTests.jl/ConvexTests.jl/ECOS/Manifest.toml`
  [1520ce14] AbstractTrees v0.3.3
  [6e4b80f9] BenchmarkTools v0.5.0
  [b99e7846] BinaryProvider v0.5.10
  [6e34b625] Bzip2_jll v1.0.6+4
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
  [7c1d4256] DynamicPolynomials v0.3.13
  [e2685f51] ECOS v0.12.1
  [c2c64177] ECOS_jll v2.0.5+0
  [f6369f11] ForwardDiff v0.10.12
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
  [efe28fd5] OpenSpecFun_jll v0.5.3+3
  [bac558e1] OrderedCollections v1.3.1
  [69de0a69] Parsers v1.0.10
  [ddf597a6] PolyJuMP v0.4.1
  [189a3867] Reexport v0.2.0
  [af85af4c] RowEchelon v0.1.1
  [8e049039] SemialgebraicSets v0.2.2
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
