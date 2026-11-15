# Compact Rat-Race Hybrid Coupler — CST Simulation

**Microwave Engineering · RF design / CST Studio Suite**

Design and electromagnetic simulation of a **conventional 180° rat-race hybrid coupler** and a **miniaturized version with T-shaped stubs**. The work compares physical layout, S-parameters, and output phase relationships near a target design frequency of **2.2 GHz**.

| Conventional model | Miniaturized model |
| --- | --- |
| ![Standard rat-race](Normal%20Screen/Screenshot%201.png) | ![Compact rat-race](Mini%20Screen/Screenshot%201.png) |

## Design approach

- Designed a conventional planar hybrid coupler on an **FR-4 substrate** (reported relative permittivity approximately **4.3**, thickness **1.57 mm**).
- Developed a smaller configuration using **T-shaped stubs / equivalent transmission-line sections**, following literature on compact rat-race couplers.
- Simulated both structures in **CST Studio Suite**.
- Compared scattering parameters and relative phase behavior at the ports, alongside the physical footprints of the two structures.

## Files

| File or folder | Contents |
| --- | --- |
| `CST files/Normal_RRHC.cst` | Conventional CST model |
| `CST files/Mini_RRHC.cst` | Miniaturized CST model |
| `Normal Screen/` | Conventional-model layout and result screenshots |
| `Mini Screen/` | Compact-model layout and result screenshots |
| `docs/report-redacted.pdf` | Full design calculations and simulation discussion; student number removed |

## Explore or reproduce

1. Open the `.cst` models in **CST Studio Suite** (original screenshots indicate **CST Studio Suite 2025**).
2. Inspect the geometry, substrate, ports, and solver setup.
3. Run the electromagnetic simulations and compare the simulated S-parameters and output phases.
4. See the redacted course report for the design calculations and original comparisons.

## Scope and limitations

This is a **simulation-based coursework design**, not a fabricated or experimentally measured coupler. Performance and size comparisons should be understood in the context of the supplied CST models and report; no measured hardware results are claimed.

**Author:** Sina Hemmati · B.Sc. Electrical Engineering (Telecommunications), K. N. Toosi University of Technology.
