# Motor Dynamics

**Modular BLDC motor platform — one motor core, configurable into a standalone controller, a standalone motor, or a complete high-torque cycloidal actuator.**

Built for Egypt's growing robotics and industrial automation sector, which currently depends almost entirely on imported actuator modules ($27K–35K per unit, long lead times, no local service).

## What we're building

| Layer | Product |
|---|---|
| 01 | Standalone BLDC motor (custom-wound, N52 magnets) |
| 02 | Motor + cycloidal/planetary gearbox |
| 03 | Motor + embedded FOC controller + CAN (smart motor) |
| 04 | Complete integrated actuator (motor + gearbox + control + sensing) |

## Current stage

Concept moving into engineering validation. No finished physical MVP yet — see [`/docs/roadmap.md`](docs/roadmap.md) for the path to a validated motor prototype.

Originated from a graduation project (BLDC Cycloidal Actuator, Ain Shams University, Mechatronics Engineering) — see [`/docs/architecture.md`](docs/architecture.md) for the full technical architecture (electromagnetic design, FOC control, power electronics, CAN/telemetry, validation plan).

## Team

| Function | Owner |
|---|---|
| Mechanical & structural engineering | Abdelrahman Hany |
| Power electronics & thermal engineering | Ibrahim Fayez |
| Embedded systems, FOC & motor control | Tarek Salem |
| Systems integration & software | Yusuf Amr |

## Why Egypt

Local design and manufacturing of motors, reducers, drives, and sensing reduces dependence on imported actuator modules, foreign-currency exposure, long lead times, and difficult overseas maintenance — supporting Egypt Vision 2030's industrial and technology-transfer priorities.

---
*SmartX Hackathon 2026 — Smart Industry track*
