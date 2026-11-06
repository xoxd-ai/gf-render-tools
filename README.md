# gf-render-tools

This repository mirrors one prebuilt tool for the GloriousFlywheel installation render: the static toybox 0.8.15 binary for x86_64 Linux. The render fetches it by a pinned hash, so a cold native build does not depend on the upstream host. Operator ruling R675 (TIN-5447) set this up.

## Release `toybox-0.8.15`

| Field | Value |
|---|---|
| Asset | `toybox-x86_64`, unmodified |
| Origin | https://landley.net/toybox/downloads/binaries/0.8.15/toybox-x86_64 |
| Origin `last-modified` | Mon, 05 Oct 2026 17:47:55 GMT |
| Size | 777976 bytes |
| sha256 | `38e03ffd8aead8ca26833e1e5c90a9ea7250f3719c29d779ebff7aa55c9d2dac` |
| Nix NAR hash, executable | `sha256-viXu2rPA0Y9fxnS4FPikMRFHg5IgV7tnoxPk4cN2QpU=` |
| Toybox source tag | `0.8.15`, commit `a57b091d05ec366dcd4dd737784c03761cb6a4b1` at https://github.com/landley/toybox |
| Licences | See `NOTICES`: toybox 0BSD and musl MIT |

## Provenance

Upstream publishes sha256 sums on a separate server, linked from the binaries README: https://lists.landley.net/pipermail/toybox/2026-October/010015.html. Its toybox-x86_64 line equals the sha256 above. Upstream publishes no signature. The hash above comes from the first fetch, and two hosts saw the same bytes. A fetch from a second network is still to be recorded. The mirror adds availability and a record.

The release is immutable. A change would be a new release with a new tag, and the render pin would move with it.
