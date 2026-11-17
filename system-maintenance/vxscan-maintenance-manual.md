# VxScan Maintenance Manual

For reference information on VxScan, see the following links:

* **Hardware Overview -** [VxScan Hardware](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/vxscan-hardware "mention")
* **Software Functionality -** [VxScan Function](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/vxscan-function "mention")

## Hardware Maintenance

Review the warnings and cautions listed below first. Then below that, find specific recommendations about scanner cleaning, printer paper, and other maintenance.

### Warnings

1. **Never** try to perform complex repairs on VxScan.
2. The top and bottom panel are sealed. The screen and the speaker are sealed under the top panel, and the computer and USB hub are sealed under the bottom left panel. Do **not** remove the seals or panels. Only VotingWorks should perform repairs that require removing panels.
3. Keep the scanner clean, the printer paper loaded, and the screen and USB ports clean.
4. **Never** disconnect the cables inside the unit, which can be seen after opening the poll worker door and scanner access door (see photo below). You should never need to handle these cables, and you should never handle them while the unit is plugged in. These cables are normally connected securely and safely. However, if any of these cables are disconnected or loosened in any way, then note how it happened and how the machine was behaving at the time, and then contact VotingWorks with these details to confirm how to proceed. If the power was on when a cable was disconnected, then power down the machine before continuing to use it or before making any more changes. If the power was off when a cable was disconnected, still confer with VotingWorks before proceeding.

<figure><img src="../.gitbook/assets/photo-vxscan-scanner-internal-cables.jpg" alt="Photo of cables seen after opening scanner access door.  From left to right on the scanner metal: ribbon cable, twisted pair of wires, and a single wire. On the far right: another single wire connected to the scanner access door." width="375"><figcaption><p>Do not disconnect, cut, unplug, or remove these cables or wires</p></figcaption></figure>

5. The VxBox unit used with VxScan should be stored in a climate-controlled environment when possible, and never in conditions hotter than 90 °F.  Extended periods of heat can weaken the hinges.

### Scanner Cleaning

Clean the scanner for every election, before pre-election testing and again after pre-election testing. For instructions, see [Scanner Management](../vxscan/scanner-management.md "mention") in the user manual. VotingWorks recommends using Ricoh Cleaner F1 (PN: PA03950-0352) with cleaning wipes (PN: CG90000-120001) or equivalent. You can also use other scanner-specific cleaning fluids or greater than 70% isopropyl alcohol for the cleaning fluid, and a microfiber or lint-free cloth for the wipe. You may also blow out paper dust from the scanner with compressed air after wiping.

If the software detects streaks in a scanned ballot, VxScan alerts you and prompts you to clean the scanner. To identify streaks proactively, an election manager or system administrator can perform a test scan in the diagnostics interface. For instructions, see the [VxScan Diagnostics](../vxscan/vxscan-diagnostics.md "mention") article.

If the scanner is not used for an election, then the scanner should still be cleaned after approximately 15,000 scans or every 6 months, whichever comes first. After 100,000 scans, VotingWorks recommends inspecting the scanner rollers and cleaning them using wipes and alcohol as mentioned above, if they were not cleaned previously.

### Printer Paper Management

VxScan features a full letter-width report printer. In order for VxScan to print reports, it must be properly loaded with a thermal paper roll. Polls cannot be opened or closed without the paper installed. The thermal paper rolls are provided by VotingWorks. While it is possible to use thermal rolls from another vendor that meet the requirements specified in the [Approved Parts List](approved-parts-list.md "mention"), it is not recommended.

The thermal paper rolls are 78 ft in length. The amount of paper used depends on the number of reports printed and the number of contests appearing on the report. 78 ft is enough for an entire election, including pre-election testing, in almost all cases. VotingWorks recommends replacing the thermal paper roll once for each election. You may choose to reuse rolls between elections, but doing so greatly increases the risk of running out of paper in the middle of an election. In those situations, an unprepared poll worker may have to replace paper or wait for an election administrator.

Replacing the paper roll is generally performed by an election manager, but may also be performed by a system administrator, a technician, or in rare cases a poll worker. VxScan guides you through loading paper. For additional instructions, see the [Printer Management](../vxscan/printer-management.md "mention") article in the user manual.

When the scanner is not in use between elections, the thermal paper roll should be left loaded in the scanner to protect the thermal printer head.

### Other Maintenance Tasks

VotingWorks recommends cleaning the screen and USB ports as needed. Clean the screen by gently wiping it with cleaning wipes, such as ULINE S-12236 or equivalent. Clean the USB ports by blowing them out with air in a can, such as ULINE S-6771 or equivalent, from a distance of at least one foot. Read all manufacturer safety instructions before using air in a can.

### Long-Term Hardware Maintenance

To keep a VxScan machine functioning smoothly over many years, VotingWorks recommends servicing it periodically after every 100,000 scans or every 3 years, whichever comes first. At these intervals, the following preventative maintenance tasks can be done:

* [Clean the scanner glass and rollers](vxscan-maintenance-manual.md#scanner-cleaning) (you can do this yourself)
* [Recalibrate the image sensors](../vxscan/scanner-management.md#image-sensor-calibration) (you can do this yourself)
* Test the scanner speed and recalibrate it if needed (a VotingWorks technician should do this)

Contact VotingWorks support to schedule help with long-term maintenance tasks.

## Ballot Box (VxBox) Maintenance

The ballot box that works with VxScan requires little maintenance, but it should be inspected and cleaned as needed for every election before pre-election testing and again after pre-election testing. Inspection confirms that it works as expected and checks for debris in or on the ballot box. Cleaning should remove debris from inside the ballot box bag and inside the emergency bin. The plastic surfaces can also be wiped down with a lint-free wipe, or equivalent.

## Software Maintenance

There are no required steps for maintaining the software or firmware. The software is installed by VotingWorks and cannot be modified. The underlying databases for all applications are self-maintaining, so you don't need to tune them.

## Data Maintenance

As VxScan is used for an election, it gradually stores more and more ballot data. As long as you stay within the specified [System Limits](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-performance-and-specifications/system-limits "mention"), VxScan shouldn't exceed its data limits. System administrators and election managers can see the free disk space available on VxScan by selecting `Diagnostics` from the side menu.

When you unconfigure the machine or clear ballot data, the disk space is recovered. The free disk space may not appear to return to 100%, but new files eventually replace old files and the disk space is reused.

VotingWorks recommends that all cast vote records (CVRs) are backed up to a USB drive before being cleared from the application. As ballots are scanned, cast vote records are automatically backed up to the attached USB drive. If an additional backup is required, an election manager can separately save CVRs.

## Maintenance Support & Spare Recommendations

VotingWorks recommends having scanner cleaning supplies immediately available at all times. If streaking is detected in the scanned images, the scanner must be cleaned to continue scanning. To avoid delays in voting, keep scanner cleaning supplies at all voting locations.

VotingWorks recommends having extra thermal paper rolls easily available at all times. If thermal paper runs out, the polls cannot be opened or closed until paper is reloaded. Pre-election testing typically prevents paper issues, but it may still occur when election managers do not load new rolls for each election. Extra thermal paper rolls should either be available at every voting location or transportable to voting locations within a reasonable time window.
