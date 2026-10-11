# `Usb4HostRouter_1.sys`

[Назад до індексу](../README.uk.md) · [English version](Usb4HostRouter_1.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `60545983B8A91834043F17C9F8634FE51032E144CBE8C94D67C5809C7272A331` | `2125990B432F348D54BA4D7629101E105413076E` | `07DB3961F031524FC737695535E6ED69` |

## Метадані

- **Ім'я файлу:** `Usb4HostRouter_1.sys` (Ідентичні копії: `Usb4HostRouter_2.sys`)
- **Розмір:** 1168792 bytes
- **Архітектура:** 0x8664
- **Компанія:** Microsoft Corporation
- **Продукт:** Microsoft® Windows® Operating System
- **Опис:** USB4(TM) Host Router Driver
- **Підпис:** signed
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
