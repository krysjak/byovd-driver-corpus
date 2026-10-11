# `GlPciSD.sys`

[Назад до індексу](../README.uk.md) · [English version](GlPciSD.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `53A63122BCBC080B453DEF19277DC3F5EF4111B8426CA9AB53969A0826DFC71D` | `EF576992187B58B47837C3532349A091D641CCEF` | `9EF7CAF5A6FD81D6F7AFD0B2D1D21235` |

## Метадані

- **Ім'я файлу:** `GlPciSD.sys`
- **Розмір:** 228592 bytes
- **Архітектура:** 0x8664
- **Компанія:** Genesys Logic
- **Продукт:** Genesys Logic PCI CardReader Driver
- **Опис:** Genesys Logic PCI CardReader Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 125

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`, `MmMapIoSpaceEx`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
