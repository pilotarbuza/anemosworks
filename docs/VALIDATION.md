# Validation

[ English | [Русский](VALIDATION.ru.md) ]

State as of 29 October 2026, engine version 1.3.0. The results cover the CAD engine and the MCP integration. The desktop installer has not been released.

| Check | Result |
|---|---|
| Python unit and integration tests | 326 passed |
| Live Autodesk Fusion run (2706.1.14) | 284 assertions, 0 errors |
| Timeouts, retries and cancellation | 11 tests, 0 errors |
| Fusion cloud configurations | 7 stages passed, including switching configurations and cleaning up test data |
| Fresh MCP session over stdio | 140 tools; 109 Fusion CAD operations available, 19 explicitly unavailable |
| Ruff and distribution packaging | Passed |

## What Fusion can't do yet

- 12 drawing operations, 5 simulation and motion studies and 2 exploded-view animation commands are not available in the Fusion adapter.
- Ribs and sheet metal contour flanges use Fusion preview APIs, so they depend on Fusion updates.
- Switching configurations needs a design saved to the cloud and a license that allows it.
- Feature reconstruction works on the supported shapes only. It cannot recognize arbitrary geometry.
- Complex intersections of several weldment beams still need work.
- A CAD call that is already running can't be stopped safely. Cancelling protects the queue and keeps the next commands from being sent.

Passing tests don't mean any model will come out right. A qualified engineer must check critical dimensions, mates, tolerances, drawings and stress results before anything goes to manufacturing.

[Back to the overview](../README.md)
