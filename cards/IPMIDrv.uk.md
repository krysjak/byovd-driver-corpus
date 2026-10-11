# `IPMIDrv.sys`

[Назад до індексу](../README.uk.md) · [English version](IPMIDrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `4399C3F5E6DB1ADA50447B3725EBA48849CE1B437BD1593B5084F165148DEFA0` | `4B81A0347ECD6CEF22E5AE8738DD58BA5C3AC68E` | `DAEAF84E2A9620BEF93254D0BBF76BD3` |

## Метадані

- **Ім'я файлу:** `IPMIDrv.sys` (Ідентичні копії: `IPMIDrv_1.sys`)
- **Розмір:** 169440 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** WMI IPMI DRIVER
- **Підпис:** signed
- **Джерело:** `candidate_drivers`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Unknown
- **Score:** 0

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
