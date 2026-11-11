# VxScan Diagnostics

The diagnostics interface is used to test hardware before or between elections and monitor the status of the machine. It is accessible from both the election manager and system administrator menus.

<div><figure><img src="../.gitbook/assets/vxscan-em-diagnostics.png" alt="VxScan election manager menu with the Diagnostics button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxscan-sa-diagnostics.png" alt="VxScan system administrator menu with the Diagnostics button highlighted" width="375"><figcaption></figcaption></figure></div>

The VxScan diagnostics screen shows information about how the machine is configured, how much storage is left on the device, and the current status of the scanner and printer. Prior to each election, walk through each test to verify each component is in working order. During normal operations, if one of the components fails, VxScan will display an error message on screen.

Select `Perform Test Scan` and insert a blank sheet of paper as prompted. This test verifies the scanner is clean and ballot images are clear. If the test fails, you'll be prompted to clean the scanner. The test will also fail if the sheet is not blank.

Select `Print Test Page` to ensure the paper roll is installed properly. If the paper roll was installed backwards, nothing will print. After the test print completes, you must indicate whether the print was successful or not.

Select `Test Sound` to verify the speaker is working properly.

Select `Test Uninterruptible Power Supply` to confirm that the UPS is connected and fully charged.

The most recent test result for each piece of hardware is shown on the diagnostics screen and included in the readiness report.

<figure><img src="../.gitbook/assets/vxscan-em-diagnostics-full.png" alt="Full VxScan Diagnostics page with configuration, storage, scanner, printer, speaker, and UPS sections" width="375"><figcaption></figcaption></figure>

The readiness report can be used as a record of system diagnostic verification. Select `Save Readiness Report` to save a copy to a USB drive.

<figure><img src="../.gitbook/assets/vxscan-readiness-report.png" alt="VxScan readiness report listing configuration, storage, scanner, printer, speaker, and UPS status" width="375"><figcaption><p>Example VxScan Readiness Report</p></figcaption></figure>
