Table of contents:

```@contents
Pages = ["SCS.md"]
Depth = 4
```


Compilation warmup gives an estimate of 46 seconds of compilation time.

## SCS 
These tests were run on October 6, 2020 at 10:44 (UTC).

Tests run with `eps=1e-6`.

Excluded problems and classes of problems:
```julia
Regex[r"mip"]
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
<tr><td style="text-align:left;border-right: solid 2px;">SCS tests</td>
<td style="text-align:center;color:green;">2052</td>
<td style="text-align:center;color:red;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2057</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">423</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">424</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">139</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">139</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;exp</td>
<td style="text-align:center;color:green;">27</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">27</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_and_exp</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">65</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">66</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Semidefinite_constraint</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
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
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
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
<td style="text-align:center;color:green;">1629</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1633</td>
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
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
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
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">683</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">684</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_infeasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;simple_matrix</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_concave_then_convex_cubic</td>
<td style="text-align:center;color:green;">13</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">13</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rearrangement</td>
<td style="text-align:center;color:green;">25</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">25</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;maxcut</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
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
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_feasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;chebyshev</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo9</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
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
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_horn</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_rem</td>
<td style="text-align:center;color:green;">48</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">48</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;motzkin</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo10</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_maxdegree</td>
<td style="text-align:center;color:green;">56</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">56</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_options_pricing</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
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
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;choi</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4_rem</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_2_rem</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr></table>
```

### Errors

```julia
Error in testset sdp_sdp_constraints:
Test Failed at /home/runner/.julia/packages/Convex/aYxJA/src/problem_depot/problems/sdp.jl:68
  Expression: ≈(p.optval, 1, atol = atol, rtol = rtol)
   Evaluated: Inf ≈ 1 (atol=0.001, rtol=0.0)

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 16.800893389330025 ≈ 21.51 (atol=0.1, rtol=0.0)

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 27.30979082216331 ≈ 17.17 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 11.416756508838047 ≈ 13.2 (atol=0.1, rtol=0.0)

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/45IuO/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 17.21054415450617 ≈ 13.2 (atol=0.1, rtol=0.0)

```


