# Engineering status and design gates

## Revision C additions
- Individual MCC outgoing feeder schedule for nine motors
- Functional DOL, VFD and star-delta control typicals with E-stop, stop and overload contacts
- Feeder references and protection-coordination checklist
- Equipment locations, provisional cable-tray routes and lighting/emergency zones
- BOQ and verification register

## Example calculation (not final fault study)
630 kVA, 400 V transformer: rated LV current = 630000/(sqrt(3)*400) = 909 A. At assumed 6% impedance, simple transformer-terminal bolted-fault screening current ≈ 15.2 kA. This excludes upstream impedance, tolerance, motor contributions, cable impedance and actual earthing/fault conditions. Never select breaking capacity from this approximation alone.

## Hold points before detailed design approval
1. Actual building architectural plan, dimensions, equipment locations, environmental classification and cable routes.
2. Motor manufacturer data, actual motor efficiency, power factor, duty and starter compatibility.
3. Utility supply requirements, transformer impedance, protection and short-circuit study.
4. Earthing arrangement, loop impedance, disconnection times and residual-current strategy.
5. Cable ampacity tables, grouping, installation method, voltage drop, thermal fault withstand.
6. Protection manufacturer curves, breaking capacity, overload settings and discrimination study.
7. Safety-rated emergency stop design, STO validation and functional safety assessment.
8. Photometric lighting model, emergency egress requirements and regulatory approval.
9. Supplier RFQs, itemized quantities, VAT and labor rates.

## Scope note
This package is intended for demonstration of engineering workflow, not procurement or construction.
