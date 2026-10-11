# `WwanNet.sys`

[Назад до індексу](../README.uk.md) · [English version](WwanNet.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `84954F363E456659289559744AEFA4D50C1B896C983F31BE3B478968C6B3D9D4` | `9D66D325135AF3003CDC6AD3687D11FA9C0C5C15` | `47A9D3A60B2F0D135A7E6F6D1A8DEAFB` |

## Метадані

- **Ім'я файлу:** `WwanNet.sys`
- **Розмір:** 459320 bytes
- **Архітектура:** 0x8664
- **Компанія:** Fibocom Wireless Inc.
- **Продукт:** Fibocom Wwan 5G NetAdapter Stack
- **Опис:** Fibocom Wwan NetAdapter Mbb-Client Driver"
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `contiguous physical allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `MmAllocateContiguousMemory`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
