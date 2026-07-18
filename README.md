# Ground Motion Analyzer

**Live tool:** https://arashnassirpour.com/ground-motion/

A standalone browser-based tool for processing earthquake acceleration records, calculating engineering intensity measures, generating linear damped response spectra, and comparing recorded motion against seismic-code targets.

## Features

- Built-in educational pulse and sine-sweep records.
- Upload support for CSV, TXT, and AT2 acceleration records.
- Acceleration-unit conversion and amplitude scaling.
- Mean or linear-trend baseline correction.
- Peak ground acceleration, velocity and displacement metrics.
- Arias intensity, cumulative absolute velocity and significant duration.
- Linear SDOF response spectra calculated with Newmark average acceleration.
- Code-spectrum overlays for Eurocode 8, ASCE/SEI 7-22, AS 1170.4 and NZS 1170.5.
- CSV import from the companion Design Spectrum tool.
- Downloadable processed results.

## Run locally

Open `index.html` in a modern browser or serve the repository with any static web server.

The application is self-contained and requires no build step. Internet access is used only to load the shared Building Response record library when available.

## Scope

This tool is intended for engineering education, preliminary analysis and transparent comparison. Results must be independently verified before use in professional design, assessment or safety-critical decisions.

## Deployment

The site publishes this repository at https://arashnassirpour.com/ground-motion/.

## Licence

Copyright (C) 2026 Arash Nassirpour.

Licensed under the GNU Affero General Public License v3.0 only (`AGPL-3.0-only`). See [LICENSE](LICENSE).
