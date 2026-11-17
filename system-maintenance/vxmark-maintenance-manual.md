# VxMark Maintenance Manual

For reference information on VxMark, see the following links:

* **Hardware Overview -** [VxMark Hardware](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/vxmark-hardware "mention")
* **Software Functionality -** [VxMark Function](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/vxmark-function "mention")

## Hardware Maintenance

Review the warnings and cautions listed below first. Then below that, find specific recommendations about other maintenance.

### Warnings

1. **Never** try to perform complex repairs on VxMark.
2. The bottom panel is sealed. Do **not** remove the seals. Only VotingWorks should perform repairs that require removing panels.
3. The VxMark HP4001dn printer performs best when stored at room temperature.  If the HP4001dn printer or its toner is ever stored in hot conditions above 100 °F for more than 4 hours, replace the toner for optimal function. If the HP4001dn printer is ever stored in cold conditions below 60 °F, avoid suddenly bringing it up to warmer temperatures and using it, and instead let it sit at room temperature as long as possible before printing with it.

{% hint style="info" %}
If the HP4001dn printer must ever be operated at cold temperatures below 60 °F for more than an hour, then to preserve print quality you must configure the printer settings as follows using the menu buttons in the front of the printer:

`Main Menu` > `Setup` > `Tray Management` > `Default Paper Type` > `Mid-Weight 96-110g`

Don't change any other printer menu settings. You can return this setting to the default when using the printer again at typical warmer temperatures.
{% endhint %}

### VxMark Cleaning

VotingWorks recommends cleaning the screen, accessible controller, and USB port as needed. Clean the screen and controller by gently wiping them with cleaning wipes, such as ULINE S-12236 or equivalent. Clean the USB port by blowing it out with air in a can, such as ULINE S-6771 or equivalent, from a distance of at least one foot. Read all manufacturer safety instructions before using air in a can.

### VxMark Printer Maintenance <a href="#vxmark-printer-maintenance" id="vxmark-printer-maintenance"></a>

VxMark uses a HP LaserJet Pro 4001dn printer to print ballots. The [manufacturer specifications](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/hp-laserjet-pro-4001dn/hp-laserjet-pro-4001dn-datasheet.pdf) and [manufacturer user guide](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/hp-laserjet-pro-4001dn/hp-laserjet-pro-4001dn-user-guide.pdf) are included in the documentation repository. For more troubleshooting tips on the printer, consult the [HP Printer FAQs](../miscellaneous/hp-printer-faqs.md "mention") section.

#### Paper Specifications <a href="#paper-specifications" id="paper-specifications"></a>

VotingWorks recommends using only the printer's Tray 2, which is the bottom, higher capacity tray. When using this printer with VxMark, paper should be between 28 lb and 32 lb bond weight, to account for both printer [manufacturer specifications](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/hp-laserjet-pro-4001dn/hp-laserjet-pro-4001dn-datasheet.pdf) and to ensure printed ballots are scannable by VxScan. Using paper outside of the manufacturer specified weight range may result in jams and incorrect operation. All paper should be letter-sized.

#### Toner Specifications <a href="#toner-specifications" id="toner-specifications"></a>

The HP LaserJet Pro 4001dn requires genuine HP toner cartridges. Both the HP 148A Black Original LaserJet Toner Cartridge and the HP 148X High Yield Black Original LaserJet Toner Cartridge are acceptable.

The printer comes with toner installed. When replacing the toner, refer to the [manufacturer's instructions](https://support.hp.com/us-en/document/ish_5455373-5578919-16).

