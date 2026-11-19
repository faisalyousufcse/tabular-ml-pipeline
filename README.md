# tabular-ml-pipeline

End-to-end pipeline for tabular data: features, models and reports.

> Status: planned. This repository holds the project outline, and the code is on its way.

## Overview

An opinionated pipeline that takes a tabular dataset from raw CSV to a validated model with cross-validation, feature importance and a written report.

## Planned features

- Schema checks and leakage guards before training
- Cross-validated model selection with a fixed budget
- Feature importance and calibration plots
- One-command reproducible runs

## Tech stack

Python, scikit-learn, LightGBM, pandas

## Roadmap

- [ ] Project skeleton and CI
- [ ] Core implementation
- [ ] Tests and examples
- [ ] Documentation

## License

MIT. See [LICENSE](LICENSE).
