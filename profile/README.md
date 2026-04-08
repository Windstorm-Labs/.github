# Windstorm-Labs

**Experimental code and reproducibility infrastructure for the Windstorm Institute paper series.**

This organization contains runnable experiments, raw data, and analysis code supporting research on information-theoretic constraints in serial decoding systems.

---

## Series Index

| # | Repository | Status | Compute | Key Result |
|---|------------|--------|---------|------------|
| 1 | [fons-constraint](./fons-constraint) | 📋 Planned | — | 64-codon derivation |
| 2 | [receiver-limited-floor](./receiver-limited-floor) | ✅ Complete | ~8 hrs RTX 5090 | 1,749 models, BPT ⊥ vocab |
| 3 | [throughput-basin](./throughput-basin) | 📋 Planned | Meta-analysis | 31 systems |
| 4 | [dissipative-decoder](./dissipative-decoder) | 📋 Planned | ~6 hrs RTX 5090 | 27-model energy benchmark |
| 5 | [serial-decoding-basin](./serial-decoding-basin) | 📋 Planned | — | τ = 4.16 ± 0.19 bits |
| 6 | [inherited-constraint](./inherited-constraint) | 📋 Planned | ~4 hrs RTX 5090 | 7-corpus shuffling |
| 7 | [agi-extensions](./agi-extensions) | 🚧 In Progress | 32-56 hrs RTX 5090 | 6 new experiments |

Legend: ✅ Complete | 🚧 In Progress | 📋 Planned

---

## Quick Links

- **Paper Publications:** https://github.com/Windstorm-Institute
- **Institute Website:** https://windstorminstitute.org
- **Principal Investigator:** Grant Lavell Whitmer III

---

## Reproducibility

All experiments designed for:
- **Hardware:** NVIDIA RTX 5090 (32GB VRAM)
- **OS:** Ubuntu 24.04
- **Python:** 3.11+

See individual repository READMEs for:
- Quick start instructions
- Exact dependency versions
- Runtime estimates
- Results validation

---

## Contributing

Found an issue? [Open a ticket](../../issues)  
Want to extend? Fork and submit a PR  
Questions? Contact via institute website

---

*Code: MIT License | Data: CC BY 4.0*
