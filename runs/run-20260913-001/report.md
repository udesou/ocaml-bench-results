# run-20260913-001

**Candidate `ocaml-5.5.1-46e1c32-fp` vs baseline `ocaml-5.5.1-46e1c32`** (deltas relative to the baseline; negative = `ocaml-5.5.1-46e1c32-fp` is better)

| benchmark | wall | instructions | max RSS |
|---|---|---|---|
| `alt_ergo_chain_default` | +3.2% ⬆ | +11.6% ⬆ | +0.1% |
| `alt_ergo_chain_large` | +3.4% ⬆ | +11.2% ⬆ | +0.0% |
| `coqc_tree_default` | +0.0% | -0.0% | -0.0% |
| `coqc_tree_large` | -0.0% | +0.0% | +0.0% |
| `cpdf_squeeze_default` | +2.4% ⚠ | +5.5% ⬆ | -0.1% |
| `cpdf_squeeze_large` | +1.1% ⚠ | +6.3% ⬆ | +0.0% |
| `devkit_htmlstream_default` | +12.8% ⬆ | +6.9% ⬆ | +0.0% |
| `devkit_htmlstream_large` | +10.3% ⬆ | +6.9% ⬆ | +0.0% |
| `eio_conc_default` | +3.7% ⬆ | +5.4% ⬆ | +0.3% |
| `eio_conc_large` | +2.7% ⚠ | +4.9% ⬆ | -0.6% |
| `frama_c_eva_sqlite_default` | +4.3% ⬆ | +11.0% ⬆ | +0.0% |
| `frama_c_eva_sqlite_large` | +5.0% ⬆ | +11.3% ⬆ | +0.1% |
| `goblint_gen_default` | +3.7% ⬆ | +12.2% ⬆ | +0.2% |
| `goblint_gen_large` | +3.4% ⬆ | +11.6% ⬆ | +0.3% |
| `infer_default` | +0.2% | +1.9% ⚠ | -0.2% |
| `infer_large` | +4.4% ⬆ | +10.0% ⬆ | +1.4% ⚠ |
| `irmin_mem_rw_default` | +2.4% ⚠ | +8.7% ⬆ | +0.0% |
| `irmin_mem_rw_large` | +2.1% ⚠ | +8.4% ⬆ | +0.4% |
| `jsoo_default` | +4.0% ⬆ | +7.4% ⬆ | +0.1% |
| `jsoo_large` | +3.9% ⬆ | +7.2% ⬆ | +0.0% |
| `liq_parse_typecheck_default` | +5.0% ⬆ | +4.1% ⬆ | +4.2% ⬆ |
| `liq_parse_typecheck_large` | +5.7% ⬆ | +4.0% ⬆ | +9.7% ⬆ |
| `liq_video_frames_pool_default` | +0.1% | +0.0% | +0.0% |
| `liq_video_frames_pool_large` | +0.1% | +0.0% | +0.0% |
| `menhir_ocamly` | +4.7% ⬆ | +9.0% ⬆ | -0.2% |
| `menhir_sysver_canonical` | +3.2% ⬆ | +2.5% ⚠ | +0.0% |
| `ocamlc_compile_uucp_default` | +3.6% ⬆ | +9.8% ⬆ | -0.7% |
| `ocamlc_compile_uucp_large` | +3.5% ⬆ | +9.3% ⬆ | -2.3% ⚠ |
| `ocamlformat_rocq_default` | +4.8% ⬆ | +8.1% ⬆ | +0.1% |
| `ocamlformat_rocq_large` | +4.4% ⬆ | +8.7% ⬆ | +0.0% |
| `owl_gc_default` | +0.1% | +0.0% | +0.0% |
| `owl_gc_large` | +0.0% | +0.0% | -0.0% |
| `pplacer_like_default` | -5.3% ⬇ | +2.0% ⚠ | +0.0% |
| `pplacer_like_large` | -17.0% ⬇ | +2.0% ⚠ | +0.0% |
| `sedlex_tokenize_default` | +3.1% ⬆ | +6.9% ⬆ | +0.0% |
| `sedlex_tokenize_large` | +3.3% ⬆ | +6.9% ⬆ | +0.0% |
| `test_decompress_default` | +5.0% ⬆ | +8.3% ⬆ | -0.0% |
| `test_decompress_large` | +5.0% ⬆ | +8.3% ⬆ | +0.0% |
| `ydump_repeat_default` | +3.5% ⬆ | +4.4% ⬆ | +0.0% |
| `ydump_repeat_large` | +3.4% ⬆ | +4.4% ⬆ | +0.0% |
| `zarith_pi_default` | +0.3% | +0.2% | +0.0% |
| `zarith_pi_large` | +0.1% | +0.1% | +0.0% |

**Candidate `ocaml-5.5.1-46e1c32-flambda` vs baseline `ocaml-5.5.1-46e1c32`** (deltas relative to the baseline; negative = `ocaml-5.5.1-46e1c32-flambda` is better)

