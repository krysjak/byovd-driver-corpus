# `qcwlan64_1.sys`

[Назад до індексу](../README.uk.md) · [English version](qcwlan64_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D02783837B43C543EC84F7391A6D25D05D3573DC78A005629059A0B1AB9DF04F` | `5C983AEBEC35526F440D7363B477A65D06C11EBD` | `DA0C0ADADA63333D2BBB4A14F9AEA34F` |

## Метадані

- **Ім'я файлу:** `qcwlan64_1.sys`
- **Розмір:** 3150168 bytes
- **Архітектура:** 0x8664
- **Компанія:** Qualcomm Atheros, Inc.
- **Продукт:** Driver for Qualcomm Atheros QCA61x4/QCA9377 Network Adapter
- **Опис:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
