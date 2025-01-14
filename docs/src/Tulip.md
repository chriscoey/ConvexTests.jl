Table of contents:

```@contents
Pages = ["Tulip.md"]
Depth = 4
```


Compilation warmup gives an estimate of 51 seconds of compilation time.

## Tulip Float64
These tests were run on October 6, 2020 at 10:39 (UTC).

Tests run with default parameters in type `Float64`.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"socp", r"sdp"]
```

### Tests

Tests took 1 minute, 40 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">Tulip tests</td>
<td style="text-align:center;color:green;">730</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">730</td>
</tr></table>
```

### Errors

```julia
```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:             100s / 99.5%           9.31GiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1    59.0s  59.6%   59.0s   5.10GiB  55.0%  5.10GiB
   lp                       1    58.9s  59.4%   58.9s   5.09GiB  54.9%  5.09GiB
     dsos_cheby_biv...      1    10.1s  10.2%   10.1s   0.94GiB  10.1%  0.94GiB
     dsos_univariat...      1    9.16s  9.24%   9.16s    712MiB  7.49%   712MiB
     dsos_options_p...      1    8.60s  8.68%   8.60s    700MiB  7.37%   700MiB
     dsos_concave_t...      1    6.82s  6.88%   6.82s    565MiB  5.95%   565MiB
     dsos_term_fixed        1    5.12s  5.16%   5.12s    371MiB  3.91%   371MiB
     dsos_horn              1    4.45s  4.49%   4.45s    334MiB  3.52%   334MiB
     dsos_quartic_c...      1    3.13s  3.15%   3.13s    255MiB  2.68%   255MiB
     dsos_scaled_bi...      1    2.93s  2.96%   2.93s    229MiB  2.41%   229MiB
     dsos_term              1    2.69s  2.72%   2.69s    189MiB  1.99%   189MiB
     dsos_quartic_c...      1    627ms  0.63%   627ms   25.9MiB  0.27%  25.9MiB
     dsos_bivariate...      1    558ms  0.56%   558ms   26.3MiB  0.28%  26.3MiB
     dsos_cheby_uni...      1   98.0ms  0.10%  98.0ms   12.5MiB  0.13%  12.5MiB
     dsos_scaled_un...      1   12.4ms  0.01%  12.4ms    518KiB  0.01%   518KiB
     dsos_univariat...      1   6.93ms  0.01%  6.93ms    517KiB  0.01%   517KiB
 Convex                     1    40.1s  40.4%   40.1s   4.17GiB  45.0%  4.17GiB
   affine                   1    25.0s  25.2%   25.0s   2.65GiB  28.6%  2.65GiB
     affine_Partial...      1    2.85s  2.88%   2.85s    334MiB  3.51%   334MiB
     affine_permute...      1    2.52s  2.54%   2.52s    384MiB  4.04%   384MiB
     affine_hcat_atom       1    2.05s  2.07%   2.05s    176MiB  1.85%   176MiB
     affine_dot_mul...      1    2.03s  2.04%   2.03s    130MiB  1.36%   130MiB
     affine_multipl...      1    2.01s  2.03%   2.01s    213MiB  2.25%   213MiB
     affine_transpo...      1    1.26s  1.27%   1.26s   81.2MiB  0.85%  81.2MiB
     affine_vcat_atom       1    1.19s  1.20%   1.19s   95.7MiB  1.01%  95.7MiB
     affine_Diagona...      1    1.09s  1.10%   1.09s    110MiB  1.16%   110MiB
     affine_satisfy...      1    987ms  1.00%   987ms   55.2MiB  0.58%  55.2MiB
     affine_add_atom        1    854ms  0.86%   854ms   55.5MiB  0.58%  55.5MiB
     affine_conv_atom       1    783ms  0.79%   783ms   49.0MiB  0.52%  49.0MiB
     affine_dualvalue       1    609ms  0.61%   609ms   71.1MiB  0.75%  71.1MiB
     affine_dot_atom        1    593ms  0.60%   593ms   17.8MiB  0.19%  17.8MiB
     affine_index_atom      1    564ms  0.57%   564ms   41.6MiB  0.44%  41.6MiB
     affine_reshape...      1    536ms  0.54%   536ms   26.1MiB  0.27%  26.1MiB
     affine_sum_atom        1    342ms  0.34%   342ms   27.8MiB  0.29%  27.8MiB
     affine_kron_atom       1    193ms  0.20%   193ms   10.8MiB  0.11%  10.8MiB
     affine_diag_atom       1    123ms  0.12%   123ms   12.9MiB  0.14%  12.9MiB
     affine_dot_ato...      1    106ms  0.11%   106ms   4.90MiB  0.05%  4.90MiB
     affine_negate_...      1   78.6ms  0.08%  78.6ms   3.51MiB  0.04%  3.51MiB
     affine_trace_atom      1   40.8ms  0.04%  40.8ms   2.38MiB  0.03%  2.38MiB
   constant                 1    8.53s  8.61%   8.53s    873MiB  9.19%   873MiB
     constant_fix!_...      1    3.09s  3.11%   3.09s    251MiB  2.64%   251MiB
     constant_Issue...      1    2.60s  2.62%   2.60s    283MiB  2.98%   283MiB
     constant_Issue...      1    675ms  0.68%   675ms   49.6MiB  0.52%  49.6MiB
     constant_fix!_...      1    516ms  0.52%   516ms   41.9MiB  0.44%  41.9MiB
     constant_Test_...      1    342ms  0.34%   342ms   18.1MiB  0.19%  18.1MiB
     constant_fix!_...      1    250ms  0.25%   250ms   19.6MiB  0.21%  19.6MiB
   lp                       1    6.30s  6.35%   6.30s    654MiB  6.88%   654MiB
     lp_dotsort_atom        1    1.12s  1.13%   1.12s   92.4MiB  0.97%  92.4MiB
     lp_dual_abs_atom       1    603ms  0.61%   603ms   61.5MiB  0.65%  61.5MiB
     lp_min_atom            1    515ms  0.52%   515ms   43.9MiB  0.46%  43.9MiB
     lp_sumlargest_...      1    488ms  0.49%   488ms   44.5MiB  0.47%  44.5MiB
     lp_sumsmallest...      1    454ms  0.46%   454ms   42.4MiB  0.45%  42.4MiB
     lp_max_atom            1    387ms  0.39%   387ms   37.5MiB  0.39%  37.5MiB
     lp_minimum_atom        1    343ms  0.35%   343ms   26.1MiB  0.27%  26.1MiB
     lp_dual_norm_i...      1    337ms  0.34%   337ms   21.1MiB  0.22%  21.1MiB
     lp_neg_atom            1    194ms  0.20%   194ms   10.8MiB  0.11%  10.8MiB
     lp_maximum_atom        1    178ms  0.18%   178ms   12.1MiB  0.13%  12.1MiB
     lp_pos_atom            1   72.2ms  0.07%  72.2ms   5.80MiB  0.06%  5.80MiB
     lp_dual_norm_1...      1   66.5ms  0.07%  66.5ms   3.34MiB  0.04%  3.34MiB
     lp_hinge_loss_...      1    153μs  0.00%   153μs   47.7KiB  0.00%  47.7KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## Tulip BigFloat
