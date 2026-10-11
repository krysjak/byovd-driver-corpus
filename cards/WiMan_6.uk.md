# `WiMan_6.sys`

[Назад до індексу](../README.uk.md) · [English version](WiMan_6.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `D64BCB8267D89F4B5E5219929E103FE3E6680BD436C56C876C39F4380336E1A0` | `8993A1BEA104415B4BEE864C4D89D0B615DAA07C` | `C53173F6D5A8C74784D7E9C6808DF314` |

## Метадані

- **Ім'я файлу:** `WiMan_6.sys`
- **Розмір:** 169048 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel® Wireless Manageability
- **Опис:** Intel® Wireless Manageability
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 85

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical address resolution`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmGetPhysicalAddress`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
