---
description: >-
  Part of the Central System, VxCentralScan is used by election administrators
  to rapidly scan ballots.
---

# VxCentralScan Hardware Setup

## Hardware Overview

VxCentralScan is a commercial off-the-shelf (COTS) laptop pre-installed with VxCentralScan software that connects to a batch scanner.

<div><figure><img src="../.gitbook/assets/photo-vxcentralscan-in-cases.png" alt="VxCentralScan in cases" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/photo-vxcentralscan-setup.jpg" alt="VxCentralScan set up with fi-8170" width="375"><figcaption></figcaption></figure></div>

Four models of scanner are supported:

* Ricoh fi-8170 - Small. Recommended maximum batch size of 30 ballots.
* Ricoh fi-7600 - Medium. Recommended maximum batch size of 100 ballots.
* Ricoh fi-8950 - Large. Recommended maximum batch size of 250 ballots.
* interScan DeskPro 631 - Extra-large. Recommended maximum batch size of 250 ballots.

Backup power for the scanner is provided by the APC uninterruptible power supply (UPS).

## Set Up VxCentralScan

VxCentralScan can be set up through the following steps:

1. **Unbox and set up the scanner.** For the Ricoh fi-8170:
   * [ ] Remove the scanner and power cord from the case
   * [ ] Attach and pull out the paper feed guide tray (A)
   * [ ] Pull out the paper holder tray (B)
   * [ ] Plug the USB cord (C) into the back of the scanner and into the USB hub
   * [ ] Plug the power cord (D) into the back of the scanner and into the APC UPS
   * [ ] Plug the UPS into a power outlet
   * [ ] Turn on the UPS
   * [ ] Press the power button (E) to turn the scanner on

   <div><figure><img src="../.gitbook/assets/photo-vxcentralscan-scanner-ricoh-fi8170.jpg" alt="Remove scanner and power cord from case" width="188"><figcaption><p>Remove the scanner and power cord from the case</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo-vxcentralscan-scanner-trays-labeled.jpg" alt="Attach and pull out paper trays" width="188"><figcaption><p>Attach and pull out the paper trays</p></figcaption></figure></div>

   <div><figure><img src="../.gitbook/assets/photo-vxcentralscan-scanner-rear-ports-labeled.jpg" alt="Plug cords in" width="188"><figcaption><p>Plug in the cords</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo-vxcentralscan-scanner-power-button-labeled.jpg" alt="Press the power button to turn on" width="188"><figcaption><p>Press the power button to turn on</p></figcaption></figure></div>

   For the interScan DeskPro 631:
   * [ ] Set up the scanner, including the extended input tray and output hopper if used, as described in the manufacturer's instructions
   * [ ] Plug the USB cord into the back of the scanner and into the USB hub
   * [ ] Plug in the scanner's power cord
   * [ ] Turn the scanner on

2. **Set up the VxCentralScan laptop:**
   * [ ] Remove and document seals as necessary
   * [ ] Open the case by lifting the latches on the front

   <div align="left"><figure><img src="../.gitbook/assets/photo-vxcentralscan-case-seals.png" alt="Closed tan VxCentralScan case with red tamper-evident seals on both latches circled." width="375"><figcaption><p>Remove and document seals as necessary</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo-vxcentralscan-case-latches.png" alt="Closed tan VxCentralScan case with arrows pointing to the two front latches." width="375"><figcaption><p>Lift the latches</p></figcaption></figure></div>

   * [ ] Remove the laptop
   * [ ] Pull the power cord (A) out and plug into the laptop and an outlet
   * [ ] Pull the USB hub (B) out and plug into the laptop
   * [ ] Pull the scanner cord (C) out and plug into the USB hub and the scanner
   * [ ] Turn the laptop on

   <div><figure><img src="../.gitbook/assets/photo-vxcentralscan-laptop-in-case.jpg" alt="Remove laptop" width="188"><figcaption><p>Remove the laptop</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo-vxcentralscan-peripherals-in-case.jpg" alt="Remove components" width="188"><figcaption><p>Remove the components</p></figcaption></figure> <figure><img src="../.gitbook/assets/photo-vxcentralscan-setup.jpg" alt="Plug components in" width="188"><figcaption><p>Plug in the components</p></figcaption></figure></div>

## Pack Up VxCentralScan

To pack up VxCentralScan:

* [ ] Place all of the components back into the case as displayed above
* [ ] Package the batch document scanner
* [ ] Secure the laptop case as required by sealing the eyelets highlighted below

<figure><img src="../.gitbook/assets/photo-vxcentralscan-case-seals.png" alt="Closed tan VxCentralScan case with red tamper-evident seals on both latches circled." width="375"><figcaption><p>Seal the case</p></figcaption></figure>

## Imprinting

All four scanners can be used with an optional imprinter:

* Ricoh fi-8170 - Uses the fi-819PRB. See the [fi-819PRB user guide](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/ricoh-fi-8170/ricoh-fi-819prb-user-guide.pdf) for assembly instructions.
* Ricoh fi-7600 - Uses the fi-760PRB. See the [fi-760PRB user guide](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/ricoh-fi-7600/ricoh-fi-760prb-user-guide.pdf) for assembly instructions.
* Ricoh fi-8950 - Uses the fi-890PRB. See the [fi-890PRB user guide](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/ricoh-fi-8950/ricoh-fi-890prb-user-guide.pdf). The one-time installation must be performed by a Ricoh support technician.
* interScan DeskPro 631 - Uses the HD Rear Imprinter (PN: 6X-IM-SPDPST-R), which prints on each ballot after it is scanned. The one-time installation must be performed by an interScan technician.

For the detachable imprinters, the scanner must be off when attaching the imprinter. After the imprinter is attached, adjust the paper guides on the imprinter to match the paper width of each batch, which is 8.5 in. for hand-marked paper ballots and ballots printed by VxMark, or 8 in. for ballots printed by VxMarkScan.

For all imprinters, adjust the position of the imprinter to ensure that imprinting is done outside of the ballot marking area on each ballot. Test imprinting on blank paper or test ballots before using it on official ballots.

## Scanner Maintenance

Clean the scanner before every election. Replace the rollers occasionally depending on scanning volume. Consult [VxAdmin, VxCentralScan, & VxPrint Maintenance Manual](../system-maintenance/vxadmin-and-vxcentralscan-maintenance-manual.md "mention") for instructions on cleaning and maintaining each scanner.
