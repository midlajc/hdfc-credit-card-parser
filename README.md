# HDFC Statement Parser

Convert HDFC credit card statement PDFs into CSV directly in your browser.

## Open App

- https://hdfc-parser.midlajc.dev/

## What It Supports

- HDFC credit card statement PDFs
- Old and new statement layouts (auto-detected)
- Password-protected PDFs (asks for password)
- Multiple PDF uploads at once
- CSV download per statement
- PDF and CSV preview inside the app

## PWA Features

- Installable on mobile and desktop
- Share PDF to app on supported mobile browsers
- macOS desktop file open support via `Open With -> HDFC Parser`
- Offline app shell support after first load

## How To Use

1. Open https://hdfc-parser.midlajc.dev/.
2. Upload PDF(s) using drag-and-drop or file picker.
3. If prompted, enter the PDF password.
4. Wait for parsing to complete.
5. Download the generated CSV.

## Privacy

- All processing happens locally in your browser.
- PDF files are not uploaded to a server by this app.

## Notes

- Parsing is heuristic and depends on statement text layout.
- If you update/reinstall the PWA, relaunch the app before testing share/open flows.
