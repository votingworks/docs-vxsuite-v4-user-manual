# User Manual Style Guide

How to write and edit the VxSuite user manual. It applies to new text and to
any passage being edited; bring a passage up to this guide when you change
it, and leave untouched passages alone.

The manual tells election officials and poll workers how to use the system:
system administrators, election managers and poll workers setting up,
testing, running and closing out an election. Test labs also review it as
part of the technical data package.

**How this guide works.** Every rule has an ID (`UM-301`) so a review can
cite it. IDs are permanent: a new rule takes the next free number in its
section, and a removed rule's ID is never reused. Each rule states one
thing; an exception is part of the rule. The Guidance section at the end
explains the reasons behind rules and covers judgment calls; it is advice,
not something to flag. Claude and GitBook's Agent both review against this
file, which is the only copy: after changing it, re-import it into the
GitBook site's style guide.

## Voice and Tone

- **UM-101** Address the reader as "you", and write steps as imperatives:
  "You will create election manager and poll worker cards." "Insert the
  poll worker card."
- **UM-102** Contractions are fine ("you'll", "doesn't").
- **UM-103** Don't write "simply", "just" or "easy".
- **UM-104** No exclamation marks.
- **UM-105** No all-caps emphasis.
- **UM-106** "Please" only when asking the reader to contact someone.
- **UM-107** "We" only in the reader's own voice, as in an FAQ question
  ("Do we need to install toner?"). Never "we" for VotingWorks: write
  "VotingWorks recommends…".
- **UM-108** When a task belongs to a role, name it in lowercase: system
  administrator, election manager, poll worker.
- **UM-109** "Election official" for jurisdiction staff in general; "your
  election administrator" only for the person a poll worker contacts.
- **UM-110** Never "the user" or "end users".

## Modal Verbs and Tense

- **UM-201** "Should" for a result the reader checks, followed where
  possible by what to do if it doesn't happen: "The `Scan Ballots` page
  should show zeroes. If it doesn't, …"
- **UM-202** Present tense for what the system does in response to an
  action: "VxScan prints the polls opened report."
- **UM-203** "Must" for requirements.
- **UM-204** "VotingWorks recommends" for recommendations.

## Page Shape

- **UM-301** One H1 per page, identical to the page's title in `SUMMARY.md`.
- **UM-302** Task page titles and headings are imperatives ("Open Polls",
  "Load the Election Package", "Pack Up VxScan").
- **UM-303** Reference page titles and headings are nouns ("Supply List",
  "VxScan Error Messages").
- **UM-304** Titles and headings in Title Case, with short words lowercase
  ("the", "a", "and", "to", "on").
- **UM-305** No skipped heading levels.
- **UM-306** No bold in headings, and no bold paragraphs standing in for
  headings.
- **UM-307** Don't add role hints. Keep only the existing ones, which
  documentation requirements call for, and never use one for a poll worker
  task.
- **UM-308** A role hint opens its page, in this wording (with the role that
  applies, or "…by a system administrator or an election manager" when
  either can):

  ```
  {% hint style="info" %}
  These steps must be completed by an election manager.
  {% endhint %}
  ```

- **UM-309** A task page opens with one or two sentences on what the task
  does and when to do it, then the steps.
- **UM-310** Parallel device sections (VxScan, VxCentralScan, VxPrint,
  VxMark, VxMarkScan) use the same page types, section order and headings:
  configure, hardware setup, open and close polls, voting sessions,
  diagnostics, error messages, retaining and removing files, packing up,
  checklist.
- **UM-311** Parallel device pages use the same wording where the behavior
  is the same.
- **UM-312** A feature that spans devices (VxCentralScan sending CVRs to
  VxAdmin) has one home page, which shows the screens from every device
  involved.
- **UM-313** Other pages mention a cross-device feature only where what they
  say would otherwise be wrong, with a sentence and a link to its home page.

## Procedures

