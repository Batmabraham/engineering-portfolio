# Tasks and Open Questions

This file tracks pending work, questions, and preliminary suggestions. Update completion here. The [design brief](design-brief.md) defines the design; the [decision log](decision-log.md) records decisions and their reasoning.

## Define the application and requirements

- [ ] Choose a physically specified industrial pipe scenario or a hypothetical frame with simplified loads.
- [ ] Define pipe diameter, wall thickness, material, contents, and supported length.
- [ ] Define pipe position, attachment, and load transfer to the beam.
- [ ] Establish span, height, clearance, and access needs.
- [ ] Derive gravity loading, including pipe, contents, hardware, insulation where applicable, and frame self-weight.
- [ ] Justify the lateral load scenario, magnitude, direction, and application point.
- [ ] Select connection and base assumptions.
- [ ] Select material grade and strength-checking approach.
- [ ] Establish justified vertical deflection and lateral displacement limits.
- [ ] Define compression-member and out-of-plane stability checks appropriate to scope.
- [ ] Choose the comparison objective: structural mass, cost, or another measure.
- [ ] Decide whether to include inclined struts connecting near the beam midpoint.
- [ ] Choose spreadsheet or MATLAB for the computational model.

## Analysis and verification

- [ ] Develop the load cases and hand calculations.
- [ ] Build the computational model and document inputs, units, and reproduction instructions.
- [ ] Check units, equilibrium, and suitable reference cases against hand calculations.
- [ ] Examine sensitivity to connection assumptions and member properties.
- [ ] Compare alternatives and document resulting design revisions.
- [ ] Record calculated results, member selections, verification evidence, and limitations.

## Presentation and portfolio

- [ ] Add drawings and comparison figures.
- [ ] Prepare the six-minute presentation for the November 8, 2026 deadline; presentations begin November 9.
- [ ] Review the READMEs with Thomas.
- [ ] Update the portfolio summary to reflect the evidence produced.

## Preliminary suggestions retained for discussion

These originated in AI-assisted brainstorming. They are not approved requirements, derived loads, or verified inputs.

| Topic | Suggestion |
| --- | --- |
| Span and height | 2.0 m each |
| Material | Carbon structural steel; no grade selected |
| Vertical pipe load | 2,000 N, illustrative only |
| Horizontal load | 400 N, illustrative only |
| Baseline restraint | Rigid beam-to-column joints and fixed bases |
| Initial model | Static, in-plane |
| Pipe position | Beam midpoint |
| Objective | Minimize structural mass subject to performance criteria; assess installed cost separately |
| Additional alternative | Inclined struts connecting near the beam midpoint |

When a proposal is adopted, record the decision and its basis in the decision log and the resulting design requirement in the brief. Completing a task alone does not require rewriting either document.
