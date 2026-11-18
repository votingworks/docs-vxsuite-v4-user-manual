# User Manual Style Guide

How to write and edit the VxSuite user manual. It applies to new text and to
any passage being edited; bring a passage up to this guide when you change
it. The TDP has its own guide (`docs-vxsuite-v4-tdp/STYLE.md`); this one
follows it except where noted.

The manual tells election officials and poll workers how to use the system:
system administrators, election managers and poll workers setting up,
testing, running and closing out an election. Test labs also review it as
part of the technical data package.

## Voice and Tone

- Address the reader as "you"; write steps as imperatives. "You will create
  election manager and poll worker cards." "Insert the poll worker card."
- Friendly and plain. Contractions are fine ("you'll", "doesn't"). No
  "simply", "just" or "easy" (the reader may not find it so), no
  exclamation marks, no all-caps emphasis. "Please" only when asking the
  reader to contact someone.
- "We" only in the reader's own voice, as in an FAQ question ("Do we need to
  install toner?"). Never for VotingWorks: write "VotingWorks recommends…".
- Name the role when a task belongs to one: system administrator, election
  manager, poll worker (lowercase). "Election official" for jurisdiction
  staff in general; "your election administrator" only for the person a poll
  worker contacts. Never "the user" or "end users".

## Modal Verbs and Tense

- "Should" for a result the reader checks, followed where possible by what
  to do if it doesn't happen: "The `Scan Ballots` page should show zeroes.
  If it doesn't, …"
- Present tense for what the system does in response to an action: "VxScan
  prints the polls opened report."
- "Must" for requirements; "VotingWorks recommends" for recommendations.

## Page Shape

- One H1 per page, identical to its title in `SUMMARY.md`.
- Task titles and headings are imperatives ("Open Polls", "Load the Election
  Package", "Pack Up VxScan"); reference pages are nouns ("Supply List",
  "VxScan Error Messages"). Title Case, with short words lowercase ("the",
  "a", "and", "to", "on"). No skipped heading levels, no bold in headings, no
  bold paragraphs standing in for headings.
