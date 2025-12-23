# Infra Drift Auditor

Scaffold for a Go-based CLI that validates Linux system configurations against baseline definitions.

## Structure
- `cmd/idr`: CLI entrypoint
- `internal/baseline`: baseline YAML handling
- `internal/checker`: checker interfaces and implementations
- `internal/report`: reporting utilities
- `internal/runner`: orchestrator to tie components together
- `baselines`: sample baseline files
