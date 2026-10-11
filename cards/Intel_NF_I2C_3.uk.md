# `Intel_NF_I2C_3.sys`

[Назад до індексу](../README.uk.md) · [English version](Intel_NF_I2C_3.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `C5AC16043AD6214DA945F6C16E29C31981915BC360554DAF13573570842D74AF` | `71E21371C033D22F66F8BECF02AEE60FFD39282B` | `64A87437654815CC35EA52CA0D09494C` |

## Метадані

- **Ім'я файлу:** `Intel_NF_I2C_3.sys`
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
