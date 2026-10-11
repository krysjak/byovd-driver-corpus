# `Intel_NF_I2C_5.sys`

[Назад до індексу](../README.uk.md) · [English version](Intel_NF_I2C_5.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `CC5EF39BB0FD1DCE1E256C9DA492B768F87CC8FEA9D5D49DF7AA35777BA8DD2B` | `0E3461BE51DA6503F974E80C205967C1E3DCC2D5` | `1DBE9E1637BE584101891113B8BDC28C` |

## Метадані

- **Ім'я файлу:** `Intel_NF_I2C_5.sys`
- **Розмір:** 223016 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) NF I2C Driver
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 70

## Профіль можливостей

**Primitives:** `MDL allocation`, `physical memory mapping`

**Imports:** `IoAllocateMdl`, `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
