---
description: How the openMOOF VanMoof S3 repair and service manual is organized.
---

# Manual structure

The manual is divided into six areas. This keeps reusable specifications separate from procedures while giving workshop findings and supporting files a permanent home.

| Area | Purpose |
| --- | --- |
| [Reference](reference/README.md) | Fasteners, torque specifications, tools, connectors, bearings, seals, and spare parts |
| [Disassembly](disassembly/README.md) | Chronological removal procedures |
| [Assembly](assembly/README.md) | Reassembly in reverse order, with links to reference data |
| [Maintenance](maintenance/README.md) | Cleaning, lubrication, inspection, and preservation |
| [Reverse engineering](reverse-engineering/README.md) | Construction, materials, weaknesses, measurements, and community-developed parts |
| [Appendix](appendix/README.md) | Parts lists, photographs, CAD models, and printable files |

## Document identifiers

Use a stable identifier when adding an individual document:

* `REF-###` for reference material
* `DEM-###` for disassembly procedures
* `MON-###` for assembly procedures
* `WAR-###` for maintenance procedures
* `RE-###` for reverse-engineering records

The number identifies the document and should not be reused if a page is later removed. Human-readable filenames and titles should follow the identifier.

## Procedure records

Record the following information whenever it is known and applicable:

| Field | Description |
| --- | --- |
| Tool | Required wrench, socket, bit, puller, or other tool |
| Torque | Manufacturer specification or a value verified in practice; clearly identify which |
| VanMoof part number | Original part number, if known |
| Related chapter | Relevant disassembly or assembly procedure |
| Photograph | A reference image that clearly identifies the part or fastener |

{% hint style="warning" %}
Do not present an estimated torque or an unverified part identification as a manufacturer specification. Label the source and verification status of workshop data.
{% endhint %}
