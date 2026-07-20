# ATMC.App.KMC.H5.ChassisBoltTorque

Chassis bolt torque jarayonini monitoring qilish va sifat nazorati uchun Windows desktop ilovasi.

## Overview

This repository is a public portfolio page for the **ChassisBoltTorque** project. The production source code is intentionally not included because the application belongs to an industrial automation environment.

## What the application does

Chassis bolt torque bosqichida o'lchov va stansiya natijalarini yig'ib, me'yorga mosligini tekshiradi.

## Main features

- Torque nazorat jarayoni uchun operator interfeysi
- PLC/robot stansiyasi bilan integratsiya
- Sifat natijalarini OK/NG formatida baholash
- Result log va DB yozuvlari uchun strukturalangan natija

## How it works

1. The operator starts the Windows desktop application at the station.
2. The application loads station/model settings and waits for the production cycle.
3. PLC/robot/vision-related signals and scan results are collected during the cycle.
4. Registration or measurement results are evaluated against configured tolerances.
5. The application shows OK/NG status on the dashboard and prepares result data for logs/database storage.

## Technologies and methods used

- C# and .NET Framework 4.8
- Windows Forms desktop UI
- Industrial PLC communication layer
- Robot/automation integration
- Vision/3D registration result processing
- Result logging and database-oriented save flow
- Operator dashboard for production-line monitoring

## Media

Screenshots and short demo videos can be added later without exposing source code.

### Screenshots

Put image files here:

``text
media/screenshots/
``

Recommended names:

``text
media/screenshots/main-dashboard.png
media/screenshots/result-screen.png
media/screenshots/settings-screen.png
``

After adding screenshots, replace this section with Markdown image links, for example:

``md
![Main dashboard](media/screenshots/main-dashboard.png)
``

### Videos

Put short recordings here:

``text
media/videos/
``

Recommended names:

``text
media/videos/demo-cycle.mp4
media/videos/operator-flow.mp4
``

For GitHub, keep videos short and compressed. If a file is large, upload it through GitHub Releases or link an external demo.

## Repository note

Only documentation and media placeholders are published in this repository. Visual Studio solution files, source code, configuration files, binaries, and build outputs are excluded on purpose.