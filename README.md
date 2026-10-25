# Industrial Factory Electrical Engineering — Revision C

**Portfolio study | Preliminary design — NOT FOR CONSTRUCTION**

A hypothetical Sri Lankan light-manufacturing and packaging facility (2,200 m²) with a candidate 630 kVA, 11/0.4 kV transformer, nine active motors, two MCCs, lighting and office distribution.

## Deliverables
- `calculations/Industrial_Engineering_RevC.xlsx`: design basis, motor register, demand study, feeder schedule, protection coordination register, panel schedule, MCC I/O, routing, BOQ, hold points.
- `drawings/01_...dxf`: distribution SLD.
- `drawings/02_...dxf`: DOL power and functional control schematic.
- `drawings/03_...dxf`: star-delta functional sequence.
- `drawings/04_...dxf`: VFD feeder and I/O interface.
- `drawings/05_...dxf`: factory equipment and cable routing concept.
- `drawings/06_...dxf`: Rev B lighting reference.

Open DXF drawings using **LibreCAD**. Drawings are editable CAD entities.

## Scope and limitations
This is a **design exercise**, not a surveyed site, certified protection study or approved installation. Motor nameplate data, 11 kV utility interface, actual cable routes, earthing, fault levels, protective-device discrimination, safety functions, fire requirements and supplier quotes are not verified. Cable and breaker sizes are intentionally not invented. The factory plan is conceptual and not to scale. Motor starter schematics are educational functional representations, not construction wiring diagrams.

## Engineering approach
1. Establish motor and auxiliary connected loads.
2. Calculate input kW and nominal motor full-load current from assumed efficiency and power factor.
3. Apply provisional coincidence factors and evaluate transformer demand.
4. Identify feeders, panels, routing assumptions and protection hold points.
5. Develop functional DOL, star-delta and VFD control diagrams.
6. Obtain site/utility/manufacturer data before final coordination.

## Suggested repository
`industrial-factory-electrical-design`