### Timing information
```julia
 ──────────────────────────────────────────────────────────────────────────────
                                       Time                   Allocations      
                               ──────────────────────   ───────────────────────
       Tot / % measured:             308s / 99.3%           22.5GiB / 100%     

 Section               ncalls     time   %tot     avg     alloc   %tot      avg
 ──────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1     214s  70.2%    214s   14.5GiB  65.1%  14.5GiB
   sdp                      1    90.4s  29.6%   90.4s   6.12GiB  27.4%  6.12GiB
     sosdemo5_infea...      1    8.22s  2.69%   8.22s    648MiB  2.83%   648MiB
     quartic_ideal_rem      1    6.60s  2.16%   6.60s    490MiB  2.14%   490MiB
     rearrangement          1    6.27s  2.05%   6.27s    406MiB  1.78%   406MiB
     sos_horn               1    4.42s  1.45%   4.42s    275MiB  1.20%   275MiB
     simple_matrix          1    4.23s  1.38%   4.23s    311MiB  1.36%   311MiB
     sos_concave_th...      1    3.90s  1.28%   3.90s    240MiB  1.05%   240MiB
     sos_scaled_biv...      1    3.80s  1.24%   3.80s    214MiB  0.94%   214MiB
     quartic_ideal          1    3.79s  1.24%   3.79s    221MiB  0.96%   221MiB
     maxcut                 1    3.73s  1.22%   3.73s    159MiB  0.69%   159MiB
     sos_term_fixed         1    3.66s  1.20%   3.66s    215MiB  0.94%   215MiB
     chebyshev              1    3.44s  1.13%   3.44s    190MiB  0.83%   190MiB
     quartic_ideal_4        1    3.36s  1.10%   3.36s    209MiB  0.91%   209MiB
     sos_cheby_univ...      1    3.29s  1.08%   3.29s    193MiB  0.84%   193MiB
     sos_options_pr...      1    3.05s  1.00%   3.05s    119MiB  0.52%   119MiB
     quartic_ideal_...      1    2.82s  0.92%   2.82s    171MiB  0.75%   171MiB
     sos_quartic_co...      1    2.81s  0.92%   2.81s    173MiB  0.76%   173MiB
     quartic_feasib...      1    2.74s  0.90%   2.74s    118MiB  0.52%   118MiB
     sos_term               1    2.67s  0.87%   2.67s    136MiB  0.60%   136MiB
     BPT12e399_rem          1    2.26s  0.74%   2.26s   74.4MiB  0.33%  74.4MiB
     sos_univariate...      1    1.81s  0.59%   1.81s    102MiB  0.44%   102MiB
     sosdemo10              1    1.27s  0.42%   1.27s    107MiB  0.47%   107MiB
     quadratic_infe...      1    1.06s  0.35%   1.06s   77.2MiB  0.34%  77.2MiB
     sos_univariate...      1    683ms  0.22%   683ms   23.6MiB  0.10%  23.6MiB
     sosdemo9               1    625ms  0.20%   625ms   40.9MiB  0.18%  40.9MiB
     quadratic_feas...      1    479ms  0.16%   479ms   27.3MiB  0.12%  27.3MiB
     choi                   1    423ms  0.14%   423ms   41.6MiB  0.18%  41.6MiB
     BPT12e399_maxd...      1    272ms  0.09%   272ms   8.04MiB  0.04%  8.04MiB
     motzkin                1    150ms  0.05%   150ms   4.72MiB  0.02%  4.72MiB
     sos_quartic_co...      1    150ms  0.05%   150ms   15.8MiB  0.07%  15.8MiB
     sosdemo5_feasible      1    140ms  0.05%   140ms   14.7MiB  0.06%  14.7MiB
     quartic_infeas...      1   77.6ms  0.03%  77.6ms    554KiB  0.00%   554KiB
     quartic_ideal_...      1   73.7ms  0.02%  73.7ms   1.62MiB  0.01%  1.62MiB
     quartic_infeas...      1   57.5ms  0.02%  57.5ms   1.89MiB  0.01%  1.89MiB
     quartic_feasib...      1   49.7ms  0.02%  49.7ms    474KiB  0.00%   474KiB
     quadratic_infe...      1   38.1ms  0.01%  38.1ms    516KiB  0.00%   516KiB
     sos_scaled_uni...      1   37.3ms  0.01%  37.3ms    556KiB  0.00%   556KiB
     sos_bivariate_...      1   36.1ms  0.01%  36.1ms    558KiB  0.00%   558KiB
     quadratic_feas...      1   34.6ms  0.01%  34.6ms    417KiB  0.00%   417KiB
   socp                     1    89.2s  29.2%   89.2s   6.20GiB  27.7%  6.20GiB
     sdsos_term_fixed       1    22.4s  7.34%   22.4s   1.43GiB  6.41%  1.43GiB
     sdsos_horn             1    12.9s  4.22%   12.9s    927MiB  4.05%   927MiB
     sdsos_concave_...      1    10.0s  3.26%   10.0s    671MiB  2.93%   671MiB
     sdsos_univaria...      1    9.11s  2.98%   9.11s    681MiB  2.97%   681MiB
     sdsos_cheby_un...      1    7.13s  2.33%   7.13s    459MiB  2.01%   459MiB
     sdsos_univaria...      1    5.67s  1.85%   5.67s    379MiB  1.66%   379MiB
     sdsos_term             1    4.51s  1.48%   4.51s    270MiB  1.18%   270MiB
     sdsos_options_...      1    4.12s  1.35%   4.12s    138MiB  0.60%   138MiB
     sdsos_scaled_u...      1    4.04s  1.32%   4.04s    268MiB  1.17%   268MiB
     sdsos_quartic_...      1    3.78s  1.24%   3.78s    247MiB  1.08%   247MiB
     sdsos_quartic_...      1    687ms  0.22%   687ms   22.8MiB  0.10%  22.8MiB
     sdsos_scaled_b...      1   62.9ms  0.02%  62.9ms   5.58MiB  0.02%  5.58MiB
     sdsos_bivariat...      1   27.2ms  0.01%  27.2ms    561KiB  0.00%   561KiB
   lp                       1    34.7s  11.3%   34.7s   2.21GiB  9.88%  2.21GiB
     dsos_options_p...      1    5.44s  1.78%   5.44s    341MiB  1.49%   341MiB
     dsos_concave_t...      1    4.34s  1.42%   4.34s    280MiB  1.22%   280MiB
     dsos_cheby_biv...      1    3.85s  1.26%   3.85s    231MiB  1.01%   231MiB
     dsos_univariat...      1    3.56s  1.16%   3.56s    227MiB  0.99%   227MiB
     dsos_term_fixed        1    3.51s  1.15%   3.51s    204MiB  0.89%   204MiB
     dsos_scaled_bi...      1    3.16s  1.03%   3.16s    199MiB  0.87%   199MiB
     dsos_quartic_c...      1    2.72s  0.89%   2.72s    173MiB  0.76%   173MiB
     dsos_horn              1    2.66s  0.87%   2.66s    166MiB  0.73%   166MiB
     dsos_term              1    2.58s  0.84%   2.58s    139MiB  0.61%   139MiB
     dsos_bivariate...      1    726ms  0.24%   726ms   27.3MiB  0.12%  27.3MiB
     dsos_quartic_c...      1    136ms  0.04%   136ms   15.8MiB  0.07%  15.8MiB
     dsos_scaled_un...      1   24.8ms  0.01%  24.8ms    546KiB  0.00%   546KiB
     dsos_cheby_uni...      1   22.4ms  0.01%  22.4ms    557KiB  0.00%   557KiB
     dsos_univariat...      1   14.8ms  0.00%  14.8ms    545KiB  0.00%   545KiB
 Convex                     1    91.2s  29.8%   91.2s   7.80GiB  34.9%  7.80GiB
   affine                   1    29.0s  9.48%   29.0s   2.70GiB  12.1%  2.70GiB
     affine_Partial...      1    3.27s  1.07%   3.27s    327MiB  1.43%   327MiB
     affine_permute...      1    2.89s  0.95%   2.89s    384MiB  1.68%   384MiB
     affine_dot_mul...      1    2.55s  0.83%   2.55s    153MiB  0.67%   153MiB
     affine_hcat_atom       1    2.31s  0.76%   2.31s    176MiB  0.77%   176MiB
     affine_multipl...      1    2.28s  0.75%   2.28s    213MiB  0.93%   213MiB
     affine_transpo...      1    1.48s  0.48%   1.48s   82.7MiB  0.36%  82.7MiB
     affine_vcat_atom       1    1.37s  0.45%   1.37s   95.6MiB  0.42%  95.6MiB
     affine_Diagona...      1    1.29s  0.42%   1.29s    111MiB  0.48%   111MiB
     affine_add_atom        1    1.14s  0.37%   1.14s   65.3MiB  0.29%  65.3MiB
     affine_satisfy...      1    1.11s  0.36%   1.11s   61.6MiB  0.27%  61.6MiB
     affine_conv_atom       1    917ms  0.30%   917ms   49.4MiB  0.22%  49.4MiB
     affine_dualvalue       1    758ms  0.25%   758ms   71.2MiB  0.31%  71.2MiB
     affine_dot_atom        1    749ms  0.24%   749ms   23.7MiB  0.10%  23.7MiB
     affine_index_atom      1    676ms  0.22%   676ms   41.5MiB  0.18%  41.5MiB
     affine_reshape...      1    623ms  0.20%   623ms   26.1MiB  0.11%  26.1MiB
     affine_sum_atom        1    457ms  0.15%   457ms   27.8MiB  0.12%  27.8MiB
     affine_kron_atom       1    218ms  0.07%   218ms   10.8MiB  0.05%  10.8MiB
     affine_diag_atom       1    144ms  0.05%   144ms   12.9MiB  0.06%  12.9MiB
     affine_dot_ato...      1    128ms  0.04%   128ms   4.91MiB  0.02%  4.91MiB
     affine_negate_...      1   98.3ms  0.03%  98.3ms   3.54MiB  0.02%  3.54MiB
     affine_trace_atom      1   51.4ms  0.02%  51.4ms   2.39MiB  0.01%  2.39MiB
   sdp                      1    22.1s  7.21%   22.1s   1.65GiB  7.40%  1.65GiB
     sdp_sdp_constr...      1    3.90s  1.28%   3.90s    251MiB  1.10%   251MiB
     sdp_operator_n...      1    3.36s  1.10%   3.36s    239MiB  1.04%   239MiB
     sdp_Partial_trace      1    1.93s  0.63%   1.93s    145MiB  0.63%   145MiB
     sdp_matrix_fra...      1    1.12s  0.36%   1.12s   61.9MiB  0.27%  61.9MiB
     sdp_dual_lambd...      1    1.05s  0.35%   1.05s   66.9MiB  0.29%  66.9MiB
     sdp_matrix_fra...      1    1.05s  0.34%   1.05s   56.1MiB  0.25%  56.1MiB
     sdp_Complex_Va...      1    995ms  0.33%   995ms   39.8MiB  0.17%  39.8MiB
     sdp_Complex_Se...      1    898ms  0.29%   898ms   25.6MiB  0.11%  25.6MiB
     sdp_sum_larges...      1    795ms  0.26%   795ms   36.6MiB  0.16%  36.6MiB
     sdp_socp_sumsq...      1    600ms  0.20%   600ms   40.5MiB  0.18%  40.5MiB
     sdp_lambda_min...      1    581ms  0.19%   581ms   38.3MiB  0.17%  38.3MiB
     sdp_Issue_198          1    525ms  0.17%   525ms   36.9MiB  0.16%  36.9MiB
     sdp_socp_norm2...      1    406ms  0.13%   406ms   22.1MiB  0.10%  22.1MiB
     sdp_socp_abs_atom      1    392ms  0.13%   392ms   22.1MiB  0.10%  22.1MiB
     sdp_nuclear_no...      1    369ms  0.12%   369ms   29.3MiB  0.13%  29.3MiB
     sdp_sdp_variables      1    248ms  0.08%   248ms   24.0MiB  0.10%  24.0MiB
     sdp_kron_atom          1    152ms  0.05%   152ms   18.6MiB  0.08%  18.6MiB
     sdp_Real_Varia...      1    119ms  0.04%   119ms   4.87MiB  0.02%  4.87MiB
     sdp_sigma_max_...      1    110ms  0.04%   110ms   12.2MiB  0.05%  12.2MiB
   socp                     1    18.6s  6.08%   18.6s   1.61GiB  7.22%  1.61GiB
     socp_quad_form...      1    2.74s  0.89%   2.74s   34.5MiB  0.15%  34.5MiB
     socp_dual_mini...      1    2.15s  0.70%   2.15s    147MiB  0.64%   147MiB
     socp_rational_...      1    1.86s  0.61%   1.86s    130MiB  0.57%   130MiB
     socp_sum_squar...      1    1.11s  0.36%   1.11s   83.7MiB  0.37%  83.7MiB
     socp_inv_pos_atom      1    937ms  0.31%   937ms   61.5MiB  0.27%  61.5MiB
     socp_dual_norm...      1    792ms  0.26%   792ms   62.5MiB  0.27%  62.5MiB
     socp_quad_over...      1    789ms  0.26%   789ms   27.4MiB  0.12%  27.4MiB
     socp_rational_...      1    610ms  0.20%   610ms   36.3MiB  0.16%  36.3MiB
     socp_norm_cons...      1    565ms  0.18%   565ms   25.8MiB  0.11%  25.8MiB
     socp_fix_multi...      1    520ms  0.17%   520ms   30.4MiB  0.13%  30.4MiB
     socp_geo_mean_...      1    418ms  0.14%   418ms   24.5MiB  0.11%  24.5MiB
     socp_square_atom       1    405ms  0.13%   405ms   12.4MiB  0.05%  12.4MiB
     socp_dual_frob...      1    391ms  0.13%   391ms   23.3MiB  0.10%  23.3MiB
     socp_huber_atom        1    388ms  0.13%   388ms   30.9MiB  0.13%  30.9MiB
     socp_rational_...      1    169ms  0.06%   169ms   8.36MiB  0.04%  8.36MiB
     socp_fix_and_f...      1   80.9ms  0.03%  80.9ms   5.29MiB  0.02%  5.29MiB
     socp_sqrt_atom         1   72.7ms  0.02%  72.7ms   1.49MiB  0.01%  1.49MiB
   constant                 1    10.2s  3.33%   10.2s    933MiB  4.08%   933MiB
     constant_fix!_...      1    3.53s  1.16%   3.53s    261MiB  1.14%   261MiB
     constant_Issue...      1    3.13s  1.03%   3.13s    309MiB  1.35%   309MiB
     constant_Issue...      1    954ms  0.31%   954ms   66.0MiB  0.29%  66.0MiB
     constant_fix!_...      1    620ms  0.20%   620ms   42.2MiB  0.18%  42.2MiB
     constant_Test_...      1    366ms  0.12%   366ms   18.2MiB  0.08%  18.2MiB
     constant_fix!_...      1    304ms  0.10%   304ms   20.6MiB  0.09%  20.6MiB
   lp                       1    5.83s  1.91%   5.83s    495MiB  2.16%   495MiB
     lp_dotsort_atom        1    982ms  0.32%   982ms   56.3MiB  0.25%  56.3MiB
     lp_min_atom            1    594ms  0.19%   594ms   38.2MiB  0.17%  38.2MiB
     lp_sumlargest_...      1    563ms  0.18%   563ms   43.0MiB  0.19%  43.0MiB
     lp_max_atom            1    425ms  0.14%   425ms   30.7MiB  0.13%  30.7MiB
     lp_minimum_atom        1    368ms  0.12%   368ms   25.3MiB  0.11%  25.3MiB
     lp_dual_abs_atom       1    292ms  0.10%   292ms   17.1MiB  0.07%  17.1MiB
     lp_sumsmallest...      1    264ms  0.09%   264ms   19.6MiB  0.09%  19.6MiB
     lp_maximum_atom        1    244ms  0.08%   244ms   11.9MiB  0.05%  11.9MiB
     lp_neg_atom            1    234ms  0.08%   234ms   10.7MiB  0.05%  10.7MiB
     lp_dual_norm_i...      1    131ms  0.04%   131ms   3.51MiB  0.02%  3.51MiB
     lp_pos_atom            1   84.8ms  0.03%  84.8ms   5.70MiB  0.02%  5.70MiB
     lp_dual_norm_1...      1   69.7ms  0.02%  69.7ms   3.18MiB  0.01%  3.18MiB
     lp_hinge_loss_...      1    249μs  0.00%   249μs   47.7KiB  0.00%  47.7KiB
   exp                      1    3.32s  1.09%   3.32s    264MiB  1.15%   264MiB
     exp_log_atom           1    1.07s  0.35%   1.07s   80.8MiB  0.35%  80.8MiB
     exp_entropy_atom       1    464ms  0.15%   464ms   34.3MiB  0.15%  34.3MiB
     exp_exp_atom           1    338ms  0.11%   338ms   16.8MiB  0.07%  16.8MiB
     exp_log_sum_ex...      1    325ms  0.11%   325ms   22.2MiB  0.10%  22.2MiB
     exp_logistic_l...      1    253ms  0.08%   253ms   12.8MiB  0.06%  12.8MiB
     exp_log_perspe...      1    239ms  0.08%   239ms   14.8MiB  0.06%  14.8MiB
     exp_relative_e...      1   58.9ms  0.02%  58.9ms   4.47MiB  0.02%  4.47MiB
   sdp_and_exp              1    1.97s  0.65%   1.97s    160MiB  0.70%   160MiB
     sdp_and_exp_lo...      1    1.88s  0.62%   1.88s    146MiB  0.64%   146MiB
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
Status `~/work/ConvexTests.jl/ConvexTests.jl/SCS/Manifest.toml`
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
  [4536629a] OpenBLAS_jll v0.3.10+0
  [efe28fd5] OpenSpecFun_jll v0.5.3+3
  [bac558e1] OrderedCollections v1.3.1
  [69de0a69] Parsers v1.0.10
  [ddf597a6] PolyJuMP v0.4.1
  [189a3867] Reexport v0.2.0
  [af85af4c] RowEchelon v0.1.1
  [c946c3f1] SCS v0.7.0
  [f4f2fc5b] SCS_jll v2.1.2+0
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
