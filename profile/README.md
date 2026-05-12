# Windstorm Labs

**Experimental code and reproducibility infrastructure for the Windstorm Institute paper series.**



---

## Series Index

| # | Repository | Status | DOI | Compute |
|---|------------|--------|-----|---------|
| 1 | [fons-constraint](https://github.com/Windstorm-Labs/fons-constraint) | ✅ Published | [10.5281/zenodo.19274048](https://doi.org/10.5281/zenodo.19274048) | — |
| 2 | [receiver-limited-floor](https://github.com/Windstorm-Labs/receiver-limited-floor) | ✅ Published | [10.5281/zenodo.19322973](https://doi.org/10.5281/zenodo.19322973) | ~8 hrs Nvidia GPU |
| 3 | [throughput-basin](https://github.com/Windstorm-Labs/throughput-basin) | ✅ Published | [10.5281/zenodo.19323194](https://doi.org/10.5281/zenodo.19323194) | Meta-analysis |
| 4 | [serial-decoding-basin](https://github.com/Windstorm-Labs/serial-decoding-basin) | ✅ Published | [10.5281/zenodo.19323423](https://doi.org/10.5281/zenodo.19323423) | — |
| 5 | [dissipative-decoder](https://github.com/Windstorm-Labs/dissipative-decoder) | ✅ Published | [10.5281/zenodo.19433048](https://doi.org/10.5281/zenodo.19433048) | ~6 hrs Nvidia GPU |
| 6 | [inherited-constraint](https://github.com/Windstorm-Labs/inherited-constraint) | ✅ Published | [10.5281/zenodo.19432911](https://doi.org/10.5281/zenodo.19432911) | ~4 hrs Nvidia GPU |
| 7 | [throughput-basin-origin](https://github.com/Windstorm-Labs/throughput-basin-origin) | ✅ Published | [10.5281/zenodo.19498582](https://doi.org/10.5281/zenodo.19498582) | ~14.5 hrs Nvidia GPU |
| 8 | [vision-basin](https://github.com/Windstorm-Labs/vision-basin) | ✅ Published | [10.5281/zenodo.19672827](https://doi.org/10.5281/zenodo.19672827) | ~30 hrs Nvidia GPU |
| 9 | [hardware-basin](https://github.com/Windstorm-Labs/hardware-basin) | ✅ Published | [10.5281/zenodo.19672921](https://doi.org/10.5281/zenodo.19672921) | ~10 hrs Nvidia GPU |

**Paper 7 canonical repository:** [Windstorm-Institute/throughput-basin-origin](https://github.com/Windstorm-Institute/throughput-basin-origin). The Labs mirror tracks the experiment protocols; the canonical repo holds the formal manuscript, the internal adversarial review, complete CSVs, plots, and the [Paper 7.1 tracking issue](https://github.com/Windstorm-Institute/throughput-basin-origin/issues/1).

> **Read this before citing Paper 7.** The paper is published together with its full internal adversarial review, which identifies four blocking items that constrain the headline. The defensible claim is *"At 92M parameters, on Markov synthetic data with corpus-specific BPE tokenizers, training-data token entropy is the dominant predictor of achieved BPT, and we find no positive evidence of a transformer-specific ~4-bit ceiling in this regime."* The stronger claim requires the Paper 7.1 re-runs.

---

## Track 2 — Entropic Bounds in Analog Systems · 6 papers (Papers 10–15 globally)

The same Clausius-inequality lens applied to gravity-adjacent physical systems. Code mirrors for the Track 2 papers live here; the analyses span QuTiP Lindblad simulations, SPARC and Genzel reanalyses, dimensional-analysis case studies, and lattice quantum field theory.

| # | Repository | Status | DOI | Compute |
|---|------------|--------|-----|---------|
| 10 | [phonon-extraction-bound](https://github.com/Windstorm-Labs/phonon-extraction-bound) | ✅ Published | [10.5281/zenodo.20014391](https://doi.org/10.5281/zenodo.20014391) | QuTiP Lindblad — CPU |
| 11 | [gravitational-entropy-escrow](https://github.com/Windstorm-Labs/gravitational-entropy-escrow) | ✅ Published | [10.5281/zenodo.20032023](https://doi.org/10.5281/zenodo.20032023) | SPARC + Genzel reanalyses — CPU |
| 12 | [c8-clarification-note](https://github.com/Windstorm-Labs/c8-clarification-note) | ✅ Published | [10.5281/zenodo.20041992](https://doi.org/10.5281/zenodo.20041992) | sympy + numerical — CPU (<1s) |
| 13 | [lattice-qft-test](https://github.com/Windstorm-Labs/lattice-qft-test) | ✅ Published | [10.5281/zenodo.20057538](https://doi.org/10.5281/zenodo.20057538) | numpy + scipy.linalg.eigh — CPU (~10 min for 1+1D scan); 3+1D companion uses Nvidia GPU |
| 14 | [Spacetime as Escrow Bookkeeping](https://github.com/Windstorm-Institute/escrow-spacetime) *(5th in track; translation of standard GR results into the escrow vocabulary; companion to Paper 11)* | [10.5281/zenodo.20126091](https://doi.org/10.5281/zenodo.20126091) | [Labs](https://github.com/Windstorm-Labs/escrow-spacetime) |
| 15 | [The 𝒩<sub>esc</sub> Recipe](https://github.com/Windstorm-Institute/nesc-recipe) | Formalizes the 𝒩<sub>esc</sub> notation from Paper 14 as a two-argument function 𝒩<sub>esc</sub>(*E*, *L*) ≡ 2π*EL*/(ℏ*c*) plus a regime-specific recipe extracting (*E*, *L*) from |*U*|/*T*. Observes that the same one-function recipe, applied across three qualitatively distinct settings — test mass in Schwarzschild, Bekenstein–Hawking via Smarr, and Casini's QFT bound in a Rindler wedge — evaluates to the Bekenstein-bound saturation form in each. Lattice verification at *N* ∈ [200, 1200]: boost-generator BW identification at 0.087% mean accuracy; Casini–BW inequality verified within max 5.4% saturation. Theorem 1 conditional on BW, Casini, and moment-positivity. Five pre-registered retractions. Continuation of Paper 14. | [10.5281/zenodo.20145106](https://doi.org/10.5281/zenodo.20145106) | [Labs](https://github.com/Windstorm-Labs/nesc-recipe) |
---

## Quick Links

- **Paper publications:** [Windstorm-Institute](https://github.com/Windstorm-Institute)
- **Institute website:** [windstorminstitute.org](https://windstorminstitute.org)
- **Principal Investigator:** Grant Lavell Whitmer III

## Reproducibility

All experiments designed for:
- **Hardware:** Current-generation Nvidia GPU (32 GB VRAM, CUDA)
- **OS:** Ubuntu 24.04
- **Python:** 3.11+

See individual repository READMEs for quick-start instructions, exact dependency versions, runtime estimates, and validation steps.

## Contributing

- Found an issue? Open a ticket on the relevant repository.
- Want to extend? Fork and submit a PR.
- Questions? Contact via the institute website.

---

*Code: MIT License · Data: CC BY 4.0*
