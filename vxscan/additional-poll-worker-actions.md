# Additional Poll Worker Actions

{% hint style="info" %}
The following steps must be completed by a poll worker.
{% endhint %}

### Pause or Resume Voting

The _`Pause Voting`_ action in the poll worker screen is generally used by jurisdictions conducting early voting over multiple days or during an emergency situation. To pause voting and prevent ballots from being cast at VxScan:

* [ ] insert a poll worker card and select _`Menu`_
* [ ] select _`Pause Voting`_

<div><figure><img src="../.gitbook/assets/close-polls copy 2.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/pw-menu-while-open copy.png" alt=""><figcaption></figcaption></figure></div>

* [ ] select _`Reprint Voting Paused Report`_ to print more reports as necessary
* [ ] remove the poll worker card

<div><figure><img src="../.gitbook/assets/voting-is-paused.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/voting-paused-voter.png" alt=""><figcaption></figcaption></figure></div>

Voting is now paused. To later resume voting:

* [ ] insert a poll worker card and select _`Resume Voting`_

<figure><img src="../.gitbook/assets/resume-voting-flow.png" alt="" width="375"><figcaption></figcaption></figure>

One copy of the voting resumed report will print. If additional reports are needed, select _`Reprint Voting Resumed Report`_ to print more. The voting resumed report and the voting paused report should have the same ballots scanned count.

* [ ] remove the poll worker card

<figure><img src="../.gitbook/assets/voting-was-resumed.png" alt="" width="375"><figcaption></figcaption></figure>

The polls are now open. Below are examples of the voting paused report and voting resumed report.

<div><figure><img src="../.gitbook/assets/voting-paused-report.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/voting-resumed-report.png" alt=""><figcaption></figcaption></figure></div>

### Printing Previous Reports

If additional copies of a report need to be printed at any time, insert a poll worker card and select _`Menu`_ to access the poll worker menu. Select _`Print xxx Report`_ to print additional copies.

<div><figure><img src="../.gitbook/assets/pw-menu-while-open copy 3.png" alt=""><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/pw-menu-closed copy 3.png" alt=""><figcaption></figcaption></figure></div>

### Hash Validation

VotingWorks equipment provides additional system security by allowing you to confirm the software is the same as the certified version. To confirm on VxScan, insert a Poll Worker Card, select _`No`_, and select _`Hash Validation`_. Then navigate to check.voting.works on your phone and scan the QR code on the VxScan. The site will validate the QR code data and verify the software is the same as the certified version.

<div><figure><img src="../.gitbook/assets/image (18).png" alt="" width="375"><figcaption><p>select Hash Validation</p></figcaption></figure> <figure><img src="../.gitbook/assets/Hash Validation check voting works.png" alt="" width="237"><figcaption><p>validate at check.voting.works</p></figcaption></figure></div>

{% hint style="warning" %}
If the hash is not validated at check.voting.works contact your election administrator immediately.
{% endhint %}
