# aiuc1explorer-docs

Generated static-HTML output of [aiuc1explorer][code]. Each release of the
analytical harness writes a flat bundle of HTML files into this repository's
root.

Entry point: [`index.html`](./index.html).

[code]: https://github.com/axigetik/aiuc1explorer-code

## Layout

Flat. Pages-safe (no JS, all assets inlined as base64).

| File | Content |
|---|---|
| `index.html` | Overview, methodology, derived counts, release snapshot table, composition trajectory chart, transition links. |
| `transition-{prev}-{cur}.html` | Per-transition report: 6a requirement-level table (grouped by principle), 6b composition deltas, 6c bullet detail (gated/banded/merge-flagged). |
| `principle-{A..F}.html` | Per-principle aggregation across transitions. |

## Sources and attribution

- **Source content** (AIUC-1 standard): © 2025–2026 Caliber Labs, PBC DBA
  Artificial Intelligence Underwriting Company (AIUC). Sources:
  [GitHub changelog repo](https://github.com/aiunderwriting/AIUC-1-Changelog),
  [website changelog](https://www.aiuc-1.com/changelog).
- **Tool and derived analytical expression**: © 2025–2026 Baden Hughes.
  Not open or redistributable. See [LICENSE](./LICENSE).

This output is transformative — changes, deltas and classifications with
bounded snippets only. It is not a substitute for the standard; read the
source directly for canonical text.
