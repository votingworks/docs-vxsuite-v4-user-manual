# VxMark Error Messages

VxMark is programmed to intuitively explain to a voter or poll worker problems that may occur with a ballot or the VxMark. The following is a list of potential error messages, in alphabetical order, and the actions a voter or a poll worker should take to remedy the error.

| Error Message | Voter Action | Poll Worker Action | Log File Entry |
| --- | --- | --- | --- |
| Ballot Not Printed | Ask a poll worker for help. | Remove anything that did print since it may not be a valid ballot. After addressing any printer issues, direct the voter to repeat their voting session. | <p>eventId: ballot-print-complete<br>disposition: failure<br>message: "The ballot failed to print."</p> |
| Card Backward | N/A | Remove the smart card, turn it around, and insert it again. | <p>eventId: auth-login<br>disposition: failure<br>reason: card_error</p> |
| Internal Connection Problem\*\* | Ask a poll worker for help. | Reboot VxMark by holding the power button on the back left of the machine until the screen goes black. Press the button again to turn it back on. If the error persists after restarting, ask your election official to contact VotingWorks support. | No specific log entry. |
| Invalid Card - Remove the card to continue. | N/A | Try inserting the card again. If the problem persists, contact your election administrator for a new poll worker card. | <p>eventId: auth-login<br>disposition: failure<br>reason: Multiple possible values</p> |
| No Printer Detected | Ask a poll worker for help. | If polls are open, insert a poll worker card to silence the alert, then connect the printer to resume voting. Otherwise, connect the printer to continue. | <p>eventId: printer-config-removed<br>message: "The previously configured printer is no longer detected."</p> |
| Number of \<limitType> in \<electionEntity> (\<value>) exceeds VxMark system limit of \<limitValue>. | N/A | N/A | <p>eventId: election-configured<br>disposition: failure</p> |
| Printer Needs Attention | Ask a poll worker for help. | Read the specific message and fix the printer accordingly. This may involve loading paper or clearing a jam. | No specific log entry. |
| Something went wrong - Ask a poll worker to restart the ballot marking device.\* | Ask a poll worker for help. | Restart the machine. If problems persist after restarting, ask your election official to contact VotingWorks support. | eventId: unknown-error |
| The printer is low on toner. Replace toner cartridge. | N/A | Replace the toner cartridge as soon as possible. Voting can continue as long as the printer produces ballots that scan successfully. | No specific log entry. |

\*Error messages with an asterisk next to them correspond to unexpected error states where the cause is not immediately known. VotingWorks will likely ask for logs after the election to identify the cause and improve the product for future elections.

\*\*Error messages with a double asterisk next to them are meant to aid technicians assembling machines. They are not expected to be seen in the field.
