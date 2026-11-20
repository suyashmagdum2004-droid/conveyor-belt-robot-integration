# Design and Development of a Belt Conveyor for Robotic Arm Integration

A compact, mechanically driven belt-conveyor project developed as part of an Automation and Robotics diploma programme at Sharad Institute of Technology Polytechnic, Yadrav, Maharashtra, India.

> **Project status:** The conveyor was physically fabricated and demonstrated. Robotic-arm integration was a planned application, not a completed integration. No formal performance-test results are currently available.

## Project overview

The project focused on building a simple conveyor mechanism to move small items along a belt, with the intention of using it as a material-transfer stage for a robotic-arm pick-and-place application.

The prototype used:
- A **polyester conveyor belt**.
- A **stepper motor** as the drive source.
- A **direct coupling device** connecting the motor shaft to the shaft of one end roller.
- Rollers, bearings and a supporting frame.
- A compact layout based on the dimensions recorded in the available project drawing.

The motor drives one roller through the coupling. Rotation of this roller moves the belt around the conveyor path. The opposite roller supports the return path and belt movement.

## Simple mechanism layout

The diagram in [drawings/conveyor-layout.svg](drawings/conveyor-layout.svg) is a simplified explanatory drawing based on the project description. It is not a recovered CAD assembly or a manufacturing drawing.

## Available design information

The sample report contains a conveyor layout drawing and a separate roller drawing. Some dimensions can be read from those drawings, but the complete dimension set and tolerances are not available. See [engineering/recovered-dimensions.md](engineering/recovered-dimensions.md).

## Drive details

The project owner reports a stepper motor with a stated rating of **“4.2 kg torque.”** The original motor datasheet and exact torque unit have not been recovered. This value is therefore recorded as user-reported information only; it must not be treated as a verified torque specification. See [engineering/design-assumptions.md](engineering/design-assumptions.md).

## Robotic-arm application

The conveyor was intended to support material transfer for a robotic-arm application. Physical integration, synchronized control, sensor-based object detection and automated pick-and-place operation were not confirmed as completed parts of this prototype.

## Testing and limitations

The conveyor was physically fabricated and demonstrated. However, no formal records were available for:
- Maximum payload or load capacity.
- Belt speed or speed variation.
- Motor current, temperature or power consumption.
- Continuous operating duration.
- Repeatability, tracking or endurance tests.

No performance figures are claimed in this repository.

## Repository contents

- `drawings/` — simplified explanatory layout.
- `engineering/` — dimensions recovered from the report and notes on assumptions and missing calculations.
- `docs/` — project description and working principle.
- `publication/` — citation for the related published review paper.

## How to use this repository

This repository is a technical portfolio record of a physical mechanical project. It does not contain control software, because the project was primarily mechanical and no original software source was supplied.

## Authorship and evidence note

The recovered information comes from the project sample report and clarifications supplied by the project owner. New explanatory documentation and the simplified SVG layout were prepared for this repository. They should not be mistaken for original CAD files, original fabrication drawings or formal test reports.

## Publication

S. S. Magdum et al., “A Review Design and Development of Conveyor Belt for the Robotics Arm,” *Journal of Mechanical Robotics*, vol. 9, no. 1, pp. 7–11, 2024. Full citation details are in [publication/published-paper.md](publication/published-paper.md).
