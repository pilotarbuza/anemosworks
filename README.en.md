# AnemosWorks

**AI automation for SOLIDWORKS and Autodesk Fusion.**

[Русский](README.md) · [Downloads](docs/DOWNLOADS.md) · [Roadmap](docs/ROADMAP.md) · [Validation](docs/VALIDATION.md)

## Development status

The CAD engine and MCP server are working. The latest validated engine version is **1.3.0**.
**A public Windows EXE installer has not been released.** The desktop application and installer
are under development. This repository contains public product information, documentation,
roadmap and future downloads. The commercial engine source is maintained privately.

## Capabilities

- Parametric sketches, features, dimensions and model editing.
- Assemblies, supported mates/joints, components and fasteners.
- Geometry inspection, mass properties, rebuild checks and CAD exports.
- Supported sheet-metal operations and structural profiles.
- Verified reconstruction of supported prismatic and revolved bodies into editable features.
- CAD tools exposed through MCP for compatible AI clients.

Fusion currently implements **109 of 128 shared CAD operations**, with explicit restrictions.
This is not full parity with SOLIDWORKS. See [validation and limitations](docs/VALIDATION.md).

## Planned product experience

Two modes share one CAD engine: an MCP server for compatible AI clients and a standalone desktop
application with chat, tasks and history. Automatic discovery of supported CAD sessions and
document-bound routing are planned. These desktop features are not yet released.

Users bring their own AI account through provider-approved integrations or their own API key.
AnemosWorks does not include or resell an AI subscription. Provider subscription access is not
universally available: supported authentication, quotas and eligibility depend on each provider.
Claude, OpenAI, Gemini and Kimi integrations are planned, subject to those requirements.
Users also need appropriate CAD licences.

Pricing is not yet announced and payments are not being accepted.

## Downloads and feedback

The future Windows installer, checksum and installation instructions will be published through
[GitHub Releases](https://github.com/pilotarbuza/anemosworks/releases).
There is currently no public installer to download.

Developed by **Maksim Akhmadulin** · [GitHub](https://github.com/pilotarbuza).
Use [Issues](https://github.com/pilotarbuza/anemosworks/issues) for feedback.
Never include credentials or confidential CAD files in public reports.

AnemosWorks is an independent product. CAD and AI product names belong to their respective owners;
their mention does not imply endorsement or partnership.

© 2026 Maksim Akhmadulin. See [LICENSE](LICENSE).
