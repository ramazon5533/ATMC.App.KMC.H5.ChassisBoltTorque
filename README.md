# Chassis Bolt Torque Monitoring

A Windows desktop application for monitoring chassis bolt torque operations and quality-control results.

## Overview

This repository presents **ATMC.App.KMC.H5.ChassisBoltTorque** as a public portfolio project. The production source code is intentionally not included because the application belongs to an industrial automation environment.

## Project Purpose

The application collects station and measurement results during the chassis bolt torque process, evaluates whether the operation meets configured limits, and shows the result to the operator.

## Key Features

- Operator interface for torque process monitoring
- PLC/robot station integration
- Quality result evaluation in OK/NG format
- Structured result flow for traceability and reporting

## Workflow

1. The operator starts the Windows desktop application at the production station.
2. The application loads station and model settings for the current operation.
3. PLC, robot, sensor, and vision-related results are collected during the production cycle.
4. Registration or measurement results are evaluated against configured tolerances.
5. The dashboard shows station status and the final OK/NG result.
6. Structured result data is prepared for logs, database records, and quality traceability.

## Technologies and Methods

- C# and .NET Framework 4.8
- Windows Forms desktop interface
- Industrial PLC communication
- Robot and automation-system integration
- Vision and 3D registration result processing
- Production result logging
- Database-oriented quality-control records
- Operator dashboard design for manufacturing environments

## Media Placeholders

Screenshots and short demo videos can be added later without exposing source code.

### Screenshots

Place screenshots in:

`	ext
media/screenshots/
`

Recommended file names:

`	ext
media/screenshots/main-dashboard.png
media/screenshots/result-screen.png
media/screenshots/settings-screen.png
`

After adding screenshots, you can display them in this README like this:

`md
![Main dashboard](media/screenshots/main-dashboard.png)
`

### Demo Videos

Place short screen recordings in:

`	ext
media/videos/
`

Recommended file names:

`	ext
media/videos/demo-cycle.mp4
media/videos/operator-flow.mp4
`

For GitHub, videos should be short and compressed. Large videos can be published through GitHub Releases or linked from an external demo page.

## Confidentiality Note

This repository is documentation-focused. Visual Studio solution files, source code, configuration files, binaries, and build outputs are excluded intentionally. Screenshots and videos should be reviewed before upload so that no private factory data, customer data, IP addresses, credentials, or internal settings are visible.