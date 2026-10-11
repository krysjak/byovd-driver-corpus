# `iaLPSS2_I2C_TGL.sys`

[Назад до індексу](../README.uk.md) · [English version](iaLPSS2_I2C_TGL.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `56A0FD540DB34782A68E7FAA3D74C5F00D8C1A1D78F9926A965501E86847F77E` | `1F7EFA826BE4AD4C561B2A8AEDB5AC5785A7F20F` | `FEBA04F32864E9E316C9312858E6546B` |

## Метадані

- **Ім'я файлу:** `iaLPSS2_I2C_TGL.sys`
- **Розмір:** 201376 bytes
- **Архітектура:** 0x8664
- **Компанія:** Intel Corporation
- **Продукт:** Intel(R) Serial IO Driver
- **Опис:** Intel(R) Serial IO I2C Driver v2
- **Підпис:** signed
- **Джерело:** `oem:dell`
- **Додано до репо:** 2026-10-11
- **Створює пристрій:** — · **Створює symlink:** — · **Немає перевірки probe:** так
- **У системах:** OEM package
- **Score:** 60

## Профіль можливостей

**Primitives:** `physical memory mapping`

**Imports:** `MmMapIoSpaceEx`

## Задокументоване використання (LOLDrivers)

Публічної документації немає. Кандидат за статичною евристикою — наявні небезпечні імпорти, вразливість НЕ підтверджена.

## Виявлення

Блокуйте/шукайте за SHA256, SHA1 або ім'ям файлу. Моніторте події завантаження драйверів (Sysmon 6, Defender for Endpoint) за цими хешами.
