# `TbtBusDrv.sys`

[Назад до індексу](../README.uk.md) · [English version](TbtBusDrv.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C487612D8207F791400086A052A6B11781D8831809565B13E5081B6113F14ACC` | `9B68FDEBB9D173BBC825D35FAF1932BE53DDE6E7` | `7DB011D7110C30ED773D97435107FDE6` |

## Метадані

- **Ім'я файлу:** `TbtBusDrv.sys`
- **Розмір:** 3183200 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Thunderbolt(TM) Bus Driver
- **Опис:** Thunderbolt(TM) Bus Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 100

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