| benchmark | wall | instructions | max RSS |
|---|---|---|---|
| `alt_ergo_chain_default` | -17.1% ⬇ | -19.6% ⬇ | +1.5% ⚠ |
| `alt_ergo_chain_large` | -16.7% ⬇ | -19.4% ⬇ | +1.0% |
| `coqc_tree_default` | -0.1% | +0.0% | -0.0% |
| `coqc_tree_large` | -0.0% | -0.0% | +0.0% |
| `cpdf_squeeze_default` | +1.4% ⚠ | -1.0% ⚠ | -1.2% ⚠ |
| `cpdf_squeeze_large` | +3.6% ⬆ | -0.6% | -8.8% ⬇ |
| `devkit_htmlstream_default` | -4.0% ⬇ | -0.6% | +41.2% ⬆ |
| `devkit_htmlstream_large` | -5.0% ⬇ | -0.6% | +61.7% ⬆ |
| `eio_conc_default` | -4.1% ⬇ | -1.7% ⚠ | -1.4% ⚠ |
| `eio_conc_large` | -0.7% | +0.5% | +0.3% |
| `frama_c_eva_sqlite_default` | -10.5% ⬇ | -10.9% ⬇ | +11.9% ⬆ |
| `frama_c_eva_sqlite_large` | -11.5% ⬇ | -7.5% ⬇ | +12.9% ⬆ |
| `goblint_gen_default` | -4.9% ⬇ | -0.3% | +22.5% ⬆ |
| `goblint_gen_large` | -2.1% ⚠ | +2.1% ⚠ | +15.4% ⬆ |
| `infer_default` | -1.4% ⚠ | -12.2% ⬇ | -0.0% |
| `infer_large` | -19.5% ⬇ | -21.9% ⬇ | +1.4% ⚠ |
| `irmin_mem_rw_default` | -9.9% ⬇ | -9.2% ⬇ | +8.6% ⬆ |
| `irmin_mem_rw_large` | -9.1% ⬇ | -8.3% ⬇ | +5.3% ⬆ |
| `jsoo_default` | -7.2% ⬇ | -10.2% ⬇ | +2.3% ⚠ |
| `jsoo_large` | -7.0% ⬇ | -9.7% ⬇ | -1.7% ⚠ |
| `liq_parse_typecheck_default` | -0.8% | +2.6% ⚠ | +3.1% ⬆ |
| `liq_parse_typecheck_large` | -1.6% ⚠ | +4.6% ⬆ | -0.7% |
| `liq_video_frames_pool_default` | -0.1% | -0.0% | +0.2% |
| `liq_video_frames_pool_large` | -0.2% | -0.1% | +0.2% |
| `menhir_ocamly` | -4.2% ⬇ | -6.1% ⬇ | -2.1% ⚠ |
| `menhir_sysver_canonical` | -16.5% ⬇ | -22.7% ⬇ | -7.0% ⬇ |
| `ocamlc_compile_uucp_default` | -3.0% ⚠ | -2.4% ⚠ | +0.5% |
| `ocamlc_compile_uucp_large` | -3.2% ⬇ | -2.2% ⚠ | -0.3% |
| `ocamlformat_rocq_default` | -7.9% ⬇ | -12.6% ⬇ | +1.2% ⚠ |
| `ocamlformat_rocq_large` | -5.4% ⬇ | -13.6% ⬇ | -13.5% ⬇ |
| `owl_gc_default` | -1.4% ⚠ | -1.3% ⚠ | +1.8% ⚠ |
| `owl_gc_large` | -0.1% | -0.1% | +1.0% ⚠ |
| `pplacer_like_default` | -3.2% ⬇ | -0.6% | +1.6% ⚠ |
| `pplacer_like_large` | -1.8% ⚠ | -0.7% | +1.3% ⚠ |
| `sedlex_tokenize_default` | -7.7% ⬇ | -8.1% ⬇ | +4.5% ⬆ |
| `sedlex_tokenize_large` | -7.6% ⬇ | -8.3% ⬇ | +4.6% ⬆ |
| `test_decompress_default` | -11.6% ⬇ | -8.6% ⬇ | -0.4% |
| `test_decompress_large` | -11.5% ⬇ | -8.5% ⬇ | -0.4% |
| `ydump_repeat_default` | -3.0% ⬇ | -1.2% ⚠ | +0.0% |
| `ydump_repeat_large` | -3.3% ⬇ | -1.2% ⚠ | +0.0% |
| `zarith_pi_default` | -4.1% ⬇ | -5.0% ⬇ | +0.1% |
| `zarith_pi_large` | -2.5% ⚠ | -2.9% ⚠ | +0.1% |

**Candidate `ocaml-5.5.1-46e1c32-fp-flambda` vs baseline `ocaml-5.5.1-46e1c32`** (deltas relative to the baseline; negative = `ocaml-5.5.1-46e1c32-fp-flambda` is better)

