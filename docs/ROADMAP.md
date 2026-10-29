# Engineering Roadmap

[ English | [Русский](ROADMAP.ru.md) ]

Status indicators reflect current development reality. This roadmap does not constitute a binding delivery commitment.

---

## Validated Foundation

- Unified CAD engine and MCP server for SOLIDWORKS and Autodesk Fusion.
- Parametric modeling, supported assembly constraints/mates, and multi-format exports.
- Output validation, geometry integrity checks, and Fusion sketch failure rollback.
- Command timeout handling, pending queue cancellation, and idempotency protection against replay.
- Fusion add-in version negotiation and automatic backup creation upon updates.

---

## Initial Desktop Release — Planned

- Windows EXE installer with automated runtime dependency resolution.
- Native UI for task execution, visual history, and direct chat.
- Automatic discovery of running CAD host processes.
- Task attachment directly to the active document without manual platform pre-selection.
- Connection wizard for supported MCP clients.
- Direct authentication with AI providers via supported vendor protocols.
- AnemosWorks account licensing, device management, and automatic in-app updates.

---

## Subsequent Phases

- Reusable automated engineering workflow scripts.
- Additional validation benchmarks against real-world mechanical assemblies.
- Expansion of CAD version compatibility and AI client adapters.
- Additional CAD platform adapters following dedicated testing.

The web service, user registration, and billing will launch at a later stage. GitHub currently serves as the official public hub.

[Submit a feature request](https://github.com/pilotarbuza/anemosworks/issues/new/choose)
