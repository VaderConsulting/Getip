# Getip

VB6 `GetIP` class module that resolves any hostname to IPv4 via Winsock `gethostbyname`. Set the `HostName` property, then read `IPAddress`. Based on David Diedrich's local-only sample (netfokus.dk/vbadmincode), extended to arbitrary hosts and wrapped as a reusable class. Tree is sources-only (no `.vbp`).

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** class module / sources

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `GetIP` (`Getip.cls`) | VB6 | class | Hostname to IPv4 via Winsock |

## How to open

Open `Getip.cls` in Visual Basic 6.0 IDE (no `.vbp` in this tree).

## Requirements

- Visual Basic 6.0 IDE
- Winsock (`WSOCK32.DLL`)

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VB/Old/Getip`.
Original sample by David Diedrich; see embedded `readme.txt` and http://www.netfokus.dk/vbadmincode/.

## License

Third-party / shared sample code remains under its original terms (or none, where none were supplied). See `readme.txt`. Do not treat this tree as VaderConsulting original MIT-licensed work.
