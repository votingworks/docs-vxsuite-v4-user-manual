# L\&A Overview

Logic & accuracy testing (L\&A) is meant to ensure that every component of the voting system is operating as expected and has been configured properly for a specific election. Testing rules vary by jurisdiction and/or state. The following functions may be useful as tests are conducted.

### VxAdmin Tally Report&#x20;

Before starting the testing process, using an Election Manager Card, confirm VxAdmin does not have CVRs loaded. Select Reports from the side menu and select _`Full Election Tally Report`_ to print a "zero" report.

<figure><img src="../.gitbook/assets/image (862).png" alt="" width="267"><figcaption></figcaption></figure>

### Test Ballot v. Official Ballot Mode&#x20;

VxScan and VxCentralScan can be placed into Test Ballot Mode to only accept test ballots. If official ballots are used for testing, _`Official Ballot Mode`_ should be used. VxScan and VxCentralScan default to test mode after configuration.

In VxScan, insert an Election Manager Card, select Configuration from the side menu, and select the correct mode.&#x20;

<figure><img src="../.gitbook/assets/image (863).png" alt="" width="266"><figcaption></figcaption></figure>

In VxCentralScan, insert an Election Manager Card, select Settings from the side menu, and select  _`Toggle to Official Ballot Mode`_.&#x20;

<figure><img src="../.gitbook/assets/image (864).png" alt="" width="266"><figcaption></figcaption></figure>

