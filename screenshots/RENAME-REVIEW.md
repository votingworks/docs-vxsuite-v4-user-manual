# Manual asset rename: spot-check table

Sorted by source. `how` says why a gallery image was chosen (perceptual-hash distance, 0 = identical layout; "reviewed match" = an agent viewed both).

| # | old name | new ID | source | app | how / notes | pages |
|---|---|---|---|---|---|---|
| 1 | `image (37).png` | `vxadmin-adjudication-ballot-view.png` | generated | vxadmin | hash 2 | election-night-guides/adjudication.md |
| 2 | `image (42).png` | `vxadmin-adjudication-ballot-view-after-changes.png` | generated | vxadmin | hash 2 | election-night-guides/adjudication.md |
| 3 | `image (46).png` | `vxadmin-adjudication-blank-ballot-view.png` | generated | vxadmin | hash 1 | election-night-guides/adjudication.md |
| 4 | `image (47).png` | `vxadmin-adjudication-complete.png` | generated | vxadmin | reviewed match Candidate dist was 41 but it is visually the same screen and state. | election-night-guides/adjudication.md |
| 5 | `image (41).png` | `vxadmin-adjudication-contest-view-after-selection.png` | generated | vxadmin | hash 5 | election-night-guides/adjudication.md |
| 6 | `image (44).png` | `vxadmin-adjudication-marginal-contest-view.png` | generated | vxadmin | hash 2 | election-night-guides/adjudication.md |
| 7 | `image (45).png` | `vxadmin-adjudication-marginal-dismissed.png` | generated | vxadmin | hash 3 | election-night-guides/adjudication.md |
| 8 | `image (36).png` | `vxadmin-adjudication-start-adjudicate-highlighted.png` | generated | vxadmin | reviewed match | election-night-guides/adjudication.md |
| 9 | `image (40).png` | `vxadmin-adjudication-write-in-add-candidate.png` | generated | vxadmin | hash 9 | election-night-guides/adjudication.md |
| 10 | `image (39).png` | `vxadmin-adjudication-write-in-dropdown-open.png` | generated | vxadmin | hash 9 | election-night-guides/adjudication.md |
| 11 | `backups-006-backup-saved.png` | `vxadmin-backup-saved.png` | generated | vxadmin | tail + hash 4 | vxadmin-system-setup/backup-and-restore.md |
| 12 | `image (56).png` | `vxadmin-ballot-count-report-precinct.png` | generated | vxadmin | reviewed match | election-night-guides/reports.md |
| 13 | `image (4).png` | `vxadmin-confirm-format-usb-drive-button.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/usb-formatting.md |
| 14 | `system-administrator-008-confirm-unconfigure-button.png` | `vxadmin-confirm-unconfigure-button.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/configure-vxadmin.md |
| 15 | `results-002-cvrs-loaded.png` | `vxadmin-cvrs-loaded.png` | generated | vxadmin | tail + hash 8 | election-night-guides/tally-results.md |
| 16 | `image (6).png` | `vxadmin-diagnostics-screen.png` | generated | vxadmin | reviewed match No button highlighted, so vxadmin-print-test-page-button is not a match. The current catalog capture of vxadmin-diagnostics-screen renders an empty content area (likely captured before data loaded) and should be regenerated. | vxadmin-system-setup/vxadmin-diagnostics.md |
| 17 | `system-administrator-005-election-screen-configured.png` | `vxadmin-election-screen-configured.png` | generated | vxadmin | reviewed match Catalog version has an additional Save Backup button. | vxadmin-system-setup/configure-vxadmin.md |
| 18 | `image (62).png` | `vxadmin-election-screen-revert-highlighted.png` | generated | vxadmin | reviewed match | election-night-guides/mark-results-as-official.md |
| 19 | `system-administrator-004-election-screen-select-election-package.png` | `vxadmin-election-screen-select-election-package.png` | generated | vxadmin | reviewed match Catalog version has an additional Restore from Backup button. | vxadmin-system-setup/configure-vxadmin.md |
| 20 | `system-administrator-003-election-screen-unconfigured.png` | `vxadmin-election-screen-unconfigured.png` | generated | vxadmin | reviewed match Catalog version has an additional Restore from Backup button. | vxadmin-system-setup/configure-vxadmin.md |
| 21 | `enter-card-pin-16_10 (1).jpg` | `vxadmin-enter-card-pin.png` | generated | vxadmin | reviewed match JPEG crop of the PIN entry screen; perceptual-hash candidates (VxMarkScan screens) were unrelated, matched against the catalog ID directly. | vxadmin-system-setup/unlocking-locking-hardware.md |
| 22 | `backups-001-enter-restore-mode-modal.png` | `vxadmin-enter-restore-mode-modal.png` | generated | vxadmin | tail + hash 0 | vxadmin-system-setup/backup-and-restore.md |
| 23 | `image (5).png` | `vxadmin-format-usb-drive-button.png` | generated | vxadmin | reviewed match Perceptual-hash candidates were VxPrint settings screens; matched against the catalog ID directly. | vxadmin-system-setup/usb-formatting.md |
| 24 | `image (49).png` | `vxadmin-full-election-tally-report-actions-highlighted.png` | generated | vxadmin | reviewed match Older rendition (dist 49); same screen, same highlighted action bar. | after-election-night/retaining-and-removing-election-files.md, election-night-guides/reports.md |
| 25 | `results-001-load-cvrs.png` | `vxadmin-load-cvrs.png` | generated | vxadmin | tail + hash 7 | election-night-guides/tally-results.md |
| 26 | `image (8).png` | `vxadmin-lock-machine-button.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/unlocking-locking-hardware.md |
| 27 | `machine-locked-unconfigured.png` | `vxadmin-machine-locked-unconfigured.png` | generated | vxadmin | reviewed match Catalog version adds a version/machine ID footer; same screen. | vxadmin-system-setup/unlocking-locking-hardware.md |
| 28 | `manual-tallies-contest.png` | `vxadmin-manual-tallies-contest.png` | generated | vxadmin | hash 0 | election-night-guides/manual-tallies.md |
| 29 | `image (11).png` | `vxadmin-manual-tallies-metadata-selection.png` | generated | vxadmin | reviewed match Older rendition of the same state. | election-night-guides/manual-tallies.md |
| 30 | `image (10).png` | `vxadmin-manual-tallies-tab-empty.png` | generated | vxadmin | reviewed match Older rendition: catalog version has an extra Networked Scanners tab and no page title header. | election-night-guides/manual-tallies.md |
| 31 | `manual-tallies-total-ballots-cast.png` | `vxadmin-manual-tallies-total-ballots-cast.png` | generated | vxadmin | hash 0 | election-night-guides/manual-tallies.md |
| 32 | `image (30).png` | `vxadmin-qualified-write-in-add-candidate-highlighted.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 33 | `image (27).png` | `vxadmin-qualified-write-in-add-candidates-highlighted.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 34 | `image (38).png` | `vxadmin-qualified-write-in-adjudication-contest.png` | generated | vxadmin | hash 4 | election-night-guides/adjudication.md |
| 35 | `image (35).png` | `vxadmin-qualified-write-in-adjudication-dropdown.png` | generated | vxadmin | hash 3 | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 36 | `image (33).png` | `vxadmin-qualified-write-in-save-highlighted.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 37 | `image (7).png` | `vxadmin-readiness-report.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/vxadmin-diagnostics.md |
| 38 | `image (55).png` | `vxadmin-reports-ballot-count-section-highlighted.png` | generated | vxadmin | reviewed match | election-night-guides/reports.md |
| 39 | `image (48).png` | `vxadmin-reports-full-election-tally-highlighted.png` | generated | vxadmin | reviewed match Older rendition (dist 47) but same screen and same highlighted button; sidebar slightly wider. | after-election-night/retaining-and-removing-election-files.md, election-night-guides/reports.md |
| 40 | `vxadmin-reports-screen-unofficial (1).png` | `vxadmin-reports-full-election-tally-highlighted.png` | generated | vxadmin | reviewed match Older rendition with a different header layout; same screen and highlight. | logic-and-accuracy-pre-election-testing/l-and-a-overview.md |
| 41 | `image (59).png` | `vxadmin-reports-mark-official-highlighted.png` | generated | vxadmin | reviewed match | election-night-guides/mark-results-as-official.md |
| 42 | `image (60).png` | `vxadmin-reports-screen-official.png` | generated | vxadmin | reviewed match | election-night-guides/mark-results-as-official.md |
| 43 | `vxadmin-reports-screen-unofficial-tally-report-builder-highlight.png` | `vxadmin-reports-tally-report-builder-highlighted.png` | generated | vxadmin | reviewed match Older rendition with a different header layout and an Other Reports section; same screen and highlight. | election-night-guides/reports.md |
| 44 | `image (57).png` | `vxadmin-reports-write-in-adjudication-highlighted.png` | generated | vxadmin | reviewed match | election-night-guides/reports.md |
| 45 | `backups-000-restore-from-backup-button.png` | `vxadmin-restore-from-backup-button.png` | generated | vxadmin | tail + hash 3 | vxadmin-system-setup/backup-and-restore.md |
| 46 | `image (2).png` | `vxadmin-sa-confirm-save-election-package-button.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/save-election-package.md |
| 47 | `image (1).png` | `vxadmin-sa-save-election-package-button.png` | generated | vxadmin | reviewed match Catalog version also shows a Save Backup button; same screen and highlight. | vxadmin-system-setup/save-election-package.md |
| 48 | `backups-002-save-backup-button.png` | `vxadmin-save-backup-button.png` | generated | vxadmin | tail + hash 7 | vxadmin-system-setup/backup-and-restore.md |
| 49 | `backups-003-save-backup-connect-backup-drive.png` | `vxadmin-save-backup-connect-backup-drive.png` | generated | vxadmin | tail + hash 2 | vxadmin-system-setup/backup-and-restore.md |
| 50 | `backups-005-save-backup-in-progress.png` | `vxadmin-save-backup-in-progress.png` | generated | vxadmin | tail + hash 1 | vxadmin-system-setup/backup-and-restore.md |
| 51 | `backups-004-save-backup-modal.png` | `vxadmin-save-backup-modal.png` | generated | vxadmin | tail + hash 1 | vxadmin-system-setup/backup-and-restore.md |
| 52 | `set-date-and-time-cropped.jpg` | `vxadmin-set-date-and-time.png` | generated | vxadmin | reviewed match Image is a crop of just the modal. The dialog is identical across apps; the manual page (miscellaneous/setting-date-and-time) is not app-specific, so the VxAdmin catalog shot was chosen as the closest match. | miscellaneous/setting-date-and-time.md |
| 53 | `image (3).png` | `vxadmin-smart-cards-blank-card.png` | generated | vxadmin | reviewed match Older rendition (wider sidebar, no battery indicator); same screen and state as the catalog capture. | vxadmin-system-setup/programming-cards.md |
| 54 | `system-administrator-020-smart-cards-em-existing.png` | `vxadmin-smart-cards-em-existing.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/programming-cards.md |
| 55 | `system-administrator-019-smart-cards-em-programmed.png` | `vxadmin-smart-cards-em-programmed.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/programming-cards.md |
| 56 | `system-administrator-012-smart-cards-no-card.png` | `vxadmin-smart-cards-no-card.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/programming-cards.md |
| 57 | `system-administrator-023-smart-cards-pw-existing.png` | `vxadmin-smart-cards-pw-existing.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/programming-cards.md |
| 58 | `system-administrator-022-smart-cards-pw-programmed.png` | `vxadmin-smart-cards-pw-programmed.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/programming-cards.md |
| 59 | `system-administrator-016-smart-cards-sa-existing.png` | `vxadmin-smart-cards-sa-existing.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/programming-cards.md |
| 60 | `system-administrator-015-smart-cards-sa-programmed.png` | `vxadmin-smart-cards-sa-programmed.png` | generated | vxadmin | reviewed match | vxadmin-system-setup/programming-cards.md |
| 61 | `image (51).png` | `vxadmin-tally-report-builder.png` | generated | vxadmin | reviewed match | election-night-guides/reports.md |
| 62 | `image (54).png` | `vxadmin-tally-report-builder-actions-highlighted.png` | generated | vxadmin | reviewed match | election-night-guides/reports.md |
| 63 | `image (52).png` | `vxadmin-tally-report-builder-filter-dropdown-open.png` | generated | vxadmin | reviewed match Catalog dropdown includes an extra Polling Place option; same state. | election-night-guides/reports.md |
| 64 | `image (53).png` | `vxadmin-tally-report-builder-generate-highlighted.png` | generated | vxadmin | reviewed match | election-night-guides/reports.md |
| 65 | `results-000-tally-screen-empty.png` | `vxadmin-tally-screen-empty.png` | generated | vxadmin | reviewed match Catalog version has an extra Networked Scanners tab. | election-night-guides/tally-results.md |
| 66 | `image (31).png` | `vxadmin-tally-screen-location-cvrs-panel-remove-highlighted.png` | generated | vxadmin | hash 5 | election-night-guides/tally-results.md |
| 67 | `image (61).png` | `vxadmin-tally-screen-official.png` | generated | vxadmin | reviewed match Older rendition: manual image shows the old CVR file table with Load CVRs / Remove All CVRs buttons; catalog shows the newer locations layout. Same screen and state. | election-night-guides/mark-results-as-official.md |
| 68 | `results-003-tally-screen-with-cvrs.png` | `vxadmin-tally-screen-with-cvrs.png` | generated | vxadmin | tail + hash 12 | election-night-guides/tally-results.md |
| 69 | `image (63).png` | `vxadmin-unconfigure-button.png` | generated | vxadmin | reviewed match Older rendition lacks the Save Backup button present in the catalog version; same screen and highlight. | after-election-night/retaining-and-removing-election-files.md |
| 70 | `image.png` | `vxadmin-unconfigure-button.png` | generated | vxadmin | reviewed match Catalog version has an additional Save Backup button; same screen and highlight. | vxadmin-system-setup/configure-vxadmin.md |
| 71 | `image (58).png` | `vxadmin-write-in-adjudication-report.png` | generated | vxadmin | reviewed match | election-night-guides/reports.md |
| 72 | `screenshots-013-adjudication-blank-ballot.png` | `vxcentralscan-adjudication-blank-ballot.png` | generated | vxcentralscan | tail + hash 11 | vxcentralscan/scanning-ballots.md |
| 73 | `screenshots-012-adjudication-overvote.png` | `vxcentralscan-adjudication-overvote.png` | generated | vxcentralscan | tail + hash 9 | vxcentralscan/scanning-ballots.md |
| 74 | `screenshots-015-adjudication-unreadable.png` | `vxcentralscan-adjudication-unreadable.png` | generated | vxcentralscan | tail + hash 5 | vxcentralscan/scanning-ballots.md |
| 75 | `image (71).png` | `vxcentralscan-batch-history.png` | generated | vxcentralscan | hash 9 | vxcentralscan/scanning-ballots.md |
| 76 | `screenshots-002-configuring.png` | `vxcentralscan-configuring.png` | generated | vxcentralscan | tail + hash 6 | vxcentralscan/configure-ballot-scanner.md |
| 77 | `image (72).png` | `vxcentralscan-diagnostics-screen.png` | generated | vxcentralscan | hash 11 | vxcentralscan/vxcentralscan-diagnostics.md |
| 78 | `screenshots-001-em-insert-usb.png` | `vxcentralscan-em-insert-usb.png` | generated | vxcentralscan | tail + hash 4 | vxcentralscan/configure-ballot-scanner.md |
| 79 | `screenshots-008-em-settings-confirm-unconfigure-button (1).png` | `vxcentralscan-em-settings-confirm-unconfigure-button.png` | generated | vxcentralscan | tail + hash 9 | vxcentralscan/retaining-and-removing-files-vxcentralscan.md |
| 80 | `screenshots-008-em-settings-confirm-unconfigure-button.png` | `vxcentralscan-em-settings-confirm-unconfigure-button.png` | generated | vxcentralscan | tail + hash 9 | vxcentralscan/configure-ballot-scanner.md |
| 81 | `screenshots-006-em-settings-imprinting-disabled-button.png` | `vxcentralscan-em-settings-imprinting-disabled-button.png` | generated | vxcentralscan | reviewed match Manual image shows Imprinting Enabled still selected with Disabled highlighted; catalog capture already has Disabled selected. Same highlight. | vxcentralscan/scanning-ballots.md |
| 82 | `image (43).png` | `vxcentralscan-em-settings-official-ballot-mode-button.png` | generated | vxcentralscan | reviewed match | vxcentralscan/configure-ballot-scanner.md |
| 83 | `screenshots-005-em-settings-official-ballot-mode-button.png` | `vxcentralscan-em-settings-official-ballot-mode-button.png` | generated | vxcentralscan | reviewed match Older rendition without the Imprinting section; same screen and highlight. Used on a page about all devices, not just VxCentralScan. | logic-and-accuracy-pre-election-testing/prepare-for-election-day.md |
| 84 | `screenshots-009-em-settings-save-logs-button.png` | `vxcentralscan-em-settings-save-logs-button.png` | generated | vxcentralscan | reviewed match | vxcentralscan/retaining-and-removing-files-vxcentralscan.md |
| 85 | `screenshots-007-em-settings-unconfigure-machine-button (1).png` | `vxcentralscan-em-settings-unconfigure-machine-button.png` | generated | vxcentralscan | reviewed match Duplicate of 'screenshots-007-em-settings-unconfigure-machine-button.png'. | vxcentralscan/retaining-and-removing-files-vxcentralscan.md |
| 86 | `screenshots-007-em-settings-unconfigure-machine-button.png` | `vxcentralscan-em-settings-unconfigure-machine-button.png` | generated | vxcentralscan | reviewed match Duplicate of 'screenshots-007-em-settings-unconfigure-machine-button (1).png'. | vxcentralscan/configure-ballot-scanner.md |
| 87 | `screenshots-018-readiness-report.png` | `vxcentralscan-readiness-report.png` | generated | vxcentralscan | tail + hash 12 | vxcentralscan/vxcentralscan-diagnostics.md |
| 88 | `screenshots-014-scan-ballots-batch-complete.png` | `vxcentralscan-scan-ballots-batch-complete.png` | generated | vxcentralscan | tail + hash 5 | vxcentralscan/scanning-ballots.md |
| 89 | `screenshots-011-scan-ballots-empty-batch-stats-highlight.png` | `vxcentralscan-scan-ballots-empty-batch-stats-highlight.png` | generated | vxcentralscan | tail + hash 4 | vxcentralscan/configure-ballot-scanner.md, vxcentralscan/scanning-ballots.md |
| 90 | `screenshots-011-scan-ballots-empty-start-scanning-button.png` | `vxcentralscan-scan-ballots-empty-start-scanning-button.png` | generated | vxcentralscan | tail + hash 6 | vxcentralscan/scanning-ballots.md |
| 91 | `image (68).png` | `vxcentralscan-scan-ballots-paused.png` | generated | vxcentralscan | hash 7 | vxcentralscan/scanning-ballots.md |
| 92 | `image (69).png` | `vxcentralscan-scan-ballots-save-cvrs-button.png` | generated | vxcentralscan | reviewed match Duplicate of 'screenshots-023-scan-ballots-save-cvrs-button.png'. | vxcentralscan/scanning-ballots.md |
| 93 | `screenshots-023-scan-ballots-save-cvrs-button.png` | `vxcentralscan-scan-ballots-save-cvrs-button.png` | generated | vxcentralscan | reviewed match Duplicate of 'image (69).png'. The catalog ID says scan-ballots but the screen is Batch History. | vxcentralscan/retaining-and-removing-files-vxcentralscan.md |
| 94 | `screenshots-013-scan-ballots-scanning.png` | `vxcentralscan-scan-ballots-scanning.png` | generated | vxcentralscan | tail + hash 10 | vxcentralscan/scanning-ballots.md |
| 95 | `image (34).png` | `vxcentralscan-scan-ballots-test-mode-election-info-highlight.png` | generated | vxcentralscan | reviewed match Catalog capture shows a 'No polling place selected' warning with Start Scanning disabled, whereas the manual image has a polling place selected and is ready to scan; same screen and highlight. Consider selecting a polling place before capturing. | vxcentralscan/configure-ballot-scanner.md |
| 96 | `screenshots-000-unconfigured-screen.png` | `vxcentralscan-unconfigured-screen.png` | generated | vxcentralscan | tail + hash 0 | vxcentralscan/configure-ballot-scanner.md |
| 97 | `VxMark-DiagnosticsMenu.png` | `vxmark-em-diagnostics-full.png` | generated | vxmark | reviewed match Full-page (scrolled) capture, 1080x3409. Catalog version has no polling place selected. | vxmark/diagnostics.md |
| 98 | `em-insert-usb.png` | `vxmark-em-insert-usb.png` | generated | vxmark | hash 1 | vxmark/configure-vxmark.md, vxmarkscan/configure-vxmarkscan.md |
| 99 | `VxMark-Diagnostics1.png` | `vxmark-em-menu-diagnostics-highlighted.png` | generated | vxmark | reviewed match (auto match rejected: Manual image highlights the Diagnostics button on the EM menu (diagnostics page)) | vxmark/diagnostics.md |
| 100 | `VxMark-Configure-Fix-03.png` | `vxmark-em-menu-no-polling-place.png` | generated | vxmark | hash 5 | vxmark/configure-vxmark.md |
| 101 | `VxMark-SelectPollingPlace-TESTMode.jpg` | `vxmark-em-menu-official-ballot-mode-highlighted.png` | generated | vxmark | hash 1 | logic-and-accuracy-pre-election-testing/prepare-for-election-day.md, vxmark/configure-vxmark.md |
| 102 | `VxMark-SelectPollingPlace-OFFICIALMode.jpg` | `vxmark-em-menu-test-ballot-mode-highlighted.png` | generated | vxmark | hash 1 | vxmark/configure-vxmark.md |
| 103 | `VxMark-UnconfigureMenuButton.jpg` | `vxmark-em-menu-unconfigure-highlighted.png` | generated | vxmark | hash 9 | vxmark/configure-vxmark.md |
| 104 | `VxMark-UnconfigureModal.jpg` | `vxmark-em-unconfigure-modal.png` | generated | vxmark | reviewed match Older rendition; the catalog version uses a trash icon instead of an x icon on the delete button. | vxmark/configure-vxmark.md |
| 105 | `Mark _languageaccessibility_patsize-06.jpg` | `vxmark-pat-device-identified.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md |
| 106 | `Mark _languageaccessibility_patsize-02.jpg` | `vxmark-pat-identify-move.png` | generated | vxmark | hash 1 | vxmark/voting-session-language-and-accessibility-settings.md |
| 107 | `Mark _languageaccessibility_patsize-04.jpg` | `vxmark-pat-identify-select.png` | generated | vxmark | hash 1 | vxmark/voting-session-language-and-accessibility-settings.md |
| 108 | `Mark _languageaccessibility_patsize-01.jpg` | `vxmark-pat-intro.png` | generated | vxmark | hash 2 | vxmark/voting-session-language-and-accessibility-settings.md |
| 109 | `Mark _languageaccessibility_patsize-03.jpg` | `vxmark-pat-move-identified.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md |
| 110 | `Mark _languageaccessibility_patsize-05.jpg` | `vxmark-pat-select-identified.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md |
| 111 | `blank-ballot-printing-003-print-blank-ballot-options-selected.png` | `vxmark-print-blank-ballot-options-selected.png` | generated | vxmark | tail + hash 0 | vxmark/printing-blank-ballots.md |
| 112 | `blank-ballot-printing-002-print-blank-ballot-precinct-dropdown-open.png` | `vxmark-print-blank-ballot-precinct-dropdown-open.png` | generated | vxmark | tail + hash 0 | vxmark/printing-blank-ballots.md |
| 113 | `bmd-ballot-600w.png` | `vxmark-printed-ballot.png` | generated | vxmark | reviewed match Crop of an older three-column rendition of the printed BMD ballot (Unofficial Test Ballot, older fixture election); catalog version is a full-page official ballot. Could equally represent the VxMarkScan printed ballot; README context is generic. | README.md |
| 114 | `Mark-OpenClose-ClosePolls2.jpg` | `vxmark-pw-close-polls-modal.png` | generated | vxmark | reviewed match Manual image was taken from the polls-open menu; the catalog screenshot shows the same dialog over the polls-paused menu. | vxmark/open-and-close-polls.md |
| 115 | `Mark-OpenClose-PausePolls1.jpg` | `vxmark-pw-menu-pause-voting-highlighted.png` | generated | vxmark | hash 1 | vxmark/open-and-close-polls.md |
| 116 | `Mark-OpenClose-OpenPolls1.jpg` | `vxmark-pw-menu-polls-closed.png` | generated | vxmark | hash 1 | vxmark/open-and-close-polls.md, vxmark/packing-up-vxmark.md |
| 117 | `Mark-OpenClose-ClosePolls1.jpg` | `vxmark-pw-menu-polls-open.png` | generated | vxmark | hash 1 | vxmark/open-and-close-polls.md |
| 118 | `Mark-OpenClose-OpenPolls3.jpg` | `vxmark-pw-menu-polls-open.png` | generated | vxmark | hash 1 | vxmark/open-and-close-polls.md |
| 119 | `Mark-OpenClose-PausePolls3.jpg` | `vxmark-pw-menu-polls-paused.png` | generated | vxmark | hash 3 | vxmark/open-and-close-polls.md |
| 120 | `Mark-OpenClose-ResumePolls1.jpg` | `vxmark-pw-menu-polls-paused.png` | generated | vxmark | hash 4 | vxmark/open-and-close-polls.md |
| 121 | `blank-ballot-printing-000-pw-menu-print-blank-ballot-highlighted.png` | `vxmark-pw-menu-print-blank-ballot-highlighted.png` | generated | vxmark | tail + hash 0 | vxmark/printing-blank-ballots.md |
| 122 | `Mark-OpenClose-OpenPolls2.jpg` | `vxmark-pw-open-polls-modal.png` | generated | vxmark | hash 8 | vxmark/open-and-close-polls.md |
| 123 | `Mark-OpenClose-PausePolls2.jpg` | `vxmark-pw-pause-voting-modal.png` | generated | vxmark | hash 5 | vxmark/open-and-close-polls.md |
| 124 | `VxMark_Votingsessions_Activating3.jpg` | `vxmark-pw-remove-card-to-begin.png` | generated | vxmark | hash 0 | vxmark/voting-sessions.md |
| 125 | `Mark-OpenClose-ResumePolls2.jpg` | `vxmark-pw-resume-voting-modal.png` | generated | vxmark | hash 8 | vxmark/open-and-close-polls.md |
| 126 | `Mark-OpenClose-ResumePolls3.jpg` | `vxmark-pw-start-voting-session-button.png` | generated | vxmark | hash 2 | vxmark/voting-sessions.md |
| 127 | `VxMark-Diagnostics3.png` | `vxmark-readiness-report.png` | generated | vxmark | reviewed match Catalog version shows a 'No polling place selected' warning instead of a configured polling place and ballot styles. | vxmark/diagnostics.md |
| 128 | `VxMark-Diagnostics4.png` | `vxmark-readiness-report-page2.png` | generated | vxmark | hash 3 | vxmark/diagnostics.md |
| 129 | `VxMark-Diagnostics5.png` | `vxmark-sa-menu-diagnostics-highlighted.png` | generated | vxmark | hash 3 | vxmark/diagnostics.md |
| 130 | `Mark-OpenClose-PollsClosedB4Open.jpg` | `vxmark-unauthenticated-polls-closed.png` | generated | vxmark | hash 3 | vxmark/open-and-close-polls.md |
| 131 | `VxMark_Votingsessions_Activating1.jpg` | `vxmark-unauthenticated-polls-opened.png` | generated | vxmark | hash 3 | vxmark/voting-sessions.md |
| 132 | `VxMark-Configure-Fix-01.png` | `vxmark-unconfigured-screen.png` | generated | vxmark | hash 0 | vxmark/configure-vxmark.md |
| 133 | `VxMark_Votingsessions_Reviewing3.jpg` | `vxmark-voting-almost-done.png` | generated | vxmark | hash 2 | vxmark/voting-sessions.md |
| 134 | `Mark _languageaccessibility_TOPImage1.jpg` | `vxmark-voting-language-and-settings-highlighted.png` | generated | vxmark | hash 8 | vxmark/voting-session-language-and-accessibility-settings.md |
| 135 | `Mark _languageaccessibility_BallotLanguage1.jpg` | `vxmark-voting-language-settings.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md |
| 136 | `VxMark_Votingsessions_Reviewing2.jpg` | `vxmark-voting-printing.png` | generated | vxmark | hash 1 | vxmark/voting-sessions.md |
| 137 | `VxMark_Votingsessions_Reviewing1.jpg` | `vxmark-voting-review.png` | generated | vxmark | hash 5 | vxmark/voting-sessions.md, vxmarkscan/voting-sessions.md |
| 138 | `Mark _languageaccessibility_Audio2.jpg` | `vxmark-voting-settings-audio-only-mode.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 139 | `voter-settings-002-voting-settings-color-1.png` | `vxmark-voting-settings-color-1.png` | generated | vxmark | tail + hash 0 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 140 | `voter-settings-003-voting-settings-color-2.png` | `vxmark-voting-settings-color-2.png` | generated | vxmark | tail + hash 1 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 141 | `voter-settings-004-voting-settings-color-3.png` | `vxmark-voting-settings-color-3.png` | generated | vxmark | tail + hash 7 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 142 | `voter-settings-005-voting-settings-color-4.png` | `vxmark-voting-settings-color-4.png` | generated | vxmark | tail + hash 3 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 143 | `Mark _languageaccessibility_textsize-04.jpg` | `vxmark-voting-settings-text-size-1.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 144 | `Mark _languageaccessibility_textsize-03.jpg` | `vxmark-voting-settings-text-size-2.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 145 | `Mark _languageaccessibility_textsize-02.jpg` | `vxmark-voting-settings-text-size-3.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 146 | `Mark _languageaccessibility_textsize-01 .jpg` | `vxmark-voting-settings-text-size-4.png` | generated | vxmark | hash 0 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 147 | `VxMark_Votingsessions_Marking2(No3rdImage).jpg` | `vxmark-voting-single-seat-selection.png` | generated | vxmark | hash 11 | vxmark/voting-sessions.md |
| 148 | `VxMark_Votingsessions_Marking1.jpg` | `vxmark-voting-start-screen.png` | generated | vxmark | hash 1 | vxmark/voting-sessions.md, vxmarkscan/voting-sessions.md |
| 149 | `VxMark_Votingsessions_WriteIn3.jpg` | `vxmark-voting-write-in-accepted.png` | generated | vxmark | hash 0 | vxmark/voting-sessions.md, vxmarkscan/voting-sessions.md |
| 150 | `VxMark_Votingsessions_WriteIn1.jpg` | `vxmark-voting-write-in-button.png` | generated | vxmark | hash 5 | vxmark/voting-sessions.md, vxmarkscan/voting-sessions.md |
| 151 | `VxMark_Votingsessions_WriteIn2.jpg` | `vxmark-voting-write-in-keyboard.png` | generated | vxmark | reviewed match Pixel-identical to vxmarkscan-voting-write-in-keyboard; used on both the VxMark and VxMarkScan voting-sessions pages. Chose the VxMark ID per the filename. | vxmark/voting-sessions.md, vxmarkscan/voting-sessions.md |
| 152 | `additional-options-004-em-diagnostics-full (1).png` | `vxmarkscan-em-diagnostics-full.png` | generated | vxmarkscan | tail + hash 9 | vxmarkscan/diagnostics.md |
| 153 | `additional-options-000-em-menu-diagnostics-highlighted (1).png` | `vxmarkscan-em-menu-diagnostics-highlighted.png` | generated | vxmarkscan | tail + hash 2 | vxmarkscan/diagnostics.md |
| 154 | `basic-election-flow-002-em-menu-no-polling-place.png` | `vxmarkscan-em-menu-no-polling-place.png` | generated | vxmarkscan | tail + hash 5 | vxmarkscan/configure-vxmarkscan.md |
| 155 | `basic-election-flow-004-em-menu-official-ballot-mode-highlighted.png` | `vxmarkscan-em-menu-official-ballot-mode-highlighted.png` | generated | vxmarkscan | tail + hash 1 | vxmarkscan/configure-vxmarkscan.md |
| 156 | `additional-options-001-em-menu-save-logs-highlighted.png` | `vxmarkscan-em-menu-save-logs-highlighted.png` | generated | vxmarkscan | tail + hash 2 | vxmark/retaining-and-removing-files.md, vxmarkscan/retaining-and-removing-files.md |
| 157 | `basic-election-flow-005-em-menu-test-ballot-mode-highlighted.png` | `vxmarkscan-em-menu-test-ballot-mode-highlighted.png` | generated | vxmarkscan | tail + hash 1 | vxmarkscan/configure-vxmarkscan.md |
| 158 | `basic-election-flow-031-em-menu-unconfigure-highlighted.png` | `vxmarkscan-em-menu-unconfigure-highlighted.png` | generated | vxmarkscan | tail + hash 9 | vxmarkscan/configure-vxmarkscan.md |
| 159 | `basic-election-flow-032-em-unconfigure-modal.png` | `vxmarkscan-em-unconfigure-modal.png` | generated | vxmarkscan | reviewed match Old generator output; catalog version uses a trash icon on the delete button. | vxmarkscan/configure-vxmarkscan.md |
| 160 | `basic-election-flow-028-pw-close-polls-modal.png` | `vxmarkscan-pw-close-polls-modal.png` | generated | vxmarkscan | reviewed match Manual image was taken from the polls-open menu; the catalog screenshot shows the same dialog over the polls-paused menu. | vxmarkscan/open-and-close-polls.md |
| 161 | `basic-election-flow-015-pw-load-ballot-sheet.png` | `vxmarkscan-pw-load-ballot-sheet.png` | generated | vxmarkscan | tail + hash 1 | vxmarkscan/voting-sessions.md |
| 162 | `basic-election-flow-016-pw-loading-sheet.png` | `vxmarkscan-pw-loading-sheet.png` | generated | vxmarkscan | tail + hash 0 | vxmarkscan/voting-sessions.md |
| 163 | `basic-election-flow-008-pw-menu-open-polls-highlighted.png` | `vxmarkscan-pw-menu-open-polls-highlighted.png` | generated | vxmarkscan | tail + hash 1 | vxmarkscan/open-and-close-polls.md |
| 164 | `additional-options-006-pw-menu-pause-voting-highlighted.png` | `vxmarkscan-pw-menu-pause-voting-highlighted.png` | generated | vxmarkscan | reviewed match | vxmarkscan/open-and-close-polls.md |
| 165 | `basic-election-flow-013-pw-menu-polls-open (1).png` | `vxmarkscan-pw-menu-polls-open.png` | generated | vxmarkscan | tail + hash 4 | vxmarkscan/voting-sessions.md |
| 166 | `additional-options-010-pw-menu-resume-voting-highlighted.png` | `vxmarkscan-pw-menu-resume-voting-highlighted.png` | generated | vxmarkscan | tail + hash 4 | vxmarkscan/open-and-close-polls.md |
| 167 | `basic-election-flow-010-pw-open-polls-modal.png` | `vxmarkscan-pw-open-polls-modal.png` | generated | vxmarkscan | tail + hash 10 | vxmarkscan/open-and-close-polls.md |
| 168 | `additional-options-007-pw-pause-voting-modal.png` | `vxmarkscan-pw-pause-voting-modal.png` | generated | vxmarkscan | reviewed match | vxmarkscan/open-and-close-polls.md |
| 169 | `basic-election-flow-015-pw-remove-card-to-vote.png` | `vxmarkscan-pw-remove-card-to-vote.png` | generated | vxmarkscan | tail + hash 2 | vxmarkscan/voting-sessions.md |
| 170 | `additional-options-011-pw-resume-voting-modal.png` | `vxmarkscan-pw-resume-voting-modal.png` | generated | vxmarkscan | tail + hash 7 | vxmarkscan/open-and-close-polls.md |
| 171 | `basic-election-flow-014-pw-start-voting-session-button (1).png` | `vxmarkscan-pw-start-voting-session-button.png` | generated | vxmarkscan | tail + hash 5 | vxmarkscan/voting-sessions.md |
| 172 | `additional-options-005-readiness-report.png` | `vxmarkscan-readiness-report.png` | generated | vxmarkscan | tail + hash 8 | vxmarkscan/diagnostics.md |
| 173 | `additional-options-012-sa-menu-diagnostics-highlighted.png` | `vxmarkscan-sa-menu-diagnostics-highlighted.png` | generated | vxmarkscan | tail + hash 1 | vxmarkscan/diagnostics.md |
| 174 | `sa-menu-save-logs-button.png` | `vxmarkscan-sa-menu-save-logs-highlighted.png` | generated | vxmarkscan | reviewed match Manual image is from an unconfigured machine (Unconfigure/Reset buttons disabled, no election footer), so it is indistinguishable between VxMark and VxMarkScan; it is used on both apps' retaining-files pages. vxmark-sa-menu-save-logs-highlighted is the VxMark equivalent. Catalog version is configured. | vxmark/retaining-and-removing-files.md, vxmarkscan/retaining-and-removing-files.md |
| 175 | `basic-election-flow-030-unauthenticated-polls-closed-final.png` | `vxmarkscan-unauthenticated-polls-closed-final.png` | generated | vxmarkscan | tail + hash 2 | vxmarkscan/open-and-close-polls.md |
| 176 | `basic-election-flow-011-unauthenticated-polls-opened.png` | `vxmarkscan-unauthenticated-polls-opened.png` | generated | vxmarkscan | tail + hash 3 | vxmarkscan/voting-sessions.md |
| 177 | `em-insert-card.png` | `vxmarkscan-unconfigured-screen.png` | generated | vxmarkscan | hash 0 | vxmarkscan/configure-vxmarkscan.md |
| 178 | `basic-election-flow-026-voting-ballot-cast.png` | `vxmarkscan-voting-ballot-cast.png` | generated | vxmarkscan | tail + hash 0 | vxmarkscan/voting-sessions.md |
| 179 | `basic-election-flow-025-voting-casting-ballot.png` | `vxmarkscan-voting-casting-ballot.png` | generated | vxmarkscan | tail + hash 0 | vxmarkscan/voting-sessions.md |
| 180 | `voter-settings-000-voting-language-and-settings-highlighted.png` | `vxmarkscan-voting-language-and-settings-highlighted.png` | generated | vxmarkscan | tail + hash 4 | vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 181 | `voter-settings-001-voting-language-settings.png` | `vxmarkscan-voting-language-settings.png` | generated | vxmarkscan | reviewed match Manual image lists English, Spanish and Chinese; catalog version lists more languages. vxmark-voting-language-settings (dist 8) is the VxMark rendition with English-language names. | vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 182 | `basic-election-flow-024-voting-post-print-review.png` | `vxmarkscan-voting-post-print-review.png` | generated | vxmarkscan | reviewed match Old generator output; catalog version renders filled purple checkboxes. | vxmarkscan/voting-sessions.md |
| 183 | `voting-printing.png` | `vxmarkscan-voting-printing.png` | generated | vxmarkscan | hash 0 | vxmarkscan/voting-sessions.md |
| 184 | `Mark _languageaccessibility_Audio1.jpg` | `vxmarkscan-voting-settings-audio.png` | generated | vxmarkscan | hash 1 | vxmark/voting-session-language-and-accessibility-settings.md, vxmarkscan/voting-session-language-and-accessibility-settings.md |
| 185 | `basic-election-flow-017-voting-single-seat-selection.png` | `vxmarkscan-voting-single-seat-selection.png` | generated | vxmarkscan | tail + hash 11 | vxmarkscan/voting-sessions.md |
| 186 | `VxPrint-configuration-LoadElectionPackage2.png` | `vxprint-em-configuring.png` | generated | vxprint | hash 7 | vxprint/configure-vxprint.md |
| 187 | `image (16).png` | `vxprint-em-diagnostics-full.png` | generated | vxprint | hash 7 | vxprint/vxprint-diagnostics.md |
| 188 | `VxPrint-configuration-LoadElectionPackage3.png` | `vxprint-em-election-screen.png` | generated | vxprint | hash 12 | vxprint/configure-vxprint.md |
| 189 | `VxPrint-configuration-RemoveConfigData1.png` | `vxprint-em-election-unconfigure-highlighted.png` | generated | vxprint | hash 12 | vxprint/configure-vxprint.md |
| 190 | `VxPrint-configuration-LoadElectionPackage1.png` | `vxprint-em-insert-usb.png` | generated | vxprint | hash 9 | vxprint/configure-vxprint.md |
| 191 | `VxPrint-configuration-selectapollplace.png` | `vxprint-em-polling-place-dropdown.png` | generated | vxprint | hash 12 | vxprint/configure-vxprint.md |
| 192 | `VxPrint-Printing-ElecManType1.png` | `vxprint-em-print-absentee-highlighted.png` | generated | vxprint | reviewed match Old rendition has an extra Test Decks nav item. | vxprint/printing-ballots.md |
| 193 | `VxPrint-Printing-ElecManType3-allballotstyles.png` | `vxprint-em-print-all-ballot-styles-highlighted.png` | generated | vxprint | reviewed match | vxprint/printing-ballots.md |
| 194 | `VxPrint-Printing-ElecManType3-allballotstyles-2.png` | `vxprint-em-print-all-ballot-styles-modal.png` | generated | vxprint | reviewed match | vxprint/printing-ballots.md |
| 195 | `VxPrint-Printing-ElecManType2-copies.png` | `vxprint-em-print-copies-highlighted.png` | generated | vxprint | reviewed match | vxprint/printing-ballots.md |
| 196 | `VxPrint-configuration-ChangeBallotMode2.png` | `vxprint-em-settings-ballot-mode-official-highlighted.png` | generated | vxprint | hash 8 | vxprint/configure-vxprint.md |
| 197 | `VxPrint-configuration-ChangeBallotMode1.png` | `vxprint-em-settings-ballot-mode-test-highlighted.png` | generated | vxprint | hash 9 | vxprint/configure-vxprint.md |
| 198 | `VxPrint-savelogs1.jpg` | `vxprint-em-settings-save-logs-highlighted.png` | generated | vxprint | hash 8 | vxprint/reportingandlogs.md |
| 199 | `VxPrint-savelogs2.jpg` | `vxprint-em-settings-save-logs-modal.png` | generated | vxprint | hash 7 | vxprint/reportingandlogs.md |
| 200 | `VxPrint-configuration-RemoveConfigData2.png` | `vxprint-em-unconfigure-modal.png` | generated | vxprint | reviewed match Old rendition has an extra Test Decks nav item and a different button icon; same dialog and highlight. | vxprint/configure-vxprint.md |
| 201 | `VxPrint-Reports3.png` | `vxprint-pw-ballots-printed-report.png` | generated | vxprint | reviewed match Not among the hash candidates; matched by viewing the catalog screenshot of the printed report. | vxprint/reportingandlogs.md |
| 202 | `VxPrint-Printing-Basics4-sep.png` | `vxprint-pw-print-no-split-with-selections.png` | generated | vxprint | hash 8 | vxprint/printing-ballots.md |
| 203 | `VxPrint-Printing-Basics1.png` | `vxprint-pw-print-split-no-selections.png` | generated | vxprint | hash 10 | vxprint/printing-ballots.md |
| 204 | `VxPrint-Printing-Basics2.png` | `vxprint-pw-print-split-with-selections.png` | generated | vxprint | hash 9 | vxprint/printing-ballots.md |
| 205 | `VxPrint-Printing-Basics4.png` | `vxprint-pw-printing.png` | generated | vxprint | hash 10 | vxprint/printing-ballots.md |
| 206 | `VxPrint-Reports2.png` | `vxprint-pw-report-filtered.png` | generated | vxprint | reviewed match Candidate dist was 64 but it is the same screen in the same filtered state. | vxprint/reportingandlogs.md |
| 207 | `VxPrint-Reports1.png` | `vxprint-pw-report-full.png` | generated | vxprint | reviewed match Candidate dist was 61 but it is the same screen in the same unfiltered state; old version lists more rows. | vxprint/reportingandlogs.md |
| 208 | `image (19).png` | `vxprint-readiness-report.png` | generated | vxprint | hash 6 | vxprint/vxprint-diagnostics.md |
| 209 | `VxPrint-settings.jpg` | `vxprint-sa-settings.png` | generated | vxprint | reviewed match | vxprint/configure-vxprint.md |
| 210 | `image (14).png` | `vxscan-ballot-counted.png` | generated | vxscan | hash 1 | election-day-guides/assisting-voters.md |
| 211 | `voting-013-blank-ballot-warning.png` | `vxscan-blank-ballot-warning.png` | generated | vxscan | tail + hash 0 | election-day-guides/assisting-voters.md |
| 212 | `voting-021-close-polls-button.png` | `vxscan-close-polls-button.png` | generated | vxscan | tail + hash 9 | election-day-guides/closing-polls.md |
| 213 | `configuration-023-em-diagnostics.png` | `vxscan-em-diagnostics.png` | generated | vxscan | tail + hash 8 | vxscan/vxscan-diagnostics.md |
| 214 | `configuration-024-em-diagnostics-full.png` | `vxscan-em-diagnostics-full.png` | generated | vxscan | tail + hash 12 | vxscan/vxscan-diagnostics.md |
| 215 | `image (22).png` | `vxscan-em-early-voting-button.png` | generated | vxscan | hash 8 | vxscan/additional-vxscan-settings.md |
| 216 | `configuration-002-em-election-manager-menu.png` | `vxscan-em-election-manager-menu.png` | generated | vxscan | reviewed match (auto match rejected: Same screen, but the gallery image highlights the Early Voting button, which the) | vxscan/configure-vxscan.md |
| 217 | `vxscan-insert-usb-drive.png` | `vxscan-em-insert-usb.png` | generated | vxscan | reviewed match Old image is 3470x1951; same screen. | vxscan/configure-vxscan.md |
| 218 | `image (9) (1).png` | `vxscan-em-mute-sounds.png` | generated | vxscan | hash 8 | vxscan/additional-vxscan-settings.md |
| 219 | `configuration-004-em-official-ballot-mode-button.png` | `vxscan-em-official-ballot-mode-button.png` | generated | vxscan | reviewed match Old rendition also shows the Early Voting/Election Day toggle; same highlighted control. | vxscan/configure-vxscan.md |
| 220 | `image (25).png` | `vxscan-em-official-ballot-mode-button.png` | generated | vxscan | reviewed match Older rendition lacks the Early Voting / Election Day toggle; same screen and highlighted button. | logic-and-accuracy-pre-election-testing/prepare-for-election-day.md |
| 221 | `configuration-010-em-printer-load-new-roll.png` | `vxscan-em-printer-load-new-roll.png` | generated | vxscan | reviewed match | vxscan/printer-management.md |
| 222 | `configuration-011-em-printer-paper-detected.png` | `vxscan-em-printer-paper-detected.png` | generated | vxscan | reviewed match | vxscan/printer-management.md |
| 223 | `configuration-009-em-printer-remove-roll-holder.png` | `vxscan-em-printer-remove-roll-holder.png` | generated | vxscan | tail + hash 9 | vxscan/printer-management.md |
| 224 | `configuration-008-em-printer-tab.png` | `vxscan-em-printer-tab.png` | generated | vxscan | tail + hash 9 | vxscan/printer-management.md |
| 225 | `configuration-016-em-save-cvrs-button.png` | `vxscan-em-save-cvrs-button.png` | generated | vxscan | tail + hash 8 | after-election-night/retaining-and-removing-election-files.md |
| 226 | `image (7) (1).png` | `vxscan-em-save-cvrs-button.png` | generated | vxscan | hash 8 | vxscan/additional-vxscan-settings.md |
| 227 | `configuration-017-em-save-logs-button.png` | `vxscan-em-save-logs-button.png` | generated | vxscan | tail + hash 8 | after-election-night/retaining-and-removing-election-files.md, vxscan/additional-vxscan-settings.md |
| 228 | `configuration-018-em-save-logs-modal.png` | `vxscan-em-save-logs-modal.png` | generated | vxscan | reviewed match | vxscan/additional-vxscan-settings.md |
| 229 | `image (5) (1).png` | `vxscan-em-scanner-tab.png` | generated | vxscan | hash 8 | vxscan/scanner-management.md |
| 230 | `configuration-019-em-set-date-time.png` | `vxscan-em-set-date-time.png` | generated | vxscan | tail + hash 8 | vxscan/additional-vxscan-settings.md |
| 231 | `configuration-020-em-set-date-time-modal (1).png` | `vxscan-em-set-date-time-modal.png` | generated | vxscan | reviewed match | vxscan/additional-vxscan-settings.md |
| 232 | `configuration-006-em-unconfigure-machine-button.png` | `vxscan-em-unconfigure-machine-button.png` | generated | vxscan | reviewed match Old rendition also shows the Early Voting/Election Day toggle; same highlighted control. | vxscan/configure-vxscan.md |
| 233 | `image (64).png` | `vxscan-em-unconfigure-machine-button.png` | generated | vxscan | hash 9 | after-election-night/retaining-and-removing-election-files.md |
| 234 | `configuration-007-em-unconfigure-machine-modal.png` | `vxscan-em-unconfigure-machine-modal.png` | generated | vxscan | reviewed match | vxscan/configure-vxscan.md |
| 235 | `image (15).png` | `vxscan-insert-ballot.png` | generated | vxscan | hash 3 | election-day-guides/assisting-voters.md |
| 236 | `early-voting-002-insert-ballot-early-voting.png` | `vxscan-insert-ballot-early-voting.png` | generated | vxscan | reviewed match Old rendition lacks the English language button in the top bar. | vxscan/additional-vxscan-settings.md |
| 237 | `voting-008-insert-ballot-election-info.png` | `vxscan-insert-ballot-election-info.png` | generated | vxscan | tail + hash 3 | election-day-guides/opening-polls.md |
| 238 | `voting-009-language-button.png` | `vxscan-language-button.png` | generated | vxscan | tail + hash 3 | election-day-guides/assisting-voters.md |
| 239 | `voting-010-language-settings.png` | `vxscan-language-settings.png` | generated | vxscan | reviewed match Older generator output with four languages; catalog version lists six. Same screen and state. | election-day-guides/assisting-voters.md |
| 240 | `vxscan-marginal-mark-warning.png` | `vxscan-marginal-mark-warning.png` | generated | vxscan | hash 0 | election-day-guides/assisting-voters.md |
| 241 | `voting-016-mixed-overvote-undervote-warning.png` | `vxscan-mixed-overvote-undervote-warning.png` | generated | vxscan | tail + hash 1 | election-day-guides/assisting-voters.md |
| 242 | `voting-002-open-polls-button.png` | `vxscan-open-polls-button.png` | generated | vxscan | tail + hash 8 | election-day-guides/opening-polls.md |
| 243 | `voting-015-overvote-warning.png` | `vxscan-overvote-warning.png` | generated | vxscan | tail + hash 0 | election-day-guides/assisting-voters.md |
| 244 | `vxscan-pat-tutortial-06.png` | `vxscan-pat-device-identified.png` | generated | vxscan | hash 11 | election-day-guides/assisting-voters.md |
| 245 | `vxscan-pat-tutortial-02.png` | `vxscan-pat-identify-move.png` | generated | vxscan | hash 3 | election-day-guides/assisting-voters.md |
| 246 | `vxscan-pat-tutortial-04.png` | `vxscan-pat-identify-select.png` | generated | vxscan | reviewed match (auto match rejected: Manual image is step 3 of 3, Identify the Select Input (captioned Step 3 on the ) | election-day-guides/assisting-voters.md |
| 247 | `vxscan-pat-tutortial-01.png` | `vxscan-pat-intro.png` | generated | vxscan | hash 6 | election-day-guides/assisting-voters.md |
| 248 | `vxscan-pat-tutortial-03.png` | `vxscan-pat-move-identified.png` | generated | vxscan | hash 3 | election-day-guides/assisting-voters.md |
| 249 | `vxscan-pat-tutortial-05.png` | `vxscan-pat-select-identified.png` | generated | vxscan | reviewed match (auto match rejected: Manual image is step 3 of 3, Input Identified: Select (the Input identified capt) | election-day-guides/assisting-voters.md |
| 250 | `voting-025-polls-closed.png` | `vxscan-polls-closed-final.png` | generated | vxscan | hash 3 | election-day-guides/closing-polls.md |
| 251 | `image (10) (1).png` | `vxscan-polls-closed-initial.png` | generated | vxscan | hash 3 | election-day-guides/opening-polls.md |
| 252 | `polls-closed.png` | `vxscan-polls-closed-initial.png` | generated | vxscan | reviewed match Image is 3470x1951 (scaled). | logic-and-accuracy-pre-election-testing/prepare-for-election-day.md |
| 253 | `voting-038-polls-closed-report-multi-batch.png` | `vxscan-polls-closed-report-multi-batch.png` | generated | vxscan | reviewed match | election-day-guides/closing-polls.md |
| 254 | `voting-003-polls-opened.png` | `vxscan-polls-opened.png` | generated | vxscan | tail + hash 9 | election-day-guides/opening-polls.md |
| 255 | `por-west-lincoln.png` | `vxscan-polls-opened-report.png` | generated | vxscan | hash 5 | election-day-guides/opening-polls.md |
| 256 | `voting-034-pw-menu-button.png` | `vxscan-pw-menu-button.png` | generated | vxscan | tail + hash 9 | vxscan/additional-poll-worker-actions.md |
| 257 | `voting-035-pw-pause-voting-button.png` | `vxscan-pw-pause-voting-button.png` | generated | vxscan | tail + hash 9 | vxscan/additional-poll-worker-actions.md |
| 258 | `image (23).png` | `vxscan-pw-pause-voting-prompt-button.png` | generated | vxscan | reviewed match | vxscan/additional-vxscan-settings.md |
| 259 | `image (18).png` | `vxscan-pw-power-down.png` | generated | vxscan | hash 9 | election-day-guides/packing-up-vxscan.md |
| 260 | `voting-027-pw-print-polls-closed-report-button.png` | `vxscan-pw-print-polls-closed-report-button.png` | generated | vxscan | tail + hash 11 | vxscan/additional-poll-worker-actions.md |
| 261 | `voting-006-pw-print-polls-opened-report-button.png` | `vxscan-pw-print-polls-opened-report-button.png` | generated | vxscan | tail + hash 8 | vxscan/additional-poll-worker-actions.md |
| 262 | `write-in-report-000-pw-print-write-in-image-report-button.png` | `vxscan-pw-print-write-in-image-report-button.png` | generated | vxscan | tail + hash 10 | vxscan/additional-poll-worker-actions.md |
| 263 | `voting-031-pw-resume-voting-button.png` | `vxscan-pw-resume-voting-button.png` | generated | vxscan | tail + hash 10 | vxscan/additional-poll-worker-actions.md |
| 264 | `voting-036-pw-voting-paused.png` | `vxscan-pw-voting-paused.png` | generated | vxscan | tail + hash 10 | vxscan/additional-poll-worker-actions.md |
| 265 | `voting-032-pw-voting-resumed.png` | `vxscan-pw-voting-resumed.png` | generated | vxscan | tail + hash 10 | vxscan/additional-poll-worker-actions.md |
| 266 | `write-in-report-001-pw-write-in-image-report-printed.png` | `vxscan-pw-write-in-image-report-printed.png` | generated | vxscan | tail + hash 11 | vxscan/additional-poll-worker-actions.md |
| 267 | `readiness-report-1 (2).png` | `vxscan-readiness-report.png` | generated | vxscan | hash 12 | vxscan/vxscan-diagnostics.md |
| 268 | `voting-024-reprint-polls-closed-report-button.png` | `vxscan-reprint-polls-closed-report-button.png` | generated | vxscan | tail + hash 12 | election-day-guides/closing-polls.md |
| 269 | `image (6) (1).png` | `vxscan-sa-calibrate-image-sensors.png` | generated | vxscan | hash 8 | vxscan/scanner-management.md |
| 270 | `configuration-030-sa-diagnostics.png` | `vxscan-sa-diagnostics.png` | generated | vxscan | tail + hash 10 | vxscan/vxscan-diagnostics.md |
| 271 | `image (8) (1).png` | `vxscan-sa-reset-polls-to-paused-button.png` | generated | vxscan | hash 9 | vxscan/additional-vxscan-settings.md |
| 272 | `configuration-031-sa-save-logs-button.png` | `vxscan-sa-save-logs-button.png` | generated | vxscan | tail + hash 8 | vxscan/additional-vxscan-settings.md |
| 273 | `configuration-029-sa-set-date-time.png` | `vxscan-sa-set-date-time.png` | generated | vxscan | tail + hash 9 | vxscan/additional-vxscan-settings.md |
| 274 | `vxscan-sys-admin-unconfigure-machine.png` | `vxscan-sa-unconfigure-machine-button.png` | generated | vxscan | reviewed match Not among the hash candidates (old image is 2880x1620); matched by viewing the catalog screenshot. | vxscan/configure-vxscan.md |
| 275 | `image (13) (1).png` | `vxscan-scanning.png` | generated | vxscan | hash 1 | election-day-guides/assisting-voters.md |
| 276 | `voting-017-settings-button.png` | `vxscan-settings-button.png` | generated | vxscan | tail + hash 5 | election-day-guides/assisting-voters.md |
| 277 | `color-mode.png` | `vxscan-settings-color.png` | generated | vxscan | reviewed match Older rendition at HiDPI (3470x1951) with a 'Settings:' colon in the heading; same screen and state. | election-day-guides/assisting-voters.md |
| 278 | `text-size-mode.png` | `vxscan-settings-text-size.png` | generated | vxscan | reviewed match Older rendition at HiDPI (3470x1951) with a 'Settings:' colon in the heading; same screen and state. | election-day-guides/assisting-voters.md |
| 279 | `early-voting-001-unauthenticated-early-voting.png` | `vxscan-unauthenticated-early-voting.png` | generated | vxscan | tail + hash 2 | vxscan/additional-vxscan-settings.md |
| 280 | `vxscan-insert-card.png` | `vxscan-unconfigured-screen.png` | generated | vxscan | reviewed match Old image is 3470x1951; same screen. | vxscan/configure-vxscan.md |
| 281 | `image (24).png` | `vxscan-undervote-warning.png` | generated | vxscan | hash 1 | election-day-guides/assisting-voters.md |
| 282 | `voting-030-voting-paused.png` | `vxscan-voting-paused.png` | generated | vxscan | tail + hash 3 | vxscan/additional-poll-worker-actions.md |
| 283 | `multi-station-6.png` | `vxadmin-adjudication-multi-station-disable-highlighted.png` | unspecced | vxadmin | Image is 3072x1920 (scaled). wanted: Host VxAdmin as election manager with multi-station enabled and all ballots adjudicated, Adjudication screen, highlighting the Disable button. | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 284 | `multi-station-4.png` | `vxadmin-adjudication-multi-station-enable-highlighted.png` | unspecced | vxadmin | Same screen as multi-station-2 with the Enable Multi-Station button highlighted. Image is 3072x1920 (scaled). wanted: Host VxAdmin as election manager with CVRs loaded and stations connected, Adjudication screen, highlighting the Enable Multi-Station button. | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 285 | `multi-station-3.png` | `vxadmin-adjudication-multi-station-network-offline.png` | unspecced | vxadmin | Image is 3072x1920 (scaled). wanted: Host VxAdmin as election manager with CVRs loaded, Adjudication screen while the network connection is down. | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 286 | `multi-station-2.png` | `vxadmin-adjudication-multi-station-off.png` | unspecced | vxadmin | Image is 3072x1920 (scaled). wanted: Host VxAdmin as election manager with CVRs loaded and networking on, Adjudication screen with several adjudication stations connected and multi-station not yet enabled. | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 287 | `multi-station-5.png` | `vxadmin-adjudication-multi-station-online.png` | unspecced | vxadmin | Image is 3072x1920 (scaled). wanted: Host VxAdmin as election manager after enabling multi-station, Adjudication screen with stations in a mix of statuses (active, adjudicating, locked, disconnected). | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 288 | `vxadmin-election-manager-settings-screen-logs-highlight.png` | `vxadmin-em-settings-save-logs-highlighted.png` | unspecced | vxadmin | Catalog only has the system administrator version (vxadmin-sa-save-logs-button, with Smart Cards nav and USB Formatting section); this one shows the election manager nav (Election, Tally, Adjudication, Reports, Settings, Diagnostics). Older header layout. wanted: VxAdmin configured with an election, logged in as election manager, Settings page selected, with the Save Logs button highlighted. | after-election-night/retaining-and-removing-election-files.md |
| 289 | `multi-station-1.png` | `vxadmin-sa-settings-switch-to-adjudication-station-highlighted.png` | unspecced | vxadmin | Multi-station adjudication screens are not in the current catalog. Image is 3072x1920 (scaled). wanted: VxAdmin as system administrator with networking enabled, Settings screen, highlighting the Switch to Adjudication Station Mode button under Machine Mode. | vxadmin-system-setup/pre-election-adjudication-setup.md |
| 290 | `vxadmin-tally-screen-with-cvrs.png` | `vxadmin-tally-screen-with-cvrs-remove-all-highlighted.png` | unspecced | vxadmin | Older CVR file-table layout. Catalog has vxadmin-tally-screen-with-cvrs (no highlight) and vxadmin-tally-screen-location-cvrs-panel-remove-highlighted (highlights a single file's trash icon, a different control). wanted: VxAdmin as election manager, Tally screen on the Cast Vote Records tab with at least one CVR export loaded, highlighting the Remove All button. | logic-and-accuracy-pre-election-testing/prepare-for-election-day.md |
| 291 | `basic-election-flow-027-pw-menu-close-polls-highlighted.png` | `vxmarkscan-pw-menu-polls-open-close-polls-highlighted.png` | unspecced | vxmarkscan | Existing vxmarkscan-pw-menu-close-polls-highlighted shows the polls-paused menu (Resume Voting / Close Polls layout), a different state; vxmarkscan-pw-menu-polls-open is the same menu without the highlight. wanted: VxMarkScan configured with polls open, poll worker card inserted, poll worker menu shown with the Close Polls button highlighted (no dialog). | vxmarkscan/open-and-close-polls.md |
| 292 | `vxscan-headphone-audio-settings.png` | `vxscan-a11y-settings-audio-headphones-connected.png` | unspecced | vxscan | Candidate vxscan-a11y-settings-audio shows the no-headphones state ('Audio is muted', 'No headphones detected'); this image shows the connected state, so a new id. wanted: VxScan with polls open and headphones connected, voter Settings opened from the header, Audio tab selected (audio on, volume and rate of speech controls visible). | election-day-guides/assisting-voters.md |
| 293 | `vxscan-test-mode.png` | `vxscan-polls-closed-test-ballot-mode.png` | unspecced | vxscan | Catalog has no test-mode variant of the polls closed screen. Image is 2880x1620 (2x scale). wanted: VxScan configured in test ballot mode, no card inserted, polls closed, before any sheets are scanned. | logic-and-accuracy-pre-election-testing/l-and-a-overview.md |
| 294 | `signed-hash-validation.png` | `vxscan-pw-signed-hash-validation.png` | unspecced | vxscan | Catalog has vxscan-em-signed-hash-validation and vxscan-sa-signed-hash-validation (same modal over the election manager / system administrator menus) but no poll worker version. Image is 3470x1951 (scaled); manual notes it is from a dev unit (UNVERIFIED hash). wanted: VxScan with a poll worker card inserted, voting paused, open Signed Hash Validation from the poll worker menu. | miscellaneous/signed-hash-validation.md |
| 295 | `hmpb-600w.png` | `diagram-hmpb-test-ballot-page-1.png` | manual-photo |  | Not a screen of any app; a rendered HMPB from the hmpb library. No catalog screenshot shows a printed HMPB, so the id uses no app prefix. Reclassified as diagram: not a VxSuite screen. | README.md |
| 296 | `Hash Validation check voting works.png` | `diagram-signed-hash-validation-check-site-verified.png` | manual-photo |  | Phone screenshot of the VotingWorks hash-check website, not one of the six apps, so no app prefix; could alternatively be treated as diagram-signed-hash-validation-check-site. Not reproducible from the screenshot suites. Reclassified as diagram: not a VxSuite screen. | miscellaneous/signed-hash-validation.md |
| 297 | `image (678).png` | `diagram-smart-card-types.png` | manual-photo |  |  | vxadmin-system-setup/programming-cards.md |
| 298 | `smartcard-laptop-16_10.png` | `photo-laptop-insert-smart-card.png` | manual-photo |  | Shared by VxAdmin and VxCentralScan pages (same laptop hardware), so not app-specific. | vxadmin-system-setup/programming-cards.md, vxadmin-system-setup/unlocking-locking-hardware.md, vxcentralscan/configure-ballot-scanner.md |
| 299 | `printer case.png` | `photo-printer-in-case.png` | manual-photo |  | Shared by VxAdmin and VxPrint hardware setup pages. | vxadmin-system-setup/vxadmin-hardware-setup.md, vxprint/vxprint-hardware-setup.md |
| 300 | `printer power.png` | `photo-printer-power-button.png` | manual-photo |  | Shared by VxAdmin and VxPrint hardware setup pages. | vxadmin-system-setup/vxadmin-hardware-setup.md, vxprint/vxprint-hardware-setup.md |
| 301 | `printer plug.png` | `photo-printer-power-cord-port.png` | manual-photo |  | Shared by VxAdmin and VxPrint hardware setup pages. | vxadmin-system-setup/vxadmin-hardware-setup.md, vxprint/vxprint-hardware-setup.md |
| 302 | `VxAdmin in case.png` | `photo-vxadmin-case-closed.png` | manual-photo | vxadmin |  | vxadmin-system-setup/vxadmin-hardware-setup.md |
| 303 | `VxAdmin case latches.png` | `photo-vxadmin-case-latches.png` | manual-photo | vxadmin | Very low resolution (244x154). | vxadmin-system-setup/vxadmin-hardware-setup.md |
| 304 | `VxAdmin case sealed.png` | `photo-vxadmin-case-seals.png` | manual-photo | vxadmin | Appears to be the same photograph as image (692).png at a much lower resolution (205x154); given the same ID, keep the larger copy. | vxadmin-system-setup/vxadmin-hardware-setup.md |
| 305 | `image (692).png` | `photo-vxadmin-case-seals.png` | manual-photo | vxadmin | Same photograph as VxAdmin case sealed.png (higher-resolution copy); same ID assigned. | vxadmin-system-setup/vxadmin-hardware-setup.md |
| 306 | `PXL_20241119_220230549.jpg` | `photo-vxadmin-laptop-in-case.jpg` | manual-photo | vxadmin |  | vxadmin-system-setup/vxadmin-hardware-setup.md |
| 307 | `PXL_20241119_220512937.jpg` | `photo-vxadmin-peripherals-in-case.jpg` | manual-photo | vxadmin |  | vxadmin-system-setup/vxadmin-hardware-setup.md |
| 308 | `PXL_20241119_221005359.jpg` | `photo-vxadmin-setup.jpg` | manual-photo | vxadmin | Unlabeled version of photo-vxadmin-setup-labeled. | vxadmin-system-setup/vxadmin-hardware-setup.md |
| 309 | `PXL_20241119_221005359 (1).jpg` | `photo-vxadmin-setup-labeled.jpg` | manual-photo | vxadmin | Same photograph as PXL_20241119_221005359.jpg but with A/B/C callout labels added; also used on the VxPrint hardware setup page. | vxadmin-system-setup/vxadmin-hardware-setup.md, vxprint/vxprint-hardware-setup.md |
| 310 | `Vxcs case latches.png` | `photo-vxcentralscan-case-latches.png` | manual-photo | vxcentralscan |  | vxcentralscan/vxcentralscan-hardware-setup.md |
| 311 | `image (397).png` | `photo-vxcentralscan-case-seals.png` | manual-photo | vxcentralscan |  | vxcentralscan/vxcentralscan-hardware-setup.md |
| 312 | `vxcentralscan-in-cases-22_10 (1).png` | `photo-vxcentralscan-in-cases.png` | manual-photo | vxcentralscan | angle-bracket markdown link; classified by hand | vxcentralscan/vxcentralscan-hardware-setup.md |
| 313 | `PXL_20241119_220118873 (1).jpg` | `photo-vxcentralscan-laptop-in-case.jpg` | manual-photo | vxcentralscan | angle-bracket markdown link; classified by hand | vxcentralscan/vxcentralscan-hardware-setup.md |
| 314 | `PXL_20241119_220606004.jpg` | `photo-vxcentralscan-peripherals-in-case.jpg` | manual-photo | vxcentralscan |  | vxcentralscan/vxcentralscan-hardware-setup.md |
| 315 | `ricoh-03-4_3.jpeg` | `photo-vxcentralscan-scanner-power-button-labeled.jpg` | manual-photo | vxcentralscan |  | vxcentralscan/vxcentralscan-hardware-setup.md |
| 316 | `PXL_20241125_223330294.jpg` | `photo-vxcentralscan-scanner-rear-ports-labeled.jpg` | manual-photo | vxcentralscan |  | vxcentralscan/vxcentralscan-hardware-setup.md |
| 317 | `ricoh-01-4_3.jpeg` | `photo-vxcentralscan-scanner-ricoh-fi8170.jpg` | manual-photo | vxcentralscan |  | vxcentralscan/vxcentralscan-hardware-setup.md |
| 318 | `ricoh-02-4_3.jpeg` | `photo-vxcentralscan-scanner-trays-labeled.jpg` | manual-photo | vxcentralscan |  | vxcentralscan/vxcentralscan-hardware-setup.md |
| 319 | `centralscan.jpg` | `photo-vxcentralscan-setup.jpg` | manual-photo | vxcentralscan | Referenced twice on the VxCentralScan hardware setup page (Hardware Overview and Setup). | vxcentralscan/vxcentralscan-hardware-setup.md |
| 320 | `Mark _packingup_image3.jpg` | `photo-vxmark-accessible-controller.jpg` | manual-photo | vxmark |  | vxmark/packing-up-vxmark.md |
| 321 | `Mark _setup_image4.jpg` | `photo-vxmark-back-compartment-cables.jpg` | manual-photo | vxmark |  | vxmark/vxmark-hardware-setup.md |
| 322 | `Mark _packingup_image5.jpg` | `photo-vxmark-case-closed.jpg` | manual-photo | vxmark |  | vxmark/packing-up-vxmark.md |
| 323 | `Mark _packingup_image4.jpg` | `photo-vxmark-case-open-screen-flat.jpg` | manual-photo | vxmark |  | vxmark/packing-up-vxmark.md |
| 324 | `Mark _setup_image1.jpg` | `photo-vxmark-cases-closed.jpg` | manual-photo | vxmark | File is actually an AVIF image with a .jpg extension (the Read tool cannot open it; converted with ffmpeg to view). Consider re-encoding as JPEG/PNG when renaming. | vxmark/vxmark-hardware-setup.md |
| 325 | `VxMark_Image.jpg` | `photo-vxmark-full-setup.jpg` | manual-photo | vxmark | Batch metadata lists 769x1600 but the image renders landscape (likely EXIF rotation); display is on the unconfigured screen. | README.md |
| 326 | `Mark _packingup_image2.jpg` | `photo-vxmark-headphones-compartment.jpg` | manual-photo | vxmark | Batch file has no width/height for this item; the image itself is a large JPEG. | vxmark/packing-up-vxmark.md |
| 327 | `Mark _configure_image1.jpg` | `photo-vxmark-insert-smart-card.jpg` | manual-photo | vxmark | Batch recorded null width/height for this file; image loads fine (1920x1080-ish JPEG). | vxmark/configure-vxmark.md |
| 328 | `Mark _packingup_image7.jpg` | `photo-vxmark-printer-in-case.jpg` | manual-photo | vxmark |  | vxmark/packing-up-vxmark.md |
| 329 | `Mark _setup_image6.jpg` | `photo-vxmark-printer-power-button.jpg` | manual-photo | vxmark | Annotated photo (yellow callout). Referenced from both hardware setup and pack-up pages. | vxmark/packing-up-vxmark.md, vxmark/vxmark-hardware-setup.md |
| 330 | `Mark _setup_image5.jpg` | `photo-vxmark-printer-rear-ports.jpg` | manual-photo | vxmark | Annotated photo (yellow callouts). | vxmark/vxmark-hardware-setup.md |
| 331 | `Mark _setup_image3.jpg` | `photo-vxmark-rotate-screen.jpg` | manual-photo | vxmark |  | vxmark/vxmark-hardware-setup.md |
| 332 | `Mark _setup_image2.jpg` | `photo-vxmark-tilt-screen-forward.jpg` | manual-photo | vxmark |  | vxmark/vxmark-hardware-setup.md |
| 333 | `VxMark ballot bin.png` | `photo-vxmarkscan-ballot-bin.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 334 | `VxMark ballot bin attached.png` | `photo-vxmarkscan-ballot-bin-attached.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 335 | `VxMark ballot bin seal.png` | `photo-vxmarkscan-ballot-bin-seal.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 336 | `PXL_20241119_202236326.jpg` | `photo-vxmarkscan-case-ballot-bin-privacy-shield.jpg` | manual-photo | vxmarkscan | Ballot bin carries a County of Los Angeles seal. | vxmarkscan/packing-up-vxmarkscan.md |
| 337 | `PXL_20241119_202304226.jpg` | `photo-vxmarkscan-case-ballot-bin-stand.jpg` | manual-photo | vxmarkscan | Ballot bin carries a County of Los Angeles seal. | vxmarkscan/packing-up-vxmarkscan.md |
| 338 | `PXL_20241125_224803109.jpg` | `photo-vxmarkscan-cleaning-printer-scanner.jpg` | manual-photo | vxmarkscan | Batch lists 769x4080 but image is 4080x3072 landscape. | vxmarkscan/vxmarkscan-hardware-setup.md |
| 339 | `vxmarkscan-1200w.png` | `photo-vxmarkscan-full-setup.png` | manual-photo | vxmarkscan |  | README.md |
| 340 | `image (26).png` | `photo-vxmarkscan-headphones-plugged-in.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 341 | `VxMark main unit.png` | `photo-vxmarkscan-main-unit.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 342 | `PXL_20241119_201847102.jpg` | `photo-vxmarkscan-peripherals-case-packed.jpg` | manual-photo | vxmarkscan | Batch lists 769x2000 but image is 2000x1506 landscape. | vxmarkscan/packing-up-vxmarkscan.md |
| 343 | `VxMark power block.png` | `photo-vxmarkscan-power-block.png` | manual-photo | vxmarkscan |  | vxmarkscan/packing-up-vxmarkscan.md |
| 344 | `VxMark add power cord holder.png` | `photo-vxmarkscan-power-block-holder.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 345 | `VxMark power block in holder.png` | `photo-vxmarkscan-power-block-in-holder.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 346 | `VxMark power button.png` | `photo-vxmarkscan-power-button.png` | manual-photo | vxmarkscan | Same photograph as 'VxMark unit plug plugged in.png' with an added arrow annotation. Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 347 | `VxMark unit plug.png` | `photo-vxmarkscan-power-cord-connector.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 348 | `VxMark unit plug plugged in.png` | `photo-vxmarkscan-power-cord-connector-plugged-in.png` | manual-photo | vxmarkscan | Same photograph as 'VxMark power button.png' without the arrow annotation. Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 349 | `VxMark power cord plugged into UPS.png` | `photo-vxmarkscan-power-cord-plugged-into-ups.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 350 | `VxMark power cord.png` | `photo-vxmarkscan-power-plug.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 351 | `VxMark printer cover open.png` | `photo-vxmarkscan-printer-cover-open.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 352 | `VxMark privacy shield holes.png` | `photo-vxmarkscan-privacy-shield-holes.png` | manual-photo | vxmarkscan | Low-resolution crop with blue circle annotations; shows an older light-grey unit. | vxmarkscan/vxmarkscan-hardware-setup.md |
| 353 | `VxMark privacy shield installed.png` | `photo-vxmarkscan-privacy-shield-installed.png` | manual-photo | vxmarkscan | Low resolution (856x540). Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 354 | `VxMark privacy shield pegs highlighted.png` | `photo-vxmarkscan-privacy-shield-pegs.png` | manual-photo | vxmarkscan | Low-resolution image with blue circle annotations. | vxmarkscan/vxmarkscan-hardware-setup.md |
| 355 | `VxMark pull leg.png` | `photo-vxmarkscan-pull-stand-leg.png` | manual-photo | vxmarkscan |  | vxmarkscan/packing-up-vxmarkscan.md |
| 356 | `VxMark push ballot bin release to remove.png` | `photo-vxmarkscan-push-ballot-bin-release.png` | manual-photo | vxmarkscan |  | vxmarkscan/packing-up-vxmarkscan.md |
| 357 | `VxMark open printer cover.png` | `photo-vxmarkscan-push-printer-cover-button.png` | manual-photo | vxmarkscan | Page text before the next image is 'Push the printer cover button'; this photo shows that step. Distinct from 'VxMark printer cover open.png'. | vxmarkscan/vxmarkscan-hardware-setup.md |
| 358 | `VxMark printer cover open remove ballot bin.png` | `photo-vxmarkscan-remove-ballot-bin.png` | manual-photo | vxmarkscan |  | vxmarkscan/packing-up-vxmarkscan.md |
| 359 | `PXL_20241119_204113175.jpg` | `photo-vxmarkscan-smart-card-reader.jpg` | manual-photo | vxmarkscan | Referenced from both the configure page (inserting smart cards) and the open polls page. | vxmarkscan/configure-vxmarkscan.md, vxmarkscan/open-and-close-polls.md |
| 360 | `VxMark all legs raised.png` | `photo-vxmarkscan-stand-all-legs-raised.png` | manual-photo | vxmarkscan | Filename says VxMark but the page is the VxMarkScan hardware setup; the unit shown in the related photos has the built-in printer. | vxmarkscan/vxmarkscan-hardware-setup.md |
| 361 | `VxMark all legs down.png` | `photo-vxmarkscan-stand-folded.png` | manual-photo | vxmarkscan |  | vxmarkscan/packing-up-vxmarkscan.md |
| 362 | `VxMark one leg raised.png` | `photo-vxmarkscan-stand-one-leg-raised.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 363 | `VxMark stand power cord holder and power block istalled.png` | `photo-vxmarkscan-stand-power-block-installed.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 364 | `VxMark raising one leg.png` | `photo-vxmarkscan-stand-raise-leg.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 365 | `VxMark support bar.png` | `photo-vxmarkscan-stand-support-bar.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 366 | `VxMark support bar installed.png` | `photo-vxmarkscan-stand-support-bar-installed.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 367 | `VxMark put support bar in place.png` | `photo-vxmarkscan-support-bar.png` | manual-photo | vxmarkscan | Referenced from both hardware setup and pack-up pages. | vxmarkscan/packing-up-vxmarkscan.md, vxmarkscan/vxmarkscan-hardware-setup.md |
| 368 | `VxMark place unit on legs.png` | `photo-vxmarkscan-unit-on-stand.png` | manual-photo | vxmarkscan |  | vxmarkscan/vxmarkscan-hardware-setup.md |
| 369 | `PXL_20241125_222936358.jpg` | `photo-vxmarkscan-usb-port.jpg` | manual-photo | vxmarkscan | Annotated photo (cyan arrow). Batch lists 769x4080 but the image is 4032x2268 landscape. | vxmarkscan/configure-vxmarkscan.md |
| 370 | `VxPrint-configuration-smartcardinsert.png` | `photo-vxprint-insert-smart-card.jpg` | manual-photo | vxprint | File is actually AVIF data despite the .png extension; it was converted to PNG in the scratchpad to view. Same generic laptop photo may be reused by other laptop apps. | vxprint/configure-vxprint.md |
| 371 | `PXL_20241031_184245241.jpg` | `photo-vxscan-access-door-open-scanner-closed.jpg` | manual-photo | vxscan | Portrait phone photo; section is Scanner Cleaning. | vxscan/scanner-management.md |
| 372 | `PXL_20241031_184238006.jpg` | `photo-vxscan-access-door-release-latch.jpg` | manual-photo | vxscan | Portrait phone photo; section is Scanner Cleaning. | vxscan/scanner-management.md |
| 373 | `vxscan - emergency bin putting a ballot in.png` | `photo-vxscan-auxiliary-bin-insert-ballot.png` | manual-photo | vxscan | Manual calls it the emergency bin in the filename but the page heading is Auxiliary Bin. | election-day-guides/vxscan-setup.md |
| 374 | `vxscan emergency bin.png` | `photo-vxscan-auxiliary-bin-location.png` | manual-photo | vxscan | Photo has an annotation arrow drawn on it. | election-day-guides/vxscan-setup.md |
| 375 | `vxscan emergency bin out and sealed.png` | `photo-vxscan-auxiliary-bin-seal-highlighted.png` | manual-photo | vxscan | Photo has an annotation rectangle drawn on it. | election-day-guides/vxscan-setup.md |
| 376 | `PXL_20241031_185834321.jpg` | `photo-vxscan-ballot-box-collapsed.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 377 | `PXL_20241031_182758328.jpg` | `photo-vxscan-ballot-box-collapsed-straps-closed.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 378 | `PXL_20241031_185822709.jpg` | `photo-vxscan-ballot-box-collapsing.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 379 | `PXL_20241031_184832238.jpg` | `photo-vxscan-ballot-box-door-sealed.jpg` | manual-photo | vxscan | Portrait phone photo. | election-day-guides/vxscan-setup.md |
| 380 | `PXL_20241031_183046879.jpg` | `photo-vxscan-ballot-box-expanded-lid-closed.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 381 | `PXL_20241031_183032911.jpg` | `photo-vxscan-ballot-box-expanded-lid-open.jpg` | manual-photo | vxscan | Used in both VxScan Setup (box fully expanded) and Packing Up (after lifting the lid). | election-day-guides/packing-up-vxscan.md, election-day-guides/vxscan-setup.md |
| 382 | `PXL_20241031_183116725.jpg` | `photo-vxscan-ballot-box-expanded-top-view.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 383 | `PXL_20241031_185919884.jpg` | `photo-vxscan-ballot-box-fasten-strap.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 384 | `PXL_20241031_182921409.jpg` | `photo-vxscan-ballot-box-fasten-strap-to-lid.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 385 | `PXL_20241031_185802759.jpg` | `photo-vxscan-ballot-box-foot-hook.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 386 | `PXL_20241031_183004440.jpg` | `photo-vxscan-ballot-box-lid-straps-stored.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 387 | `PXL_20241031_185738805.jpg` | `photo-vxscan-ballot-box-lift-lid.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 388 | `PXL_20241031_183140058.jpg` | `photo-vxscan-ballot-box-lifting-lid.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 389 | `PXL_20241031_185722806.jpg` | `photo-vxscan-ballot-box-press-lid-latch.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 390 | `PXL_20241031_185851437.jpg` | `photo-vxscan-ballot-box-remove-strap-from-lid.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 391 | `PXL_20241031_190014226.jpg` | `photo-vxscan-ballot-box-strapped.jpg` | manual-photo | vxscan | Very similar to PXL_20241031_182758328.jpg (item 35) but without the telescoping handle extended. | election-day-guides/packing-up-vxscan.md |
| 392 | `PXL_20241031_185927692.jpg` | `photo-vxscan-ballot-box-tighten-strap.jpg` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 393 | `PXL_20241031_182928523.jpg` | `photo-vxscan-ballot-box-tighten-strap-to-lid.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 394 | `PXL_20241031_183652085.jpg` | `photo-vxscan-case-back-cord-plugged-in.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 395 | `PXL_20241031_183628378.jpg` | `photo-vxscan-case-back-cord-wrapped.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 396 | `VxScan open the latches.png` | `photo-vxscan-case-latches.png` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 397 | `PXL_20241031_183312800.jpg` | `photo-vxscan-case-on-ballot-box.jpg` | manual-photo | vxscan |  | election-day-guides/vxscan-setup.md |
| 398 | `PXL_20241031_182622227.jpg` | `photo-vxscan-components-packed.jpg` | manual-photo | vxscan | UPS is not pictured despite the surrounding text listing it as a component. | election-day-guides/vxscan-setup.md |
| 399 | `PXL_20241031_183331525.jpg` | `photo-vxscan-full-setup.jpg` | manual-photo | vxscan | Same photo as vxscan-1200w.png (item 4) at full size; both given the same id. | election-day-guides/vxscan-setup.md |
| 400 | `vxscan-1200w.png` | `photo-vxscan-full-setup.png` | manual-photo | vxscan | Same photo as PXL_20241031_183331525.jpg (item 43) at a smaller size; both given the same id. | README.md |
| 401 | `VxScan insert poll worker card 2.png` | `photo-vxscan-insert-poll-worker-card.png` | manual-photo | vxscan |  | election-day-guides/closing-polls.md, election-day-guides/opening-polls.md |
| 402 | `scan_install_pat+audio-attached-front-1600x1200.jpg` | `photo-vxscan-pat-and-headphones-attached.jpg` | manual-photo | vxscan | Batch metadata lists 769x1600 but the image renders landscape. | election-day-guides/assisting-voters.md |
| 403 | `VxScan poll worker door sealed.png` | `photo-vxscan-poll-worker-door-seal.png` | manual-photo | vxscan |  | election-day-guides/closing-polls.md |
| 404 | `VxScan Polls Opened Report.png` | `photo-vxscan-polls-opened-report-printing.png` | manual-photo | vxscan | Same photo as 'VxScan Polls Closed Report Printing.png' (item 14) without the blur. | election-day-guides/opening-polls.md |
| 405 | `VxScan cord wrapped.png` | `photo-vxscan-power-cord-storage.png` | manual-photo | vxscan | Case is on a table, not on the ballot box; different photo from PXL_20241031_183628378.jpg (item 44). | election-day-guides/packing-up-vxscan.md |
| 406 | `VxScan open panels to access printer roll.png` | `photo-vxscan-printer-open-panels.png` | manual-photo | vxscan | Photograph with numbered arrow annotations. | vxscan/printer-management.md |
| 407 | `VxScan pull paper up.png` | `photo-vxscan-printer-pull-paper-over-tear-bar.png` | manual-photo | vxscan |  | vxscan/printer-management.md |
| 408 | `VxScan push green button printer roll.png` | `photo-vxscan-printer-push-release-lever.png` | manual-photo | vxscan |  | vxscan/printer-management.md |
| 409 | `VxScan put paper container back in.png` | `photo-vxscan-printer-roll-holder-reinsert.png` | manual-photo | vxscan |  | vxscan/printer-management.md |
| 410 | `VxScan remove printer roll case.png` | `photo-vxscan-printer-roll-holder-remove.png` | manual-photo | vxscan |  | vxscan/printer-management.md |
| 411 | `VxScan put one side of paper on roll.png` | `photo-vxscan-printer-roll-place-one-end.png` | manual-photo | vxscan |  | vxscan/printer-management.md |
| 412 | `VxScan snap other side of paper roll in.png` | `photo-vxscan-printer-roll-snap-other-end.png` | manual-photo | vxscan |  | vxscan/printer-management.md |
| 413 | `VxScan remove any excess paper.png` | `photo-vxscan-printer-tear-excess-paper.png` | manual-photo | vxscan |  | vxscan/printer-management.md |
| 414 | `VxScan Polls Closed Report Printing.png` | `photo-vxscan-report-printing.png` | manual-photo | vxscan | Same photo as 'VxScan Polls Opened Report.png' (item 19) with the 'Opening Polls...' text blurred out so it can stand in for the polls closed report; given a separate generic id because the visible text differs. | election-day-guides/closing-polls.md |
| 415 | `PXL_20241031_203337811.jpg` | `photo-vxscan-scanner-cleaning-cloth.jpg` | manual-photo | vxscan | Portrait phone photo; section is Scanner Cleaning. | vxscan/scanner-management.md |
| 416 | `vxscan-scanner-cables-focus.jpg` | `photo-vxscan-scanner-internal-cables.jpg` | manual-photo | vxscan |  | system-maintenance/vxscan-maintenance-manual.md |
| 417 | `PXL_20241031_184257763.jpg` | `photo-vxscan-scanner-open.jpg` | manual-photo | vxscan | Portrait phone photo; section is Scanner Cleaning. | vxscan/scanner-management.md |
| 418 | `PXL_20241031_185345256.jpg` | `photo-vxscan-security-bolt-release.jpg` | manual-photo | vxscan | Packing-up counterpart of PXL_20241031_183949135.jpg (item 46), which pushes the bolt down to secure. | election-day-guides/packing-up-vxscan.md |
| 419 | `PXL_20241031_184055101.jpg` | `photo-vxscan-security-bolt-sealed.jpg` | manual-photo | vxscan | Portrait phone photo (769x2000). Used in both the VxScan Setup checklist and the Scanner Cleaning section. | election-day-guides/vxscan-setup.md, vxscan/scanner-management.md |
| 420 | `PXL_20241031_183949135.jpg` | `photo-vxscan-security-bolt-secure.jpg` | manual-photo | vxscan | Setup counterpart of PXL_20241031_185345256.jpg (item 21), which releases the bolt. | election-day-guides/vxscan-setup.md |
| 421 | `VxScan slide black case on the ballot box.png` | `photo-vxscan-slide-case-onto-ballot-box.png` | manual-photo | vxscan |  | election-day-guides/packing-up-vxscan.md |
| 422 | `VxScan usb drive.png` | `photo-vxscan-usb-drive-inserted.png` | manual-photo | vxscan | Image has a blue annotation circle around the USB port. | election-day-guides/closing-polls.md |