- Role hints exist only where a page must state who performs it (a
  documentation requirement); don't add new ones, and don't use them for poll
  worker tasks. Where one exists, it opens the page in this wording:

  ```
  {% hint style="info" %}
  These steps must be completed by an election manager.
  {% endhint %}
  ```

  (or the role that applies; "…by a system administrator or an election
  manager" when either can).
- A task page opens with one or two sentences on what the task does and when
  to do it, then the steps.
- Parallel device sections (VxScan, VxCentralScan, VxPrint, VxMark,
  VxMarkScan) use the same page types, section order and headings, and the
  same wording where the behavior is the same: configure, hardware setup,
  open and close polls, voting sessions, diagnostics, error messages,
  retaining and removing files, packing up, checklist. A change to one
  device's page is checked against its siblings.

## Procedures

- A procedure (steps done in order to finish a task) is a checkbox list, one
  action per item, no closing period:

  ```
  * [ ] Insert the poll worker card
  * [ ] Select `Open Polls`
  ```

- Options and alternatives (settings a voter can choose, ways to do
  something) are not procedures: describe them in prose or a bulleted list,
  not checkboxes.
- Results are not checkbox items. State them in a plain sentence after the
  step they follow: "The polls opened report prints."
- A procedure with phases is a numbered list of bold phase labels with the
  checkboxes nested under each: `1. **Set up the ballot box:**`.
- Conditional steps start with the condition: "If prompted, select the
  ballot language". No italics.
- Close with the outcome: "The polls are now open and voting can begin."
- Screenshots and photos follow the steps they illustrate. A result screen
  that also holds the next step's control (a "saved" dialog with `Eject
  USB`) follows that next step.

## User Interface

- "Select" is the only verb for choosing an on-screen control; not click,
  tap or press. Physical buttons are pushed or pressed.
- Inline code for anything clickable (buttons, menu items, tabs, dropdown
  options) and for things typed or stored (paths, setting keys): "select
  `Save CVRs`", "the `/logs` folder".
- Straight double quotes for other on-screen text: screen titles, banners,
  messages, counters, field labels. A "Blank Ballot Detected" banner; the
  "Sheets Scanned" count.
- Plain lowercase prose for modes and report types: "test ballot mode",
  "the polls opened report".
- Navigation: "Select `Reports` from the side menu and select `Ballot
  Count`." Device menus: `Main Menu` > `Setup` > `Paper`, each item in code.
- Hardware parts in plain text; callout letters uppercase in parentheses:
  "the power cord (A)". Product names never bold.

## Callouts

- `info` hints for the role hint, notes and tips.
- `warning` hints only where getting it wrong loses data, damages equipment,
  or affects ballots or chain of custody. No `danger` or `success` hints, no
  "Note:" paragraphs.
- A passage repeated on more than one page is an include in
  `.gitbook/includes/`, not a copy.

## Figures

### When to Add a Screenshot

- The screen where the reader acts, the first time a procedure reaches it.
- Every confirmation dialog for a destructive or irreversible action
  (unconfigure, delete, format, remove CVRs, mark results official).
- The result the reader checks: wherever the text says what "should" appear
  (CVRs loaded, the polls opened report).
- Anything the reader has to read or compare: voter-facing warnings, error
  screens, reports.
- A photo for a physical step whose location or part words can't make
  obvious (ports, latches, seals, card slots); one photo can cover a group
  of steps.

Not for: a step on a screen already shown when the control is obvious, a
loading or transient screen (except one voters see with every ballot:
VxScan's scanning screen, the "Printing Your Ballot" screen), a message the text already quotes, checklists
(link to the full page instead), or reference pages other than error
screens. Don't repeat an image within a procedure; a later procedure on
the page (packing up after setting up) can show it again.

### Highlights

- Highlight the control the step tells the reader to select. One highlight
  per screenshot.
- Don't highlight it when it is the screen's only control, or when it is
  the one primary (highest-weight) option of a dialog or a full-screen
  prompt, such as `Confirm` over `Cancel`. A dialog or prompt step that
  selects a lesser option, or one of buttons of equal weight, gets a
  highlight. On menus and app pages, highlight the control even when it is
  the primary button.
- No highlight on result screens or screens shown for reading, except to
  mark the one area of a result screen the text asks the reader to check
  (the election information panel after configuring).
- Highlighted captures carry a `highlight` field in the screenshot catalog;
  new ones end in `-highlighted`. To get one that doesn't exist, request it
  in vxsuite-screenshots ("highlight `Unconfigure Machine`").

### Markup

- GitBook figure markup with alt text that says what the figure shows.
- Width 375 for landscape screenshots and photos; 188 for portrait (VxMark
  and VxMarkScan) screenshots and small detail photos; 563 for wide diagrams.
  One width per side-by-side row (`<div>` of figures). A row holds at most
  three portrait screenshots or two landscape images; split a longer
  sequence into rows as even as possible (four as two and two).
- Screenshots have no caption; photos have a short sentence-case action
  caption ("Push the release lever"). No code in captions.
- Screenshots use their gallery ID as the file name; the screenshots workflow
  keeps them current. Each device's pages show that device's screens. Photos
  are `photo-…` and diagrams `diagram-…`, kebab-case.

## Terminology

Product names exactly as written: VxAdmin, VxCentralScan, VxMark, VxMarkScan,
VxPrint, VxScan, VxSuite; never abbreviated ("VxCS").

Ballots (an exception to the TDP, from user feedback):
- **hand-marked paper ballot** and **machine-marked paper ballot** when the
  text is about how a ballot was produced (marked by the voter, or printed by
  VxMark or VxMarkScan);
- **bubble ballot** and **summary ballot** when the text is about the ballot
  type or layout (for example, what VxPrint can print).

Otherwise as in the TDP:

| Use | Not |
| --- | --- |
| test ballot mode, official ballot mode | test mode, official mode |
| ballot-marking device (BMD) | ballot marking device |
| cast vote record (CVR) | cast-vote record |
| personal assistive technology (PAT) | Personal Assistive Technology |
| contest | race |
| USB drive | USB (as a noun) |
| VotingWorks support | customer support |
| Ethernet, Wi-Fi | ethernet, Wi-fi |
| tamper-evident | tamper evident |

Expand an abbreviation on its first use on each page: CVR, L&A, PAT, UPS,
COTS.

## Numbers and Punctuation

As in the TDP: thousands separators from 1,000; a space between number and
unit ("120 V", "64 GB", "5 mm", "100 °F"); an en dash for ranges; an em dash
without spaces in prose; "e.g.," and "i.e.," with a comma, no "ex." or "aka";
the Oxford comma.

## Links and Tables

- Pages by GitBook mention link with the page title as link text; sections by
  relative link with an anchor. TDP pages by GitBook space mention. GitHub
  links to VotingWorks source repositories pinned to the latest official
  release tag (currently `v4.1.1`), never `main`. Links into
  `docs-vxsuite-v4` (datasheets, guides, reports) stay on `main`: that
  repository has no release tags.
- Error message pages: pipe tables. Columns `Error Message | Election
  Official Action | Log File Entry`, or `Error Message | Voter Action | Poll
  Worker Action | Log File Entry` on voter-facing devices. Bold category rows
  without a colon. Messages as "Title - body" in the device's exact wording;
  actions in the imperative; the same error worded the same on every device
  unless the action really differs. "Multiple possible values" for a
  variable log field.
- Checklists: one H2 per phase or device, checkbox items as in Procedures.
