# `RtsP2Stor.sys`

[Назад до індексу](../README.uk.md) · [English version](RtsP2Stor.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `42E1B1251425081D43258D6F94AEDD3D77CCF4C28B05D79D87B755D6F4DD72CE` | `0117EF0F87BEBC0CED8E541E5C88ED870723580A` | `798330E809C5B3EDB2BA156533C57D1D` |

## Метадані

- **Ім'я файлу:** `RtsP2Stor.sys`
- **Розмір:** 330176 bytes
- **Архітектура:** 0x8664
- **Компанія:** Realtek Semiconductor Corp.
- **Продукт:** Realtek Pcie CardReader Driver for 2K/XP/Vista/Win7/Win8
- **Опис:** Realtek Pcie CardReader Driver for 2K/XP/Vista/Win7/Win8
- **Підпис:** signed
- **Джерело:** `oem:hp`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** так · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 100

## Профіль можливостей

**Primitives:** `MDL allocation`, `page locking`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpace`, `MmProbeAndLockPages`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
