<p align="center">
  <img src="assets/banner.svg" alt="AnemosWorks — CAD Automation" width="100%">
</p>

<p align="center">
  [ English | <a href="README.ru.md">Русский</a> ] ·
  <a href="docs/DOWNLOADS.md">Downloads</a> ·
  <a href="docs/ROADMAP.md">Roadmap</a> ·
  <a href="docs/VALIDATION.md">Validation</a> ·
  <a href="https://github.com/pilotarbuza/anemosworks/issues">Issues</a>
</p>

---

AnemosWorks is a CAD automation engine for SOLIDWORKS and Autodesk Fusion. It provides programmatic modeling tools (sketches, features, assemblies, drawings, and geometry checks) through an MCP server and an upcoming desktop application.

## Status

The CAD engine and MCP server are working (v1.3.0). The desktop application and standalone installer are in development.

This repository contains public product information, documentation, validation reports, and future release downloads. The core engine is maintained in a private repository.

## Capabilities

- **Parametric parts**: 2D/3D sketches, constraints, dimensions, extrusions, revolves, sweeps, lofts, fillets, chamfers, patterns.
- **Assemblies**: component insertion, standard mates/joints, hardware fasteners, and interference checks.
- **Inspection & Export**: mass properties, bounding boxes, rebuild checks, STEP/IGES/STL/Parasolid export.
- **Sheet metal & Profiles**: sheet metal flanges and structural weldment profiles.
- **Feature reconstruction**: converts supported prismatic and revolved solid bodies into editable feature trees with geometric deviation checks.
- **MCP interface**: 140 CAD tools exposed over standard Model Context Protocol.

Autodesk Fusion implements 109 of 128 shared CAD operations. Drawings, FEA studies, and animations in Fusion currently have platform limits. See [docs/VALIDATION.md](docs/VALIDATION.md).

## Modes of Operation

1. **MCP Server**: runs as a local tool provider for compatible clients (Claude Desktop, Cursor, and other MCP environments).
2. **AnemosWorks App**: standalone desktop client with task history, active CAD session detection, and direct document binding (in progress).

## Releases

When ready, signed Windows installers will be distributed through [GitHub Releases](https://github.com/pilotarbuza/anemosworks/releases). Current details: [docs/DOWNLOADS.md](docs/DOWNLOADS.md).

## Author

Maksim Akhmadulin — [pilotarbuza.com](https://pilotarbuza.com)  
Issues & suggestions: [GitHub Issues](https://github.com/pilotarbuza/anemosworks/issues)
