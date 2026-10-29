<p align="center">
  <img src="assets/banner.svg" alt="AnemosWorks — AI Automation for CAD" width="100%">
</p>

<p align="center">
  <strong>AI Automation for SOLIDWORKS and Autodesk Fusion</strong><br>
  Parametric models, feature-based editing, assemblies, and engineering verification via AI tools.
</p>

<p align="center">
  [ English | <a href="README.ru.md">Русский</a> ] ·
  <a href="docs/DOWNLOADS.md">Downloads</a> ·
  <a href="docs/ROADMAP.md">Roadmap</a> ·
  <a href="docs/VALIDATION.md">Validation</a> ·
  <a href="https://github.com/pilotarbuza/anemosworks/issues">Feedback</a>
</p>

---

## Development Status

**The application is currently in active development. A public Windows EXE installer has not been released yet.**
The core CAD engine and MCP server are operational; the current validated core version is **1.3.0**.
The desktop installer and native UI application are being prepared separately.

This repository serves as the public product showcase: documentation, technical validation, roadmap, and future downloads.
The commercial core engine source code is maintained in a private repository.

---

## CAD Engine Capabilities

- **Parametric Parts & Features**: Generates and edits parametric parts including sketches, constraints, dimensions, extrusions, revolves, patterns, fillets, chamfers, and advanced modeling features.
- **Assemblies & Components**: Manages assembly hierarchies, components, standard mates/joints, and fasteners.
- **Engineering Inspection**: Inspects mass properties, dimensions, interference, rebuild health, and exports standard CAD exchange formats (STEP, IGES, STL, Parasolid).
- **Sheet Metal & Weldments**: Performs supported sheet metal flange operations and structural weldment profiles within CAD adapter capabilities.
- **Feature-Tree Reconstruction**: Reconstructs supported prismatic and revolved solid bodies back into editable feature trees, verified against the original geometry.
- **Model Context Protocol (MCP)**: Exposes 140+ CAD operations as standard tools for compatible AI agents and IDEs.

CAD support varies between platforms: Autodesk Fusion implements **109 of 128 shared CAD operations**.
Drawings, simulation studies, and animated exploded views in Fusion currently have platform-specific constraints.
For detailed operational coverage and restrictions, see **[docs/VALIDATION.md](docs/VALIDATION.md)**.

---

## Operational Modes

| Mode | Target Workflow | Status |
|---|---|---|
| **MCP Server** | CAD automation tools integrated into user-selected AI clients (Claude Desktop, Cursor, etc.) | Core operational; platform packaging and validation ongoing |
| **AnemosWorks App** | Standalone native desktop UI featuring structured tasks, execution history, and direct AI provider integration | In development |

Future releases plan automatic detection of running CAD sessions and dynamic command binding to the active document without manual platform switching.

---

## AI Account & Licensing

AnemosWorks does not resell neural network subscriptions. The application is designed to utilize the user's own AI accounts via provider-authorized integrations or user-supplied API keys. AnemosWorks licensing and third-party AI provider billing remain separate.

Integration targets include Claude (Anthropic), OpenAI, Google Gemini, and Kimi. Subscription usage allowances, account tiers, and supported client protocols depend strictly on the respective AI provider.

Commercial pricing and subscription terms have not been published. Payments are not currently accepted.
CAD host software requires appropriate standalone licenses from their respective vendors.

---

## Downloads & Releases

A public installer is not currently available. Once released, digitally signed Windows installers, release notes, SHA-256 checksums, and setup guides will be distributed exclusively via **[GitHub Releases](https://github.com/pilotarbuza/anemosworks/releases)**.

For notification of future releases, configure **Watch -> Custom -> Releases** on GitHub.
Current status details: **[docs/DOWNLOADS.md](docs/DOWNLOADS.md)**.

---

## Author & Feedback

- **Lead Engineer**: Maksim Akhmadulin ([GitHub Profile](https://github.com/pilotarbuza) · [pilotarbuza.com](https://pilotarbuza.com))
- **Technical Feedback & Issues**: [GitHub Issues](https://github.com/pilotarbuza/anemosworks/issues)

Do not post API keys, access tokens, passwords, or confidential CAD geometry in public issues.

SOLIDWORKS and Autodesk Fusion are registered trademarks of their respective owners.
AnemosWorks is an independent product; references to AI providers and CAD packages do not imply official endorsement or partnership.

Copyright 2026 Maksim Akhmadulin. Terms of use: [LICENSE](LICENSE).
