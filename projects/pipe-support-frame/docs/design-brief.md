# Design Brief

## Purpose

Investigate a small industrial pipe-support structure through the engineering design loop: define the problem, research, compare alternatives, select and model a preliminary design, verify its performance, and improve it.

## Selected direction

- Baseline: two columns supporting a horizontal beam.
- Investigate combined vertical and lateral performance.
- Compare the baseline with diagonal bracing.
- Define geometry, loads, and performance requirements before calculations.

## Requirements still to be established

| Item | Information needed |
| --- | --- |
| Supported pipe | Diameter, wall thickness, material, and contents |
| Supported length | Pipe length whose weight is carried by this frame, justified by the support arrangement |
| Load transfer | Pipe position, attachment, and how forces enter the beam |
| Geometry | Span, height, clearance, and access needs |
| Gravity loading | Pipe, contents, hardware, insulation if applicable, and frame self-weight |
| Lateral loading | Physical scenario, force magnitude, direction, and application point |
| Connections and bases | Modeling assumptions and limitations |
| Strength | Material grade and the selected design/checking approach |
| Serviceability | Justified vertical deflection and lateral displacement limits |
| Stability | Compression-member and out-of-plane checks appropriate to scope |
| Objective | Whether to prioritize structural mass, cost, or another measure |

## Alternatives

| Arrangement | Question to investigate |
| --- | --- |
| Unbraced two-column frame | Can a defined moment-resisting system meet the requirements efficiently? |
| Diagonally braced frame | How much does bracing change lateral performance, material use, and access? |
| Frame with inclined struts to the beam | Does intermediate vertical support improve the design enough to justify added members and connections? |

The third alternative remains optional. Do not assume that X-bracing supplies an intermediate vertical beam support.

## Proposed starting assumptions — not approved requirements

| Parameter | Preliminary suggestion | Status |
| --- | --- | --- |
| Beam span | 2.0 m | Unconfirmed |
| Frame height | 2.0 m | Unconfirmed |
| Material | Carbon structural steel | Grade unselected |
| Vertical pipe load | 2,000 N | Illustrative; derive from the pipe scenario |
| Horizontal load | 400 N | Illustrative; justify a physical scenario |
| Baseline joints and bases | Rigid joints and fixed bases | Modeling proposal; not a connection design |
| Initial model | Static, in-plane | Scope proposal |
| Pipe position | Beam midpoint | Unconfirmed |

These values came from preliminary AI-assisted discussion. They must not be presented as derived loads, approved requirements, or verified design inputs.

## Verification plan

Before accepting computational results, check units and equilibrium, compare appropriate simplified cases against hand calculations, and examine sensitivity to connection assumptions and member properties. Record what was checked and any discrepancies.

## Immediate next step

Decide whether the loading will come from a physically specified industrial pipe scenario or a deliberately hypothetical structural example. Then establish the pipe specifications and supported load.
