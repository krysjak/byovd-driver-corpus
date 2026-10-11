# `amd_dpfc.sys`

[Назад до індексу](../README.uk.md) · [English version](amd_dpfc.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `3C134B5D0702231A72C97237CCF632BB5FE43FFDCEDD45F333D0FB6F7C7243AD` | `BE0E1DAA1A5EB849514229EFB2800F5AD72076B6` | `A22E152982CDD234FAA33FBD582E2A64` |

## Метадані

- **Ім'я файлу:** `amd_dpfc.sys`
- **Розмір:** 58808 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices
- **Продукт:** AMD Dynamic Power and Frequency Control Service Driver
- **Опис:** AMD Dynamic Power and Frequency Control Service Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** так · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 105

## Профіль можливостей

**Primitives:** `physical address resolution`, `physical memory mapping`

**Imports:** `MmGetPhysicalAddress`, `MmMapIoSpace`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
