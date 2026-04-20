# Windstorm Labs

**Experimental code and reproducibility infrastructure for the Windstorm Institute paper series.**



---

## Series Index

| # | Repository | Status | DOI | Compute |
|---|------------|--------|-----|---------|
| 1 | [fons-constraint](https://github.com/Windstorm-Labs/fons-constraint) | ✅ Published | [10.5281/zenodo.19274048](https://doi.org/10.5281/zenodo.19274048) | — |
| 2 | [receiver-limited-floor](https://github.com/Windstorm-Labs/receiver-limited-floor) | ✅ Published | [10.5281/zenodo.19322973](https://doi.org/10.5281/zenodo.19322973) | ~8 hrs RTX 5090 |
| 3 | [throughput-basin](https://github.com/Windstorm-Labs/throughput-basin) | ✅ Published | [10.5281/zenodo.19323194](https://doi.org/10.5281/zenodo.19323194) | Meta-analysis |
| 4 | [serial-decoding-basin](https://github.com/Windstorm-Labs/serial-decoding-basin) | ✅ Published | [10.5281/zenodo.19323423](https://doi.org/10.5281/zenodo.19323423) | — |
| 5 | [dissipative-decoder](https://github.com/Windstorm-Labs/dissipative-decoder) | ✅ Published | [10.5281/zenodo.19433048](https://doi.org/10.5281/zenodo.19433048) | ~6 hrs RTX 5090 |
| 6 | [inherited-constraint](https://github.com/Windstorm-Labs/inherited-constraint) | ✅ Published | [10.5281/zenodo.19432911](https://doi.org/10.5281/zenodo.19432911) | ~4 hrs RTX 5090 |
| 7 | [throughput-basin-origin](https://github.com/Windstorm-Labs/throughput-basin-origin) | ✅ Published | [10.5281/zenodo.19498582](https://doi.org/10.5281/zenodo.19498582) | ~14.5 hrs RTX 5090 |
| 8 | [vision-basin](https://github.com/Windstorm-Labs/vision-basin) | ✅ Published | [10.5281/zenodo.19672827](https://doi.org/10.5281/zenodo.19672827) | ~30 hrs RTX 5090 |
| 9 | [hardware-basin](https://github.com/Windstorm-Labs/hardware-basin) | ✅ Published | [10.5281/zenodo.19672921](https://doi.org/10.5281/zenodo.19672921) | ~10 hrs RTX 5090 |

**Paper 7 canonical repository:** [Windstorm-Institute/throughput-basin-origin](https://github.com/Windstorm-Institute/throughput-basin-origin). The Labs mirror tracks the experiment protocols; the canonical repo holds the formal manuscript, the internal adversarial review, complete CSVs, plots, and the [Paper 7.1 tracking issue](https://github.com/Windstorm-Institute/throughput-basin-origin/issues/1).

> **Read this before citing Paper 7.** The paper is published together with its full internal adversarial review, which identifies four blocking items that constrain the headline. The defensible claim is *"At 92M parameters, on Markov synthetic data with corpus-specific BPE tokenizers, training-data token entropy is the dominant predictor of achieved BPT, and we find no positive evidence of a transformer-specific ~4-bit ceiling in this regime."* The stronger claim requires the Paper 7.1 re-runs.

---

## Quick Links

- **Paper publications:** [Windstorm-Institute](https://github.com/Windstorm-Institute)
- **Institute website:** [windstorminstitute.org](https://windstorminstitute.org)
- **Principal Investigator:** Grant Lavell Whitmer III

## Reproducibility

All experiments designed for:
- **Hardware:** NVIDIA RTX 5090 (32 GB VRAM)
- **OS:** Ubuntu 24.04
- **Python:** 3.11+

See individual repository READMEs for quick-start instructions, exact dependency versions, runtime estimates, and validation steps.

## Contributing

- Found an issue? Open a ticket on the relevant repository.
- Want to extend? Fork and submit a PR.
- Questions? Contact via the institute website.

---

*Code: MIT License · Data: CC BY 4.0*
