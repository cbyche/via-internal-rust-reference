# Internal Voice Agent Reference Snapshot

## Source

- Source repository: Internal Enterprise GitHub Voice Interaction Agent prototype
- Local source directory: `~/Workspace/VIA`
- Source branch: `main`
- Source commit: `b6032a4c472e18ec216b3e8592346ab269495342`
- Imported date: `2026-09-09`

## Purpose

This repository contains a reference snapshot of an existing internal
Rust-based Voice Interaction Agent prototype.

It is used as an architecture reference input for the VIA Software
Architecture project.

This implementation is NOT the approved VIA architecture.

Design choices found in this implementation must be independently
evaluated against VIA requirements, quality attributes, and
architectural decision points.

## Snapshot Policy

Files under `source/` represent the source repository at the recorded
commit above.

Do not directly modify files under `source/` for VIA architecture work.

When the internal prototype changes, import a new snapshot and record
the new source branch and commit.

## Excluded from Snapshot

- Git history (`.git/`)
- Rust build outputs (`target/`)
- Mutation-test outputs (`mutants.out/`)
- Python cache (`__pycache__/`, `*.pyc`)
- Local environment files (`.env`, `.env.*`)
- macOS metadata (`.DS_Store`)
