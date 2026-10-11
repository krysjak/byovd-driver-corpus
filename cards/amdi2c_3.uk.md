# `amdi2c_3.sys`

[Назад до індексу](../README.uk.md) · [English version](amdi2c_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `387811D57DEF06C9736D9F0BAB0DFB0F83DBAB19E5489BF9A6DCDCBD682DD8FE` | `3BC822EFF605EE91C84902A71659E1F52EAD9660` | `D0E26E590DE1424CCC4F77D1687049EF` |

## Метадані

- **Ім'я файлу:** `amdi2c_3.sys` (Ідентичні копії: `amdi2c_5.sys`)
- **Розмір:** 45568 bytes
- **Архітектура:** 0x8664
- **Компанія:** Advanced Micro Devices, Inc
- **Продукт:** AMD I2C Controller Driver
- **Опис:** AMD I2C Controller Driver
- **Підпис:** unsigned
- **Джерело:** `local`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** Live system
- **Score:** 55

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
