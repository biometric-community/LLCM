# LLCM

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green?logo=creativecommons&logoColor=white)](https://creativecommons.org/licenses/by/4.0/)
[![GitHub](https://img.shields.io/badge/GitHub-biometric--community%2FLLCM-181717?logo=github)](https://github.com/biometric-community/LLCM)
[![Access: register](https://img.shields.io/badge/access-register-important.svg)](https://github.com/ZYK100/LLCM)

**LLCM** — tbiom catalog packaging for `llcm` (reid; access `register`). Docs/helpers only; obtain data via upstream registration.

- **Dataset repository**: https://github.com/biometric-community/LLCM
- **Upstream source**: https://github.com/ZYK100/LLCM
- **License (helpers / docs)**: CC BY 4.0 (see [`LICENSE`](LICENSE))
- **License (data)**: upstream terms — this packaging does **not** relicense or redistribute gated data

| Field | Value |
|-------|-------|
| Catalog id (tbiom) | `llcm` |
| Category | `reid` |
| Access | `register` |
| Upstream homepage | https://github.com/ZYK100/LLCM |

## TL;DR

- **Access**: **register** — obtain data from the upstream homepage / license process
- **This mirror**: documentation + download helpers only (no bulk payload in git)
- **Notes**: Low-Light Cross-Modality re-ID; follow GitHub access.

## Download

### Clone this repository

```bash
git clone git@github.com:biometric-community/LLCM.git
cd LLCM
```

### tbiom monorepo helper

```bash
bash projects/datasets/scripts/download_llcm.sh
```

Place licensed archives under `projects/datasets/llcm/` (gitignored).

## Dataset structure

```text
LLCM/
├── README.md
├── LICENSE
├── .gitignore
└── extracted/   # local only after you obtain upstream data
```

## License

Helpers/docs: CC BY 4.0. Dataset files: upstream license / registration agreement.

## Contact

- Upstream: https://github.com/ZYK100/LLCM
- Packaging: https://github.com/biometric-community/LLCM/issues
