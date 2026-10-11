# `Intel_NF_I2C_4.sys`

[Назад до індексу](../README.uk.md) · [English version](Intel_NF_I2C_4.md)

## Хеші

| SHA256 | SHA1 | MD5 |
|--------|------|-----|
| `977057DF4EF3EDDA22BEC992FF519E6E871344B8B32E840FDCA8CC998D3EC7C1` | `AD9E7109DD78087043B9496F50F49D301E86848C` | `C9A7B3F036DC27892CF5FA8E38C02C94` |

## Метадані

- **Ім'я файлу:** `Intel_NF_I2C_4.sys`
- **Розмір:** 222920 bytes
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
