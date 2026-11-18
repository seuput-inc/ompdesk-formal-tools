# ompdesk-formal-tools

Byte-exact copies of the third-party tools that [OMPdesk](https://github.com/seuput-inc/ompdesk)'s formal verification downloads in CI. Upstream serves some of them under a moving tag, so OMPdesk pins a copy kept here instead.

Releases are immutable. Never delete a release that `resources/omp-builtin/formal/skills/ompdesk-formal-verify/assets/toolchain.json` in OMPdesk names: its sha256 pin would then have nothing to download.

| Release | Asset | Source | License |
|---|---|---|---|
| `tla2tools-1.8.0-d8fb231` | `tla2tools.jar` (sha256 `e1f11b75c4b5bc4478ba0ac5cb6ae28e40a01b0016bc33e0aa97da22dfdbcd7f`, 4,510,215 bytes) | [tlaplus/tlaplus](https://github.com/tlaplus/tlaplus) `v1.8.0` prerelease asset as built from [d8fb231](https://github.com/tlaplus/tlaplus/commit/d8fb231de4e4b5d02c1b2ed1ac759c086f694021) on 2026-11-06 (upstream replaces that asset on every push to master) | MIT; the license texts ship inside the jar |
