<div align="center">

# BYOVD Driver Corpus

**A Windows kernel-driver dataset for defensive security research.**

[Explore the catalog](CATALOG.md) · [Data files](manifest.csv) · [Українською](README.uk.md)

</div>

---

This repository collects Windows kernel drivers and the information needed to examine them: file hashes, signing metadata, PE imports, static-analysis observations, and references to public BYOVD research.

**It is a collection of candidates, not a list of confirmed exploitable drivers.** The static-analysis results are intended to help investigators decide what to review next.

## At a glance

| Files indexed | Unique SHA-256 | With signature metadata | LOLDrivers matches | Microsoft blocklist matches |
| ---: | ---: | ---: | ---: | ---: |
| **821** | **693** | **609** | **3** | **0** |

<sub>Snapshot: 11 October 2026. Counts reflect the recorded dataset and its matching process, not independent verification of vulnerability, certificate validity, or blocklist coverage.</sub>

## Browse the data

| Start here | What you'll find |
| :-- | :-- |
| [Driver catalog](CATALOG.md) | Complete file-level listing, with links to driver reports |
| [Technical index](drivers.md) | Driver scores, signing labels, reference matches, and selected imports |
| [Driver reports](cards/) | Individual Markdown records, with English and Ukrainian versions |
| [Manifest (CSV)](manifest.csv) · [JSON](manifest.json) | Hashes and metadata for searching or processing the collection |
| [JSON records](entries/) | Per-hash metadata and analysis results |
| [Indicator feed](feeds/protection_feed.json) | Candidate hashes for investigation and rule review |
| [Research notes](docs/README.md) · [Detection guidance](docs/BYOVD.md) | Data fields, BYOVD context, and defensive use cases |

## How the corpus was built

1. **Collect.** Discover driver samples in OEM packages, vendor support archives, Windows Update, public collections, and live systems.
2. **Extract.** Recover `.sys` files from archives and installers, including `.zip`, `.cab`, `.7z`, and `.exe` packages.
3. **Inspect.** Record PE metadata, MD5/SHA-1/SHA-256 hashes, imported functions, and indicators of device objects, symbolic links, and IOCTL-related surfaces.
4. **Correlate.** Compare collected records with LOLDrivers and the Microsoft vulnerable-driver blocklist, then assign a heuristic score for triage.

Two files exceed GitHub's 100 MB file limit and are not included as binaries: `nvlddmkm.sys` and `amdkmdag_1.sys`. Their records remain in the index.

## Reading the results

The `byovd_score` is a **review priority signal**, not a vulnerability rating. It is based on static characteristics that may deserve closer inspection. A driver importing a memory-management API, for example, is not necessarily exposing that capability to an untrusted caller.

Similarly, the `signed` field reflects signature-related metadata found during collection; batch processing does **not** establish that every certificate chain is currently trusted. A LOLDrivers match should be checked against the exact sample hash and the underlying advisory before being treated as confirmation. An absent Microsoft blocklist match is not evidence that a driver is safe or unsafe.

The indicator feed is research input, **not a ready-to-deploy denylist**. Validate hashes, context, and potential false positives before using it in production controls.

## Purpose and responsible use

This dataset is maintained for detection engineering, threat hunting, driver inventory review, and vulnerability research. It does not replace manual reverse engineering or controlled validation.

The included binaries are associated with their respective vendors; inclusion here does not transfer ownership or grant additional distribution rights. Avoid executing unknown drivers on production systems.

For incorrect metadata, attribution concerns, or a removal request, [open an issue](https://github.com/krysjak/byovd-driver-corpus/issues).

---

<sub>BYOVD: Bring Your Own Vulnerable Driver. References to potential attack surfaces describe research hypotheses unless supported by independent evidence.</sub>
