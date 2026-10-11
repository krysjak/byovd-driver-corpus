# `qcwlan64.sys`

[Назад до індексу](../README.uk.md) · [English version](qcwlan64.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `428B90EC39DADF75041C3926990457CBAC46F3CFB2DE9833395FAE56C45657D0` | `C8592A86C2922A330A1BFED9F639078D9990D91F` | `7DEBC94DEA39D103477AC2A89AE6302C` |

## Метадані

- **Ім'я файлу:** `qcwlan64.sys`
- **Розмір:** 2706944 bytes
- **Архітектура:** 0x8664
- **Компанія:** Qualcomm Atheros, Inc.
- **Продукт:** Driver for Qualcomm Atheros QCA61x4/QCA9377 Network Adapter
- **Опис:** Qualcomm Atheros Extensible Wireless LAN device driver
- **Підпис:** unsigned
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** —
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
