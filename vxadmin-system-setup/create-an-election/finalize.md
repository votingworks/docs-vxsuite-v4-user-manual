# Finalize the Election

Finalizing the election locks it and generates its ballots. Finalize only after every ballot style has been proofed and approved: once the election is finalized, it can't be edited.

## Check That the Election Is Ready

* [ ] Select `Finalize` from the side menu

VxAdmin shows what remains before the election can be finalized:

* "Ballots Incomplete": no ballot styles exist yet. Add districts, precincts, and contests.
* Registered voter counts are entered for some precincts but not all. See [Add Precincts](precincts.md).
* Some precincts aren't served by an absentee polling place. See [Add Polling Places](polling-places.md).
* "Translations Incomplete": a ballot language is missing translations. See [Load Translations](translations.md).
* "Audio Incomplete": a ballot language is missing audio. See [Load Audio](audio.md).

<div><figure><img src="../../.gitbook/assets/vxadmin-design-finalize-incomplete.png" alt="Finalize screen showing Ballots Incomplete: VxAdmin will create ballot styles once you have created districts, precincts, and contests" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/vxadmin-design-finalize-audio-incomplete.png" alt="Finalize screen showing Audio Incomplete: load audio for English and Spanish (US) before finalizing" width="375"><figcaption></figcaption></figure></div>

When nothing remains, VxAdmin shows "Election Not Finalized".

## Finalize

* [ ] Select `Finalize Election`
* [ ] Select `Finalize Election` to confirm

<div><figure><img src="../../.gitbook/assets/vxadmin-design-finalize-election-highlighted.png" alt="Finalize screen showing Election Not Finalized with the Finalize Election button highlighted" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/vxadmin-design-finalize-confirm.png" alt="Finalize Election dialog warning that once the election is finalized it may not be edited further" width="375"><figcaption></figcaption></figure></div>

{% hint style="warning" %}
A finalized election can't be edited. Proof every ballot style before finalizing.
{% endhint %}

VxAdmin generates the official and test ballots for every ballot style and shows its progress.

<figure><img src="../../.gitbook/assets/vxadmin-design-finalize-progress.png" alt="Finalize screen showing Finalizing Election with a progress bar at Rendering test ballots" width="375"><figcaption></figcaption></figure>

When it's done, VxAdmin shows "Election Finalized".

<figure><img src="../../.gitbook/assets/vxadmin-design-finalized.png" alt="Finalize screen showing Election Finalized with Official Ballots and Test Ballots, each with a Save button" width="375"><figcaption></figcaption></figure>

## Save the Ballots

Save the official ballots for your ballot printer and the test ballots for logic and accuracy (L&A) testing.

* [ ] Insert a USB drive
* [ ] Next to "Official Ballots", select `Save`
* [ ] Select `Save`

<figure><img src="../../.gitbook/assets/vxadmin-design-save-official-ballots.png" alt="Save Official Ballots dialog naming the official ballots file to save on the inserted USB drive" width="375"><figcaption></figcaption></figure>

* [ ] Next to "Test Ballots", select `Save`
* [ ] Select `Save`
* [ ] Select `Eject USB`

Official ballots include precinct and absentee ballots for every ballot style. Test ballots can only be used with VotingWorks machines in test ballot mode. All ballot PDF files must be printed at 100% scale.

Next, [save the election package](../save-election-package.md) to configure the other machines.
