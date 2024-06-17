# Smartcards and User Roles

{% hint style="info" %}
The following steps must be completed by the System Administrator.
{% endhint %}

## Overview

Smartcards are used to configure and operate equipment. It's the same technology as the chip in your credit card, but is instead used to provide election administrators and poll workers a secure means to configure and operate the equipment. There are three user roles and cards: System Administrator, Election Manager, and Poll Worker**.**

<figure><img src="../.gitbook/assets/image (635).png" alt="" width="375"><figcaption><p>Smartcards</p></figcaption></figure>

### System Administrator Cards

System Administrator Cards allow an election administrator to load an election definition, program smartcards, and remove the election definition from VxAdmin. This card is also used to perform software updates on all machines.

System Administrator Cards should only need to be used at the very beginning and very end of an election. Keep this card in a secure location when not in use and in between elections.

###

### Election Manager Cards

Election Manager Cards allow election administrators to use central system devices and configure precinct system devices. Election Managers are responsible for:

* preparing machines for L\&A
* centrally scanning ballots
* configuring precinct equipment
* tallying CVRs
* adjudicating write-ins
* entering manual tallies
* printing and saving results

Election Manager Cards should only be used by election administrators and should be kept secure at all times.

### Poll Worker Cards

Poll Worker Cards allow poll workers to manage election day precinct tasks, including:

* opening the polls
* closing the polls
* printing precinct tally reports

Every precinct will need at least one Poll Worker Card in order to operate the polls.



##

##

## Creating Cards

For each election, you will create Election Manager and Poll Worker Cards specifically for that election. Smartcards can be created quickly and easily with VxAdmin, by logging in with a System Administrator Card and selecting Smartcards from the side menu.

<figure><img src="../.gitbook/assets/image (31).png" alt="" width="354"><figcaption></figcaption></figure>

You will use the smartcard reader in the lower lefthand side of your VxAdmin laptop to program a card. Simply insert the card of your choice and select the correct button for the card.

<div>

<figure><img src="../.gitbook/assets/image (97).png" alt="" width="262"><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/image (78).png" alt="" width="375"><figcaption></figcaption></figure>

</div>

When creating an Election Manager Card, the screen will provide you with a unique PIN for that card. Keep the PIN secure. When creating a Poll Worker Card, the screen will simply confirm the card is created.

![Election Manager Card confirmation screen with PIN](<../.gitbook/assets/image (81).png>) ![Poll Worker Card confirmation screen](<../.gitbook/assets/Create Election Card - Poll Worker.png>)







To create an additional System Administrator Card or reset the PIN, select _`Create System Administrator Cards`_ from the Smartcards screen.&#x20;

<figure><img src="../.gitbook/assets/image (32).png" alt="" width="354"><figcaption></figcaption></figure>

From the System Administrator Cards screen, insert a System Administrator Card into the card reader.&#x20;

<figure><img src="../.gitbook/assets/image (33).png" alt="" width="358"><figcaption></figcaption></figure>

If a PIN already exists, a _`Reset Card PIN`_ button will appear.  If the card is not programmed a PIN will be generated.

<div>

<figure><img src="../.gitbook/assets/image (85).png" alt="" width="188"><figcaption></figcaption></figure>

 

<figure><img src="../.gitbook/assets/image (86).png" alt="" width="188"><figcaption></figcaption></figure>

</div>

##

###

### Unprogramming Cards

If a card has already been programmed, when you insert the card into the card reader, a prompt to _`Unprogram Card`_ will be displayed. Select the _`Unprogram Card`_ button to clear the card.

<figure><img src="../.gitbook/assets/image (34).png" alt="" width="240"><figcaption></figcaption></figure>
