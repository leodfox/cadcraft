# Ardoise CAO (web editor, fork of cadcraft)

Web build of the Ardoise editor "Ardoise CAO", based on CADCraft by Learning Machines LLC (MIT OR Apache-2.0).
Branch `ardoise` starts from upstream tag v0.5.0 (https://github.com/storytold/cadcraft).

Changes in this fork: postMessage bridge for same-origin iframe embedding (`apps/cadcraft-web/src/bridge.rs`),
Ardoise branding in the UI (the upstream name, wordmark and logos are not used), single web-only CI
workflow (`.github/workflows/web.yml`) that builds the wasm bundle and attaches the zip to a GitHub release.

Build the web bundle: see `packaging/web/README.md` and `packaging/web/package.sh`.

Licences: see LICENSE-APACHE, LICENSE-MIT and NOTICE. The copyright notices of the original authors are kept.
