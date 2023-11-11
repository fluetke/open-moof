---
description: >-
  The S3 has a knack for throwing error codes at you, that are not explained in
  the manual or the VM app. Here is a list of most known Error-codes and their
  causes.
---

# 🔢 Error codes



## Err 6 - Battery not charging

## Err 12 - Temperature to low

## Err 16 - Communication with battery lost

## Err 17 - Communication with battery lost/no power

## Err 19 - Internal communication error w/ battery

## Err 20 - Unexpected shutdown of battery

This error results from an unexpected battery shutdown, for instance when you're causing a short somewhere in the bikes electrical system.(I did that while tinkering with the shifter) or the battery is going into protection mode for any other reason.

## Err 21 - Charger not detected/Communication error with charger.

## Err 23 -&#x20;

## Err 40 - Bell button issue

This can happen when you keep pressing the Bell button for a long time or very quickly multiple times. This basically means that the bike has detected an irregularity with your bell button, caused by a short or moisture in the button or a broken wire somewhere.

## Err 41 - Boost button issue

This can happen when you keep pressing the Boost button for a long time or very quickly multiple times. This basically means that the bike has detected an irregularity with your boost button, caused by a short or moisture in the button or a broken wire somewhere.

## Err 44 - Communication with eShifter lost

This Error code points to a loss of communication with the bikes electronic shifter. This is often caused by electronic components on the eShifter PCB failing, sometimes by corrosion of parts due to moisture. See [error-44-communication-issues.md](../repair-guides/e-shifter/error-44-communication-issues.md "mention") for a few hints on diagnosing and fixing this error.

## Err 45 - Communication with motor lost

The error 45 often comes paired with error 48 and idicates a communication issue between the smart-cartridge and the bikes hub-motor. This is a tricky one - possible reasons can be a faulty sensor in the hub-motor(see [hub-motor](../repair-guides/hub-motor/ "mention")) or a broken wire in the bikes wiring harness. While the former is easily fixed by replacing the sensor in question, the latter often requires disassembly of the entire bike to replace or fix the  harness (see [full-disassembly.md](../repair-guides/full-disassembly.md "mention"))

## Err 54 - Sim Card issue

This error comes from your bike not being able to communicate with or detect the simcard inside of the smart cartridge.