- **UM-401** A procedure (steps done in order to finish a task) is a
  checkbox list with one action per item:

  ```
  * [ ] Insert the poll worker card
  * [ ] Select `Open Polls`
  ```

- **UM-402** No closing period on a checkbox item.
- **UM-403** Options and alternatives (settings a voter can choose, ways to
  do something) are prose or a bulleted list, not checkboxes.
- **UM-404** A result is not a checkbox item: state it in a plain sentence
  after the step it follows. "The polls opened report prints."
- **UM-405** A procedure with phases is a numbered list of bold phase labels
  with the checkboxes nested under each: `1. **Set up the ballot box:**`.
- **UM-406** A conditional step starts with the condition, without italics:
  "If prompted, select the ballot language".
- **UM-407** A procedure closes with the outcome: "The polls are now open
  and voting can begin."
- **UM-408** Screenshots and photos follow the steps they illustrate.
  Exception: a result screen that also holds the next step's control (a
  "saved" dialog with `Eject USB`) follows that next step.
- **UM-409** Checklists have one H2 per phase or device, with checkbox items
  as in procedures.

## User Interface

- **UM-501** "Select" is the only verb for choosing an on-screen control.
  Don't write click, tap or press for a control on screen.
- **UM-502** Physical buttons are pushed or pressed.
- **UM-503** Inline code for anything clickable (buttons, menu items, tabs,
  dropdown options): "select `Save CVRs`".
- **UM-504** Inline code for things typed or stored (paths, setting keys):
  "the `/logs` folder".
- **UM-505** Straight double quotes for other on-screen text (screen titles,
  banners, messages, counters, field labels): a "Blank Ballot Detected"
  banner, the "Sheets Scanned" count.
- **UM-506** Modes and report types in plain lowercase prose: "test ballot
  mode", "the polls opened report".
- **UM-507** Navigation in this form: "Select `Reports` from the side menu
  and select `Ballot Count`."
- **UM-508** Device menu paths with each item in code, joined by " > ":
  `Main Menu` > `Setup` > `Paper`.
- **UM-509** Hardware parts in plain text, with callout letters uppercase in
  parentheses: "the power cord (A)".
- **UM-510** Product names are never bold.

## Callouts

- **UM-601** `info` hints for the role hint, notes and tips.
- **UM-602** A `warning` hint only where getting it wrong loses data,
  damages equipment, or affects ballots or chain of custody.
- **UM-603** No `danger` or `success` hints.
- **UM-604** No "Note:" paragraphs; use an `info` hint.
- **UM-605** A passage repeated on more than one page is an include in
  `.gitbook/includes/`, not a copy.

## Screenshots and Photos

- **UM-701** A procedure shows the screen where the reader acts the first
  time it reaches that screen.
- **UM-702** Every confirmation dialog for a destructive or irreversible
  action (unconfigure, delete, format, remove CVRs, mark results official)
  gets a screenshot.
- **UM-703** Wherever the text says what "should" appear (CVRs loaded, the
  polls opened report), a screenshot shows it.
- **UM-704** Anything the reader has to read or compare (voter-facing
  warnings, error screens, reports) gets a screenshot.
- **UM-705** A physical step whose location or part words can't make
  obvious (ports, latches, seals, card slots) gets a photo; one photo can
  cover a group of steps.
- **UM-706** No screenshot for a step on a screen already shown when the
  control is obvious.
- **UM-707** No screenshot of a loading or transient screen. Exception:
  screens seen with every ballot (VxScan's scanning screen, the "Printing
  Your Ballot" screen, and VxMarkScan's loading-sheet and casting-ballot
  screens).
- **UM-708** No screenshot of a message the text already quotes.
- **UM-709** No screenshots on checklists; link to the full page instead.
- **UM-710** No screenshots on reference pages. Exception: error screens.
- **UM-711** Don't repeat an image within a procedure. A later procedure on
  the same page (packing up after setting up) can show it again.
