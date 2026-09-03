# run-20260902-001

**Candidate `ocaml-5.5.0-f523850-fp` vs baseline `ocaml-5.5.0-f523850`** (deltas relative to the baseline; negative = `ocaml-5.5.0-f523850-fp` is better)

| benchmark | wall | instructions | max RSS |
|---|---|---|---|
| `jsoo_default` | +4.0% (n=1)* | +7.3% ⬆ | +0.1% |
| `jsoo_large` | +4.3% (n=1)* | +7.2% ⬆ | +0.0% |
| `liq_parse_typecheck_default` | +5.9% (n=1)* | +4.1% ⬆ | +4.2% ⬆ |
| `liq_parse_typecheck_large` | +5.8% (n=1)* | +4.0% ⬆ | +9.7% ⬆ |
| `liq_video_frames_pool_default` | +0.0% (n=1)* | +0.0% | +0.0% |
| `liq_video_frames_pool_large` | +0.1% (n=1)* | +0.0% | +0.0% |
| `ocamlc_compile_uucp_default` | +2.5% (n=1)* | +9.7% ⬆ | +0.3% |
| `ocamlc_compile_uucp_large` | +2.9% (n=1)* | +9.2% ⬆ | +3.4% ⬆ |
| `owl_gc_default` | -0.1% (n=1)* | +0.0% | -0.0% |
| `pplacer_like_default` | -11.5% (n=1)* | +2.0% ⚠ | +0.0% |
| `pplacer_like_large` | -2.4% (n=1)* | +2.0% ⚠ | +0.0% |
| `sedlex_tokenize_large` | +5.4% (n=1)* | +7.0% ⬆ | -0.0% |
| `ydump_repeat_default` | +3.2% (n=1)* | +4.4% ⬆ | +0.0% |
| `ydump_repeat_large` | +3.6% (n=1)* | +4.4% ⬆ | +0.0% |
| `zarith_pi_default` | +0.4% (n=1)* | +0.2% | +0.0% |
| `zarith_pi_large` | +1.5% (n=1)* | +0.2% | -0.0% |

**Candidate `ocaml-5.5.0-f523850-flambda` vs baseline `ocaml-5.5.0-f523850`** (deltas relative to the baseline; negative = `ocaml-5.5.0-f523850-flambda` is better)

| benchmark | wall | instructions | max RSS |
|---|---|---|---|
| `jsoo_default` | -7.5% (n=1)* | -10.3% ⬇ | +2.3% ⚠ |
| `jsoo_large` | -7.0% (n=1)* | -9.7% ⬇ | -1.7% ⚠ |
| `liq_parse_typecheck_default` | -2.6% (n=1)* | +2.6% ⚠ | +3.1% ⬆ |
| `liq_parse_typecheck_large` | -3.6% (n=1)* | +4.6% ⬆ | -0.8% |
| `liq_video_frames_pool_default` | +0.0% (n=1)* | -0.0% | +0.2% |
| `liq_video_frames_pool_large` | -0.0% (n=1)* | -0.1% | +0.2% |
| `ocamlc_compile_uucp_default` | -3.5% (n=1)* | -2.5% ⚠ | +2.1% ⚠ |
| `ocamlc_compile_uucp_large` | -3.7% (n=1)* | -2.3% ⚠ | +3.7% ⬆ |
| `owl_gc_default` | -0.4% (n=1)* | -0.8% | +1.6% ⚠ |
| `pplacer_like_default` | -0.9% (n=1)* | -0.6% | +1.5% ⚠ |
| `pplacer_like_large` | -4.2% (n=1)* | -0.7% | +1.3% ⚠ |
| `sedlex_tokenize_large` | -7.1% (n=1)* | -8.3% ⬇ | +4.6% ⬆ |
| `ydump_repeat_default` | -1.0% (n=1)* | -1.2% ⚠ | +0.0% |
| `ydump_repeat_large` | -0.8% (n=1)* | -1.2% ⚠ | +0.0% |
| `zarith_pi_default` | -4.3% (n=1)* | -5.1% ⬇ | +0.1% |
| `zarith_pi_large` | -2.1% (n=1)* | -2.9% ⚠ | +0.1% |

**Candidate `ocaml-5.5.0-f523850-fp-flambda` vs baseline `ocaml-5.5.0-f523850`** (deltas relative to the baseline; negative = `ocaml-5.5.0-f523850-fp-flambda` is better)

| benchmark | wall | instructions | max RSS |
|---|---|---|---|
| `jsoo_default` | -4.4% (n=1)* | -6.1% ⬇ | +2.3% ⚠ |
| `jsoo_large` | -4.3% (n=1)* | -5.6% ⬇ | -1.6% ⚠ |
| `liq_parse_typecheck_default` | +4.4% (n=1)* | +6.8% ⬆ | +0.5% |
| `liq_parse_typecheck_large` | +3.5% (n=1)* | +8.8% ⬆ | -0.2% |
| `liq_video_frames_pool_default` | +0.1% (n=1)* | -0.0% | +0.3% |
| `liq_video_frames_pool_large` | -0.1% (n=1)* | -0.1% | +0.2% |
| `ocamlc_compile_uucp_default` | -0.8% (n=1)* | +6.9% ⬆ | -1.3% ⚠ |
| `ocamlc_compile_uucp_large` | -1.0% (n=1)* | +6.6% ⬆ | +2.9% ⚠ |
| `owl_gc_default` | -0.3% (n=1)* | -0.8% | +1.6% ⚠ |
| `pplacer_like_default` | +0.6% (n=1)* | +1.4% ⚠ | +1.6% ⚠ |
| `pplacer_like_large` | -2.9% (n=1)* | +1.3% ⚠ | +1.3% ⚠ |
| `sedlex_tokenize_large` | -2.6% (n=1)* | -3.2% ⬇ | +4.6% ⬆ |
| `ydump_repeat_default` | +2.7% (n=1)* | +3.0% ⚠ | +0.0% |
| `ydump_repeat_large` | +2.5% (n=1)* | +3.0% ⚠ | +0.0% |
| `zarith_pi_default` | -3.6% (n=1)* | -4.9% ⬇ | +0.1% |
| `zarith_pi_large` | -1.9% (n=1)* | -2.8% ⚠ | +0.1% |

wall: 0 regressed, 0 improved, 0 warn, 0 unchanged, 48 gated · instructions: 14 regressed, 8 improved, 13 warn, 13 unchanged · max RSS: 7 regressed, 0 improved, 13 warn, 5 unchanged, 23 gated

\* wall time below 3 invocations: indicative only, never a verdict.
<sub>medians across invocations; bands ±1% warn, ±3% significant; RSS verdicts need ≥ 1 MiB moved. Thresholds are provisional (service.json `report`).</sub>
