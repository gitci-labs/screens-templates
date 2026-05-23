# Screens Templates

Canonical GitCI Screens template packs, scene set templates, components, palettes, themes, and target definitions.

This repo is intentionally data-first: reusable items live under `gitci/screens/packs` with versioned `*.gitci.json` manifests so the Swift planner and future native app can browse the catalog without executing template code.

CI renders a temporary project with this repository as `GITCI_SCREENS_TEMPLATES_ROOT`, which keeps the canonical pack honest against the current public CLI.

Tagged releases attach a tarball containing `gitci/screens` plus README/license files. The native app can download that archive without needing this repository's CI metadata.
