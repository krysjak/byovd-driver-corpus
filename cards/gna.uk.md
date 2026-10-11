# `gna.sys`

[Назад до індексу](../README.uk.md) · [English version](gna.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `ADF0A51C612499644E616AEFD8C051292C7C0405ACADB5C60D6609D05D4A5982` | `1F9FE42B907313244D32E9B9E38183140E23CC2E` | `BF631234B2C3C7543E9F1219EAFA4818` |

## Метадані

- **Ім'я файлу:** `gna.sys`
- **Розмір:** 90304 bytes
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
