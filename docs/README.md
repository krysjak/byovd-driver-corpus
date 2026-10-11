# Vulnerable / Candidate Driver Repository

A catalog of signed Windows kernel drivers collected by `driver_hunter.py`
and scored for BYOVD (Bring Your Own Vulnerable Driver) abuse potential.

**Purpose:** defensive research — detection engineering, blocklist curation,
vulnerability assessment of the signed-driver supply chain.

## Layout

| Path | Contents |
|------|----------|
| `drivers/` | Unique `.sys` binaries (deduplicated by SHA256) |
| `entries/<sha256>.json` | Per-driver metadata card: hashes, signer info, imports, capability profile, documented usage (LOLDrivers public data), blocklist status |
| `manifest.json` / `manifest.csv` | Machine-readable index of every driver |
| `drivers.md` | Human-readable index table |
| `docs/BYOVD.md` | How signed vulnerable drivers get loaded/abused and how to detect it |

## Stats

Generated from `candidate_drivers/` (see `candidate_drivers/manifest.json`).
Counts are in `manifest.json`: unique drivers, LOLDrivers matches, MS blocklist matches.

## Scoring

`byovd_score` is a heuristic: dangerous kernel imports (MmMapIoSpace,
ZwMapViewOfSection, MmCopyVirtualMemory, …), reachable IOCTL surface
(IoCreateDevice + IoCreateSymbolicLink), missing ProbeForRead validation,
and code-signing status. A high score means *worth reviewing*, not
*confirmed exploitable*.

## Notes

- `signature: catalog_cert` = the file carries an Authenticode/certificate
  table; it was NOT chain-verified in batch mode.
- Binaries are proprietary drivers repackaged from public vendor/OEM
  packages. Keep this repository private: publishing driver binaries raises
  copyright and platform-ToS issues. Publish hashes and metadata instead —
  that is the model loldrivers.io uses.
