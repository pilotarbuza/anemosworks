# Roadmap

[ English | [Русский](ROADMAP.ru.md) ]

This is where development stands today. Nothing here is a promise of a delivery date.

## Done and tested

- One CAD engine and MCP server for both SOLIDWORKS and Autodesk Fusion.
- Parametric modeling, the supported assembly mates and export to several formats.
- Output checks, geometry checks and rollback when a Fusion sketch fails.
- Command timeouts, cancelling queued commands, and protection against a command running twice.
- Version negotiation with the Fusion add-in, with a backup made before every update.

## First desktop release (planned)

- A Windows installer that sets up its runtime dependencies itself.
- Its own interface for running tasks, with history and a chat.
- Finding running CAD sessions automatically.
- Attaching a task to the open document, so you don't pick the CAD system by hand.
- A setup wizard for supported MCP clients.
- Signing in to AI providers through the protocols those providers support.
- AnemosWorks accounts with licensing, device management and in-app updates.

## Later

- Reusable engineering workflows.
- More validation on real mechanical assemblies.
- More CAD versions and AI clients.
- Adapters for other CAD systems, each after its own round of testing.

A website, registration and billing will come later. For now GitHub is the project's public home.

[Suggest a feature](https://github.com/pilotarbuza/anemosworks/issues/new/choose)
