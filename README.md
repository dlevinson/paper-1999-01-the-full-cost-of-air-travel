# Full Cost of Air Travel in the California Corridor

## Bibliographic Information

- Row ID: `paper-1999-01`
- Citation: Gillen, David, and David M. Levinson. (1999). "Full Cost of Air Travel in the California Corridor." Transportation Research Record 1662:1-9. https://doi.org/10.3141/1662-01
- Audit timestamp: 2026-05-17 06:33:07 AEST

## Package Status

This package has been rebuilt from the paper outward. The article estimates the full cost of California-corridor air travel using airway infrastructure/FAA allocation tables, terminal and airside airport cost models, carrier cost assumptions, congestion and user-time calculations, accident rates, noise estimates, and air-pollution cost estimates. The package stages the air-specific Full Cost Project files that correspond to those calculations.

The package is treated as `READY-TO-UPLOAD/PUBLIC` because the selected materials are aggregate/model/statistical inputs, legacy model workbooks, and source workpapers. No individual-level records were identified in the selected payload. Repository-level provenance wording should still identify the underlying public/statistical sources, including FAA cost-allocation reports, airport operating/capital-cost summaries, carrier cost references, NTSB accident statistics, and published noise/pollution valuation sources.

Repeated Full Cost report/social-cost workbooks are not duplicated here. The Full Cost report PDF, air noise/congestion workbooks, and social-cost charts live under `_shared_sources/full-cost-intercity-transportation-1996/`; this package keeps pointer documentation plus the air-paper-specific airport cost workbooks and source workpapers.

The package/source boundary was rechecked on 2026-05-17. A checksum pass confirmed that 10 included files in `SOURCE_FILE_REVIEW.csv` byte-match their source-folder originals, with no failures. The very old Mac Excel 5 airport-cost files are retained as originals with string extracts because LibreOffice conversion produced blank/duplicate workbooks.

## Contents

- `paper/`: final/published paper PDF copied for audit reference.
- `data/air_full_cost_model/original_legacy/`: selected original legacy air-cost model/data files from the Full Cost Project.
- Converted air noise/congestion/social-cost workbooks and their CSV exports live in `_shared_sources/full-cost-intercity-transportation-1996/`; per-paper duplicates are intentionally not retained here.
- `documentation/full_cost_report/`: final Chapter Five air-cost source document and air-cost summary tables.
- `documentation/source_workpapers/`: substantive accident, congestion, noise, and pollution source workpapers used to support the paper's social-cost components.
- `documentation/legacy_text_extracts/`: text extracts from selected legacy Word documents for easier review.
- `data/DEDUP_POINTER_MANIFEST.csv`: report/social-cost workbook files removed from this package because they are available through the shared Full Cost source.


Some very old Mac Excel 5 files did not expose readable cells through LibreOffice. Their originals are retained, and string extracts were added under `documentation/legacy_text_extracts/` so visible labels and embedded text can still be reviewed.

## Exclusions

The broader Full Cost Project folder also contains email/correspondence, search notes, earlier chapter versions, background memoranda, and other-mode materials. Those are intentionally excluded. In particular, `Distances and Volumes` is an email-style high-speed-rail demand note with personal contact text and is not part of this air-paper package.

## Remaining Work

No further hard-drive search is expected for this paper. Before public upload, write concise provenance/license notes for the public/statistical source inputs. The shared Full Cost report/social-cost boundary has already been deduplicated to `_shared_sources/full-cost-intercity-transportation-1996/`.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 15:23:47 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->
