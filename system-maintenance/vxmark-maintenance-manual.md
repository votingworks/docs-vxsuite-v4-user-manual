# VxMark Maintenance Manual

For reference information on VxMark, see the following links:

* **Hardware Overview -** [VxMark Hardware](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/vxmark-hardware "mention")
* **Software Functionality -** [VxMark Function](https://app.gitbook.com/s/Z4bC0rbmogHEUUuMLAUa/system-overview/vxmark-function "mention")

## Hardware Maintenance

Review the warnings and cautions listed below first. Then below that, find specific recommendations about other maintenance.

### Warnings

1. **Never** try to perform complex repairs on VxMark.
2. The bottom panel is sealed. Do **not** remove the seals. Only VotingWorks should perform repairs that require removing panels.
3. The VxMark printer performs best when stored at room temperature. If the printer or its toner is ever stored in hot conditions above 100 °F for more than 4 hours, replace the toner for optimal function. If the printer is ever stored in cold conditions below 60 °F, avoid suddenly bringing it up to warmer temperatures and using it, and instead let it sit at room temperature as long as possible before printing with it.

{% hint style="info" %}
If the printer must ever be operated at cold temperatures below 60 °F for more than an hour, then to preserve print quality you must set the printer's default paper type to `Mid-Weight 96-110g` using the menu on the front of the printer. On the HP LaserJet Pro 4001dn, select:

`Main Menu` > `Setup` > `Tray Management` > `Default Paper Type` > `Mid-Weight 96-110g`

Don't change any other printer menu settings. You can return this setting to the default when using the printer again at typical warmer temperatures.
{% endhint %}

### VxMark Cleaning

VotingWorks recommends cleaning the screen, accessible controller, and USB port as needed. Clean the screen and controller by gently wiping them with cleaning wipes, such as ULINE S-12236 or equivalent. Clean the USB port by blowing it out with air in a can, such as ULINE S-6771 or equivalent, from a distance of at least one foot. Read all manufacturer safety instructions before using air in a can.

### VxMark Printer Maintenance <a href="#vxmark-printer-maintenance" id="vxmark-printer-maintenance"></a>

VxMark uses either the HP LaserJet Pro 4001dn or, for jurisdictions with color requirements on their ballots, the HP Color LaserJet Pro 4201dn to print ballots. When VxMark prints bubble ballots on the 4201dn, it prints them in color. The 4001dn [manufacturer specifications](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/hp-laserjet-pro-4001dn/hp-laserjet-pro-4001dn-datasheet.pdf) and [manufacturer user guide](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/hp-laserjet-pro-4001dn/hp-laserjet-pro-4001dn-user-guide.pdf) and the 4201dn [manufacturer specifications](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/hp-color-laserjet-pro-4201dn/hp-color-laserjet-pro-4201dn-datasheet.pdf) are included in the documentation repository. For more troubleshooting tips on the printer, consult the [HP Printer FAQs](../miscellaneous/hp-printer-faqs.md "mention") section.

#### Paper Specifications <a href="#paper-specifications" id="paper-specifications"></a>

VotingWorks recommends using only the printer's Tray 2, which is the bottom, higher capacity tray. When using this printer with VxMark, paper should be between 28 lb and 32 lb bond weight, to account for both printer [manufacturer specifications](https://github.com/votingworks/docs-vxsuite-v4/blob/main/hardware-assets/cots-documentation/central-system/hp-laserjet-pro-4001dn/hp-laserjet-pro-4001dn-datasheet.pdf) and to ensure printed ballots are scannable by VxScan. Using paper outside of the manufacturer specified weight range may result in jams and incorrect operation. All paper should be letter-sized.

#### Toner Specifications <a href="#toner-specifications" id="toner-specifications"></a>

The HP LaserJet Pro 4001dn requires genuine HP toner cartridges. Both the HP 148A Black Original LaserJet Toner Cartridge and the HP 148X High Yield Black Original LaserJet Toner Cartridge are acceptable.

The printer comes with toner installed. When replacing the toner, refer to the [manufacturer's instructions](https://support.hp.com/us-en/document/ish_5455373-5578919-16).

The HP Color LaserJet Pro 4201dn requires four genuine HP toner cartridges: black, cyan, magenta, and yellow. Both the HP 210A Original LaserJet Toner Cartridges and the HP 210X High Yield Original LaserJet Toner Cartridges are acceptable.

The 4201dn comes with introductory toner cartridges installed, which are rated for about 1,200 black pages and 1,000 color pages. Low toner is indicated on the printer's screen and also in the diagnostics section. When replacing toner, follow the instructions in HP's user guide for the printer.

