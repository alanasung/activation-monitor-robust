<p align="center">
  <h1 align="center">How Brittle Are Activation Monitors Under Distribution Shift</h1>
  <p align="center"><strong>Stress-test activation monitors for deception/harm signals under shift and simple adaptive attacks.</strong></p>
</p>

---

## Overview

This repository implements experimental profiles for **How Brittle Are Activation Monitors Under Distribution Shift**. Config, caching, hooks, metrics, ablations, reporting, and CI support local pilots on small open-weight models.

Hypothesis (one line): Stress-test activation monitors for deception/harm signals under shift and simple adaptive attacks.

## Status

Shared infrastructure is in place; domain stages must pass harness validation before any measured claim.

| Command | Purpose |
|---|---|
| `make install-dev` | editable install + pinned requirements |
| `make test` | full unit suite |
| `make ci` | lint + test + typecheck |
| `make pilot` | end-to-end pilot profile |
