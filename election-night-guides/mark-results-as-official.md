# Mark Results as Official

{% hint style="info" %}
These steps must be completed by an election manager.
{% endhint %}

When you are ready to certify election results, you can mark VxAdmin results as official to print official reports.

{% hint style="warning" %}
Make sure that you've imported all cast vote record (CVR) files, completed all adjudication, and added all manual tallies before proceeding.
{% endhint %}

To mark results as official:

* [ ] Select `Reports` from the side menu
* [ ] Select `Mark Election Results as Official`

<figure><img src="../.gitbook/assets/vxadmin-reports-mark-official-highlighted.png" alt="VxAdmin Election Reports screen with unofficial results and the Mark Election Results as Official button highlighted." width="375"><figcaption></figcaption></figure>

* [ ] Confirm by selecting `Mark Election Results as Official`

All references to unofficial results in VxAdmin change to official.

<div><figure><img src="../.gitbook/assets/vxadmin-reports-screen-official.png" alt="VxAdmin Election Reports screen after results are marked official, with the mark-official button disabled." width="375"><figcaption></figcaption></figure> <figure><img src="../.gitbook/assets/vxadmin-tally-screen-official.png" alt="VxAdmin Tally screen with results marked official, CVRs loaded, and a Remove All Tallies button." width="375"><figcaption></figcaption></figure></div>

If you become aware of a mistake after marking results as official (say, you forgot to import one machine's CVRs), you can revert the results to unofficial as a system administrator:

* [ ] Log in as a system administrator
* [ ] Use the `Revert Election Results to Unofficial` button

<figure><img src="../.gitbook/assets/vxadmin-election-screen-revert-highlighted.png" alt="VxAdmin Election screen as system administrator with the Revert Election Results to Unofficial button highlighted." width="375"><figcaption></figcaption></figure>

* [ ] Log out and log back in as an election manager
* [ ] Make the necessary changes
* [ ] Mark the results as official again
