# `Intel_NF_I2C_2.sys`

[Назад до індексу](../README.uk.md) · [English version](Intel_NF_I2C_2.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `33F673B49AF9A32F9EC0513E5818A2052FF7C69B6F7920C6E678A693689F7EE9` | `A8451EA6CE2279326587F20F0671FF8AA006B5C2` | `FE6262341402DB50CBD3EB08DC3523D0` |

## Метадані

- **Ім'я файлу:** `Intel_NF_I2C_2.sys`
- **Розмір:** 218056 bytes
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
