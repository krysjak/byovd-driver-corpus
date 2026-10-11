# `gna_1.sys`

[Назад до індексу](../README.uk.md) · [English version](gna_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `BF0816E1BC5561094E3E4B2F27859AEA4D655F1546E9193100DE9A8A4D4C14D3` | `025F3C681BC99DBF9B19ED6E7419383015787013` | `6EA3A12F265CB170FF3ED395AB507181` |

## Метадані

- **Ім'я файлу:** `gna_1.sys`
- **Розмір:** 88776 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel (R) Gaussian & Neural Accelerator
- **Опис:** Intel (R) GNA device driver (10.64.2.19041)
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 65

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