| benchmark | wall | instructions | max RSS |
|---|---|---|---|
| `alt_ergo_chain_default` | -13.4% ⬇ | -12.6% ⬇ | +1.3% ⚠ |
| `alt_ergo_chain_large` | -13.0% ⬇ | -12.7% ⬇ | +1.0% |
| `coqc_tree_default` | -0.0% | +0.0% | +0.0% |
| `coqc_tree_large` | -0.0% | +0.0% | -0.0% |
| `cpdf_squeeze_default` | +1.2% ⚠ | +3.7% ⬆ | -1.2% ⚠ |
| `cpdf_squeeze_large` | +0.4% | +5.3% ⬆ | -8.8% ⬇ |
| `devkit_htmlstream_default` | +1.7% ⚠ | +6.0% ⬆ | +41.3% ⬆ |
| `devkit_htmlstream_large` | +0.7% | +5.9% ⬆ | +61.8% ⬆ |
| `eio_conc_default` | +1.3% ⚠ | +2.8% ⚠ | -1.4% ⚠ |
| `eio_conc_large` | +4.9% ⬆ | +5.1% ⬆ | +0.3% |
| `frama_c_eva_sqlite_default` | -9.2% ⬇ | -3.1% ⬇ | +12.1% ⬆ |
| `frama_c_eva_sqlite_large` | -4.4% ⬇ | +2.0% ⚠ | +13.2% ⬆ |
| `goblint_gen_default` | +0.2% | +11.2% ⬆ | +22.8% ⬆ |
| `goblint_gen_large` | +4.1% ⬆ | +13.3% ⬆ | +15.7% ⬆ |
| `infer_default` | -1.7% ⚠ | -4.7% ⬇ | +1.2% ⚠ |
| `infer_large` | -17.8% ⬇ | -16.5% ⬇ | +1.0% ⚠ |
| `irmin_mem_rw_default` | -5.2% ⬇ | -2.3% ⚠ | +8.7% ⬆ |
| `irmin_mem_rw_large` | -4.7% ⬇ | -1.6% ⚠ | +5.4% ⬆ |
| `jsoo_default` | -3.9% ⬇ | -6.0% ⬇ | +2.4% ⚠ |
| `jsoo_large` | -3.8% ⬇ | -5.5% ⬇ | -1.6% ⚠ |
| `liq_parse_typecheck_default` | +3.0% ⚠ | +6.8% ⬆ | -0.4% |
| `liq_parse_typecheck_large` | +2.2% ⚠ | +8.8% ⬆ | -0.2% |
| `liq_video_frames_pool_default` | -0.1% | -0.0% | +0.3% |
| `liq_video_frames_pool_large` | -0.1% | -0.1% | +0.2% |
| `menhir_ocamly` | -1.2% ⚠ | +1.1% ⚠ | -2.1% ⚠ |
| `menhir_sysver_canonical` | -15.5% ⬇ | -21.5% ⬇ | -7.0% ⬇ |
| `ocamlc_compile_uucp_default` | -0.3% | +7.0% ⬆ | +1.1% ⚠ |
| `ocamlc_compile_uucp_large` | -0.3% | +6.7% ⬆ | +0.1% |
| `ocamlformat_rocq_default` | -5.4% ⬇ | -6.8% ⬇ | +1.2% ⚠ |
| `ocamlformat_rocq_large` | -3.0% ⚠ | -7.4% ⬇ | -13.4% ⬇ |
| `owl_gc_default` | -1.3% ⚠ | -1.3% ⚠ | +1.9% ⚠ |
| `owl_gc_large` | -0.1% | -0.1% | +1.0% ⚠ |
| `pplacer_like_default` | -1.9% ⚠ | +1.4% ⚠ | +1.6% ⚠ |
| `pplacer_like_large` | -0.5% | +1.3% ⚠ | +1.3% ⚠ |
| `sedlex_tokenize_default` | -2.4% ⚠ | -3.1% ⬇ | +4.5% ⬆ |
| `sedlex_tokenize_large` | -2.3% ⚠ | -3.2% ⬇ | +4.6% ⬆ |
| `test_decompress_default` | -5.7% ⬇ | -1.4% ⚠ | -0.4% |
| `test_decompress_large` | -5.7% ⬇ | -1.3% ⚠ | -0.4% |
| `ydump_repeat_default` | +0.8% | +3.0% ⚠ | +0.0% |
| `ydump_repeat_large` | +0.7% | +3.0% ⚠ | +0.0% |
| `zarith_pi_default` | -3.3% ⬇ | -4.8% ⬇ | +0.1% |
| `zarith_pi_large` | -1.9% ⚠ | -2.7% ⚠ | +0.1% |

wall: 29 regressed, 42 improved, 26 warn, 29 unchanged · instructions: 42 regressed, 32 improved, 27 warn, 25 unchanged · max RSS: 23 regressed, 6 improved, 28 warn, 22 unchanged, 47 gated

<sub>medians across invocations; bands ±1% warn, ±3% significant; RSS verdicts need ≥ 1 MiB moved. Thresholds are provisional (service.json `report`).</sub>
