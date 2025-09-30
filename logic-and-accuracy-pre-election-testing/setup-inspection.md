# Setup Inspection

VotingWorks recommends completing the following setup inspection procedures before, during, or after logic and accuracy testing for each election. All readiness inspection tasks can be completed by an election manager.

## Software Inspection

All users can use [signed-hash-validation.md](../miscellaneous/signed-hash-validation.md "mention") on each device to verify that the software is certified VotingWorks software and has not been tampered with. The software on each device should not change between elections except in cases of VotingWorks-managed upgrades.

## Equipment Cleaning & Calibration

All devices with a scanner (VxScan, VxCentralScan, and VxMarkScan) should be cleaned and VxScan double sheet detection should be calibrated.

## Equipment Readiness Inspection

Election managers can use each device's diagnostic interface to confirm the machine is ready for an election. The diagnostic interfaces and the exportable readiness reports are documented for each device in [vxadmin-diagnostics.md](../vxadmin-system-setup/vxadmin-diagnostics.md "mention"), [vxscan-diagnostics.md](../vxscan/vxscan-diagnostics.md "mention"), [diagnostics.md](../vxmarkscan/diagnostics.md "mention"), and [vxcentralscan-diagnostics.md](../vxcentralscan/vxcentralscan-diagnostics.md "mention"). For each device:

* [ ] Verify configuration information matches election
* [ ] Verify storage capacity is greater than 90%
* [ ] On the central system only, verify battery level is greater than 90%
* [ ] On the central system only, verify device is charging when connected to power
* [ ] Perform all available hardware diagnostic tests
* [ ] Export a readiness report to a USB drive

Successfully completing all tests and producing a complete readiness report also confirms that all necessary cabling is functioning.

## Physical and Digital Storage Location Zero Checks

Election managers should confirm that the VxScan and VxMarkScan ballot boxes are physically empty and that relevant digital storage locations are clear:

* [ ] VxAdmin - _Reports > Ballot Count_ on the election manager screen should be 0
* [ ] VxScan - _Sheets Scanned_ on the election manager screen should be 0
* [ ] VxCentralScan - "No ballots have been scanned" should be displayed on the election manager screen
* [ ] VxMarkScan - _Ballots Printed_ on the election manager screen should be 0

## USB Drive Inspection

USB drives should be properly formatted and free of data from previous elections before pre-election testing. While it is possible to inspect the USB drives manually on most computers, VotingWorks recommends simply using the [usb-formatting.md](../vxadmin-system-setup/usb-formatting.md "mention") feature on VxAdmin to ensure all drives are formatted and clear.

USB drives and the device's internal hard disk are the only voting device storage locations that hold election information that can change during the election. USB drive inspection and the aforementioned storage capacity check as part of [#equipment-readiness-inspection](setup-inspection.md#equipment-readiness-inspection "mention") ensure all storage locations are inspected pre-election.

## Consumables Inspection

All required consumable levels should be checked:

* [ ] VxAdmin
  * [ ] Toner level is greater than 10% (included in readiness report)
  * [ ] Paper is loaded, sufficient for printing your expected number of reports
* [ ] VxCentralScan
  * [ ] Imprinter toner level (toner should be replaced every six months or when unique identifier is not printed legibly scanned sheet)
* [ ] VxScan
  * [ ] Thermal paper roll is loaded (included in readiness report)
* [ ] VxMarkScan
  * [ ] Thermal ballot paper supply is sufficient for expected number of voters
  * [ ] Headphone ear cover supply is sufficient for expected number of voters

## Backup Power Inspection

All backup power supplies (also known as UPSs for uninterruptible power supplies) must be fully charged. When fully charged, backup power supplies will allow powering devices for approximately four hours without power. Even when fully charged, however, backup power supplies should be connected to a standard 120V wall outlet to avoid draining the battery unnecessary.

To confirm that the charge is full before an election, check the LED display. On the GoldenMate 1000VA/600W, tap the power button to illuminate (or hide) the display. On the APC BN1500M2, press any button to illuminate the display. Refer to the user manual provided with your UPS for more information if needed.

## Factory Seal Inspection

While most seals are applied during the course of an election, some seals are applied when the device is first manufactured. These factory seals are intended to be permanent except in cases where VotingWorks performs a repair. The presence of each factory seal should be confirmed before each election as a check against hardware tampering.

VxAdmin and VxCentralScan have one factory seal that wraps around the right side of the laptop. VxScan has three factory seals: bottom left panel, bottom right panel, top panel. VxMarkScan has one behind the touchscreen.

All seals should start with `VX-` and should appear whole and free of defects.

## Setup Inspection Checklist

The setup inspection procedures described above are intended to be completed before, during, or after logic and accuracy testing for each election _in addition to_ the jurisdiction-specific logic and accuracy testing which validates the election configuration, the ballots, and full system operation. The steps below may be completed in a variety of orders depending on your logic and accuracy procedures:

* [ ] Complete [signed-hash-validation.md](../miscellaneous/signed-hash-validation.md "mention") on all devices to verify that only certified software is installed
* [ ] Calibrate [#double-sheet-detection](../vxscan/scanner-management.md#double-sheet-detection "mention") on VxScan for the upcoming election's ballot paper weight
* [ ] Clean scanners for each VxScan, VxCentralScan, and VxMarkScan
* [ ] Complete an [#equipment-readiness-inspection](setup-inspection.md#equipment-readiness-inspection "mention") for each device
* [ ] Format all USB drives as part of the [#usb-drive-inspection](setup-inspection.md#usb-drive-inspection "mention")
* [ ] Confirm backup power supplies are at full charge
* [ ] Confirm factory seals are present for each device

{% hint style="warning" %}
If these checks are not completed prior to election day, there's a risk that the system will not work properly.

* Software hash checks and hardware seal checks protect against tampering
* Calibrating and cleaning scanners ensures proper ballot handling and interpretation
* Equipment readiness inspection ensures equipment will function on election day
* Charging batteries ensures the system will function during a power outage
* Checking consumables ensures voting and reporting will not be hampered by a lack of supplies
{% endhint %}