- **UM-712** A screenshot shows the state the text next to it describes:
  after "each batch should show that it was sent", every batch shows as
  sent.
- **UM-713** Don't show variants of a screen that differ only in a label or
  status: show the normal state and name the others in prose.
- **UM-714** When a change adds to a screen the page already shows (a new
  section on the diagnostics screen), replace that capture rather than add
  a second.

## Highlights

- **UM-801** Highlight the control the step tells the reader to select.
- **UM-802** At most one highlight per screenshot.
- **UM-803** No highlight when the control is the screen's only control.
- **UM-804** No highlight when the control is the one primary
  (highest-weight) option of a dialog or full-screen prompt, such as
  `Confirm` over `Cancel`. Exception: on menus and app pages, highlight the
  control even when it is the primary button.
- **UM-805** A dialog or prompt step that selects a lesser option, or one of
  several buttons of equal weight, gets a highlight.
- **UM-806** No highlight on result screens or screens shown for reading.
  Exception: mark the one area of a result screen the text asks the reader
  to check (the election information panel after configuring).

## Figure Markup

- **UM-901** Figures use GitBook figure markup, with alt text that says what
  the figure shows.
- **UM-902** Width 375 for landscape screenshots and photos.
- **UM-903** Width 188 for portrait (VxMark and VxMarkScan) screenshots and
  small detail photos.
- **UM-904** Width 563 for wide diagrams.
- **UM-905** One width per side-by-side row (a `<div>` of figures).
- **UM-906** A row holds at most three portrait screenshots or two landscape
  images; split a longer sequence into rows as even as possible (four as two
  and two).
