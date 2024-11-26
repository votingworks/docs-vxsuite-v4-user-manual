# L\&A Overview

Logic & accuracy testing (L\&A) is meant to ensure that every component of the voting system is operating as expected and has been configured properly for a specific election. Testing rules vary by jurisdiction. The following functions may be useful as tests are conducted and are referenced in the [l-and-a-testing-checklist.md](l-and-a-testing-checklist.md "mention").

### VxAdmin Tally Report&#x20;

Before starting the testing process, using an using an election manager card, confirm VxAdmin does not have CVRs loaded. Select _`Reports`_ from the side menu and select _`Full Election Tally Report`_ to print a "zero" report.

<figure><img src="../.gitbook/assets/reports-screen-unofficial-highlighted.jpg" alt="" width="375"><figcaption></figcaption></figure>

### Test Ballot vs. Official Ballot Mode&#x20;

VxScan, VxCentralScan, and VxMark can be placed into test ballot mode to only accept test ballots. If official ballots are used for testing, _`Official Ballot Mode`_ should be used. VxScan and VxCentralScan default to test mode after configuration.

In VxScan, insert an election manager card and select the correct mode.&#x20;

<figure><img src="../.gitbook/assets/election-manager-settings copy.png" alt="" width="375"><figcaption></figcaption></figure>

In VxCentralScan, insert an election manager card, select _`Settings`_ from the side menu, and select the correct mode.

<figure><img src="../.gitbook/assets/cs-settings-2 copy 4.png" alt="" width="375"><figcaption></figcaption></figure>

In VxMark, insert an election manager card and select the correct mode.

<figure><img src="../.gitbook/assets/mk-em-landing copy.png" alt="" width="188"><figcaption></figcaption></figure>

{% hint style="info" %}
An orange _Test Ballot Mode_ banner will display at the top of each screen when the device is in test ballot mode.&#x20;
{% endhint %}
