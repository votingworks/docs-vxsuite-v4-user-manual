# Load Translations

If your ballots must be available in languages other than English, add those languages and load a translation for every piece of election text: the election title, district and precinct names, contest titles, ballot measure text, and so on. Translations are prepared outside VxAdmin, one language at a time, in a translations file that VxAdmin saves and loads. Skip this page if all ballots are English only.

## Add Languages

* [ ] Select `Translations` from the side menu
* [ ] Open the language menu and select `Manage Languages…`
* [ ] Select each language your ballots need
* [ ] Select `Save`

<div><figure><img src="../../.gitbook/assets/vxadmin-design-translations-language-menu.png" alt="Translations screen with the language menu open, listing Spanish (US) and Manage Languages" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/vxadmin-design-translations-manage-languages.png" alt="Manage Languages dialog with a checkbox for each supported language, English and Spanish (US) selected" width="375"><figcaption></figcaption></figure></div>

English is always included.

## Review Translations

Choose a language from the language menu. VxAdmin lists every piece of election text, grouped by where it appears, and marks each one that is missing a translation. The count of missing translations and the time translations were last loaded appear under the language menu.

Select an item in the list to see its English text, its translation, and its ID, which identifies it in the translations file. Use `Search…` to find an item.

<figure><img src="../../.gitbook/assets/vxadmin-design-translations-missing.png" alt="Translations screen for Spanish (US) with 29 translations missing, the election text listed by section with warning icons, and the election title's translation marked Missing" width="375"><figcaption></figcaption></figure>

## Save and Load the Translations File

To have text translated, save the translations file for the language to a USB drive. The file is a spreadsheet (CSV) listing each item's ID, where it appears, its English text, and its current translation, if any. Fill in the translations using the tool or service of your choice, without changing the IDs or English text.

* [ ] Insert a USB drive
* [ ] Choose the language from the language menu
* [ ] Select `Save Translations`
* [ ] Select `Save`

<figure><img src="../../.gitbook/assets/vxadmin-design-translations-save.png" alt="Save Translations dialog naming the Spanish (US) translations file to save on the inserted USB drive" width="375"><figcaption></figcaption></figure>

When the translations are filled in, load the file back into VxAdmin:

* [ ] Insert the USB drive containing the filled-in translations file
* [ ] Choose the language from the language menu
* [ ] Select `Load Translations`
* [ ] Select the translations file

VxAdmin reports how many translations were loaded.

* [ ] Select `Close`

<div><figure><img src="../../.gitbook/assets/vxadmin-design-translations-loaded.png" alt="Translations Loaded dialog reporting 29 translations loaded for Spanish (US)" width="375"><figcaption></figcaption></figure> <figure><img src="../../.gitbook/assets/vxadmin-design-translations-complete.png" alt="Translations screen for Spanish (US) showing All strings translated and the election title's Spanish translation" width="375"><figcaption></figcaption></figure></div>

"All strings translated" should appear under the language menu. If translations are still missing, add them to the file and load it again. Loading a file replaces the language's translations with the ones in the file, so you can save, correct, and reload the file as many times as you need.

Ballot measure text keeps its formatting in translation.

<figure><img src="../../.gitbook/assets/vxadmin-design-translations-ballot-measure.png" alt="Translations screen showing the Library Levy description in English and its Spanish translation" width="375"><figcaption></figcaption></figure>

Every language must have a complete set of translations before you can load its audio or finalize the election.

Continue with [Load Audio](audio.md).