- **UM-907** Screenshots have no caption.
- **UM-908** Photos have a short sentence-case action caption ("Push the
  release lever"), with no code.
- **UM-909** A screenshot's file name is its gallery ID.
- **UM-910** Photo file names start `photo-` and diagram file names start
  `diagram-`, in kebab-case.

## Terminology

- **UM-1001** Product names exactly as written, never abbreviated: VxAdmin,
  VxCentralScan, VxMark, VxMarkScan, VxPrint, VxScan, VxSuite. Not "VxCS".
- **UM-1002** **hand-marked paper ballot** and **machine-marked paper
  ballot** when the text is about how a ballot was produced (marked by the
  voter, or printed by VxMark or VxMarkScan).
- **UM-1003** **bubble ballot** and **summary ballot** when the text is
  about the ballot type or layout (for example, what VxPrint can print).
- **UM-1004** Expand an abbreviation on its first use on each page, as
  "Term (ABBR)": CVR, L&A, PAT, UPS, COTS. Product names are never expanded.
- **UM-1005** Use these terms, not the alternatives:

| ID | Use | Not |
| --- | --- | --- |
| UM-1010 | test ballot mode, official ballot mode | test mode, official mode |
| UM-1011 | ballot-marking device (BMD) | ballot marking device |
| UM-1012 | cast vote record (CVR) | cast-vote record |
| UM-1013 | personal assistive technology (PAT) | Personal Assistive Technology |
| UM-1014 | contest | race |
| UM-1015 | USB drive | USB (as a noun) |
| UM-1016 | VotingWorks support | customer support |
| UM-1017 | Ethernet, Wi-Fi | ethernet, Wi-fi |
| UM-1018 | tamper-evident | tamper evident |

## Numbers and Punctuation

- **UM-1101** Thousands separators from 1,000: "10,000 ballots".
- **UM-1102** A space between a number and its unit: "120 V", "64 GB",
  "5 mm", "100 °F".
- **UM-1103** An en dash for ranges: "105–177 gsm".
- **UM-1104** An em dash without spaces in prose.
- **UM-1105** "e.g.," and "i.e.," with a comma. Not "ex." or "aka".
- **UM-1106** The Oxford comma: "VxAdmin, VxCentralScan, and VxPrint".

## Links

- **UM-1201** Link a whole page by GitBook mention, with the page title as
  link text.
- **UM-1202** Link a section by a relative link with an anchor.
- **UM-1203** Link a TDP page by GitBook space mention.
- **UM-1204** Links to VotingWorks source repositories on GitHub are pinned
  to the latest official release tag (currently `v4.1.1`), never `main`,
  even for a feature that first appears in a later release.
- **UM-1205** Links into `docs-vxsuite-v4` (datasheets, guides, reports)
  stay on `main`.

## Error Message Pages

- **UM-1301** Error messages are in pipe tables with the columns `Error
  Message | Election Official Action | Log File Entry`.
- **UM-1302** On voter-facing devices, the columns are `Error Message |
  Voter Action | Poll Worker Action | Log File Entry`.
- **UM-1303** Category rows are bold, without a colon.
- **UM-1304** Messages are written "Title - body", in the device's exact
  wording.
- **UM-1305** Actions are in the imperative.
- **UM-1306** The same error is worded the same on every device unless the
  action really differs.
- **UM-1307** "Multiple possible values" for a variable log field.

## Photos

- **UM-1401** Photos are JPEG files.
- **UM-1402** A photo is 4:3 landscape at 1600×1200 or 3:4 portrait at
  1200×1600.
- **UM-1403** A photo never shares a row with a screenshot: give it its own
  row.
- **UM-1404** Photos in one row have the same shape, all 4:3 or all 3:4.
- **UM-1405** A photo's file name is `photo-<device>-<subject>.jpg`, in
  lowercase kebab-case: `photo-vxscan-power-cord.jpg`.
- **UM-1406** A photo carries no metadata: no location, camera or date.

## Guidance

Advice and reasons, not rules to flag.

- **Friendly and plain.** The reader is often a poll worker on election
  morning. "Simply" and "easy" are out because the reader may not find it
  so.
- **The ballot terms differ from the TDP's** (UM-1002, UM-1003), from user
  feedback: officials think of how a ballot was marked. The TDP says bubble
  ballot and summary ballot throughout.
- **Role hints** (UM-307) exist only where a documentation requirement says
  a page must state who performs it.
- **Parallel pages:** a change to one device's page is checked against its
  siblings (UM-310, UM-311).
- **Pinned links** (UM-1204) move to a new release tag all together.
  `docs-vxsuite-v4` stays on `main` because that repository has no release
  tags.
- **Screenshots come from the gallery.** The screenshots workflow keeps
  files named by gallery ID current (UM-909). Highlighted captures carry a
  `highlight` field in the screenshot catalog, and new ones end in
  `-highlighted`. To get one that doesn't exist yet, request it in
  vxsuite-screenshots ("highlight `Unconfigure Machine`"). Reusing an
  existing capture doesn't waive a highlight UM-801 calls for: request the
  `-highlighted` variant.
- **Don't delete images in a docs pull request,** even ones a change stops
  using. Deleting any image makes GitBook rebuild the whole space, so its
  diff marks every page as edited. An unused image is harmless; remove
  unused images in a separate cleanup pull request.
- **Taking photos.** Shoot in the phone's 4:3 mode, the default on iPhone
  and Pixel, and fill the frame with the subject on a plain background.
  Shoot landscape for setups and portrait for tall subjects. Set the camera
  to save JPEG ("Most Compatible" on iPhone) and turn off location tagging.
  Crop to 4:3 or 3:4 and resize to 1600 px on the long side before adding a
  photo.
- **The photos check** on pull requests fails on location metadata, since
  this repository is public, and warns on the other photo rules (UM-1401 to
  UM-1405). Strip metadata with `exiftool -all= -tagsfromfile @
  -icc_profile <file>`, which keeps the colors and changes no pixels.
- **Why photos and screenshots don't share rows:** screenshots come in three
  shapes (16:10 on VxAdmin, VxCentralScan and VxPrint, 16:9 on VxScan, 9:16
  on VxMark and VxMarkScan), and a 4:3 or 3:4 photo beside any of them
  renders at a different height.
