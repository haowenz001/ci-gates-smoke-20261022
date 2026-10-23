# ci-gates smoke test

This repository is an end-to-end smoke test for the ci-gates MVP template.

- Runner: `scripts/gate/gate.mjs`
- Workflow: `.github/workflows/gate.yml`
- Config: `.github/ci-gates.json`
- Cases: `test/cases/case-catalog.yaml`


PR smoke test: verify pull_request lanes and @case marker.
