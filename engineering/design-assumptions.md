# Design Details, Assumptions and Open Items

## Details confirmed by the project owner

- The conveyor was physically fabricated and demonstrated.
- The belt material was polyester.
- A stepper motor was used.
- The motor was connected to one side roller using a direct coupling device.
- Robotic-arm integration was planned, not completed.
- No formal performance testing was documented.

## Motor torque wording

The project owner described the motor as having “4.2 kg torque.” The exact unit and motor datasheet have not been recovered. Torque is normally specified with a force-length unit, for example kgf·cm or N·m. It would be unsafe to assume which unit was intended.

Until the motor nameplate or datasheet is checked, this repository records the rating only as:

**Reported motor rating: “4.2 kg torque” (unit unverified).**

Do not use this figure in torque, load or power calculations until its unit is confirmed.

## Items not established by available evidence

- Motor manufacturer, model, rated voltage and current.
- Exact torque unit and holding torque.
- Roller material and shaft material.
- Bearing model and bearing arrangement.
- Belt thickness, width, length and tensile rating.
- Frame material grade and cross-section.
- Actual payload and maximum load.
- Belt linear speed.
- Pulley/roller effective diameter under belt tension.
- Fabrication tolerances and alignment values.

## Engineering calculations

No original calculations were supplied. Motor sizing, belt tension, shaft stress, bearing life, frame deflection and load-capacity calculations are therefore not presented as completed work.

If calculations are reconstructed later, they must be clearly labelled as retrospective estimates and must list every assumption and input value.