These tests were run on October 6, 2020 at 10:40 (UTC).

Tests run with default parameters in type `BigFloat`.

Excluded problems and classes of problems:
```julia
Regex[r"mip", r"exp", r"socp", r"sdp"]
```

### Tests

Tests took 37 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">Tulip tests</td>
<td style="text-align:center;color:green;">229</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">229</td>
</tr></table>
```

### Errors

```julia
```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:            36.8s / 100%            3.73GiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 Convex                     1    36.8s   100%   36.8s   3.73GiB  100%   3.73GiB
   constant                 1    22.3s  60.6%   22.3s   2.02GiB  54.0%  2.02GiB
     constant_Issue...      1    20.8s  56.6%   20.8s   1.91GiB  51.1%  1.91GiB
     constant_fix!_...      1    390ms  1.06%   390ms   19.5MiB  0.51%  19.5MiB
     constant_fix!_...      1    199ms  0.54%   199ms   8.34MiB  0.22%  8.34MiB
     constant_Issue...      1    123ms  0.33%   123ms   8.01MiB  0.21%  8.01MiB
     constant_Test_...      1    123ms  0.33%   123ms   3.76MiB  0.10%  3.76MiB
     constant_fix!_...      1   59.5ms  0.16%  59.5ms   2.84MiB  0.07%  2.84MiB
   affine                   1    10.4s  28.2%   10.4s    847MiB  22.2%   847MiB
     affine_multipl...      1    3.98s  10.8%   3.98s    296MiB  7.74%   296MiB
     affine_transpo...      1    631ms  1.72%   631ms   21.8MiB  0.57%  21.8MiB
     affine_dot_mul...      1    588ms  1.60%   588ms   27.9MiB  0.73%  27.9MiB
     affine_dualvalue       1    585ms  1.59%   585ms   61.9MiB  1.62%  61.9MiB
     affine_Partial...      1    436ms  1.18%   436ms   52.0MiB  1.36%  52.0MiB
     affine_reshape...      1    343ms  0.93%   343ms   14.4MiB  0.38%  14.4MiB
     affine_Diagona...      1    290ms  0.79%   290ms   17.5MiB  0.46%  17.5MiB
     affine_index_atom      1    286ms  0.78%   286ms   20.9MiB  0.55%  20.9MiB
     affine_sum_atom        1    264ms  0.72%   264ms   18.1MiB  0.47%  18.1MiB
     affine_satisfy...      1    208ms  0.57%   208ms   8.19MiB  0.21%  8.19MiB
     affine_add_atom        1    191ms  0.52%   191ms   9.92MiB  0.26%  9.92MiB
     affine_conv_atom       1    148ms  0.40%   148ms   7.79MiB  0.20%  7.79MiB
     affine_diag_atom       1    146ms  0.40%   146ms   12.8MiB  0.34%  12.8MiB
     affine_hcat_atom       1    131ms  0.36%   131ms   7.47MiB  0.20%  7.47MiB
     affine_vcat_atom       1    118ms  0.32%   118ms   10.0MiB  0.26%  10.0MiB
     affine_dot_ato...      1    102ms  0.28%   102ms   3.10MiB  0.08%  3.10MiB
     affine_dot_atom        1   77.5ms  0.21%  77.5ms   5.38MiB  0.14%  5.38MiB
     affine_negate_...      1   73.3ms  0.20%  73.3ms   2.53MiB  0.07%  2.53MiB
     affine_trace_atom      1   52.6ms  0.14%  52.6ms   2.40MiB  0.06%  2.40MiB
     affine_permute...      1   37.6ms  0.10%  37.6ms   3.80MiB  0.10%  3.80MiB
     affine_kron_atom       1   26.8ms  0.07%  26.8ms   2.99MiB  0.08%  2.99MiB
   lp                       1    4.11s  11.2%   4.11s    909MiB  23.8%   909MiB
     lp_dotsort_atom        1    533ms  1.45%   533ms   69.3MiB  1.81%  69.3MiB
     lp_max_atom            1    484ms  1.31%   484ms    261MiB  6.82%   261MiB
     lp_min_atom            1    438ms  1.19%   438ms    225MiB  5.88%   225MiB
     lp_dual_norm_i...      1    292ms  0.79%   292ms   16.5MiB  0.43%  16.5MiB
     lp_dual_abs_atom       1    253ms  0.69%   253ms   23.2MiB  0.61%  23.2MiB
     lp_sumlargest_...      1    248ms  0.68%   248ms   44.4MiB  1.16%  44.4MiB
     lp_minimum_atom        1    240ms  0.65%   240ms   17.9MiB  0.47%  17.9MiB
     lp_sumsmallest...      1    226ms  0.61%   226ms   58.9MiB  1.54%  58.9MiB
     lp_maximum_atom        1    101ms  0.28%   101ms   17.8MiB  0.46%  17.8MiB
     lp_pos_atom            1   88.8ms  0.24%  88.8ms   7.03MiB  0.18%  7.03MiB
     lp_dual_norm_1...      1   84.0ms  0.23%  84.0ms   7.70MiB  0.20%  7.70MiB
     lp_neg_atom            1   74.5ms  0.20%  74.5ms   6.50MiB  0.17%  6.50MiB
     lp_hinge_loss_...      1    156μs  0.00%   156μs   47.7KiB  0.00%  47.7KiB
 ──────────────────────────────────────────────────────────────────────────────
```

