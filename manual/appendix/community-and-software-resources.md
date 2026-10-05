# Community and software resources

This page collects external projects that are useful when repairing, diagnosing, or reverse engineering VanMoof bikes.

> **Naming note:** Several unrelated projects use the name **OpenMoof**. They should not be treated as the same project.

## OpenMoof firmware project

- Website: https://openmoof.com/
- GitHub organization: https://github.com/openmoof

The **OpenMoof GitHub organization is a separate project from Bernardus/openmoof**. It was initiated by **Revotronics** with the goal of developing an open-source firmware ecosystem for VanMoof bikes.

For the S3/X3, the project has publicly described work on replacement/custom firmware and an accompanying app. Public project updates describe working control of core bike functions including the motor, battery, e-shifter, matrix display, lights, sound, buttons, and kick lock, with additional diagnostic and configuration features under development.

Because this work is actively evolving, firmware behavior, installation procedures, compatibility, and release status should be checked against the current OpenMoof project documentation before use.

**Relevance to this handbook:** firmware replacement, diagnostics, Smart Cartridge research, bike communication, and long-term independence from proprietary VanMoof software.

## Bernardus/openmoof

- Repository: https://github.com/Bernardus/openmoof

Bernardus/openmoof is an **independent community resource collection** started in 2023. It collects links to projects intended to keep VanMoof bikes operational, including Bluetooth tools, alternative apps, repair information, e-shifter work, manual-shifter conversions, patents, and community resources.

Despite the similar name, it is **not the OpenMoof firmware project / GitHub organization described above**.

**Relevance to this handbook:** historical community links and discovery of repair/reverse-engineering projects.

## VanMoof reverse-engineering tools

- Repository: https://github.com/chwdt/vanmoof-tools

vanmoof-tools contains tools and technical notes for S3/X3 firmware reverse engineering. It documents known firmware images and their target controllers, including the Smart Cartridge main MCU, Bluetooth MCU, motor-control MCU, e-shifter MCU, and battery/BMS firmware.

**Relevance to this handbook:** firmware formats, MCU identification, internal communication, debug interfaces, and Smart Cartridge reverse engineering.

## VanMoofSelfRepair

- Community: https://www.reddit.com/r/VanMoofSelfRepair/

A major source of practical repair reports, measurements, component identification, board-level repairs, wiring information, and failure analysis. Community claims should be independently verified where possible before being marked as confirmed in this handbook.

## Source handling in openMOOF

External information should be classified according to evidence quality:

- **[BESTÄTIGT]** — verified by measurement, direct observation, manufacturer documentation, or multiple sufficiently independent sources.
- **[UNSICHER]** — plausible community information that has not yet been independently verified.
- **[ZU PRÜFEN]** — useful lead requiring measurement or further research.
- **[ABGELEITET]** — technical conclusion derived from observations rather than directly observed.

When similarly named projects exist, always record the exact repository or organization URL so that attribution remains unambiguous.
