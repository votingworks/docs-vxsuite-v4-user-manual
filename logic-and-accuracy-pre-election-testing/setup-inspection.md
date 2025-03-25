# Setup Inspection

VotingWorks recommends completing the following setup inspection procedures before, during, or after logic and accuracy testing for each election. All readiness inspection tasks can be completed by an election manager.

## Software Inspection

All users can use [signed-hash-validation.md](../miscellaneous/signed-hash-validation.md "mention") on each device to verify that the software is certified VotingWorks software and has not been tampered with. The software on each device should not change between elections except in cases of VotingWorks-managed upgrades.&#x20;

## Equipment Cleaning & Calibration

All devices with a scanner (VxScan, VxCentralScan, and VxMark) should be cleaned and VxScan double sheet detection should be calibrated.

## Equipment Readiness Inspection

Election managers can use each device's diagnostic interface to confirm the machine is ready for an election. The diagnostic interfaces and the exportable readiness reports are documented for each device in [vxadmin-diagnostics.md](../vxadmin-system-setup/vxadmin-diagnostics.md "mention"), [vxscan-diagnostics.md](../vxscan/vxscan-diagnostics.md "mention"), [system-administrator-functions-and-system-diagnostics.md](../vxmark/system-administrator-functions-and-system-diagnostics.md "mention"), and [vxcentralscan-diagnostics.md](../vxcentralscan/vxcentralscan-diagnostics.md "mention"). For each device:

* [ ] verify configuration information matches election
* [ ] verify storage capacity is greater than 90%
* [ ] on the central system only, verify battery level is greater than 90%
* [ ] on the central system only, verify device is charging when connected to power
* [ ] perform all available hardware diagnostic tests
* [ ] export a readiness report to a USB drive

Successfully completing all tests and producing a complete readiness report also confirms that all necessary cabling is functioning.&#x20;

In addition to the readiness report, election managers should validate that vote counters are zero and ballot boxes are empty:

* [ ] VxAdmin - _Reports > Ballot Count_
* [ ] VxScan - _Sheets Scanned_
* [ ] VxScan - Ballot Box Visual Inspection
* [ ] VxCentralScan - _No ballots have been scanned._
* [ ] VxMark - _Ballots Printed_
* [ ] VxMark - Ballot Box Visual Inspection

## USB Drive Inspection

USB drives should be properly formatted and free of data from previous elections before pre-election testing. While it is possible to inspect the USB drives manually on most computers, VotingWorks recommends simply using the [usb-formatting.md](../vxadmin-system-setup/usb-formatting.md "mention") feature on VxAdmin to ensure all drives are formatted and clear.&#x20;

## Consumables Inspection

All required consumable levels should be checked:

* [ ] VxAdmin
  * [ ] toner level is greater than 10% (included in readiness report)
  * [ ] paper is loaded, sufficient for printing your expected number of reports
* [ ] VxScan
  * [ ] thermal paper roll is loaded (included in readiness report)
* [ ] VxMark
  * [ ] thermal ballot paper supply is sufficient for expected number of voters
  * [ ] headphone ear cover supply is sufficient for expected number of voters&#x20;

## Backup Power Inspection

All backup power supplies (also known as UPSs for uninterruptible power supplies) must be fully charged. When fully charged, backup power supplies will allow powering devices for approximately four hours without power. Even when fully charged, however, backup power supplies should be connected to a standard 120V wall outlet to avoid draining the battery unnecessary.

To confirm that the charge is full before an election, check the LED display. On the Anker Solix C300, tap the power button to illuminate (or hide) the display. On the APC BN1500M2, press any button to illuminate the display. Refer to the user manual provided with your UPS for more information if needed.

## Factory Seal Inspection

While most seals are applied during the course of an election, some seals are applied when the device is first manufactured. These factory seals are intended to be permanent except in cases where VotingWorks performs a repair. The presence of each factory seal should be confirmed before each election as a check against hardware tampering.

VxAdmin and VxCentralScan have one factory seal that wraps around the right side of the laptop. VxScan has three factory seals: bottom left panel, bottom right panel, top panel. VxMark has one behind the touchscreen.&#x20;

All seals should have an identifier beginning with `VX-` and should appear whole and free of defects.

## Setup Inspection Checklist

The setup inspection procedures described above are intended to be completed before, during, or after logic and accuracy testing for each election _in addition to_ the jurisdiction-specific logic and accuracy testing which validates the election configuration, the ballots, and full system operation. The steps below may be completed in a variety of orders depending on your logic and accuracy procedures:

* [ ] Complete [signed-hash-validation.md](../miscellaneous/signed-hash-validation.md "mention") on all devices to verify that only certified software is installed
* [ ] Calibrate [#double-sheet-detection](../vxscan/scanner-management.md#double-sheet-detection "mention") on VxScan for the upcoming election's ballot paper weight
* [ ] Clean scanners for each VxScan, VxCentralScan, and VxMark
* [ ] Complete an [#equipment-readiness-inspection](setup-inspection.md#equipment-readiness-inspection "mention") for each device
* [ ] Format all USB drives as part of the [#usb-drive-inspection](setup-inspection.md#usb-drive-inspection "mention")
* [ ] Confirm backup power supplies are at full charge
* [ ] Confirm factory seals are present for each device

{% hint style="warning" %}
If these checks are not completed prior to election day, there's a risk that the system will not work properly.&#x20;

* Software hash checks and hardware seal checks protect against tampering
* Calibrating and cleaning scanners ensures proper ballot handling and interpretation
* Equipment readiness inspection ensures the equipment will function on election day
* Charging batteries ensures the system will function during a power outage
* Checking consumables ensures voting and reporting will not be hampered by a lack of supplies
{% endhint %}