## Version information
`versioninfo()`:
```julia
Julia Version 1.5.2
Commit 539f3ce943 (2020-09-23 23:17 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) CPU E5-2673 v4 @ 2.30GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-9.0.1 (ORCJIT, broadwell)
```

Manifest:
```julia
Status `~/work/ConvexTests.jl/ConvexTests.jl/Tulip/Manifest.toml`
  [14f7f29c] AMD v0.4.0
  [1520ce14] AbstractTrees v0.3.3
  [6e4b80f9] BenchmarkTools v0.5.0
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
  [9aa1b823] FastClosures v0.3.2
  [f6369f11] ForwardDiff v0.10.12
  [cd3eb016] HTTP v0.8.19
  [83e8ac13] IniFile v0.5.0
  [82899510] IteratorInterfaceExtensions v1.0.0
  [682c06a0] JSON v0.21.1
  [7d188eb4] JSONSchema v0.3.2
  [4076af6c] JuMP v0.21.4
  [ba0b0d4f] Krylov v0.5.3
  [40e66cde] LDLFactorizations v0.6.0
  [5c8ed15e] LinearOperators v1.1.0
  [1914dd2f] MacroTools v0.5.5
  [b8f27783] MathOptInterface v0.9.17
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
  [10f199a5] QPSReader v0.2.0
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
  [6dd1b50a] Tulip v0.6.2
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
  [4607b0f0] SuiteSparse
  [8dfed614] Test
  [cf7118a7] UUIDs
  [4ec0a83e] Unicode
```
