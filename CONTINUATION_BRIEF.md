# Continuation Brief

This repo is intentionally initialized as a minimal, safe starting point for the Muay Thai Training App.

## Current direction

- Keep the training app layered as a lightweight React + Three.js app.
- Build the `Jab POC` in isolation at `/jab-poc`.
- Keep the main app shell separate from the motion-validation experiment.
- Prefer debug-mode inspection over blind tuning.
- Keep external assets in durable storage URLs and do not commit large binaries into the source tree.

## High-priority next tasks

1. Confirm the GLB asset path and load state.
2. Verify the scene root, bounding box, camera framing, and material visibility.
3. Add debug hooks for mesh count, skinned mesh count, bone names, and animation names.
4. Fix the Soldier jab motion readability in the web viewer.
5. Only then decide whether the Ch36 path should be revisited.

## Guardrails

- Do not read or commit `.env` files.
- Do not deploy from this repo.
- Do not execute destructive commands.
- Do not bundle large external assets into source control.

## Project status

This repository is the initial scaffold and should be treated as a clean foundation for later implementation work.
